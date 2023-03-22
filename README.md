

# Intune Blog Summarizer with GPT 
![ailonag_an_info_graphic_of_an_AI_robot_taking_in_an_RSS_feed_an_152da832 7865 4f2f ae46 59cb840773eb](https://user-images.githubusercontent.com/81778135/227051825-e9a664c1-d4fb-4234-8430-84a78b270754.jpg)

Microsoft Tech Community - Latest Blogs - Microsoft Intune Blog

Script will monitor the RSS feed and email a summarization of the article thats easy to share on othe platforms.  The action script will run once an hour and only send an email if there is a new post. 

![image](https://user-images.githubusercontent.com/81778135/227055885-967d7893-2a83-4a02-ab19-6cc3c05beb01.png)



To use clone this repo and create your own open ai account and enviroment secrets so this can run in their own repro, please follow these steps:

1. Open a terminal on your local machine and navigate to the directory where you want to store the cloned repo.
2. Type git clone https://github.com/ailonag/Intune-FeedSummarizer.git and press Enter to create a local copy of the remote repo.
3. modify email as well as the Feed URL to any MS RSS feed you would like. 
4. if you want to use gmail as your smtp follow the instructions here https://support.google.com/mail/answer/7126229 otherwise specify your own smtp server 
5. Go to https://openai.com/ and sign up for an account if you don't have one already. You will need an API key to access the OpenAI services.
6. In your OpenAI account dashboard, go to API Keys and click Create an API key. Copy the secret key that starts with sk_ and keep it safe.
7. In your local repo, Set secrets in Settings/Secrets/Actions -> 'New repository secret'. Use the same secret name inside actions.yml and main.py
8. You have successfully cloned the repo and created your own environment secrets. You can now run the code in your own repro using Python 


