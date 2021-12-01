<p align="center">
    <img src="https://styles.redditmedia.com/t5_2qw2g/styles/communityIcon_itciy1qmjp871.png?width=256&s=b9a021ec4e8a588ba97530546668d3ba88136630" />
</p>

# Awesome GameMaker 2 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
An awesome list of 100+ libraries, snippets, guides, and projects for GameMaker Studio 2. 😎

Many libraries here will completely replace native tools in the IDE. I highly recommend exploring everything here so you can start making games as quickly as possible!

This is based on a list from [GameMaker Libraries](https://github.com/FaultyFunctions/GameMakerLibraries) and from Gleb Tsereteli's [Google Doc](https://docs.google.com/document/d/1wUm8FZPm8AKLZgC-P76TPJAMXs0EN2s5mJGvvUFwycw/edit). I just categorized it and added some additional links/details. If you need more general game development resources, check out [Awesome Gamedev](https://notabug.org/Calinou/awesome-gamedev).

💸 are premium assets. Everything else is free. Most stuff here is licensed MIT/CC but double check before you use these in your commercial projects.

## Getting Started

Here are some recommendations on how I use GMS2. You don't have to follow them, but it might save you some time/energy.

- Do not use the DND feature. Learn GML instead.
- The native sprite editor is not very robust. Try AESprite instead.
- Don't be afraid to use other developer libraries. A lot of them are free for a reason.
- Updates to the IDE and runtime can break your game (like syntax changes to GML). If you are working in a group, make sure you are running on the same version of GMS2 and only update when given a fair warning. You can reinstall previous versions of your IDE at the GMS2 download page.

[GameMaker 2 Manual](https://manual.yoyogames.com/#t=Content.htm)

[GMS2 Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=nBCDzE9MDbk&list=PLPRT_JORnIur4v19PHXCtJ5P05vaokFdP) - Shaun Spalding

## Utilities 🛠️

[gm-core](https://github.com/gm-core) - Foundational utility suite and a great starting point for new GameMaker projects. Comes with quality of life methods, networking tools, testing framework, delta timing, and more.

[FAST](https://github.com/Hyomoto/FAST) - Flexible Assistant Toolkit. Similar to gm-core but comes with input and resolution handling.

[Stitch](https://github.com/bscotch/stitch#readme) - Pipeline Development Kit.

[Outside the Box](https://rousr.itch.io/outsidethebox) - More system-level utility tools. Includes saving/loading files outside of the GMS2 sandbox, toggling borderless/windowed modes at runtime, and querying detailed memory usage information.

[DDDEditor](https://github.com/DragoniteSpam/DDDEditorGMS2) - General purpose game editor.

[Iota](https://github.com/JujuAdams/iota) - Lightweight timestep library.

[Stopwatch](https://github.com/Lojemiru/Stopwatch) - Replacement for GameMaker Studio 2.3 alarms.

[DoLater](https://github.com/JujuAdams/DoLater) - Deferred code execution.

[fuwafuwa](https://github.com/kemonologic/fuwafuwa) - Easy-to-use timer system.

[wTimer](https://mors-games.itch.io/wtimer) - Robust alternative for alarms.

[Timer](https://github.com/nommiin/Timers) - Timer methods based on setTimeout and setInterval from JS.

[EventGML](https://github.com/Soves/EventGML) - Lightweight and fast Node.js style Events Library.

[Polarca](https://github.com/VitorEstevam/polarca) - Interpolation functions.

[Coroutines](https://github.com/JujuAdams/Coroutines) - Asynchronous functions for GameMaker.

[Map](https://github.com/GameMakerDiscord/Map.gml) - Hash table implementations.

[Matrices](https://github.com/JujuAdams/matrices) - A collection of matrix handling scripts.

[gm-stream](https://github.com/daikon-games/gm-stream) - Data structure manipulation.

[Promises](https://github.com/YAL-GameMaker/Promise.gml) - An adaptation of JavaScript Promises.

[Destructors](https://github.com/DatZach/Destructors) - Allows you to use ds_* types such as lists and maps inside of structs.

[SNAP](https://github.com/JujuAdams/SNAP) - Easy data format saving and loading.

[LWO](https://github.com/tabularelf/lwo) - Lightweight objects using structs.

[Lock And Key](https://github.com/AlubJ/Lock-And-Key) - String and file encryption.

[Mathematical Scripts](https://adam-rumpf.itch.io/gamemaker-studio-2-mathematical-scripts) - A collection of math scripts.

[GMVerlet-Integration](https://github.com/tabularelf/GMVerlet-Integration) - Verlet integration example used for visuals.

[Cottonwool](https://github.com/JujuAdams/Cottonwool) - Safe surfaces without memory leaks.

[zlib functions](https://yellowafterlife.itch.io/gamemaker-zlib) - Simple compression/decompression functions.

[Window Taskbar](https://yellowafterlife.itch.io/gamemaker-window-taskbar) - Windows only. Flash the game window border and/or its taskbar button.

[Extension Collection](https://samuel-venable.itch.io/gamemaker-extension-collection) - A suite of various extensions.

[GML+](https://xgasoft.itch.io/gmlp)💸 - a script collection with a goal to "fill the gaps" in GML.

[GMLive](https://yellowafterlife.itch.io/gamemaker-live)💸 - Livecoding / interactive programming.

## Debugging 🪲🔨

[rt-shell](https://github.com/daikon-games/rt-shell) - Easy to use in-game shell.

[Olympus](https://github.com/bscotch/olympus#readme) - Testing Framework.

[Crispy](https://github.com/bfrymire/crispy) - Unit testing in GameMaker.

[gms2-test](https://github.com/pmarincak/gms2-test) - Another unit testing framework.

[Snitch](https://github.com/JujuAdams/Snitch) - Crash and logging system.

[Meta](https://github.com/nommiin/meta) - Runtime asset inspector.

[FPS Speedometer](https://dragonite.itch.io/fps-speedometer-for-gamemaker) - Pretty framerate display.

[DeerLog](https://mulfok.itch.io/gamemaker-deerlog) - Small log writer.

## Input Handling 🕹️

[Input](https://github.com/JujuAdams/input) - No nonsense controller/keyboard library.

[XeroInput](https://www.reddit.com/r/gamemaker/comments/icoh6m/xeroinput_gms23_input_handler/) - Another library to handle multiple inputs for a single action.

[Good Vibes](https://github.com/mrdaneeyul/good-vibes) - Device vibration.

[Native Cursors](https://yellowafterlife.itch.io/gamemaker-native-cursors)💸 - System-level custom cursors.

## UI & Text 📜

[Scribble](https://github.com/JujuAdams/scribble) - Efficient multi-effects text renderer.

[Chatterbox](https://github.com/JujuAdams/chatterbox) - Narrative scripting tool.

[NotificationSystem](https://github.com/babaganosch/NotificationSystem) - Notifications in GameMaker.

[Stream](https://github.com/OmegaX1000/StreamUI) - An efficient Framework for Creating UI.

[Bento](https://github.com/JujuAdams/bento) - A modern UI framework.

[Guido](https://github.com/JujuAdams/Guido) - Simple immediate mode GUI framework.

[Emu UI](https://github.com/DragoniteSpam/Emu) - Common UI elements (text input, checkboxes, radio buttons, dialog boxes, etc).

[Easy And Fast Menu](https://pkgames.itch.io/easy-and-fast-menus-for-gms-23)

[Pause Menu](https://jasontomlee.itch.io/pause-menu-gamemaker-1-2)

[Shampoo](https://zackbanack.itch.io/shampoo)💸 - GUIs using a markup-like language.

[ImGuiGML](https://rousr.itch.io/imguigml) - DLL/GML wrapper of Dear ImGui.

[GUI Framework](https://niris.itch.io/gui-framework) - GUI implementation from Niris Games.

## Localization 🔣

[gm-i18n](https://github.com/CreativeHandOficial/gm-i18n) - Internationalization of texts simply and quickly, using JSON files.

[GMLocalize](https://github.com/DragoniteSpam/GMLocalize2)

[lexicon](https://github.com/tabularelf/lexicon)

[Small Pentapop](https://github.com/AntonBergaker/small_pp_localization_tool)

## Physics and Collisions ☄️

[Loj Hadron Collider](https://github.com/Lojemiru/Loj-Hadron-Collider) - A robust, pixel-perfect collision engine.

[On Slopes and Grids](https://forum.yoyogames.com/index.php?threads/on-slopes-and-grids-subpixel-perfect-topdown-movement-and-collision-line-without-objects.4073/) - A tutorial to implement 45° slopes.

[GMS2 Platforming System](https://benal.itch.io/basic-modern-platforming-system) - GMS2 implementation by Ben Allen and an expansion on Shaun Spalding's original 1.4 platformer tutorial.

## Sprites 👾

[AESnips](https://github.com/angelwire/AESnips) - A sprite playback system.

[phgen](https://github.com/squircledev/phgen) - Placeholder asset generation.

## Audio 🎵

[Echo/Delay Effect](https://madwolf-studios.itch.io/audio-echodelay-effect-for-gamemaker-studio-2)💸 - Optimized delay effect.

[wavload](https://github.com/nkrapivin/wavload) - Demonstrates how to externally load .wav files.

## Levels 🏔️

[LDtk to GMS](https://shynif.itch.io/ldtk-to-gms) - LDtk Importer.

[LDtkParser](https://github.com/evolutionleo/LDtkParser) - Advanced LDtk Importer.

[Room Data Inspector](https://github.com/heygleeson/GM-RoomInspector) - Get data about a different room.

[Random Dungeon Generator](https://github.com/BlaXun/Random-Dungeon-Generator-GMS-2.3) - Combines user-defined chambers to create a dungeon.

## Particles ✨

[Particles Wrapper](https://github.com/GamemakerCasts/particles)

[Advanced Particles](https://limekys.itch.io/advanced-particle-system)

## Lighting 💡

[Bulb](https://github.com/JujuAdams/Bulb) - 2D lighting and shadows.

[Lighting Systems ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/playlist?list=PLYVea5brHS8YHECGPoEp4_gWU-k6nWzUy)

[3D Fragment Point Lights](https://danieldavis.itch.io/ddg-point-light-shader-system)💸 - 3D point lights using shaders.

## Shaders 🌟

[TransFX](https://short-bread.itch.io/transfx) - Transition Library.

[BJRTFX](https://zikbakguru.itch.io/bjrtfx) - Zik's CRT Utility Shader

[bktGlitch](https://odditica.itch.io/bktglitch) - Glitch shader.

[H O R R I - F I](https://gizmo199.itch.io/horri-fi) - VHS Shader.

[Cyberpunk Hologram Effect](https://gentoogames.itch.io/cyberpunk-hologram-effect)

[Depth Sorted Sillouettes](https://pixelatedpope.itch.io/depth-sorted-silhouette-example)

[GMShaders.com](https://gmshaders.com/) - Shader tutorials from Xor. Originally hosted at "xorshaders.com".

[Voronoi](https://github.com/XorDev/GMS-Voronoi-Pixels) - Sampled pixels on a Voronoi diagram.

[Shader Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=ch4BYqkL1w8&list=PL0kTSdIvQNCNE-BDKOlYu628AalMmXy_P) - Gaming Reverends

[Shader Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=a4S7LXx6-sQ&list=PL_hT--4HOvrdkihto8Xu7hhp1-5Gj8zsa) - DragoniteSpam

## 3D 🧊

[dotobj](https://github.com/JujuAdams/dotobj) - Lightweight .obj/.mtl 3D model loader written in native GML.

[Bronze Box](https://github.com/cicadian/Bronze-Box) - Example of how to build 3d world models from a 2d grid.

[Camera3D](https://gizmo199.itch.io/camera3d) - Simple 3D camera setup.

[Three Mice In a Trench Coat](https://github.com/XorDev/ThreeMiceInaTrenchcoat) - Source for a GMS 3D game.

[3D GameMaker Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=ojfN--tdSNM&list=PL_hT--4HOvrcML9uqHe4fwBVTm650Vy3V) - DragoniteSpam

[3D Collisions Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=o7kjtTEMpeU&list=PL_hT--4HOvrf_VYo26LNl3zN5uwfuC3CC) - DragoniteSpam

[3D Optimization Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=knfAZbJJKNY&list=PL_hT--4HOvrf_CJSA7fVU1tkjGVv5Sq2t) - DragoniteSpam

## Sprite Stacking

[Fauxton3D](https://gizmo199.itch.io/fauxton3d) - Sprite stacking engine.

[Sprite Stacking Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=VIDN-nG3EOU&list=PL3Kbpztq9qwT9MbW_k4yyJU__or1r8P2j) - Gizmo199

## Networking 🌐

[GM-Online-Framework](https://github.com/evolutionleo/GM-Online-Framework)

[GMHandshake](https://gist.github.com/nkrapivin/c73f5a962466a4ecb63187a009a300d8)

[EZ Networking](https://jasontomlee.itch.io/easy-gms-networking-platformer-build)

[HTTP GML](https://github.com/Sidorakh/http.gml)

## Integrations 🔌

[DHook](https://github.com/tabularelf/DHook) - Discord integration.

[GMS2_RPC](https://github.com/Mtax-Development/GMS2_RPC) - Another Discord integration.

[NekoPresence](https://marketplace.yoyogames.com/assets/9526/nekopresence) - Oops, all Discord integration.

[Dissonance](https://rousr.itch.io/dissonance) - Knock knock. Who's there? Discord integration.

## Camera 🎥

[Camera System Guide](https://maddestudiosgames.com/gms2-meet-the-camera-system/) - Getting started with cameras in GMS2.

[Camera All-In-One](https://jasontomlee.itch.io/allinone-camera)💸 - Editor, screenshake, view-resizing, follow modes, screen effects, etc.

## Sequences ⏰

[Sequences Tutorial ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=WO6gzhrx5b8)

[Making Splash Screen Sequences ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=hTh5UpFxx1E)

## Design 🖼️

[Making Attacks Feel Good ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=RWkMsD2WUz8)

## State Machines

[SnowState](https://github.com/sohomsahaun/SnowState)

[wFSM](https://mors-games.itch.io/wfsm)

[True State](https://pixelatedpope.itch.io/truestate)💸

## Others ❔ (need to organize)

[Video Player Extension](https://forum.yoyogames.com/index.php?threads/video-player-for-windows-macos-and-ubuntu.77882/) - Play videos.

[GMESCAPI](https://marketplace.yoyogames.com/assets/9529/gmescapi) - Webcam capture.

[Smile](https://github.com/zbanack/smile) - Sentiment analysis.

[Danmaku Project](https://github.com/OmegaX1000/DanmakuProject) - Bullet hell engine.

[Dynamic Turn System](https://gentoogames.itch.io/turn-based-combat-system-for-gamemaker)

[Aquila](https://dragonite.itch.io/aquila) - A* Pathfinding.

[Grid-based Pathfinding Scripts](https://proton-squid.itch.io/pathfinding) - Flexible pathfinding system with 3 pathfinding algorithms.

[Cellular Automata](https://alessiogamedev.itch.io/gms-cellular-automata-algorithm) - Generates huge caves in a few hundred milliseconds.

[Trixscript](https://trixelized.itch.io/trixscript) - Juices up your game with useful functions.

[Mouse Trail Effect](https://all-x.itch.io/gms2-mouse-trail-effect)

[Dynamic Splitscreen](https://maddestudios.itch.io/gms2-project-dynamic-splitscreen)

## Software 💿

[YYP Maker](https://sahaun.itch.io/yyp-maker) - Makes yyp files for you.

[ASESync](https://sahaun.itch.io/asesync) - Automatically syncs aesprite files in GameMaker.

## Snippets 📝

[GMLScripts.com](https://www.gmlscripts.com/script/index)

## Useful Extras ⚗️

[GitHub Yacc to GML Fix](https://www.reddit.com/r/gamemaker/comments/n5m35l/a_simple_fix_for_github_incorrectly_detecting/)

[Tony Str's Articles](https://tonystr.net/articles)

[2.3 Syntax in Detail](https://yal.cc/gamemaker-2-3-syntax-in-details/)

[Advanced Macro Usage](https://nuxiigit.github.io/content/blog/post/gml+syntax+extensions.html)

## Community 🌎

[Community Forums](https://forum.yoyogames.com/index.php)

[Subreddit](https://www.reddit.com/r/gamemaker/)

[Discord](https://discord.gg/gamemaker)

## Special Thanks 💖

JujuAdams, FaultyFunctions, Gleb Tsereteli, Shaun Spalding, DragoniteSpam, PixelatedPope, Tony Strømsnæs, HeartBeast, Xor, Gaming Reverends, Matharoo, YellowAfterlife, Gizmo199, Avis, Josh Wilson
