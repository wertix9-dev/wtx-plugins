# WTX-SMP Plugin Suite

A polished, crossplay-ready plugin suite for **Paper 1.21.6** survival SMP servers, built and maintained
for a live PvP SMP. Restrained black/gray/white branding, Vault economy integration, and one coherent tag
system instead of several plugins fighting over the same prefixes.

## Get it

**Licensing, pricing, bundles and updates: https://discord.gg/SHE2FE7YMw**

That Discord is the only place where the plugins are sold. This repository is a catalogue — **no source
code and no JAR files are published here.**

## What is included

| Plugin | What it does |
| --- | --- |
| **WTXScoreboard** | Compact grayscale sidebar (team, kills, deaths, Money, Points, online), TAB header/list, rank tags, optional chat tags |
| **WTXShop** | WTX Points shop with `/dailypoints`, 40 pets, 40 particle trails, 40 auras, **48 cosmetic titles** with animated colour styles |
| **WTXMoneyShop** | Category shop for **every item** with quantity buttons and search, `/worth`, `/sell`, `/pay`, `/moneygive`, auction house with search, taxes, expiry and transaction history |
| **WTXTeams** | Teams, filtered names, colours, shared bank, paid chunk claims, team homes and waystones, scheduled raids with real kill-based outcomes, `/teamlist`, `/teamtop` |
| **WTXItemControl** | Configurable banned materials and a configurable Mace damage nerf |
| **WTXGuard** | Conservative fly-movement staff alerts with anti-false-positive guards, plus a **safe writer for Paper's Anti-Xray config** (backups + restore) |
| **WTXRestartAnnouncer** | Restart countdown with chat announcements, boss bar, and a configurable action at zero |
| **WTXPvPManager** | Combat tags, personal boss-bar countdown, combat-log handling, public `isTagged()` API |
| **WTXCombatPlus** | In-combat command and item restrictions (`/home`, `/tpa`, pearls, elytra, …), fair combat-log fines, statistics |
| **WTXCrossplayDisplay** | Rank/team tags and TAB rendering through the main scoreboard for **Java and Bedrock**, with Floodgate `[BE]` markers |
| **WTXEvents** | Rotating, balanced PvP modifiers on a schedule, with warnings and restart-safe state |
| **WTXSleep** | One player is enough to skip the night, with dimension-aware handling |
| **WTXTPA** | Teleport requests with expiry, cooldowns, delays, safe-destination checks and combat blocking |

## Free vs Premium

Every plugin ships as a complete, working free edition; premium editions add scale, convenience and
cosmetics — not missing basics.

| Plugin | Free | Premium |
| --- | --- | --- |
| Scoreboard | Full sidebar, TAB, tags | Extra layouts, per-rank boards, animated title packs |
| Shop | All cosmetics, core titles | Cosmetics packs, extra title sets, bundle pricing |
| MoneyShop | Full shop, auction, search, `/worth` | Extra categories, dynamic pricing, shop signs, per-rank discounts |
| Teams | Teams, claims, raids, `/teamlist` | More claim tiers, team levels, raid statistics |
| Guard | Alerts + Anti-Xray writer | Advanced checks, staff review tools |
| CombatPlus | All restrictions | Punishment ladders, combat statistics exports |
| CrossplayDisplay | Java + Bedrock tags | Per-rank display profiles, Bedrock-specific layouts |
| Events / Sleep / TPA | Complete features | Extra event pools, per-world rules, request limits |

## Requirements

- Paper 1.21.6 (or a compatible 1.21.x build) on **Java 21**
- **Vault** plus a Vault-compatible economy provider (EssentialsX Economy works) for all Money features
- Optional: **PlaceholderAPI** (scoreboard placeholders), **Floodgate/Geyser** (Bedrock markers crossplay)

## Why this suite

- **One tag system.** Shop rank/VIP tags, team tags and the sidebar are rendered by one plugin, so tags
  never duplicate or randomly overwrite each other.
- **Crossplay aware.** Bedrock markers via Floodgate and tag rendering through the main scoreboard, because
  per-player boards are less reliable for Bedrock clients.
- **Economy integrity.** Auction deny lists stop restricted items from bypassing shop rules, listings expire
  with loss-free returns for offline sellers, taxes and fees are configurable, and every transaction is
  logged.
- **Honest anti-cheat.** Conservative, configurable staff alerts with fall-distance, ping and jump guards.
  Never automatic bans or kicks on weak evidence.
- **Honest Anti-Xray.** Paper's engine stays Paper's: the plugin writes the world config textually with
  timestamped backups and restore, and says clearly that a restart is required.
- **Operator friendly.** English messages, commented configs, additive config migrations, no hardcoded
  secrets, no in-game payment processing.

## Installation

1. Download the licensed JARs from the Discord.
2. Put them in the server's `plugins/` folder (plus Vault and an economy provider).
3. Start the server once, review `plugins/<Name>/config.yml`, restart after changes.
4. Optional: `/wtxguard antixray preview`, then `apply`, then restart.

## Support

Questions, setup help and licence requests: **https://discord.gg/SHE2FE7YMw**

## Licence

Proprietary and commercial. The plugins are licensed to the purchasing server; redistribution, resale and
publishing of the source or JARs are not permitted. This repository contains descriptive material only.
