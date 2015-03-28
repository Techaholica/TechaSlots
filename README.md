# TechaSlots
A Slot machine bot for Twitch

This script was part of my Twitch Bot Tutorial on Youtube. That's why you have those additional commands. I just wanted to show off different things you can do with a bot. 

Overview
When a user enters the channel, a timer is kicked off which awards the user every 10 mins with $10 (this is customizable). Users start off with $500. They can play a slot machine in chat and win or lose money. 

- Copy the Slots folder to %APPDATA%\mirc
- Load the Slots.ini file in mIRC
- Have fun!

Commands
- !dance - Sends a message to channel saying you do a dance
- !danceParty - For admins only. Sends a message to channel saying you start a dance party
- !cash - Shows how much cash you have
- !bet ([amount]) - By itself returns how much you are currently betting. Specifying a number changes your bet amount.
- !addStats [username] [property] [amount] - Admin command to add stats to a user's property. Currently users only have two properties "cash" and "bet". If you want to give a user 100 dollars you would enter this command: !addStats username cash 100. 
- playSlots - Plays the slot machine and outputs the result to chat.

Misc
You can modify the Slots.config file to change some aspects of the script.
- cashAddAmount - changes how much a user is rewarded with the user timer
- userTimer - changes how often users are rewarded in chat. This number is in seconds.
- baseDir - If you want to rename the Slots directory, change this value as well.
- other options are here in case you want to use them. They don't do anything currently though.
