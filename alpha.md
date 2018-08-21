# Anti-gravity α

This is the first Anti-gravity event. We have two problems to solve in this event. Take a look at problem definitions and choose one to work on.

## A. Release Mattermost version of Assistant+

Since we want to use [Mattermost](http://mattermost.org) as the main messenger in our corporation, we need to migrate the old Telegram bot to Mattermost.

Take a look at [Assitant+](https://github.com/anti-graviton/assistant-bot) github repositroy and follow the instructions for contributing.

## B. Publish TFS Notifications On Mattermost

We need a Visual Studio Team Services (VSTS) extension that enables us to recieve TFS events on the Mattermost.

First step to solve such problems is to study the platform and its features. Melody and I searched a little bit and found that there is [a feature](https://docs.microsoft.com/en-us/vsts/extend/reference/targets/overview?view=vsts#service-hooks) in VSTS that allows us to publish events on different channels. But there were no Mattermost integration for this feature :(

Then we followed the white rabbit: [How to develop a service hook](https://docs.microsoft.com/en-us/vsts/extend/develop/add-service-hook?view=vsts)

It's your turn to follow it and develop an extension.

## Rules
- There's no point in starting something you don't intend to finish.
- You should use Python, Go or Javascript (family!) to develop your solution
- Stay with your language's style guide (e.g. PEP8 for Python)

## Schedule

**Wed 9:00 - 11:00** Research and Setup

**11:00 - 16:30** Develop

**16:30 - 17:30** Demo and Feedback

**17:30 - Thu 11:30** Develop

**11:30 - 12:30** Judgment
