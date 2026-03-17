# Aether-Yield (AY)

A rewrite, performance-optimized command-line administration script for Roblox.

## Overview

Aether-Yield provides a comprehensive suite of commands for Roblox game and exploration. Built with modern Luau and optimized for minimal performance impact.

## Features

- **Performance Optimized**: Lazy-loaded UI components and cached services
- **Lightweight**: Reduced memory footprint through efficient code architecture
- **Cross-Platform**: Full support for PC and mobile devices
- **Extensible**: Plugin system for custom commands
- **Modern Codebase**: Utilizes contemporary Luau features and best practices

## Usage

1. Execute the script in your preferred Roblox executor
2. Press `;` (semicolon) to open the command bar
3. Type commands to interact with the game

### Common Commands

| Command | Alias | Description |
|---------|-------|-------------|
| `goto [player]` | `to` | Teleport to a player |
| `walkspeed [number]` | `ws`, `speed` | Set movement speed |
| `jumppower [number]` | `jp` | Set jump power |
| `fly` | - | Enable flight mode |
| `noclip` | - | Walk through walls |
| `rejoin` | `rj` | Rejoin current server |
| `serverhop` | `sh` | Join a different server |
| `esp` | - | Highlight all players |
| `invisible` | `invis` | Make character invisible |
| `reset` | `re` | Reset character |

Type `cmds` or `commands` for a full list of available commands.

## Mobile Support

On mobile devices, a floating "AY" button appears in the top-center of the screen. Tap it to open the command interface.

## Technical Details

- **Architecture**: Modular design with deferred initialization
- **Memory Management**: Automatic cleanup of unused resources
- **Compatibility**: Works with major Roblox executors
- **Asset Handling**: Automatic download and caching of required assets

## Acknowledgments

Aether-Yield is based on the Aether Yield project by Edge and contributors.

Original development team:
- Edge (Creator)
- Moon (Developer)
- Zwolf (Developer)
- Toon (Developer)

## License

This project is open source. Contributions are welcome via pull requests.
