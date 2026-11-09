# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road (USA PSP), and Infinite World (USA PlayStation 2, SLUS-21842) — nine games in one launcher on Linux, Windows and Android (four consoles: GameCube, GBA, PSP and PS2), with online play and full 3-platform crossplay across 16 global server instances.

**Official website:** [nimbusrecomp.org](https://nimbusrecomp.org/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## Current version: Alpha 1.8 (Nov 8, 2026)

| Platform | File | SHA-256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04) | [`Nimbus-Alpha-1.8-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.8/Nimbus-Alpha-1.8-Linux-x86_64.run) | `dfc81ea01a0826ebd410abb9b116825a7aa1e4454933f3b5e30e63325c21f2bb` |
| Windows x64 (Windows 11, Vulkan or D3D12 GPU) | [`Nimbus-Alpha-1.8-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.8/Nimbus-Alpha-1.8-Windows-x64.zip) | `ddac9a290290ef8945d13a72676a82490b060a42246fa0f8bc4dba7742a3d6a4` |
| Android arm64 (Android 13+) | [`Nimbus-Alpha-1.8-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.8/Nimbus-Alpha-1.8-Android-arm64.apk) | `40a070969eb9d85ddf1642ee5836eb5718bfb11cd70480eb25c8c9f108e2a09a` |

Also mirrored on the CDN: [R2 builds/alpha-1.8](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-1.8/).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 1.8](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.8). HD texture packs (including Infinite World and earlier games) are on the [website](https://nimbusrecomp.org/#downloads). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbusrecomp.org/#modules).

**Known issue:** Infinite World has an FPS bug when using standard textures. Use the Infinite World texture packs on the [website](https://nimbusrecomp.org/#downloads) as the workaround.

Previous releases: [Alpha 1.7](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.7) (Nov 7, 2026) · [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6) (Nov 6, 2026) · [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, your own Tenkaichi Tag Team (USA, ULUS10537), Shin Budokai (USA, ULUS10081) and Shin Budokai – Another Road (USA, ULUS10234) ISO, CSO or ZSO, and your own Infinite World (USA, SLUS-21842) disc image. The runtime components for all nine games are bundled; no original disc images, ROMs or ISOs are included.

## What's new in Alpha 1.8

- **Dragon Ball Z: Infinite World** (PlayStation 2, SLUS-21842) joins as a native recompilation — the ninth game — and PS2 is the fourth console, on Linux, Windows and Android, with HD texture packs and general optimizations.
- **Known issue:** Infinite World has an FPS bug when using standard textures. Use the Infinite World texture packs on the website as the workaround.
- Full **3-platform crossplay** (Linux · Windows · Android) across the nine-game launcher.
- **Next up (Alpha 1.9):** Super Dragon Ball Z — coming soon only.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
