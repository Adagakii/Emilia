# emilia
a discord.py template 

##Create a server
If you don't already have a server, create one free one at https://discordapp.com. Simply log in, and then click the plus sign on the left side of the main window to create a new server.

##Create an app
Go to https://discordapp.com/developers/applications/me and create a new app. On your app detail page, save the Client ID. You will need it later to authorize your bot for your server.

##Create a bot account for your app
After creating app, on the app details page, scroll down to the section named bot, and create a bot user. Save the token, you will need it later to run the bot.

#Authorize the bot for your server
Visit the URL https://discordapp.com/oauth2/authorize?client_id=XXXXXXXXXXXX&scope=bot but replace XXXX with your app client ID. Choose the server you want to add it to and select authorize.




Run pip install from your system terminal/shell/command prompt. Make sure to install the correct version of the package. If you are using PyCharm you can open the terminal from View -> Tool Windows -> Terminal

python -m pip install discord.py==0.16.12
