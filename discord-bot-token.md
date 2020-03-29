# Discord Bot Token

## What is a discord bot token?

Discord Bot Token is a short phrase that acts as a “key” to controlling a Discord Bot. Tokens are used inside bot code to send commands back and forth to the API, which in turn controls bot actions.

## Getting a bot token

Head over to [discord discord developer portal](https://discordapp.com/developers/applications). After that look on top right and click new application

![Click on New Application](.gitbook/assets/newapplication.png)

![Time to pick a name. Pick the name of your bot you would want. Could be changed later if needed.](.gitbook/assets/newapplication2.png)

## Making the Bot

Now lets head over to the bot page on the left hand side.

![Click the bot page.](.gitbook/assets/headtobot.png)

![Click add bot](.gitbook/assets/clickaddbot.png)

![Once the bot is made it can not be removed.](.gitbook/assets/yesdoit.png)

## Inviting the bot to your server

Lets get started on inviting your newly made discord bot to your discord server. First off you will need your client token to start off with and this link. [http://absentservices.xyz/authorize/](http://absentservices.xyz/authorize/)

Head over to "General Information" tab and get the client id.

![Copy the client id](.gitbook/assets/clientdiscordbotclientid.png)

Then head over to your internet browser and paste the link

![Pick server and then authorize it.](.gitbook/assets/invitetodisc.png)

![After authorized, you will see this.](.gitbook/assets/authorizedbot.png)

## Setting Bot Permissions

To set up the discord bot permissions you could either setup a role in your server or setup permissions from the bot application. Lets head over to the bot page. and scroll down.

![if doing it this way, pick what permissions you want.](.gitbook/assets/settingbotperms.png)

Depends on what bot you are making. You will need your discord bot to have permissions to edit your chat, kick, ban, mute, manage server, or just set it as administrator. Note if your doing it this way you will need to re-invite your discord bot to the discord server using the link. After the permissions are setup use the link [http://absentservices.xyz/authorize/](http://absentservices.xyz/authorize/) , Change the permissions=0 to the Permission integer number you have setup.

![https://discordapp.com/oauth2/authorize?&amp;client\_id=YOUR\_CLIENT\_ID\_HERE&amp;scope=bot&amp;permissions=8](.gitbook/assets/setupperms.png)

## Warning

{% hint style="warning" %}
Do not share your discord bot token with anyone. Otherwise someone can control your discord bot.
{% endhint %}



