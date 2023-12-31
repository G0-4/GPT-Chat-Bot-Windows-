# GPT-Chat-Bot (Windows)
A simple Chat Bot that uses the gpt-3.5-turbo Chat API. Prompts the user to designate system prefix at the beginning. I've built the script to automatically append each previous input into the next input's prompt, so context is preserved across requests. Will automatically request a new input after each response until you press CTRL+C. On exit, the script will print a copy of all the messages you've sent and received during that run. All messages are exported to the "log.txt" file an exit, and automatically formatted to be easier to read and navigate. Tested and works with LM Studio if you want to host your own local LLM; just make sure to make the necessary adjustments with the base_url parameter. Otherwise, create your own .env file with api key and run .py file through CMD. 

# System prefix assignment and example of prompt context preservation
![image](https://github.com/G0-4/GPT-Chat-Bot-Windows-/assets/106123404/2ceaadae-0a1a-42d2-a134-f3df8ed4a55c)

# Output after pressing CTRL+C
![image](https://github.com/G0-4/GPT-Chat-Bot-Windows-/assets/106123404/7f3b2d22-8d52-4abc-9a1e-211f5fda52b8)

# log.txt file
![image](https://github.com/G0-4/GPT-Chat-Bot-Windows-/assets/106123404/7a40a248-80e6-468f-9585-da1f91ed2d61)

# New instance of script appends new messages and responses to the end of log.txt without overwriting
![image](https://github.com/G0-4/GPT-Chat-Bot-Windows-/assets/106123404/7266d712-13ae-4da2-a652-fcfbb4c416fd)
