> [!WARNING]
> ~The translation layer is no longer usable as of 02/24/2025, vector implemented a semi simulation anticheat that expects proper physics.~
> You will now have to send C0CInput packets along with ticks to move, enjoy!

# MinibloxTranslationLayer
A middleman proxy that translates Miniblox packets into Minecraft 1.8.9 packets, letting you connect to Miniblox through any supported 1.8.9 client. 

**Credit to [7GrandDad](https://youtube.com/c/7GrandDadVape) for the development and maintainance of MTL.**

## Requirements
- [Node.js](https://nodejs.org/) (latest LTS recommended)
- A cracked Minecraft 1.8.9 client (ViaVersion is supported)

## Setup
1. Download and extract this repository
2. Open a terminal in the extracted folder
3. Run `npm install`, then `node index.js`
4. Connect to `localhost` in your Minecraft 1.8.9 client

## Authentication
To play on a Miniblox account, run `/login <token>` in chat. Your token will be saved to `login.token`. Leave this blank to play as a guest ("non account.")

## Commands
| Command | Aliases | Description |
|---|---|---|
| `/play <gamemode>` | `/queue` | Queue for a gamemode (`eggwars`, `skywars`, `kitpvp`, and more) |
| `/join <code>` | | Connect directly to a server by ID |
| `/login <token>` | | Save your Miniblox session token |
| `/resync` | | Resync your position if you appear desynced |
| `/reloadchunks` | | Force-reload all chunks |
| `/desync` | | Toggle desync correction mode |

## Notes
- Only one player can be connected in a session
- The proxy runs on `localhost:25565` by default
- Skins are mapped from Miniblox cosmetics to 1.8.9-compatible textures

## License
[AGPL-3.0](LICENSE.md)
