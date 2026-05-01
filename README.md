# Poke Bot

[![Latest Release](https://img.shields.io/github/v/release/ZeddiS/zeddihub-teamspeak-pokebot)](https://github.com/ZeddiS/zeddihub-teamspeak-pokebot/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Right-click any TeamSpeak 3 client to launch a poke campaign.

Preset bursts (CZ, Symbol Storm, Silent, MAX) plus a custom dialog with Burst/Schedule mode toggle, paired sliders for count and intervals. Hard-cap of 500 pokes and 50ms anti-flood floor protect against server kicks. Native TS3 theme.

Part of the [**ZeddiHub TeamSpeak Addons**](https://github.com/ZeddiS/zeddihub-teamspeak-addons) collection.

---

## Installation

All download files are in **[Releases](https://github.com/ZeddiS/zeddihub-teamspeak-pokebot/releases/latest)**.

### Option A: TS3 native install (.ts3_plugin) -- recommended

1. Download the .ts3_plugin file matching your TeamSpeak 3 version:

| TS3 client | API | File |
|---|---|---|
| 3.5.0 | 23 | `pokebot-v1.3.0-TS3-3.5.0-api23.ts3_plugin` |
| 3.5.1 - 3.5.5 | 24 | `pokebot-v1.3.0-TS3-3.5.1-3.5.5-api24.ts3_plugin` |
| **3.5.6** | **25** | **`pokebot-v1.3.0-TS3-3.5.6-api25.ts3_plugin`** |
| 3.6.x and newer | 26 | `pokebot-v1.3.0-TS3-3.6+-api26.ts3_plugin` |

2. Double-click the downloaded file. TS3 client opens an install dialog.
3. Click **Yes** to install. TS3 copies the DLL into the plugins folder.
4. Restart TS3 if requested. Enable the plugin in **Settings -> Plugins**.

### Option B: Manual (.dll)

Download the raw DLL matching your TS3 client version:

- `zeddihub_pokebot_api23_win64.dll` -- TS3 3.5.0
- `zeddihub_pokebot_api24_win64.dll` -- TS3 3.5.1 - 3.5.5
- `zeddihub_pokebot_api25_win64.dll` -- TS3 3.5.6
- `zeddihub_pokebot_api26_win64.dll` -- TS3 3.6.x and newer

Copy the DLL to `%APPDATA%\TS3Client\plugins\`, then in TS3 go to **Settings -> Plugins -> Reload All -> tick Enabled**.

If TS3 reports 'API version not compatible', you have the wrong file -- try a different API number.

## Theme

Plugin dialogs use **TS3 client's native theme**. They look exactly like the rest of the TS3 UI -- no custom Discord-like dark theme. Whatever skin/theme you have set in TS3 will be applied.

## Source code

Source code lives in the [collection repo](https://github.com/ZeddiS/zeddihub-teamspeak-addons), folder `pokebot/`. CMake build instructions are there.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).

## License

MIT -- see [LICENSE](LICENSE).

---

## Links

- **ZeddiHub web**: https://zeddihub.eu
- **ZeddiHub Tools**: https://zeddihub.eu/tools/
- **Author**: https://zeddis.xyz
- **Collection**: [zeddihub-teamspeak-addons](https://github.com/ZeddiS/zeddihub-teamspeak-addons)

**Sister plugins:** [Poke Bot](https://github.com/ZeddiS/zeddihub-teamspeak-pokebot) | [Follow](https://github.com/ZeddiS/zeddihub-teamspeak-follow) | [MoveSpam](https://github.com/ZeddiS/zeddihub-teamspeak-movespam) | [Soundboard](https://github.com/ZeddiS/zeddihub-teamspeak-soundboard)

---

(C) 2026 [ZeddiHub.eu](https://zeddihub.eu) -- zeddis.xyz
