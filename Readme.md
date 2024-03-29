# Commands

## Admin

* **$addrole [user] [role]** - Add a role to an user on your server, in order to assign a role the bot role must be above the others.
* **$ban [user] [reason]** - Ban an user from the server.
* **$deletemsg [number]** - Delete an amount of messages, the number must be between 2 and 100.
* **$kick [user] [reason]** - Kick an user from the server.
* **$mute [user] [ms]** - Mute an user for a specific amount of time, you have to create a new role called mute to make the command work.
* **$removerole [user] [role]** - Remove a role of an user.
* **$setbotname [name]** - Set a name for the bot.
* **$setbotstatus [status]** - Set bot status.

## Games

* **$csgo [MySteamID]** - Get csgo stats for an user given by STEAMID64.
* **$csgofloat [inspect Url]** - Get informations about a skin or a weapon.
* **$lolcprot** - Display the current champion rotation in EU West.
* **$loltopfive [SummonerID]** - Display the top 5 played champions of a summoner, based on the SummonerID. You can find your SummonerID at http://www.lolking.net/

## Info

* **$help or $help [commandName]** - Display the list of commands if you just type $help or if you type $help commandName display the current command info.
* **$serverinfo** - Get server info.
* **$serverinvite [ChannelID]** - Get an invite for the server, but you must type the channelID to get the command work.
* **$uptime** - Get bot uptime.
* **$userinfo** - Get your user info.

## Music

* **$deletetrack [PositionNumberInQueue]** - Delete a song from the queue, if you want know your current queue, just type $queue and you will get the songs.
* **$play** - Play music.

## Random stuff

* **$distance [latitude1] [longitude1] [latitude2] [longitude2]** - Get the distance between the sets of coordinates
* **$dogs** - Find some cute dog pictures.
* **$flipcoin** - Flip a coin.
* **$google [query]** - Get 3 search queries from Google Custom Search, you need to provide in the json file called googleConfig, your Custom Search Api Key and your CX.
* **$ping** - Ping the bot.
* **$randomcolor** - Generates a random hex color with preview.
* **$rolldice** - Roll a dice.
* **$setafk [status]** - Set your status afk or notafk.
* **$weather [location]** - Get the forecast information for a location.

# Built with
* [Discord.js](https://discord.js.org/#/)
* [Node js](https://nodejs.org/en/)

# Known issues

The google command is not 100% correct, if you do a search query the first result will be correct, but from second above the googleResults.json will corrupt itself. This simply means you will get a wrong query.
