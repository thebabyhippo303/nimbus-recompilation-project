# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road (USA PSP), Infinite World (USA PlayStation 2, SLUS-21842), Super Dragon Ball Z (USA PlayStation 2, SLUS-21442), Budokai Tenkaichi 3 (USA PlayStation 2, SLUS-21678), Ridge Racer 2 (Europe PlayStation Portable, UCES-00422), Naruto Shippuden: Ultimate Ninja 5 (Europe PlayStation 2, SLES-55605), and Mobile Suit Gundam: Gundam vs. Gundam NEXT PLUS (Japan PlayStation Portable, NPJH-50107) — fourteen games in one launcher on Linux, Windows and Android (four consoles: GameCube, GBA, PSP and PS2), with online play and full 3-platform crossplay on regional servers. Ridge Racer 2 went online in 2.1, with 2–8 player crossplay racing through Wireless Battle.

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
- **Bleach: Heat the Soul 7** (JP, coming in Alpha 2.3): Eighting's last PSP Bleach fighter, with its 80+ fighters and 4-player battles moving from local Ad-Hoc to online crossplay.
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

## Current version: Alpha 2.2.2 (Nov 20, 2026) — Android hotfix; Linux and Windows stay on Alpha 2.2.1.

| Platform | File | SHA-256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04, Vulkan GPU) | [`Nimbus-Alpha-2.2-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.2/Nimbus-Alpha-2.2-Linux-x86_64.run) | `a2b96ccd6a46af348fc68705cc04be6b27b88af2ca3752b96724327c41266f35` |
| Windows x64 (Windows 11, Vulkan GPU) | [`Nimbus-Alpha-2.2-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.2/Nimbus-Alpha-2.2-Windows-x64.zip) | `80058e6508d5fa1e560ca9d02d65adf3da3602e2ac8a784a9da04c9d0a63b6e8` |
| Android arm64 (Android 13+, Vulkan GPU) | [`Nimbus-Alpha-2.2.2-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.2.2/Nimbus-Alpha-2.2.2-Android-arm64.apk) | `5507ffd0f88e7e86367a61621f38b0482dbfcbd45de9d621b1b5d66f5087aa60` |

Also mirrored on the CDN: [R2 builds/alpha-2.2.1](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2.1/) (Linux and Windows) and [Android 2.2.2](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2.2/android/Nimbus-Alpha-2.2.2-Android-arm64.apk). Prior Android 2.2.1 and 2.2 files remain at [R2 builds/alpha-2.2.1/android](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2.1/android/Nimbus-Alpha-2.2.1-Android-arm64.apk) and [R2 builds/alpha-2.2](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.2/).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 2.2.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.2.2) (current Android hotfix), [Alpha 2.2.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.2.1) (Linux, Windows, and the first Android hotfix), and [Alpha 2.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.2). Trailer: [Alpha 2.2 trailer](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/video/alpha-2.2/TNRP-Alpha-2.2-Trailer-web.mp4). HD texture packs (including the new compressed packs for Ultimate Ninja 5 and Gundam vs. Gundam, plus packs for Budokai Tenkaichi 3, Ridge Racer 2, Super Dragon Ball Z, Infinite World and earlier games) are on the [website](https://nimbusrecomp.org/#downloads).

# Nimbus Alpha 2.2.2 for Android

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

**Known issue:** Budokai Tenkaichi 3 shows a black screen on Pixel-class phones (Mali graphics, for example the Pixel 9a); a fix is planned for 2.3.

**Tip:** for now, launch a game in single player a time or two before jumping into multiplayer.

Previous releases: [Alpha 2.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.1) (Nov 14, 2026) · [Alpha 2.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.0) (Nov 11, 2026) · [Alpha 1.9](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.9) (Nov 9, 2026) · [Alpha 1.8](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.8) (Nov 8, 2026) · [Alpha 1.7](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.7) (Nov 7, 2026) · [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6) (Nov 6, 2026) · [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, your own Tenkaichi Tag Team (USA, ULUS10537), Shin Budokai (USA, ULUS10081) and Shin Budokai – Another Road (USA, ULUS10234) ISO, CSO or ZSO, your own Infinite World (USA, SLUS-21842) disc image, your own Super Dragon Ball Z (USA, SLUS-21442) disc image, your own Budokai Tenkaichi 3 (USA, SLUS-21678) disc image, your own Ridge Racer 2 (Europe, UCES-00422) ISO, CSO or ZSO, your own Ultimate Ninja 5 (Europe, SLES-55605) disc image, and your own Gundam vs. Gundam NEXT PLUS (Japan, NPJH-50107) ISO, CSO or ZSO. The runtime components for all fourteen games are bundled; no original disc images, ROMs or ISOs are included.

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
- **Known issue:** Budokai Tenkaichi 3 shows a black screen on Pixel-class phones (Mali graphics, for example the Pixel 9a); a fix is planned for 2.3. Gundam vs. Gundam's English text covers the main menu and its help text in 2.2; submenus and notices are still in Japanese.
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
05  NATIVE CORES    14 game cores across four console families
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

**Parallel texture path:** Decode game art → upscale by texture class → build and verify the optional pack tiers → offer as separate downloads. The compressed packs for Ultimate Ninja 5 and Gundam vs. Gundam NEXT PLUS load into graphics memory before play.

See the [full architecture notes](https://nimbusrecomp.org/architecture-notes) for the console-by-console map and release timeline.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
