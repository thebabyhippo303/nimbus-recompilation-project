# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road (USA PSP), Infinite World (USA PlayStation 2, SLUS-21842), Super Dragon Ball Z (USA PlayStation 2, SLUS-21442), Budokai Tenkaichi 3 (USA PlayStation 2, SLUS-21678), Ridge Racer 2 (Europe PlayStation Portable, UCES-00422), Naruto Shippuden: Ultimate Ninja 5 (Europe PlayStation 2, SLES-55605), Mobile Suit Gundam: Gundam vs. Gundam NEXT PLUS (Japan PlayStation Portable, NPJH-50107), and Bleach: Heat the Soul 7 (Asia PlayStation Portable, NPHG00087). Fifteen native ports on Linux, Windows and Android (four consoles: GameCube, GBA, PSP and PS2), with online play and crossplay across all three platforms on regional servers. Dragon Ball remains the heart of TNRP. Ridge Racer 2 went online in 2.1, with 2 to 8 player crossplay racing through Wireless Battle.

**Official website:** [nimbusrecomp.org](https://nimbusrecomp.org/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## World-First Native Ports

The Nimbus Recompilation Project (TNRP) brings **15 games from 4 consoles** into a single native launcher. **13 of those 15 games had never been natively ported to modern hardware before TNRP.** Of the other two, one is the first port of its original console release, and the other is a game other projects have also worked on. TNRP lifted it from the disc on its own.

Every game runs natively on **Linux (x86-64)**, **Windows (x64)** and **Android (arm64)**, with crossplay between all three and no emulator underneath.

### At a glance

| | Count | Games |
|---|---|---|
| World-first native ports | 13 | Budokai 2, Sagas, Supersonic Warriors, Taiketsu, Tenkaichi Tag Team, Shin Budokai, Shin Budokai – Another Road, Infinite World, Super Dragon Ball Z, Ridge Racer 2, Naruto Shippuden: Ultimate Ninja 5, Gundam vs. Gundam NEXT PLUS, Bleach: Heat the Soul 7 |
| First port of the original GameCube release | 1 | Dragon Ball Z: Budokai (GameCube) |
| Other projects exist, but TNRP lifted its own port from the disc, with 3-platform crossplay | 1 | Dragon Ball Z: Budokai Tenkaichi 3 |

### By console

#### PlayStation Portable: 6 of 6 are world firsts
- **Bleach: Heat the Soul 7** (Asia, new in Alpha 2.3): Eighting's last PSP Bleach fighter, with its 80+ fighters and 4-player battles moving from local Ad-Hoc to online crossplay.
- **Mobile Suit Gundam: Gundam vs. Gundam NEXT PLUS** (JP): the Japan-only arena fighter, with English text options, HD textures and 4-player (2v2) online crossplay.
- **Ridge Racer 2** (EU/JP): the PSP racer that never came to North America, with its local Wireless Battle grown into 2 to 8 player online races, plus HD texture and movie packs.
- **Dragon Ball Z: Tenkaichi Tag Team** (NA): 2v2 tag battles playable online with up to 4 players across PC and handhelds.
- **Dragon Ball Z: Shin Budokai** (NA): Dimps's PSP fighter with online versus on every platform.
- **Dragon Ball Z: Shin Budokai – Another Road** (NA): the Future Trunks story intact, with Ad-Hoc versus upgraded to online crossplay.

#### PlayStation 2: 3 of 4 are world firsts
- **Naruto Shippuden: Ultimate Ninja 5** (EU/JP): the last PS2 Ultimate Ninja, never released in North America, with HD textures included.
- **Dragon Ball Z: Infinite World** (NA): the final game on the Budokai engine, free of the frame-rate slowdowns it suffers under emulation.
- **Super Dragon Ball Z** (NA): Crafts & Meister's arcade-style fighter with online crossplay.
- **Dragon Ball Z: Budokai Tenkaichi 3** (NA): other community decompilation and port projects exist, but TNRP doesn't use any of them. We lifted it straight from the original disc ourselves. What sets TNRP apart:
  - One build of the game runs natively on Linux, Windows and Android, with crossplay between all three.
  - Built-in online play with friends, parties and voice chat, with no Parsec, plug-ins or emulator netplay setup.
  - Shaders are precompiled ahead of time, so there's no stutter while they compile mid-match.
  - It lives in the same launcher as the other 14 games, sharing one friends list and party system.

#### GameCube: 2 world firsts plus 1 GameCube first
- **Dragon Ball Z: Budokai 2** (NA): the first native port on any platform, with online versus and HD texture packs.
- **Dragon Ball Z: Sagas** (NA): the 3D action-adventure, with local and online 2-player co-op, HD textures and upscaled cutscenes.
- **Dragon Ball Z: Budokai** (NA): the first native port of the original GameCube release. An Xbox 360 HD Collection recompilation came out for Windows in 2026. What sets TNRP apart:
  - It ports the original GameCube version, not the HD Collection remaster.
  - It runs natively on Linux and Android as well as Windows, not on Windows alone.
  - It has online versus with crossplay across all three platforms, through the same friends and party system as every other TNRP game.

#### Game Boy Advance: 2 of 2 are world firsts
- **Dragon Ball Z: Supersonic Warriors** (NA): local 2-player and online crossplay inside the launcher.
- **Dragon Ball Z: Taiketsu** (NA): multiplayer across every platform.

### Games that never came to North America

Four of the world-first ports, **Ultimate Ninja 5**, **Gundam vs. Gundam NEXT PLUS**, **Ridge Racer 2** and **Bleach: Heat the Soul 7**, never had an official North American release. TNRP makes these imports playable natively on PC and Android handhelds, with modern controls, HD texture packs, English text where needed and online play through servers in 16 cities worldwide.

> **Legal notice:** TNRP ships only the native runtime. It includes no copyrighted game assets, ROMs or BIOS files. You need to supply your own legally dumped discs or ROMs.

## Why the Code Stays Closed

The retro gaming scene has a pretty bad habit of acting entitled to free labor. Nobody owes the internet their source code, especially when the project is completely free, takes zero donations, and runs on servers paid for out of our own pocket.

The moment someone drops clean, working code for desktop and mobile into a public repo, parasitic outfits start circling. DamonPS2 famously took the open source PCSX2 code, closed it off in violation of the GPL, and stacked ads and microtransactions on top of it. Egg NS pulled the exact same move with code from Yuzu and Skyline, locking other people's work behind a specific controller purchase and a monthly VIP subscription. When someone builds a unified runtime for multiple consoles and a custom porting kit from scratch, tossing the keys onto GitHub before it even leaves alpha is basically begging for a dozen sketchy Play Store clones to strip our name off it by next Tuesday.

### Engineering vs. "Vibe Coded Slop"

There is also a massive difference between systems engineering assisted by AI and the "vibe coded" slop flooding the scene right now. Slop ports grab an existing emulator or a sluggish translation shim, prompt an LLM until a title screen boots, lay touch controls over it, and upload a broken build that stutters, blows out RAM, and runs worse than standard emulation.

You cannot vibe code a unified Vulkan renderer whose shaders are precompiled once, offline BC7 and ASTC texture compression pipelines with full mip chains, and a single shared host spanning four distinct console architectures with crossplay. And you definitely cannot vibe code your way into outperforming mature emulators and established native C++ ports on real hardware. That takes actual profiling, systems architecture, targeted hotfixes, and disciplined refactors.

### Why We Won't Hand Out a Port Factory

Open sourcing a working porting kit that spans multiple consoles is nothing like open sourcing the decompilation of a single game. In the age of autonomous AI coding agents, dropping those keys onto GitHub hands out a port factory that works at the push of a button.

Within weeks, GitHub, Reddit, and sketchy APK sites would be flooded with tens of thousands of automated, half baked ports. These would be builds someone checked for ten seconds on a title screen before slapping "NATIVE 4K 60FPS RECOMP" in the title, only for them to crash on level two, corrupt saves, or break audio. Players would have no way to tell real, playtested work apart from automated dumps made in fifteen minutes, which would poison trust in the entire static recompilation movement and drive people right back to standard emulators.

Worse, bad actors would immediately use that same toolkit to mass produce standalone APKs with pirated ROMs and ISOs baked inside, monetized with ads and paywalls. That would paint a massive legal target straight onto the upstream toolchain that keeps everything here free and legally clean under a strict bring your own ROM model.

### Speed, Focus, and Ownership

Staying closed early on also has a massive practical upside: speed and focus. Look at Cemu, which stayed completely closed source for nearly eight years. People threw endless conspiracy theories and accusations at the developers, demanding they open the code to "prove" they weren't using stolen material. Meanwhile, because they never had to babysit pull requests, bikeshedding, or copycat forks while the architecture was still taking shape, Cemu ran circles around the open source alternatives and only opened its code under MPL 2.0 once the project had fully matured.

If a project is built cleanly on original code and permissive dependencies, keeping it closed, or choosing a source available license over permissive open source, is entirely the developer's call. Keeping the runtime and porting kit locked down right now isn't only about protecting our work from thieves. It is the quality gate and the legal firewall that keep the scene from drowning in automated garbage.

At the end of the day, players who just want to boot up Budokai Tenkaichi 3 or Ultimate Ninja 5 with crossplay care about whether the build runs fast and works, not whether critics on Reddit get to read the C++ files.

## Current version: Alpha 2.3 (22 Nov 2026)

| Platform | File | SHA256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04, Vulkan GPU) | [`Nimbus-Alpha-2.3-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.3/Nimbus-Alpha-2.3-Linux-x86_64.run) | `ad962ce3b46a852036987a724a5f8eb1a41dfb56ebed37a44c397c093869d352` |
| Windows x64 (Windows 11, Vulkan GPU) | [`Nimbus-Alpha-2.3-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.3/Nimbus-Alpha-2.3-Windows-x64.zip) | `370ba19211863eb8ccc3d25c0cc95e9aaf2c4f52450aca02887664564a15a13f` |
| Android arm64 (Android 13+, Vulkan GPU) | [`Nimbus-Alpha-2.3-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.3/Nimbus-Alpha-2.3-Android-arm64.apk) | `d2122ff208fc5839687199ccf1fcb4078dbfd10891f67c3019fe24539ed75a6d` |

Also mirrored on the CDN: [R2 builds/alpha-2.3](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.3/). Older Alpha 2.2.x builds remain at [R2 builds/alpha-2.2.1](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2.1/) (Linux and Windows), [Android 2.2.2](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2.2/android/Nimbus-Alpha-2.2.2-Android-arm64.apk), and [R2 builds/alpha-2.2](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2/).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 2.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.3) (current), with earlier notes at [Alpha 2.2.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.2.2), [Alpha 2.2.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.2.1), and [Alpha 2.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.2). Trailer: [Alpha 2.3 trailer](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/video/alpha-2.3/TNRP-Alpha-2.3-Trailer.mp4). HD texture packs, including the new packs for Bleach: Heat the Soul 7, are on the [website](https://nimbusrecomp.org/#alpha-2-3).

# Nimbus Alpha 2.3

Nimbus Alpha 2.3

Dragon Ball remains the heart of TNRP. This release also adds a new native port that Charles made himself.

NEW GAME
Bleach: Heat the Soul 7 joins Nimbus as its fifteenth game on Linux, Windows and Android. Link your own disc image. A provided Everything Unlocked save makes the full roster selectable.
Play online with up to four players. Two player Quick Match opens at the Soul VS opponent list. The disc's menus remain in Traditional Chinese, with English mode names.
Bleach's HD texture packs load before play. Find My Files recognizes Bleach and Gundam HD packs by game ID rather than filename, and rejects packs meant for the wrong platform.

LIBRARY AND ONLINE
All 15 original covers now fill their Library cards, grouped by console, with READY/LINK and HD badges.
A new party, or a party with only its idle leader in it, follows the last game the leader opened in the Library. Moving the highlight alone does not change the party's game.
Fixed a black Waiting for Players window that could appear on Windows after switching games.
Online play uses your chosen player name, or "Player" when no name is set. It no longer falls back to your computer account name.
Tag Team, Gundam vs. Gundam NEXT PLUS and Bleach now take two and four player parties directly to the appropriate lobby or room.
Gundam vs. Gundam NEXT PLUS online battles now start correctly.

INCLUDES THE 2.2.1 AND 2.2.2 FIXES
Gundam's movies no longer stop the game on Linux or Windows.
Android still runs on Vulkan. If a device cannot start that way, it can still start, though it may run slower.

KNOWN ISSUES
Tag Team between two handhelds (seen on the RP5 and the RG Slide) can drop the connection during a fight. This was also present in 2.2.2. A fix is planned for 2.4.
Budokai Tenkaichi 3 can show a black screen on Pixel class phones.
Older HD packs and movies keep their existing formats and loading behavior where those exceptions were already approved.

# Nimbus Alpha 2.2.2 for Android (previous release)

A second hotfix for Android. Linux and Windows stay on 2.2.1.

## Fixed

- **Phones that still showed "Nimbus could not start graphics" on 2.2.1** (for example some Helio G99 phones on Android 14) now start their games. On these phones Nimbus uses a second graphics path.
- Heads up: the second graphics path is slower than Vulkan, so games on those phones may run slower. Every other device stays on Vulkan.
- Every other device runs exactly as on 2.2.1.

## Good to know

- After updating, Nimbus prepares its shaders once more on the first start.
- Online play is unchanged: 2.2.2 on Android plays with 2.2, 2.2.1 and 2.2.2 on every platform.

## Updating

Install the 2.2.2 APK over 2.2 or 2.2.1. It updates in place and keeps your links and saves. Do not uninstall first.

Thanks to Velkooky on Reddit for finding and reporting this bug.

### Also in 2.2.1

- **Black screen, then back to the Library, when starting any game on some Android devices.** On these devices every game failed to start graphics. Games now start.
- If a device's graphics driver still cannot run Nimbus, the Library now says so and names the graphics device, where before it gave no message.

**New in 2.2:** Naruto Shippuden: Ultimate Ninja 5 and Gundam vs. Gundam NEXT PLUS join as games thirteen and fourteen — the first Naruto and Gundam titles — with a new compressed HD pack standard, shaders prepared once for every game, and local 2-player in every game.

**Known issue:** Budokai Tenkaichi 3 shows a black screen on Pixel-class phones (Mali graphics, for example the Pixel 9a); this is still present in 2.3; a fix is planned.

**Tip:** for now, launch a game in single player a time or two before jumping into multiplayer.

Previous releases: [Alpha 2.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.1) (Nov 14, 2026) · [Alpha 2.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.0) (Nov 11, 2026) · [Alpha 1.9](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.9) (Nov 9, 2026) · [Alpha 1.8](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.8) (Nov 8, 2026) · [Alpha 1.7](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.7) (Nov 7, 2026) · [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6) (Nov 6, 2026) · [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, your own Tenkaichi Tag Team (USA, ULUS10537), Shin Budokai (USA, ULUS10081) and Shin Budokai – Another Road (USA, ULUS10234) ISO, CSO or ZSO, your own Infinite World (USA, SLUS-21842) disc image, your own Super Dragon Ball Z (USA, SLUS-21442) disc image, your own Budokai Tenkaichi 3 (USA, SLUS-21678) disc image, your own Ridge Racer 2 (Europe, UCES-00422) ISO, CSO or ZSO, your own Ultimate Ninja 5 (Europe, SLES-55605) disc image, and your own Gundam vs. Gundam NEXT PLUS (Japan, NPJH-50107) ISO, CSO or ZSO, and your own Bleach: Heat the Soul 7 (Asia, NPHG00087) ISO, CSO or ZSO. The runtime components for all fifteen games are bundled; no original disc images, ROMs or ISOs are included.

## What's new in Alpha 2.2

- **Naruto Shippuden: Ultimate Ninja 5** (PlayStation 2, Europe, SLES-55605) joins as a native port — the thirteenth game and the first Naruto title — on Linux, Windows and Android. Link your own disc image; nothing from the game ships with Nimbus. HD texture packs are on the website: PC 2x, 3x and 4x, plus Android 2x lite and full. Three optional "Faster picture" settings (Native glow, Fast bright blends, Fast cut-out edges) are off by default, which gives the exact picture.
- **Mobile Suit Gundam: Gundam vs. Gundam NEXT PLUS** (PlayStation Portable, Japan, NPJH-50107) joins as the fourteenth game — the first Gundam title — on Linux, Windows and Android, with the same HD pack tiers and a "Game text" setting: English (the default) or Original.
- **A new HD texture pack standard**, starting with the two new games: BC7 on PC, ASTC on Android, every detail level made offline, and the whole linked pack loaded into graphics memory before play starts — nothing loads or builds while you play, at about four times less video memory than uncompressed textures. The other twelve games keep their existing packs in 2.2.
- **Shaders are prepared once, for every game.** The one-time "Preparing shaders" pass after an install or update now covers every game that has a shader set; Budokai Tenkaichi 3, Ultimate Ninja 5 and Gundam vs. Gundam no longer compile their own shaders at their first start.
- **Local 2 players in every game** — even games that didn't ship with it in their original release. PSP fighters and Ridge Racer 2 open two linked consoles, each with its own picture; PS2 games read the second pad; GBA games show both consoles side by side.
- **Saves:** a new in-game setting for every game — My save or Everything unlocked (the provided save, on its own copy). Ridge Racer 2 boots on your own save, Sagas has a provided save, and Android GameCube games each have their own memory card.
- **Fast-forward** now works in the PS2 games, and from a controller (hold Back + RB, rebindable) and a touch button in every game.
- **Online fixes:** Tenkaichi Tag Team's false "Connection was lost" is fixed (both players update to 2.2), and Ridge Racer 2 rooms work on a fresh install again.
- **Early in this build** (to be finished in 2.3): player save states in PSP and PS2 games (off in multiplayer), and Android pause and resume when you switch apps.
- All twelve games from Alpha 2.1 remain fully playable.
- **Known issue:** Budokai Tenkaichi 3 shows a black screen on Pixel-class phones (Mali graphics, for example the Pixel 9a); this is still present in 2.3; a fix is planned. Gundam vs. Gundam's English text covers the main menu and its help text in 2.2; submenus and notices are still in Japanese.
- **Next up (2.3):** HD movies for the two new games, new-standard packs for the other twelve games, the Budokai Tenkaichi 3 Pixel fix, and finished save states.

Bring your own legally dumped games. No copyrighted game files are included.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. See the [architecture flow](#architecture-flow-from-disc-to-player) below.

**We don't pretend to be the hardware.**

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.



## Architecture flow: from disc to player

Read top to bottom. GameCube, Game Boy Advance, PSP, and PlayStation 2 each have their own intake and runtime work. Their paths join at the Nimbus host layer.

```text
01  SOURCE          Matching disc image or ROM
                         ↓
02  INTAKE          Identify the executable and map code and data
                         ↓
03  RECOMPILE       Translate game code ahead of time and connect it
                    to the console's native runtime and services
                         ↓
04  BUILD & VERIFY  Check required features through the real launcher
                    before final profiling and optimization
                         ↓
05  NATIVE CORES    15 game cores across four console families
                         ↓
06  NIMBUS HOST     Four console hosts → one shared Vulkan renderer
                    Launcher, input, audio, saves, and netplay
                         ↓
07  PACKAGE & SIGN  Freeze, check, and sign the release builds
                         ↓
08  RELEASE DOWNLOADS  Linux .run · Windows .zip · Android .apk
                       Optional HD packs are separate downloads
                         ↓
09  ONLINE          Crossplay on Linux, Windows and Android.
                    Parties, room codes, Quick Match; up to 8 players.
                    Play on regional servers.
                         ↓
10  PLAY            Link the matching disc image or ROM you own;
                    play locally or cross-play across platforms
```

**Parallel texture path:** Decode game art → upscale by texture class → build and verify the optional pack tiers → offer as separate downloads. The compressed packs for Bleach: Heat the Soul 7, Ultimate Ninja 5 and Gundam vs. Gundam NEXT PLUS load into graphics memory before play.

See the [full architecture notes](https://nimbusrecomp.org/architecture-notes) for the console-by-console map and release timeline.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
