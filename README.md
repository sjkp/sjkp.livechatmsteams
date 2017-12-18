# SJKP Live Chat Microsoft Teams

Live customer support chat control for your web sites, that uses Microsoft Teams as the backend admin interface.

For more info see: https://devpost.com/software/live-web-chat-for-microsoft-teams 

# Installation
The Microsoft Teams bot can currently only be installed by Side Loading it into your Teams tenant, it is not available in the store. 

To get it download the zip from the release page (https://github.com/sjkp/sjkp.livechatmsteams/releases/download/1.0/sjkp.msteamslivechat.zip) and upload it to your teams tenant following this guide:
https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/apps/apps-sideload 

Once the bot is installed, simply write @Live Chat help to have it return the different commands that it supports. 

To get the embed code write @Live Chat GetWebChats 

To customize the welcome messages, title and description you can use:

* `@Live Chat SetWebChatTitle` followed by the title text you want to use on the web chat dialog
* `@Live Chat  SetWebChatText` followed by the text you want to use on the web chat dialog
* `@Live Chat  SetWelcomeMessage` followed by the text you want to use as the welcome message when the user first enter the chat


