# Discord Rewards Guide

## Editing your RocketMod RCON Settings (See below for the BOT Guide)

- Firstly, find your `Rocket.config.xml` file, it should be located at `Unturned\Servers\ServerName\Rocket\`
- Then, find the **RCON** section, it should look like this:
```
<RCON Enabled="true" Port="27115" Password="changeme" EnableMaxGlobalConnections="true" MaxGlobalConnections="10" EnableMaxLocalConnections="true" MaxLocalConnections="10" />
```
- Set `Enabled` to `true`.
- Set the `Port` to whatever you'd like, ensure your fire-wall rules are set to allow incomming connections from it.
- Set the `Password` to whatever you'd like.
- Set both `EnableMaxGlobalConnections` & `EnableMaxLocalConnections` to `True`.
- Set both `MaxGlobalConnections` & `MaxLocalConnections` to `9999`.
- Once you have done this, simply save the file and restart your Server.


## BOT Guide

- Firstly, add the BOT to your Server, get the LINK in the ImperialPlugins Product Page.
- Once added, go in-game and execute the `/validate` command.
- Then, in Discord do `!validate [License Key]` and it will validate you. **You MUST have the `Administrator` permission to use `!validate`**
- Users, after getting a code in-game, can now do `!validate [5-digit-code]`!
