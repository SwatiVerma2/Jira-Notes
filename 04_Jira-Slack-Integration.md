# Slack

## What is Slack?
- Slack is a popular collaboration and communication platform designed for teams to communicate, share files, and manage projects more effectively. 
- It serves as a central hub where team members can collaborate in real-time, organize conversations, and integrate with various tools and services.

![image](https://github.com/user-attachments/assets/2562179c-4e17-46dd-b1ef-ffb3ab35b121)

### Different Sections in Slack 
1. Apps: The Apps section of Slack is where you can find, install, and manage integrations that enhance your Slack workspace. These apps connect Slack with other tools and services you use, allowing you to bring different aspects of your work directly into Slack.
2. Channel: A shared space where a group of people can communicate and collaborate around a specific topic or project.
3. Threads:  A focused, organized discussion tied to a specific message in a channel or DM. Use threads to keep discussions on a specific message organized without cluttering the main conversation flow in a channel.
4. DM: A private, one-on-one or small group conversation between users in Slack.
   
- More section
  ![image](https://github.com/user-attachments/assets/fb5d198a-0166-430c-ac98-7ad5bc7f1ddf)

1. Huddles: Quick, impromptu audio conversations in Slack for real-time collaboration.
2. Automations: Streamline repetitive tasks using workflows, bots, and app integrations within Slack. Eg Automating onboarding processes for new team members.Setting up reminders for recurring tasks.
3. Canvases: Slack Canvases (often referred to as Slack Canvas) are collaborative spaces within Slack where teams can organize, share, and edit content in a flexible, document-like format.
   Features:
   - Canvases can include text, images, files, and other Slack-integrated tools.
   - They support real-time collaboration, allowing multiple team members to contribute simultaneously.
   - Canvases are typically linked to specific channels or DMs, providing context and keeping relevant information in one place.

### Key Features of Slack
1. Channels: Organize conversations by topic, project, or team.
2. Direct Messaging: Send private messages to individuals or small groups.
3. File Sharing: Share documents, images, and files directly within channels or messages.
4. Search: Quickly find messages, files, and channels with powerful search capabilities.
5. Mentions & Notifications: Get notified when someone mentions you or important updates occur.
6. Threaded Conversations: Keep side discussions organized without cluttering the main channel.
7. Video and Voice Calls: Start video or voice calls directly from Slack.
8. Custom Emojis: Create and use custom emojis to personalize communication.
9. Workflow Automation: Automate tasks and processes with Slack's workflow builder.
10. Integrations: Connect with hundreds of apps like Google Drive, Jira, and GitHub.


# Jira and Slack Integration

Create an account on Slack : Get started > continue with google

![image](https://github.com/user-attachments/assets/45f156ff-fb52-4156-b966-b586d3239780)

Quick start > connet tool > slack > connect > " jira cloud for Slack (official)" > learn more > a page will appear > allow --> Jira is now authenticated to slack > Go to slack

![image](https://github.com/user-attachments/assets/f5fd1171-acfb-44fb-8aa9-0739c364accd)

Type: /jira create, connect ,ISSUEKEY

In Slack, the /jira create and /jira connect commands are used to interact with Jira directly from Slack. These commands are part of the Jira Cloud for Slack integration, which allows users to manage Jira issues without leaving Slack.

Example /jira create test integration

![image](https://github.com/user-attachments/assets/cbf6a039-be96-42e6-8b2c-d69cf6d1a29c)

Click on enter then this will pop up

![image](https://github.com/user-attachments/assets/11925754-d17e-4674-811a-59d35531e8cf)

Now this will be visible in backlog on JIRA

![image](https://github.com/user-attachments/assets/5523a5e2-ec80-4c77-bd03-e58fd39c8ba4)



### Slack Automation

To get a notification on slack whenever there is a change in the board
Project setting > automation > template 
Here you can create workflows of automation
New component > add an action > type “SLACK”

![image](https://github.com/user-attachments/assets/11944f7b-2774-4816-8a55-19ffef64d4b6)

It will ask for webhook URL

![image](https://github.com/user-attachments/assets/6c1d0bb9-df59-40a3-baac-7bdaf75aa4c5)


### Webhooks
A webhook is a method used by web applications to send real-time data from one application to another whenever a specific event occurs. Instead of continuously polling for data, a webhook automatically triggers and sends the data to a specified URL as soon as the event happens.

On your browser search : Create slack app > https://api.slack.com/apps
Slack > Create app > from scratch

![image](https://github.com/user-attachments/assets/8dd87812-0f9a-4b8a-97fe-0dbf565d005b)

Incoming webhooks > activate > on > add new webhooks to workspace

![image](https://github.com/user-attachments/assets/0280080e-bac8-4989-bddc-5ce50ce0a779)

Create a channel in Slack : Redirected webhook to this channel

![image](https://github.com/user-attachments/assets/e1e18ef7-7141-4b9e-9e98-3beab7db1ff8)

Copy webhook and paste > write a message > turn on rule 

Make a transition on board and you will receive a notification on slack

![image](https://github.com/user-attachments/assets/2395e2dc-5289-4fef-8d2e-fddf7d8a6146)

![image](https://github.com/user-attachments/assets/26b0e0e7-3ed4-4479-b4de-2de4024b3a0a)

