# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road (USA PSP), Infinite World (USA PlayStation 2, SLUS-21842), Super Dragon Ball Z (USA PlayStation 2, SLUS-21442), and Ridge Racer 2 (Europe PlayStation Portable, UCES-00422) — eleven games in one launcher on Linux, Windows and Android (four consoles: GameCube, GBA, PSP and PS2), with online play and full 3-platform crossplay across 16 global server instances. Ridge Racer 2 is single player in 2.0; crossplay and 8-player racing are coming soon.

**Official website:** [nimbusrecomp.org](https://nimbusrecomp.org/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## Current version: Alpha 2.0 (Nov 11, 2026)

| Platform | File | SHA-256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04, Vulkan GPU) | [`Nimbus-Alpha-2.0-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.0/Nimbus-Alpha-2.0-Linux-x86_64.run) | `ad6d3a53641ed18f6b3ad62ec0074719890b8effb6c1751c474e1254d43fd0df` |
| Windows x64 (Windows 11, Vulkan GPU) | [`Nimbus-Alpha-2.0-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.0/Nimbus-Alpha-2.0-Windows-x64.zip) | `5e9b98b60367dac24590d3fd4392567c7e52ff2fb195f1a95761e9f675133186` |
| Android arm64 (Android 13+, Vulkan GPU) | [`Nimbus-Alpha-2.0-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-2.0/Nimbus-Alpha-2.0-Android-arm64.apk) | `f48a3ca7164a72b45dc7a8b7fd80220672a70e644fe8b49d717762bb7ac8d6a1` |

Also mirrored on the CDN: [R2 builds/alpha-2.0](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-2.0/).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 2.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-2.0). Trailer: [Alpha 2.0 trailer](https://nimbusrecomp.org/#alpha-2-0-trailer). HD texture packs (including Ridge Racer 2, Super Dragon Ball Z, Infinite World and earlier games) are on the [website](https://nimbusrecomp.org/#downloads). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbusrecomp.org/#modules).

**Fixed in 2.0:** Infinite World's classic FPS bug with standard textures. If you still see texture or frame-rate issues in Infinite World, please report them on the [website's bug report form](https://nimbusrecomp.org/#bug-report).

**Known issue:** Super Dragon Ball Z sound effects are too loud (about +6 dB); a fix is coming in an upcoming update.

**Tip:** for now, launch a game in single player a time or two before jumping into multiplayer.

Previous releases: [Alpha 1.9](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.9) (Nov 9, 2026) · [Alpha 1.8](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.8) (Nov 8, 2026) · [Alpha 1.7](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.7) (Nov 7, 2026) · [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6) (Nov 6, 2026) · [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, your own Tenkaichi Tag Team (USA, ULUS10537), Shin Budokai (USA, ULUS10081) and Shin Budokai – Another Road (USA, ULUS10234) ISO, CSO or ZSO, your own Infinite World (USA, SLUS-21842) disc image, your own Super Dragon Ball Z (USA, SLUS-21442) disc image, and your own Ridge Racer 2 (Europe, UCES-00422) ISO, CSO or ZSO. The runtime components for all eleven games are bundled; no original disc images, ROMs or ISOs are included.

## What's new in Alpha 2.0

- **Ridge Racer 2** (PlayStation Portable, UCES-00422) joins as a native recompilation — the eleventh game, the first racing title and the first European release — on Linux, Windows and Android, with optional HD texture and movie packs on the website. Single player in 2.0; crossplay and 8-player racing are coming soon.
- **Performance:** Ridge Racer 2 holds a stable 60 FPS in races, with 4.5x headroom on a Retroid Pocket 5 and 2.5-3x headroom on a Google Pixel 9a, both at 1080p with the HD packs.
- Shaders are prepared before you play. PSP, PS2 and GBA games now build everything they need behind the loading screen, so nothing compiles in the middle of a race or a fight.
- First-start preparation. After an install or update, Nimbus prepares shaders once with a progress bar. Later starts are fast, and games on the same console share the result.
- PS2 games (Infinite World, Super Dragon Ball Z) run lighter. Lower CPU overhead in the graphics path, far fewer draw calls when playing without an HD texture pack, and leaner shaders. Handhelds should run cooler and hold frame rate better in heavy scenes.
- No texture pop-in with PS2 HD packs. HD textures are ready before they are first shown.
- Vulkan is now the renderer on every platform. The OpenGL option has been removed.
- Fixes for Mali-GPU devices, including missing geometry in some scenes.
- Infinite World has been extremely optimized. Tested on a Retroid Pocket 5 and a Google Pixel 9a, it holds 60 FPS in fights with an average 2-2.5x headroom at 3x internal resolution (1080p) with the 2x lite Android texture pack applied.
- Super Dragon Ball Z holds a stable 60 FPS with 2-3x headroom on a Retroid Pocket 5.
- The three GameCube titles (Budokai, Budokai 2 and Sagas), the two GBA titles (Supersonic Warriors and Taiketsu) and the rest of the PSP titles (Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road) are fully playable, with more optimization to come.
- Fixed: Infinite World's classic FPS bug with standard textures. If you still see texture or frame-rate issues in Infinite World, please report them on the [website's bug report form](https://nimbusrecomp.org/#bug-report).
- Infinite World: updated game core with an accuracy fix.
- **Known issue:** Super Dragon Ball Z sound effects are too loud (about +6 dB); a fix is coming in an upcoming update.
- Full **3-platform crossplay** (Linux · Windows · Android) remains available for the existing games. Ridge Racer 2 is single player in 2.0; crossplay and 8-player racing are coming soon.
- **Next up:** crossplay and 8-player racing for Ridge Racer 2, and a fix for the Super Dragon Ball Z sound effects. More polish to come.

Bring your own legally dumped games. No copyrighted game files are included.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
