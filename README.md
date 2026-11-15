# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road (USA PSP), Infinite World (USA PlayStation 2, SLUS-21842), Super Dragon Ball Z (USA PlayStation 2, SLUS-21442), Budokai Tenkaichi 3 (USA PlayStation 2, SLUS-21678), and Ridge Racer 2 (Europe PlayStation Portable, UCES-00422) — twelve games in one launcher on Linux, Windows and Android (four consoles: GameCube, GBA, PSP and PS2), with online play and full 3-platform crossplay across 16 global server instances. Ridge Racer 2 went online in 2.1, with 2–8 player crossplay racing through Wireless Battle.

**Official website:** [nimbusrecomp.org](https://nimbusrecomp.org/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## Current version: Alpha 2.1 (Nov 14, 2026)

| Platform | File | SHA-256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04, Vulkan GPU) | [`Nimbus-Alpha-2.1-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.1/Nimbus-Alpha-2.1-Linux-x86_64.run) | `47f6bc77f2254e2d25122376352bcff259415a97be3affcfc88df1caedc23b03` |
| Windows x64 (Windows 11, Vulkan GPU) | [`Nimbus-Alpha-2.1-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.1/Nimbus-Alpha-2.1-Windows-x64.zip) | `773ce328e2f5fa1f8628e07d3aa1fd9618837cdb3b850f68b54aab23a268fef1` |
| Android arm64 (Android 13+, Vulkan GPU) | [`Nimbus-Alpha-2.1-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.1/Nimbus-Alpha-2.1-Android-arm64.apk) | `68aa3acbe1161b271bd7ea0da44d77049e081e756a1443360425de82209a0124` |

Also mirrored on the CDN: [R2 builds/alpha-2.1](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.1/).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 2.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.1). Trailer: [Alpha 2.1 trailer](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/video/alpha-2.1/TNRP-BT3-Early-Trailer.mp4). HD texture packs (including Budokai Tenkaichi 3, Ridge Racer 2, Super Dragon Ball Z, Infinite World and earlier games) are on the [website](https://nimbusrecomp.org/#downloads). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbusrecomp.org/#modules).

**New in 2.1:** Budokai Tenkaichi 3 joins as game twelve, and Ridge Racer 2 goes online — Alpha 2.0 made both promises, and 2.1 delivers both.

**Known issue:** Super Dragon Ball Z sound effects are too loud (about +6 dB); a fix is coming in an upcoming update.

**Tip:** for now, launch a game in single player a time or two before jumping into multiplayer.

Previous releases: [Alpha 2.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.0) (Nov 11, 2026) · [Alpha 1.9](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.9) (Nov 9, 2026) · [Alpha 1.8](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.8) (Nov 8, 2026) · [Alpha 1.7](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.7) (Nov 7, 2026) · [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6) (Nov 6, 2026) · [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, your own Tenkaichi Tag Team (USA, ULUS10537), Shin Budokai (USA, ULUS10081) and Shin Budokai – Another Road (USA, ULUS10234) ISO, CSO or ZSO, your own Infinite World (USA, SLUS-21842) disc image, your own Super Dragon Ball Z (USA, SLUS-21442) disc image, your own Budokai Tenkaichi 3 (USA, SLUS-21678) disc image, and your own Ridge Racer 2 (Europe, UCES-00422) ISO, CSO or ZSO. The runtime components for all twelve games are bundled; no original disc images, ROMs or ISOs are included.

## What's new in Alpha 2.1

- **Budokai Tenkaichi 3** (PlayStation 2, SLUS-21678) joins as a native recompilation — the twelfth game — on Linux, Windows and Android, through the same shared Vulkan renderer as every other Nimbus game. Link your own disc image (ISO, or a zip/7z holding it); nothing from the game ships with Nimbus. Optional HD texture packs are on the website: PC 2x, 3x and 4x, plus Android packs including a small "2x-lite" for handhelds.
- **Budokai Tenkaichi 3 online play**, with crossplay between all three platforms: Quick Match, Host Online with a join code (no port forwarding), Join by Code and Host LAN. Online starts both players directly at the Versus Menu (Single Battle and Team Battle) with a fully unlocked save.
- Budokai Tenkaichi 3: new video options — Distance blur (the original far-scenery blur, off by default) and Smooth motion (in-between pictures at 60 or 120; off by default, the game itself stays at 30).
- **Ridge Racer 2 goes online.** Wireless Battle now works online through private rooms and parties — Friends → Start with Party, or join with a room code. Multiplayer starts straight at Host Race / Search Race; solo play starts at the main menu. The 8-player cross-platform multiplayer work that Ridge Racer 2 set up in 2.0 now powers online play in both Ridge Racer 2 and Budokai Tenkaichi 3.
- Ridge Racer 2: player name tags with per-player colours.
- Ridge Racer 2: new Android touch HUD for racing.
- Shaders are prepared before you play, PS2 games run lighter, Vulkan is the renderer on every platform, and Mali-GPU devices get fixes.
- All eleven games from Alpha 2.0 remain fully playable, with more optimization to come.
- **Known issue:** Super Dragon Ball Z sound effects are too loud (about +6 dB); a fix is coming in an upcoming update.
- Full **3-platform crossplay** (Linux · Windows · Android) is available across the library, now including Budokai Tenkaichi 3 and Ridge Racer 2.
- **Next up:** a fix for the Super Dragon Ball Z sound effects, and more optimization and polish across the whole library.

Bring your own legally dumped games. No copyrighted game files are included.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
