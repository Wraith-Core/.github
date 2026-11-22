# Wraith Core — Open-Source RedM Framework

A modern, modular, server-authoritative **RedM (Red Dead Redemption 2)** roleplay framework built by **Wraith Studio**.

---

## Start Here

| Resource | Link | What It Is |
| :--- | :--- | :--- |
| **txAdmin Recipe** | [`Wraith-Core/txAdminRecipe`](https://github.com/Wraith-Core/txAdminRecipe) | One-click txAdmin installer for the complete free Wraith Core server |
| **Core Library (`w_lib`)** | [`Wraith-Core/w_lib`](https://github.com/Wraith-Core/w_lib) | Unified Red Dead UI, callbacks, prompts, placer, glow, DB helpers, framework bridge, locales |
| **Developer Docs** | [wraith-core.github.io/docs](https://wraith-core.github.io/docs/) ([Repo](https://github.com/Wraith-Core/docs)) | Full English installation, configuration, API reference & resource creation guide |

### One-Click txAdmin Install URL

Paste this into **txAdmin → Remote URL Template**:

```text
https://raw.githubusercontent.com/Wraith-Core/txAdminRecipe/main/wraithcore.yaml
```

---

## Free Open-Source Resources (17)

### Core Foundation
- [`w_lib`](https://github.com/Wraith-Core/w_lib) — Unified UI, callbacks, prompts, placer, glow, blips, DB exports, framework/inventory bridges & localization (`en` / `ar`)
- [`w_core`](https://github.com/Wraith-Core/w_core) — Framework core: characters, money, jobs, gangs, metadata, ranks/ACE, bans & commands *(GPL-3.0)*
- [`w_inventory`](https://github.com/Wraith-Core/w_inventory) — Slot + metadata inventory, weapons, stashes, crafting & built-in shops
- [`w_chat`](https://github.com/Wraith-Core/w_chat) — Styled roleplay chat & command suggestions
- [`w_loading`](https://github.com/Wraith-Core/w_loading) — Configurable Red Dead loading screen & transition curtain

### Character, Appearance & HUD
- [`w_creators`](https://github.com/Wraith-Core/w_creators) — Character selector, appearance studio, speaking voices & resurrection handler
- [`w_clothing`](https://github.com/Wraith-Core/w_clothing) — Clothing stores, personal wardrobes, saved outfits & toggles
- [`w_barber`](https://github.com/Wraith-Core/w_barber) — Barber chairs, hairstyles, beards, eyebrows & makeup
- [`w_hud`](https://github.com/Wraith-Core/w_hud) — Player HUD, server-authoritative needs, voice level & announcements
- [`w_zones`](https://github.com/Wraith-Core/w_zones) — Free 100% native RDR2 zone announcement banner (zero NUI) *(MIT)*

### World, Environment & Security
- [`w_weathersync`](https://github.com/Wraith-Core/w_weathersync) — Server-synced weather, time, dynamic transitions & blackout *(GPL-3.0)*
- [`w_interiors`](https://github.com/Wraith-Core/w_interiors) — Interior entity sets & IMAP loader across the map *(GPL-3.0)*
- [`w_doorlock`](https://github.com/Wraith-Core/w_doorlock) — Interactive door locks, permissions, lockpicking & in-game editor *(GPL-3.0)*

### Economy & Core Jobs
- [`w_banking`](https://github.com/Wraith-Core/w_banking) — Personal savings & gang accounts, transfers & statements *(GPL-3.0)*
- [`w_management`](https://github.com/Wraith-Core/w_management) — Boss & gang society treasury management *(GPL-3.0)*
- [`w_policejob`](https://github.com/Wraith-Core/w_policejob) — Sheriff & law enforcement job with built-in inventory armory *(GPL-3.0)*
- [`w_medic`](https://github.com/Wraith-Core/w_medic) — Doctor & hospital job with wounding, beds, revives & built-in inventory pharmacy *(GPL-3.0)*

---

## Key Highlights

- **Unified Library (`w_lib`):** One shared Red Dead paper-and-ink UI theme, one callback/prompt/locale API across every script.
- **Built-In Shops & Native UX:** Uses `w_inventory`'s built-in shop system, RDR2's native pause menu, and `w_zones` native location banners out of the box.
- **English First, Bilingual Ready:** Defaults to English (`en`) in the public recipe with full Arabic (`ar`) localization built in.
- **Lua 5.4 & OneSync:** Clean, modern server-authoritative RedM architecture.
