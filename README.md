# RedDuck-Duckling
Bridges a Discord server and Minecraft server


A simple bridge between a Discord server and a Mincraft server written in Node.

Utilizes NMP (Node Minecraft Protocol) and Rcon for MC server connections, and discord.js for Discord bottery.

To use, download source and run `npm install` to install all the required modules.

In the `mcchat.js` script edit your rcon details, add your dummy Minecraft account details (If server is in offline mode you only require the username, as it will be treated as a cracked account), and enter your Discord bot key.

Run the bot using `node mcchat.js`

##You will know the bot is running when you see 'Minecraft client logged in.' 'Minecraft client joined server' and 'Discord bot ready' in console.

[Bot in action](http://i.imgur.com/tNvqqW2.gifv)
