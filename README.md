# SSecurity
Adding security to your players using Email Authentication or Google Authentication

What it does:
With SSecurity it allows you to provide easy and secure protection to your server and your players. 
SSecurity allows for players to be able to choose between google authentication or email authentication. 
With Google authentication, it connects the user to the google authenticator app. With email authentication, it
gives the user access to easily being able to receive an email with a code!

How it works:
If both google and email authentication is enabled within the config.yml upon join the user will gain access
to chose between what s/he prefers. If you choose google authentication it will provide you with a key that 
you will input within the google authenticator application on your device and from there on in you will be fully connected. 
However if you prefer email authentication then the plugin will ask for your email address which you will simply input 
into chat (No one in chat or console will see the email address inputted) Once you have disconnected from the 
server and re-joined the plugin will ask you for a code, this code will either be within the google authenticator app 
or it has already been emailed to you and awaiting input!

Commands & Permissions:
This plugin only contains two permissions! 
If a user has SSecurity.access or SSecurity.access.plus they will gain access to inputting a login code upon joining. 
The difference between these permissions is within the commands!

NOTE: You may use /ss as a shortened version

[Requires SSecurity.access]
Allows the player to choose between email and google authentication
- /SSecurity set (email | google) 

[Requires SSecurity.access.plus]
Allows the player to remove another player the player from the yml file
- /SSecurity remove (player) 
