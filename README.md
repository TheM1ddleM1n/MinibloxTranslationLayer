> [!WARNING]
> ~The translation layer is no longer usable as of 02/24/2025, vector implemented a semi simulation anticheat that expects proper physics.~
> You will now have to send C0CInput packets along with ticks to move, enjoy!

# MinibloxTranslationLayer
A middleman proxy that translates Miniblox packets into Minecraft 1.8.9 packets, letting you connect to Miniblox through any supported 1.8.9 client.

## Setup
1. Install [Node.js](https://nodejs.org/) (latest LTS is **highly** recommended)
2. Download and extract this repository
3. Open a terminal in the extracted folder
4. Run `npm install`, then `node index.js`
5. In your Minecraft 1.8.9 client, connect to `localhost`

## Commands
| Command | Aliases | Description |
|---|---|---|
| `/play <gamemode>` | `/queue` | Queue for a gamemode (`eggwars`, `skywars`, `kitpvp`) |
