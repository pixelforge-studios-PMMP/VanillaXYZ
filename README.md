# VanillaXYZ Plugin

A PocketMine-MP plugin that automatically enables coordinate display in all worlds.

## Features

- Automatically enables the `showcoordinates` game rule for all worlds
- Loads before worlds to ensure coordinates are available immediately
- Zero-lag implementation for optimal server performance
- Works with both existing and newly loaded worlds

## Installation

1. Download the latest release from the releases page
2. Place the `VanillaXYZ.phar` file in your server's `plugins` folder
3. Restart your server

## Configuration

This plugin requires no configuration. It automatically enables coordinates in all worlds.

## How it works

- Uses GameRulesChangedPacket to send coordinate display settings to players
- Listens for player join events to apply coordinates immediately
- Zero-lag implementation using network packets
- Works for all players when they join the server

## Performance

This plugin is optimized for zero lag performance:
- Uses network packets instead of world game rule manipulation
- Minimal memory footprint
- Efficient event handling with player join events
- Zero impact on server performance

## Support

If you encounter any issues:
1. Check that you're using PocketMine-MP API 5.0.0 or compatible
2. Ensure the plugin is properly installed in the plugins folder
3. Check server logs for any error messages

## License

This plugin is released under the MIT License.
