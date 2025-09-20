# AOTWCore



AOTWCore is a modular, fully-configurable core plugin built for the AOTW Minecraft server.  
It’s inspired by 8b8tCore but completely rewritten with clean code, full configuration support, and AOTW-specific features.

## Features


- Clean, modern plugin structure.
- `/aotwcore reload` command to reload all configs without restarting the server.
- Separate `config.yml` for settings and `messages.yml` for all player-facing text.
- Easy to extend: drop new features in their own package and hook them up to the config.

## Installation



1. Build the plugin with Maven or your preferred Java build tool.
2. Place the generated `AOTWCore-x.x.x.jar` file in your server’s `plugins` folder.
3. Start the server; AOTWCore will create default `config.yml` and `messages.yml` in the plugin’s folder.

...
