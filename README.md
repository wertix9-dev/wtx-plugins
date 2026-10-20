# WTX-SMP Plugin Suite

A polished, crossplay-ready plugin suite for **Paper 1.21.6** survival SMP servers, built and maintained
for a live PvP SMP. Restrained black/gray/white branding, Vault economy integration, and one coherent tag
system instead of several plugins fighting over the same prefixes.

**All plugins are free to download and use on your server.**

## Download

**[➜ Download the latest release](https://github.com/wertix9-dev/wtx-plugins/releases/latest)**

Every JAR is attached to the release. Direct links:

| Plugin | Download |
| --- | --- |
| WTXCore | [WTXCore-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXCore-1.0.0.jar) |
| WTXScoreboard | [WTXScoreboard-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXScoreboard-1.0.0.jar) |
| WTXShop | [WTXShop-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXShop-1.0.0.jar) |
| WTXMoneyShop | [WTXMoneyShop-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXMoneyShop-1.0.0.jar) |
| WTXTeams | [WTXTeams-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXTeams-1.0.0.jar) |
| WTXItemControl | [WTXItemControl-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXItemControl-1.0.0.jar) |
| WTXGuard | [WTXGuard-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXGuard-1.0.0.jar) |
| WTXRestartAnnouncer | [WTXRestartAnnouncer-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXRestartAnnouncer-1.0.0.jar) |
| WTXPvPManager | [WTXPvPManager-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXPvPManager-1.0.0.jar) |
| WTXCombatPlus | [WTXCombatPlus-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXCombatPlus-1.0.0.jar) |
| WTXCrossplayDisplay | [WTXCrossplayDisplay-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXCrossplayDisplay-1.0.0.jar) |
| WTXEvents | [WTXEvents-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXEvents-1.0.0.jar) |
| WTXSleep | [WTXSleep-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXSleep-1.0.0.jar) |
| WTXTPA | [WTXTPA-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXTPA-1.0.0.jar) |
| WTXWebhooks | [WTXWebhooks-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXWebhooks-1.0.0.jar) |
| WTXBackup | [WTXBackup-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXBackup-1.0.0.jar) |
| WTXLeaderboards | [WTXLeaderboards-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXLeaderboards-1.0.0.jar) |
| WTXNotes | [WTXNotes-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXNotes-1.0.0.jar) |
| WTXPolls | [WTXPolls-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXPolls-1.0.0.jar) |
| WTXAnalytics | [WTXAnalytics-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXAnalytics-1.0.0.jar) |
| WTXGraves | [WTXGraves-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXGraves-1.0.0.jar) |
| WTXWaypoints | [WTXWaypoints-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXWaypoints-1.0.0.jar) |
| WTXDuels | [WTXDuels-1.0.0.jar](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXDuels-1.0.0.jar) |

The WTXGuard Anti-Xray examples are attached as well:
[paper-world-defaults example](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXGuard-paper-world-defaults-anti-xray.example.yml) ·
[Nether example](https://github.com/wertix9-dev/wtx-plugins/releases/latest/download/WTXGuard-paper-world-nether-anti-xray.example.yml)

## New in this update

- **WTXCore** (new plugin): `/wtx version`, `/wtx list` with update status, `/wtx reloadall`
- Team chat (`/team chat`) and automatic leadership handover in WTXTeams
- `/wtxpoints top|pay` and `/wtxshop gift` in WTXShop
- Auction sorting (`/ah sort`) and `/moneyshop top` in WTXMoneyShop
- Per-player sidebar toggle (`/wtxsb toggle`) and abbreviated numbers in WTXScoreboard
- `/wtxguard log` and `/wtxguard antixray verify`
- `/pvp list` and no logout punishment while the server is shutting down
- `/combatplus top`, `/tparequests`, AFK-aware one-player sleep

### New plugins

- **WTXWebhooks** — one Discord relay (join/quit/death/server start/stop) with a public API for other plugins
- **WTXBackup** — scheduled async ZIP backups with retention and path-escape protection
- **WTXLeaderboards** — `/top money|points|kills|deaths|playtime|raids`
- **WTXNotes** — staff notes per player, never shown to the player
- **WTXPolls** — GUI polls with automatic close
- **WTXAnalytics** — economy/server overview for admins
- **WTXGraves** — death graves with anti-dupe and anti-item-loss guarantees
- **WTXWaypoints** — public paid teleport network
- **WTXDuels** — 1v1 duels with escrowed bets

## What is included

| Plugin | What it does |
| --- | --- |
| **WTXCore** | Suite helper: `/wtx version`, `/wtx list` (with update status), `/wtx reloadall` |
| **WTXScoreboard** | Compact grayscale sidebar (team, kills, deaths, Money, Points, online), TAB header/list, rank tags, optional chat tags, per-player `/wtxsb toggle` |
| **WTXShop** | WTX Points shop with `/dailypoints`, 40 pets, 40 particle trails, 40 auras, 48 cosmetic titles with animated colour styles |
| **WTXMoneyShop** | Category shop for every item with quantity buttons and search, `/worth`, `/sell`, `/pay`, `/moneygive`, auction house with search, taxes, expiry and transaction history |
| **WTXTeams** | Teams, filtered names, colours, shared bank, paid chunk claims, team homes and waystones, scheduled raids with real kill-based outcomes, `/teamlist`, `/teamtop` |
| **WTXItemControl** | Configurable banned materials and a configurable Mace damage nerf |
| **WTXGuard** | Conservative fly-movement staff alerts with anti-false-positive guards, plus a safe writer for Paper's Anti-Xray config (backups + restore) |
| **WTXRestartAnnouncer** | Restart countdown with chat announcements, boss bar, and a configurable action at zero |
| **WTXPvPManager** | Combat tags, personal boss-bar countdown, combat-log handling, public `isTagged()` API |
| **WTXCombatPlus** | In-combat command and item restrictions, fair combat-log fines, combat statistics |
| **WTXCrossplayDisplay** | Rank/team tags and TAB rendering through the main scoreboard for Java and Bedrock, with Floodgate `[BE]` markers |
| **WTXEvents** | Rotating, balanced PvP modifiers on a schedule, with warnings and restart-safe state |
| **WTXSleep** | One player is enough to skip the night, with dimension-aware handling |
| **WTXTPA** | Teleport requests with expiry, cooldowns, delays, safe-destination checks and combat blocking |
| **WTXWebhooks** | Discord relay for join/quit/death/server events, plus a public API for other plugins |
| **WTXBackup** | Scheduled async ZIP backups with retention, path-escape protection and no silent deletion |
| **WTXLeaderboards** | `/top` for money, points, kills, deaths, playtime and raid wins |
| **WTXNotes** | Staff notes per player, never visible to the player |
| **WTXPolls** | Server polls with GUI voting and automatic close |
| **WTXAnalytics** | Read-only overview: money in circulation, points, teams, auctions, active event |
| **WTXGraves** | Death graves with one-viewer locks, save-before-give and expiry that never discards items |
| **WTXWaypoints** | Public paid teleport network with GUI, cooldown and safe-destination checks |
| **WTXDuels** | 1v1 duels with escrowed bets, arenas and crash-safe refunds |

## Requirements

- Paper 1.21.6 (or a compatible 1.21.x build) on **Java 21**
- **Vault** plus a Vault-compatible economy provider (EssentialsX Economy works) for all Money features.
  These are third-party plugins and are **not** bundled here:
  [Vault](https://www.spigotmc.org/resources/vault.34315/) ·
  [EssentialsX](https://essentialsx.net/downloads.html)
- Optional: **PlaceholderAPI** (scoreboard placeholders), **Floodgate/Geyser** (Bedrock markers crossplay)

## Installation

1. Download the JARs you want from the [latest release](https://github.com/wertix9-dev/wtx-plugins/releases/latest).
2. Put them in the server's `plugins/` folder (plus Vault and an economy provider for Money features).
3. Start the server once, review `plugins/<Name>/config.yml`, restart after changes.
4. Optional: `/wtxguard antixray preview`, then `apply`, then restart again.

This suite also replaces the old `SMPGuard` (now **WTXGuard**, which imports the old config) and the
third-party `TeamTags` plugin — do not run those alongside it.

## Why this suite

- **One tag system.** Shop rank/VIP tags, team tags and the sidebar are rendered by one plugin, so tags
  never duplicate or randomly overwrite each other.
- **Crossplay aware.** Bedrock markers via Floodgate and tag rendering through the main scoreboard.
- **Economy integrity.** Auction deny lists stop restricted items from bypassing shop rules, listings
  expire with loss-free returns for offline sellers, taxes and fees are configurable, everything is logged.
- **Honest anti-cheat.** Conservative, configurable staff alerts. Never automatic bans or kicks on weak
  evidence.
- **Honest Anti-Xray.** Paper's engine stays Paper's: the plugin writes the world config textually with
  timestamped backups and restore, and says clearly that a restart is required.
- **Operator friendly.** English messages, commented configs, additive config migrations, no hardcoded
  secrets, no in-game payment processing.

## Community and support

Questions and setup help: **https://discord.gg/SHE2FE7YMw**

## Licence

Free to download and use on any Minecraft server. Do not resell the plugins, republish them under another
name, or distribute modified copies as your own. The plugin source code is not published.
Third-party product names (Paper, Vault, EssentialsX, GeyserMC, Floodgate, Simple Voice Chat) belong to
their respective owners.
