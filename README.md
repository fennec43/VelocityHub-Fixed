# VelocityHub-Fixed
Fixed version of the VelocityHub plugin with compatibility updates for modern Velocity API
A Velocity plugin that dynamically registers hub commands and connects players to configured servers — now patched and buildable with recent API changes.

✅ Fixes Included:
Replaced deprecated raw channel registration with a compatible ChannelIdentifier

Added getPlugin() reference to ConfigManager for proper task scheduling

Fully compiles with mvn clean package using recent Velocity API

📥 Download
Grab the .jar from the releases page and drop it into your Velocity server’s plugins folder.

⚙️ Features
Dynamic command loading from config.yml

Permission-based access

Config reload with /vhreload

💡 Example config:
yaml
commands:
  hub:
    server: "lobby"
    enabled: true
    permission: "velocityhub.command.hub"
🙌 Contribute
Found a bug or want to improve it? Fork the repo and submit a PR!
