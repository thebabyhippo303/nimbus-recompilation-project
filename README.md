# The Nimbus Recompilation Project (TNRP)

**TNRP** (The Nimbus Recompilation Project, formerly The Nimbus Project) is a free fan project by Animorph Allocations.

Native ports of Dragon Ball Z: Budokai, Budokai 2 and Sagas (NTSC-U GameCube), Supersonic Warriors and Taiketsu (USA Game Boy Advance), Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road (USA PSP), and Infinite World (USA PlayStation 2, SLUS-21842) and Super Dragon Ball Z (USA PlayStation 2, SLUS-21442) — ten games in one launcher on Linux, Windows and Android (four consoles: GameCube, GBA, PSP and PS2), with online play and full 3-platform crossplay across 16 global server instances.

**Official website:** [nimbusrecomp.org](https://nimbusrecomp.org/)

This repository holds the finished release distros only. Grab them from [Releases](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases).

## Current version: Alpha 1.9 (Nov 9, 2026)

| Platform | File | SHA-256 |
|---|---|---|
| Linux x86_64 (Ubuntu 26.04) | [`Nimbus-Alpha-1.9-Linux-x86_64.run`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.9/Nimbus-Alpha-1.9-Linux-x86_64.run) | `484fb54d087c4cef949565b54180e68f469f00093bfc8255fdcb996f557a2166` |
| Windows x64 (Windows 11, Vulkan or D3D12 GPU) | [`Nimbus-Alpha-1.9-Windows-x64.zip`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.9/Nimbus-Alpha-1.9-Windows-x64.zip) | `b5b94f2a90dfbd6a9da5769fbb50cb4999a0e516cd57337b6ffbc38510591950` |
| Android arm64 (Android 13+) | [`Nimbus-Alpha-1.9-Android-arm64.apk`](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/download/alpha-1.9/Nimbus-Alpha-1.9-Android-arm64.apk) | `8bdd9706bd1f51241f6d1f7d2d083d3d3f41ac2c453505e077a2de9c6965eb2a` |

Also mirrored on the CDN: [R2 builds/alpha-1.9](https://pub-c43e1e02f5fe49a39b0aae898e74e6ce.r2.dev/builds/alpha-1.9/).

Check your download against `SHA256SUMS` (`sha256sum -c SHA256SUMS`). Release notes: [Alpha 1.9](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.9). Trailer: [Alpha 1.9 trailer](https://nimbusrecomp.org/#alpha-1-9-trailer). HD texture packs (including Super Dragon Ball Z, Infinite World and earlier games) are on the [website](https://nimbusrecomp.org/#downloads). Separate module downloads (host, renderer and game cores) are on the [website](https://nimbusrecomp.org/#modules).

**Known issue:** Infinite World has an FPS bug when using standard textures. Use the Infinite World texture packs on the [website](https://nimbusrecomp.org/#downloads) as the workaround. Super Dragon Ball Z has a few minor audio issues.

**Tip:** for now, launch a game in single player a time or two before jumping into multiplayer.

Previous releases: [Alpha 1.8](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.8) (Nov 8, 2026) · [Alpha 1.7](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.7) (Nov 7, 2026) · [Alpha 1.6](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.6) (Nov 6, 2026) · [Alpha 1.5](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.5) (Nov 5, 2026) · [Alpha 1.4](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.4) (Nov 3, 2026) · [Alpha 1.3](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.3) (Nov 2, 2026) · [Alpha 1.2](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.2) (Nov 2, 2026) · [Alpha 1.1](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.1) (Nov 2, 2026) · [Alpha 1.0](https://github.com/thebabyhippo303/nimbus-recompilation-project/releases/tag/alpha-1.0) (Nov 1, 2026).

You need your own NTSC-U discs, your own Supersonic Warriors (USA) and Taiketsu (USA) ROMs, your own Tenkaichi Tag Team (USA, ULUS10537), Shin Budokai (USA, ULUS10081) and Shin Budokai – Another Road (USA, ULUS10234) ISO, CSO or ZSO, your own Infinite World (USA, SLUS-21842) disc image, and your own Super Dragon Ball Z (USA, SLUS-21442) disc image. The runtime components for all ten games are bundled; no original disc images, ROMs or ISOs are included.

## What's new in Alpha 1.9

- **Super Dragon Ball Z** (PlayStation 2, SLUS-21442) joins as a native recompilation — the tenth game — on Linux, Windows and Android, with optional HD texture packs on the website.
- Performance improvements for the three PSP-era games (Tenkaichi Tag Team, Shin Budokai and Shin Budokai – Another Road).
- Configurable, bindable keyboard, controller and touch controls on Windows, Linux and Android.
- New franchise- and platform-agnostic logo.
- Bug fixes and minor improvements to the launcher UI, plus random bug fixes.
- **Known issues:** Infinite World still has an FPS bug when using standard textures (use the Infinite World texture packs on the website as the workaround). Super Dragon Ball Z has a few minor audio issues.
- Full **3-platform crossplay** (Linux · Windows · Android) across the ten-game launcher.
- **Next up:** shader stutter is the next optimization target, especially in the newer titles. More polish to come.

Bring your own legally dumped games. No copyrighted game files are included.

## How TNRP works

TNRP runs on a hybrid core that sits between recompilation and decompilation. Each game has its own native core, running on a shared Nimbus host and renderer. There's no emulator and no interpreter emulating the hardware. Every game can be played in Original or Remastered mode. Detailed architecture notes will be posted on the website later.

## Source

The Nimbus Recompilation Project is closed source for now, while server hosting, networking and cross-platform compatibility get sorted out, and to keep development focused. Open source is planned, along with a mature toolset. Everything is free, and we don't take donations. Third-party licenses and notices are included inside each download.

Contact: TheNimbusProject@yahoo.com

Made with AI assistance.
