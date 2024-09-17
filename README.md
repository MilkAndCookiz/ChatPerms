# ChatPerms [![](https://poggit.pmmp.io/shield.state/ChatPerms)](https://poggit.pmmp.io/p/ChatPerms)

A comprehensive chat and permissions management plugin for PocketMine-MP servers, with faction support.

## Features

- Custom chat formats for different groups
- Customizable nametags with health display and faction tags
- Dynamic permission management
- Faction integration (supports FactionsPro, PiggyFactions, SimpleFaction, and Factions)
- Automatic detection of compatible faction plugins
- Real-time nametag updates reflecting health changes
- Easy-to-use commands for group and permission management
- Configurable via `config.yml`

## Commands

- `/cp setgroup <player> <group>` - Assign a player to a group
- `/cp creategroup <group> <chat_format> <nametag_format> [permissions...]` - Create a new group with specified formats and permissions
- `/cp removegroup <group>` - Delete an existing group
- `/cp addgroupperm <group> <permission>` - Add a permission to a group
- `/cp removegroupperm <group> <permission>` - Remove a permission from a group
- `/cp help` - Display all available commands

## Installation

1. Place the plugin PHAR (or folder) file in your server's `plugins` folder
2. Restart the server
3. Configure the plugin in `config.yml`

## Configuration

- Customize group settings, chat formats, and nametag formats in `config.yml`
- Player group assignments are stored in `players.yml`

## Support

For issues, feature requests, or contributions, please visit the GitHub repository.
