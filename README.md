# Discord Rewards Guide


## Editing your RocketMod RCON Settings
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

