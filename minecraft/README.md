# cTurtle98 Minecraft Server Network

information for mc.cTurtle98.com minecraft server network


## global plugins

Global plugins for all cturtle98 minecraft server network servers

**bungee** plugin configuration checklist
- [x] Luckperms-bungee


### bungeecord

* [LuckPerms-bungeecord](https://luckperms.net/download)


**lobby** plugin configuration checklist
- [x] luckperms-spigot
- [x] DiscordSRV
- [ ] ViaVersion
- [ ] CoreProtect
- [x] Vault
- [ ] EssentialsX
- [x] EssentialsX Geo

**creative** plugin configuration checklist
- [x] luckperms-spigot
- [x] DiscordSRV
- [ ] ViaVersion
- [ ] CoreProtect
- [ ] Vault
- [ ] EssentialsX
- [x] EssentialsX Geo

**survival** plugin configuration checklist
- [x] luckperms-spigot
- [x] DiscordSRV
- [ ] ViaVersion
- [ ] CoreProtect
- [ ] Vault
- [ ] EssentialsX
- [ ] EssentialsX Geo


### bukkit, spigot, paper

* [LuckPerms-bukkit](https://luckperms.net/download)

* [ViaVersion](https://www.spigotmc.org/resources/viaversion.19254/)

* [CoreProtect](https://www.spigotmc.org/resources/coreprotect.8631/)

* [Vault](https://www.spigotmc.org/resources/vault.34315/)

* [EssentialsX](https://essentialsx.net/downloads.html?branch=stable)
  * EssentialsX Chat
  * EssentialsX Spawn
  * EssentialsX AntiBuild
  * EssentialsX Geo
  * EssentialsX Protect
 * [DiscordSRV](https://www.spigotmc.org/resources/discordsrv.18494/)


## Permissions

groups and permissions

plugin permissions implementation checklist
- [x] bungeecord
- [x] spigot / bukkit
- [x] minecraft
- [x] discordsrv
- [ ] luckperms
- [ ] essentialsx
- [ ] core protect


### Network_Owner
* bungeecord.command.* : true
* luckperms.* : true
* 

### Network_SuperAdmin
* bukkit.command.restart : false
* minecraft.command.* : true
* discordsrv.updatenotification : true
* 

### Network_Admin
* bungeecord.command.alert : true
* bungeecord.command.ip : true
* bukkit.command.tps : true
* bukkit.command.timings : true
* minecraft.command.say	: true
* discordsrv.reload : true
* discordsrv.debug : true
* 

### Network_Mod
* bungeecord.command.find : true
* bungeecord.command.send : true
* bukkit.command.version	: true
* minecraft.command.kick	: true
* minecraft.command.save-all	: true
* minecraft.command.spawnpoint	: true
* discordsrv.resync : true
* discordsrv.link.others : true
* discordsrv.unlink.others : true
* discordsrv.linked.others : true
* discordsrv.groupsyncwithcommands : true
* discordsrv.resync : true
* discordsrv.nicknamesync : true
* essentials.afk.others : true
* 

### Network_Member
* bungeecord.command.list : true
* bungeecord.command.server : true
* bukkit.command.plugins :	true
* minecraft.command.list	: true
* minecraft.command.seed	: true
* 

### default
* bungeecord.command.reload : false
* bukkit.command.version	: false
* bukkit.command.plugins	: false
* discordsrv.player : true
* discordsrv.sync.Network_Member : true
* 
