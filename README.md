# Awesome Browser Game Ports [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **real games that run directly inside your browser** — powered by WebAssembly, Emscripten, DOSBox, [js-dos](https://js-dos.com/), WebGL, source ports, and emulation. No installs, no plugins.

Everything here runs in a modern browser. Some projects are freeware or fully open source and play instantly; others are open-source *engines* that need you to supply your own legally obtained game files.

**Legend**

| Icon | Meaning |
|:----:|---------|
| 🎮 | Plays instantly (freeware / open assets included) |
| 🔑 | Requires your own original game files/assets |
| 🌐 | Multiplayer supported |
| 📚 | Library / collection of many games |

---

## Contents

- [Native Browser Ports](#native-browser-ports)
- [FPS Games](#fps-games)
- [Adventure Games](#adventure-games)
- [RPGs](#rpgs)
- [RTS / Strategy](#rts--strategy)
- [Action / Platformers](#action--platformers)
- [DOS Game Libraries](#dos-game-libraries)
- [Windows Game Libraries](#windows-game-libraries)
- [Console & Arcade Libraries](#console--arcade-libraries)
- [Emulators](#emulators)
- [Source Ports](#source-ports)
- [Open Source Games](#open-source-games)
- [Game Engines](#game-engines)
- [Flash & Java Preservation](#flash--java-preservation)
- [Recommended Starting Points](#recommended-starting-points)
- [Related Awesome Lists](#related-awesome-lists)
- [Coming Soon](#coming-soon)
- [Contributing](#contributing)
- [License](#license)
- [Disclaimer](#disclaimer)

---

## Native Browser Ports

Standalone ports you can click and play — no library or emulator front-end required.

| Game | Notes | Assets |
|------|-------|:------:|
| [Half-Life 2](https://hl2.slqnt.dev/) | Source Engine port running through WebAssembly. | 🔑 |
| [WebXash (Half-Life / Counter-Strike)](https://x8bitrain.github.io/webXash/) | Xash3D-based GoldSrc port; supports original assets. | 🔑 |
| [Q3JS](https://q3js.com/) | Quake III Arena running entirely in the browser (WebAssembly, online servers). | 🎮🌐 |
| [Wolfenstein 3D](https://dos.zone/wolfenstein-3d-may-05-1992/) | The classic Wolf3D, playable online via js-dos. | 🎮 |
| [DiabloWeb](https://d07riv.github.io/diabloweb/) | Diablo in the browser via DevilutionX (needs `DIABDAT.MPQ`, shareware works). | 🔑 |
| [Red Alert 2: Chrono Divide](https://chronodivide.com/) | Full browser recreation of C&C: Red Alert 2, cross-platform multiplayer. | 🎮🌐 |
| [OpenLara](http://xproger.info/projects/OpenLara/) | WebGL engine for the original Tomb Raider — demo level included. | 🎮 |
| [Silent Space Marine](https://silentspacemarine.com/) | Multiplayer Doom on Cloudflare Workers (Chocolate Doom + WebSockets). | 🎮🌐 |

---

## FPS Games

### Doom Family

Runs Doom, Doom II, Ultimate Doom, Final Doom, Heretic, Hexen, and Strife.

| Project | Notes | Assets |
|---------|-------|:------:|
| [WadCMD](https://wadcmd.com/) | Upload and play any `.wad` in the browser (PWA, installable). | 🔑 |
| [wasm-doom](https://github.com/lazarv/wasm-doom) | Chocolate/Crispy Doom compiled to WebAssembly. | 🔑 |
| [Dwasm](https://github.com/GMH-Code/Dwasm) | PrBoom+ / PrBoomX engine in the browser. | 🔑 |
| [Cloudflare doom-wasm](https://github.com/cloudflare/doom-wasm) | Chocolate Doom WASM port with WebSockets multiplayer. | 🔑🌐 |
| [Freedoom](https://freedoom.github.io/) | Free game data — pair it with any of the ports above to play instantly. | 🎮 |

### Quake Family

Quake, Quake II, and Quake III Arena.

- [Q3JS](https://q3js.com/) — Quake III Arena, multiplayer in-browser (WebAssembly) 🎮🌐
- [NetQuake.io](https://www.netquake.io/) — the original Quake in your browser 🎮🌐
- [ioquake3](https://ioquake3.org/) — the source port these are built on 🔑

### Build Engine Games

Ken Silverman's Build engine shooters, playable in-browser via js-dos.

| Game | Link | Assets |
|------|------|:------:|
| Duke Nukem 3D | [dos.zone](https://dos.zone/duke-nukem-3d-1996/) | 🎮 |
| Blood | [dos.zone](https://dos.zone/blood-may-31-1997/) | 🎮 |
| Shadow Warrior | [dos.zone](https://dos.zone/shadow-warrior/) | 🎮 |
| Redneck Rampage | [dos.zone](https://dos.zone/redneck-rampage-1997/) | 🎮 |

> Prefer a modern source port? [EDuke32](https://www.eduke32.com/) also has WebAssembly builds (bring your own game files 🔑).

### GoldSrc

Half-Life, Counter-Strike, Team Fortress Classic, and Opposing Force.

- [WebXash](https://x8bitrain.github.io/webXash/) — Xash3D-FWGS in the browser 🔑
- [Xash3D-FWGS](https://github.com/FWGS/xash3d-fwgs) — the engine behind it 🔑

### Marathon

- [AlephWeb](https://github.com/TotallyGatsby/AlephWeb) — WebGL port of Aleph One (Marathon 2 / Infinity) 🎮
- [Aleph One](https://alephone.lhowon.org/) — the open-source Marathon engine (free trilogy data) 🎮

---

## Adventure Games

Point-and-click classics — mostly LucasArts/Sierra titles running via js-dos or ScummVM in the browser.

| Game | Link | Assets |
|------|------|:------:|
| The Secret of Monkey Island | [dos.zone](https://dos.zone/the-secret-of-monkey-island/) | 🎮 |
| Day of the Tentacle | [ClassicReload](https://classicreload.com/day-of-the-tentacle.html) | 🎮 |
| Broken Sword: Shadow of the Templars | [PlayClassic](https://playclassic.games/games/point-n-click-adventure-dos-games-online/play-broken-sword-the-shadow-of-the-templars-online/) | 🎮 |
| Beneath a Steel Sky *(freeware)* | [ScummWEB](https://scummweb.tsilva.eu/) | 🎮 |

### Engines & Collections

- [ScummWEB](https://scummweb.tsilva.eu/) — browser-first ScummVM collection, quick-play adventures 🎮
- [ScummVM](https://www.scummvm.org/) — the engine behind them; runs Monkey Island, Sam & Max, Full Throttle, Simon the Sorcerer, Indiana Jones, and hundreds more 🔑
- [ScummVM freeware games](https://www.scummvm.org/games/) — legally free titles you can play immediately 🎮

---

## RPGs

| Game | Notes | Link | Assets |
|------|-------|------|:------:|
| Diablo | Browser port using DevilutionX | [DiabloWeb](https://d07riv.github.io/diabloweb/) | 🔑 |
| Ultima Underworld: The Stygian Abyss | Landmark first-person RPG, in-browser via js-dos | [dos.zone](https://dos.zone/ultima-underworld-the-stygian-abyss-1992/) | 🎮 |
| Prince of Persia | DOS version in-browser via js-dos | [dos.zone](https://dos.zone/prince-of-persia-1990/) | 🎮 |
| Betrayal at Krondor | Classic RPG, playable online | [PlayClassic](https://playclassic.games/games/role-playing-dos-games-online/) | 🎮 |
| Morrowind | Experimental OpenMW WebAssembly builds | [OpenMW](https://openmw.org/) | 🔑 |

---

## RTS / Strategy

| Game / Project | Notes | Link | Assets |
|----------------|-------|------|:------:|
| Red Alert 2 | Full browser recreation, multiplayer | [Chrono Divide](https://chronodivide.com/) | 🎮🌐 |
| C&C / Red Alert / Dune 2000 | Open-source engine reimplementation | [OpenRA](https://www.openra.net/) | 🎮🌐 |
| Freeciv (Civilization-like) | HTML5 / WebGL, play online | [play.freeciv.org](http://play.freeciv.org/) | 🎮🌐 |
| Dune II: The Building of a Dynasty | The RTS that started the genre (OpenDUNE build) | [dos.zone](https://dos.zone/dune-ii-the-building-of-a-dynasty-dec-1992/) | 🎮 |
| Warcraft II: Tides of Darkness | Classic RTS, in-browser via js-dos (multiplayer) | [dos.zone](https://dos.zone/warcraft-ii-tides-of-darkness/) | 🎮🌐 |
| Transport Tycoon | Open-source remake OpenTTD | [OpenTTD](https://openttd.org/) | 🎮 |

---

## Action / Platformers

| Game | Notes | Link | Assets |
|------|-------|------|:------:|
| Tomb Raider | WebGL engine, demo level included | [OpenLara](http://xproger.info/projects/OpenLara/) | 🎮 |
| Prince of Persia | Original DOS game in-browser | [dos.zone](https://dos.zone/prince-of-persia-1990/) | 🎮 |
| SuperTuxKart | Open-source kart racer, WebAssembly build | [SuperTuxKart](https://supertuxkart.net/) | 🎮 |

---

## DOS Game Libraries 📚

| Library | Notes |
|---------|-------|
| [Internet Archive — MS-DOS](https://archive.org/details/softwarelibrary_msdos_games) | Thousands of preserved, playable DOS games. |
| [DOS Zone](https://dos.zone/) | Large curated collection powered by js-dos. |
| [ClassicReload](https://classicreload.com/) | DOS and Windows classics in-browser. |
| [PlayClassic.games](https://playclassic.games/) | Clean DOS game archive. |
| [js-dos](https://js-dos.com/) | The DOSBox-in-WebAssembly engine that powers most of the above. |

---

## Windows Game Libraries 📚

| Project | Notes |
|---------|-------|
| [Emupedia / EmuOS](https://emupedia.net/) | Simulated Win 3.11–ME desktop preloaded with classic games and apps. |
| [v86](https://copy.sh/v86/) | Emulates full x86 PCs — DOS, Windows 95/98, Linux, BSD, in the browser. |
| [ClassicReload](https://classicreload.com/) | Windows and DOS classics. |

---

## Console & Arcade Libraries 📚

| Project | Notes |
|---------|-------|
| [EmulatorJS](https://emulatorjs.org/) | NES, SNES, N64, Game Boy/GBA, DS, Genesis, PlayStation, PSP, Atari, Neo Geo, Arcade, and more. |
| [Recompiled Games](https://recompgames.net/play) | Catalog of 70+ browser-playable recompilations and decompilation ports (N64, PS2, Xbox, PC and more), each labeled with where it is hosted and whether you need your own game files. |
| [RetroArch Web Player](https://web.libretro.com/) | Official browser build of RetroArch. |
| [webretro](https://binbashbanana.github.io/webretro/) | Standalone RetroArch-in-browser front-end. |
| [webЯcade](https://www.webrcade.com/) | Beautiful, app-store-style web front-end for emulation. |

---

## Emulators

| Category | Projects |
|----------|----------|
| **DOS** | [js-dos](https://js-dos.com/) · [DOSBox](https://www.dosbox.com/) |
| **PC / x86** | [v86](https://copy.sh/v86/) |
| **Console / Arcade** | [EmulatorJS](https://emulatorjs.org/) · [RetroArch Web](https://web.libretro.com/) · [webretro](https://binbashbanana.github.io/webretro/) |
| **Flash** | [Ruffle](https://ruffle.rs/) |
| **Java** | [CheerpJ](https://cheerpj.com/) |

---

## Source Ports

Open-source engines compiled for the browser (bring your own game data).

| Engine | Powers | Link |
|--------|--------|------|
| Xash3D-FWGS | GoldSrc (Half-Life, CS) | <https://github.com/FWGS/xash3d-fwgs> |
| Chocolate Doom | Doom | <https://www.chocolate-doom.org/> |
| wasm-doom | Doom | <https://github.com/lazarv/wasm-doom> |
| ioquake3 | Quake III | <https://ioquake3.org/> |
| DevilutionX | Diablo | <https://github.com/diasurgical/devilutionX> |
| OpenJK | Jedi Outcast / Academy | <https://github.com/JACoders/OpenJK> |
| OpenMW | Morrowind | <https://openmw.org/> |
| Aleph One | Marathon | <https://alephone.lhowon.org/> |
| OpenLara | Tomb Raider | <https://github.com/XProger/OpenLara> |

---

## Open Source Games

Fully open-source games — several ship official or community WebAssembly/WebGL builds.

| Game | Type | Link |
|------|------|------|
| OpenTTD | Transport sim | <https://openttd.org/> |
| OpenRA | RTS (C&C engine) | <https://www.openra.net/> |
| Freeciv-web | 4X strategy | <http://play.freeciv.org/> |
| Luanti (Minetest) | Voxel sandbox | <https://www.luanti.org/> |
| Veloren | Voxel action-RPG | <https://veloren.net/> |
| Endless Sky | Space trading | <https://endless-sky.github.io/> |
| Battle for Wesnoth | Turn-based strategy | <https://www.wesnoth.org/> |
| SuperTuxKart | Kart racer | <https://supertuxkart.net/> |

---

## Game Engines

Toolkits for shipping your own games to the browser.

| Engine | Website |
|--------|---------|
| Emscripten | <https://emscripten.org/> |
| Godot (Web export) | <https://godotengine.org/> |
| Unity (WebGL) | <https://unity.com/> |
| Unreal (HTML5, community) | <https://github.com/UnrealEngineHTML5> |
| PlayCanvas | <https://playcanvas.com/> |

---

## Flash & Java Preservation

| Project | Notes |
|---------|-------|
| [Ruffle](https://ruffle.rs/) | Modern Flash Player emulator written in Rust/WebAssembly. |
| [Flashpoint Archive](https://flashpointarchive.org/) | The largest Flash & web-game preservation project. |
| [CheerpJ](https://cheerpj.com/) | Run Java applets and applications directly in the browser. |

---

## Recommended Starting Points

| ⭐ | Project | Why |
|:--:|---------|-----|
| ⭐ | [Half-Life 2](https://hl2.slqnt.dev/) | A full AAA Source game in a browser tab. |
| ⭐ | [Q3JS](https://q3js.com/) | Instant, free, multiplayer Quake III. |
| ⭐ | [Chrono Divide](https://chronodivide.com/) | Red Alert 2 online, no download. |
| ⭐ | [DiabloWeb](https://d07riv.github.io/diabloweb/) | Diablo (shareware data works). |
| ⭐ | [Emupedia / EmuOS](https://emupedia.net/) | A whole retro OS full of games. |
| ⭐ | [Internet Archive DOS](https://archive.org/details/softwarelibrary_msdos_games) | Thousands of one-click classics. |
| ⭐ | [EmulatorJS](https://emulatorjs.org/) | Every console emulator in one place. |
| ⭐ | [ScummVM](https://www.scummvm.org/) | The definitive point-and-click library. |

---

## Related Awesome Lists

- [awesome-wasm](https://github.com/mbasso/awesome-wasm) — WebAssembly resources
- [awesome-game-remakes](https://github.com/radek-sprta/awesome-game-remakes) — open-source game remakes
- [awesome-gamedev](https://github.com/Kavex/GameDev-Resources) — general game-development resources

---

## Coming Soon

- [ ] Browser MMOs
- [ ] More Source Engine ports
- [ ] Unreal Engine web ports
- [ ] Unity classics
- [ ] Browser Linux distributions
- [ ] Browser Windows software
- [ ] Browser game-development tools
- [ ] WebGPU projects
- [ ] More multiplayer ports
- [ ] Experimental / bleeding-edge ports

---

## Contributing

Contributions are welcome! Please open a Pull Request if you know of a browser port, open-source project, WebAssembly engine, emulator, preservation project, or classic game collection that belongs here.

**Please include:**

- Project name and URL
- A brief, factual description
- License (if known)
- Whether original game assets are required (use the 🎮 / 🔑 legend)

Keep entries alphabetical within a section where it makes sense, and make sure links actually work before submitting.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this list. The underlying **MIT License** also applies to any repository code.

---

## Disclaimer

This repository links only to publicly available projects. Ownership of the games, engines, trademarks, and copyrights belongs to their respective owners. Some projects require users to provide their own legally obtained game assets. No copyrighted game data is hosted here.
