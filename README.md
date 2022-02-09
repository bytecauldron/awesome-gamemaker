<p align="center">
    <img src="https://styles.redditmedia.com/t5_2qw2g/styles/communityIcon_itciy1qmjp871.png?width=256&s=b9a021ec4e8a588ba97530546668d3ba88136630" />
</p>

# Awesome GameMaker 2 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
An awesome list of 100+ libraries, snippets, guides, and projects for GameMaker Studio 2. 😎

Many libraries here will completely replace native tools in the IDE. I highly recommend exploring everything here so you can start making games as quickly as possible!

This is based on a list from [GameMaker Libraries](https://github.com/FaultyFunctions/GameMakerLibraries) and from Gleb Tsereteli's [Google Doc](https://docs.google.com/document/d/1wUm8FZPm8AKLZgC-P76TPJAMXs0EN2s5mJGvvUFwycw/edit). I just categorized it and added some additional links/details. If you need more general game development resources, check out [Awesome Gamedev](https://notabug.org/Calinou/awesome-gamedev).

💸 are premium assets. Everything else is free. Most stuff here is licensed MIT/CC/GPL but double check before you use these in your commercial projects.

Have something awesome to share? Check out the [Contributing Guidelines](https://github.com/bytecauldron/awesome-gamemaker/blob/main/CONTRIBUTING.md).

## Getting Started 🔥

Here are some recommendations when using GMS2. You don't have to follow them but it might save you some time/energy.

- Recommended to avoid the DND (Drag and Drop) feature. Learn GML instead.
- The native sprite editor is not very robust. Try AESprite instead.
- Don't be afraid to use other developer libraries. A lot of them are free for a reason.
- Updates to the IDE and runtime can break your game (like syntax changes to GML). If you are working in a group, make sure you are running on the same version of GMS2 and only update when given a fair warning. You can reinstall previous versions of your IDE at the GMS2 download page.
- Unless your game requires complex physics interactions, it's generally advised to avoid GMS2's built-in physics system.

[GameMaker 2 Manual](https://manual.yoyogames.com/#t=Content.htm)

[Release Notes](https://gms.yoyogames.com/ReleaseNotes.html)

[Beginner GMS2 Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=nBCDzE9MDbk&list=PLPRT_JORnIur4v19PHXCtJ5P05vaokFdP) - Tutorials from Shaun Spalding. A comprehensive introduction to basic features of the IDE. Highly recommended to check out the full playlist if you're a complete beginner.

[Advanced GMS2 Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=n8-MuIuOQFE&list=PL_hT--4HOvrfuDcYrTufdpgwoALAczPR2) - DragoniteSpam's tutorials dive into more advanced topics related to the GML language. They also have comprehensive 3D and shader introduction videos.

## Utilities 🛠️

[gm-core](https://github.com/gm-core) - Foundational utility suite and a great starting point for new GameMaker projects. Comes with quality of life methods, networking tools, testing framework, delta timing, and more.

[FAST](https://github.com/Hyomoto/FAST) - Flexible Assistant Toolkit. Similar to gm-core but comes with input and resolution handling.

[Stitch](https://github.com/bscotch/stitch#readme) - Pipeline Development Kit. Includes cross-project imports, batch-creating/updating sprites and sounds, texture page management, and more. Tested on Windows only.

[Outside the Box](https://rousr.itch.io/outsidethebox) - More system-level utility tools. Includes saving/loading files outside of the GMS2 sandbox, toggling borderless/windowed modes at runtime, and querying detailed memory usage information.

[DDDEditor](https://github.com/DragoniteSpam/DDDEditorGMS2) - General purpose game editor.

[Iota](https://github.com/JujuAdams/iota) - Lightweight timestep library.

[Stopwatch](https://github.com/Lojemiru/Stopwatch) - Replacement for GameMaker Studio 2.3 alarms.

[DoLater](https://github.com/JujuAdams/DoLater) - Deferred code execution.

[fuwafuwa](https://github.com/kemonologic/fuwafuwa) - Easy-to-use timer system.

[wTimer](https://mors-games.itch.io/wtimer) - Robust alternative for alarms.

[Timer](https://github.com/nommiin/Timers) - Timer methods based on setTimeout and setInterval from JS.

[Broadcast](https://github.com/JulianDicken/Broadcast) - Event Handling Library

[EventGML](https://github.com/Soves/EventGML) - Lightweight and fast Node.js style Events Library.

[Polarca](https://github.com/VitorEstevam/polarca) - Interpolation functions.

[Twerp](https://pixelatedpope.itch.io/twerp) - Easing function similar to lerp().

[Coroutines](https://github.com/JujuAdams/Coroutines) - Asynchronous functions for GameMaker.

[GML-OOP](https://github.com/Mtax-Development/GML-OOP) - A constructor library for operating the primary functionalities of GMS2.

[GML-Classes](https://github.com/Nikko-the-cat/GML-Classes) - Another project that adds OOP functionality to GMS2.

[Map](https://github.com/GameMakerDiscord/Map.gml) - Hash table implementations.

[Matrices](https://github.com/JujuAdams/matrices) - A collection of matrix handling scripts.

[gm-stream](https://github.com/daikon-games/gm-stream) - Data structure manipulation.

[Promises](https://github.com/YAL-GameMaker/Promise.gml) - An adaptation of JavaScript Promises.

[Destructors](https://github.com/DatZach/Destructors) - Allows you to use ds_* types such as lists and maps inside of structs.

[SNAP](https://github.com/JujuAdams/SNAP) - Easy data format saving and loading. Please note that newer versions of GML contains `json_parse` and `json_stringify`. However, if you are converting csv, ini, xml, etc, you may find this very useful.

[LWO](https://github.com/tabularelf/lwo) - Lightweight objects using structs.

[Lock And Key](https://github.com/AlubJ/Lock-And-Key) - String and file encryption.

[Mathematical Scripts](https://adam-rumpf.itch.io/gamemaker-studio-2-mathematical-scripts) - A collection of math scripts.

[Motion Scripts](https://avis.itch.io/motion-scripts) - Provides replacement methods for built-in motion variables.

[GMVerlet-Integration](https://github.com/tabularelf/GMVerlet-Integration) - Verlet integration example used for visuals.

[Cottonwool](https://github.com/JujuAdams/Cottonwool) - Safe surfaces without memory leaks.

[zlib functions](https://yellowafterlife.itch.io/gamemaker-zlib) - Simple compression/decompression functions.

[Window Taskbar](https://yellowafterlife.itch.io/gamemaker-window-taskbar) - Windows only. Flash the game window border and/or its taskbar button.

[GMSDLL](https://github.com/YAL-GameMaker/GMSDLL) - A template project for building DLLs for GMS.

[Extension Collection](https://samuel-venable.itch.io/gamemaker-extension-collection) - A suite of various extensions.

[GMLodash](https://github.com/DatZach/GMLodash) - Functional programming in GML.

[GML+](https://xgasoft.itch.io/gmlp)💸 - a script collection with a goal to "fill the gaps" in GML.

[GMLive](https://yellowafterlife.itch.io/gamemaker-live)💸 - Livecoding / interactive programming.

## Debugging 🪲🔨

[rt-shell](https://github.com/daikon-games/rt-shell) - Easy to use in-game shell.

[Olympus](https://github.com/bscotch/olympus#readme) - Testing Framework.

[Crispy](https://github.com/bfrymire/crispy) - Unit testing in GameMaker.

[Snitch](https://github.com/JujuAdams/Snitch) - Crash and logging system.

[DeerLog](https://mulfok.itch.io/gamemaker-deerlog) - Small log writer.

[gms2-test](https://github.com/pmarincak/gms2-test) - Another unit testing framework.

[Meta](https://github.com/nommiin/meta) - Runtime asset inspector.

[FPS Speedometer](https://dragonite.itch.io/fps-speedometer-for-gamemaker) - Pretty framerate display.

## Input Handling 🕹️

[Input](https://github.com/JujuAdams/input) - No nonsense controller/keyboard library.

[XeroInput](https://www.reddit.com/r/gamemaker/comments/icoh6m/xeroinput_gms23_input_handler/) - Another library to handle multiple inputs for a single action.

[InputCandy](https://github.com/LAGameStudio/InputCandy) - Similar to Input as it acts as a wrapper for SDL, but also provides testing, on-screen diagnostics, and some other UI components related to peripherals.

[Good Vibes](https://github.com/mrdaneeyul/good-vibes) - Device vibration.

[Native Cursors](https://yellowafterlife.itch.io/gamemaker-native-cursors)💸 - System-level custom cursors.

## User Interface 📜

[Scribble](https://github.com/JujuAdams/scribble) - Efficient multi-effects text renderer.

[Scripture](https://pixelatedpope.itch.io/scripture)💸 - Another easy to use, highly compatible text renderer.

[Chatterbox](https://github.com/JujuAdams/chatterbox) - Narrative scripting tool.

[Textboxy](https://github.com/glitchroy/textboxy) - Simple textboxes.

[Crochet](https://github.com/FaultyFunctions/Crochet) - An interactive dialogue editor for writers and programmers.

[NotificationSystem](https://github.com/babaganosch/NotificationSystem) - Notifications in GameMaker.

[Stream](https://github.com/OmegaX1000/StreamUI) - An efficient Framework for Creating UI.

[Bento](https://github.com/JujuAdams/bento) - Not released yet, but keeping an eye on it. It's JuJu, so it's going to be good.

[Guido](https://github.com/JujuAdams/Guido) - Simple immediate mode GUI framework.

[GMUI-Framework](https://github.com/AlertStudios/GMUI-Framework) - A pure GML solution to structure and control your menus, drawing parallels to .NET UI.

[Emu UI](https://github.com/DragoniteSpam/Emu) - Common UI elements (text input, checkboxes, radio buttons, dialog boxes, etc).

[Easy And Fast Menu](https://pkgames.itch.io/easy-and-fast-menus-for-gms-23) - Simple implementation to have a menu up and running in seconds. Seems like a great fit if you're not looking for a bigger solution like GMUI.

[Pause Menu](https://jasontomlee.itch.io/pause-menu-gamemaker-1-2) - Another smaller implementation but has a cool animation between menu options.

[Shampoo](https://zackbanack.itch.io/shampoo)💸 - GUIs using a markup-like language.

[ImGuiGML](https://rousr.itch.io/imguigml) - DLL/GML wrapper of Dear ImGui.

[GUI Framework](https://niris.itch.io/gui-framework) - GUI implementation from Niris Games.

[Menu Tutorial ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=1ITZOrI2qkA&list=PLSFMekK0JFgx2vmcCnttxxhrNVTjUB8R1) - FriendlyCosmonaut

[Smart Clickable GUI ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=RbBgE3cUShc) - PixelatedPope

## Localization 🔣

[gm-i18n](https://github.com/CreativeHandOficial/gm-i18n) - Internationalization of texts simply and quickly, using JSON files.

[lexicon](https://github.com/tabularelf/lexicon) - Another localization solution focused on simplifying implementation.

[GMLocalize](https://github.com/DragoniteSpam/GMLocalize2) - Not a full localization solution. Extracts text strings for localization from a GameMaker Studio 2 project and saves it to a JSON file.

[Small Pentapop Localization Tool](https://github.com/AntonBergaker/small_pp_localization_tool) - Similar export tool to GMLocalize but exports to a csv.

## Physics ☄️

[Loj Hadron Collider](https://github.com/Lojemiru/Loj-Hadron-Collider) - A robust, pixel-perfect collision engine.

[On Slopes and Grids](https://forum.yoyogames.com/index.php?threads/on-slopes-and-grids-subpixel-perfect-topdown-movement-and-collision-line-without-objects.4073/) - A tutorial to implement 45° slopes.

[GMS2 Platforming System](https://benal.itch.io/basic-modern-platforming-system) - GMS2 implementation by Ben Allen and an expansion on Shaun Spalding's original 1.4 platformer tutorial.

[Inverse Kinematics Extension](https://github.com/tonystr/Inverse-Kinematics-Extension-for-Gamemaker) - A library for working with inverse kinematics.

## Sprites 👾

[AESnips](https://github.com/angelwire/AESnips) - A sprite playback system.

[phgen](https://github.com/squircledev/phgen) - Placeholder asset generation.

## Audio 🎵

[FMODGMS](https://github.com/mstop4/FMODGMS) - Supposedly this doesn't support everything FMOD has to offer and the project itself has been put on-hold. However, audio extensions are slim pickings for GMS2, so it's definitely worth keeping tabs on it.

[Echo/Delay Effect](https://madwolf-studios.itch.io/audio-echodelay-effect-for-gamemaker-studio-2)💸 - Optimized delay effect.

[wavload](https://github.com/nkrapivin/wavload) - Demonstrates how to externally load .wav files.

[SoLoud](https://github.com/jarikomppa/soloud) - Portable audio engine that "can" work with GMS with some limitations. See [here.](http://sol.gfxile.net/soloud/gamemaker_api.html)

## Levels 🏔️

[LDtk to GMS](https://shynif.itch.io/ldtk-to-gms) - LDtk Importer.

[LDtkParser](https://github.com/evolutionleo/LDtkParser) - Advanced LDtk Importer.

[Room Data Inspector](https://github.com/heygleeson/GM-RoomInspector) - Get data about a different room.

[Random Dungeon Generator](https://github.com/BlaXun/Random-Dungeon-Generator-GMS-2.3) - Combines user-defined chambers to create a dungeon.

[Random Level Generator](https://github.com/GameMakerDiscord/random-level-gen-gms2) - A random level generation example (similar to Nuclear Throne) using GameMaker Studio 2.

[Destructible Terrain](https://github.com/niksudan/gms2-destructible-terrain) - An example of collidable, destructible terrain in GameMaker Studio 2 using surfaces and grids.

## Particles ✨

[Particles Wrapper](https://github.com/GamemakerCasts/particles) - A simplistic particle system wrapper that is designed to make creating particles fun and easy.

[Advanced Particles](https://limekys.itch.io/advanced-particle-system) - A particle implementation that comes with it's own delta timing methods.

## Lighting 💡

[Bulb](https://github.com/JujuAdams/Bulb) - 2D lighting and shadows.

[Lighting System 2D](https://github.com/borup3/Lighting-System-2D) - Haven't tested this with the 2.3 syntax changes. Requires 2.2 or higher, according to the repo.

[GameMaker Lighting Engine](https://github.com/bilouw/Gamemaker-Lighting-Engine) - Tile-based Lighting Engine that projects shadows.

[Lighting Systems ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/playlist?list=PLYVea5brHS8YHECGPoEp4_gWU-k6nWzUy) - Very fast dynamic 2D lighting implementation from GrizzliusMaximus using shadow casting.

[3D Fragment Point Lights](https://danieldavis.itch.io/ddg-point-light-shader-system)💸 - 3D point lights using shaders.

## Shaders 🌟

[TransFX](https://short-bread.itch.io/transfx) - Transition Library.

[BJRTFX](https://zikbakguru.itch.io/bjrtfx) - Zik's CRT Utility Shader

[bktGlitch](https://odditica.itch.io/bktglitch) - Glitch shader.

[H O R R I - F I](https://gizmo199.itch.io/horri-fi) - VHS Shader.

[Cyberpunk Hologram Effect](https://gentoogames.itch.io/cyberpunk-hologram-effect) - Create and customize your own holographic effect using this easy-to-implement asset.

[Depth Sorted Sillouettes](https://pixelatedpope.itch.io/depth-sorted-silhouette-example) - Example project to demonstrate shader-based depth sorting sillouettes. Tested on PC, Mac, HTML5, and Android.

[GMShaders.com](https://gmshaders.com/) - Shader tutorials from Xor. Originally hosted at "xorshaders.com".

[1PassBlur](https://github.com/XorDev/1PassBlur/wiki) - Blur Shader.

[Bokeh Blur](https://github.com/XorDev/Bokeh/wiki) - Blur Shader.

[Dual-Kawase](https://github.com/XorDev/Dual-Kawase/wiki) - Blur Shader.

[Voronoi](https://github.com/XorDev/GMS-Voronoi-Pixels) - Sampled pixels on a Voronoi diagram.

[Fire-Fun](https://github.com/XorDev/Fire-Fun/wiki) - Some fun magic fireballs.

[Shader Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=ch4BYqkL1w8&list=PL0kTSdIvQNCNE-BDKOlYu628AalMmXy_P) - Gaming Reverends

[Shader Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=a4S7LXx6-sQ&list=PL_hT--4HOvrdkihto8Xu7hhp1-5Gj8zsa) - DragoniteSpam

## 3D 🧊

[BBMOD](https://github.com/blueburn-cz/BBMOD) - 3D Rendering Solution. Comes with several modules to import obj, 3D camera setup, integration with ColMesh, and more.

[dotobj](https://github.com/JujuAdams/dotobj) - Lightweight .obj/.mtl 3D model loader written in native GML.

[Bronze Box](https://github.com/cicadian/Bronze-Box) - Example of how to build 3d world models from a 2d grid.

[Camera3D](https://gizmo199.itch.io/camera3d) - Simple 3D camera setup.

[Three Mice In a Trench Coat](https://github.com/XorDev/ThreeMiceInaTrenchcoat) - Source for a GMS 3D game.

[sPart](https://marketplace.yoyogames.com/assets/7299/spart-3d-particle-system) - 3D Particle System from TheSnidr.

[ColMesh](https://forum.yoyogames.com/index.php?threads/colmesh-3d-collisions-made-easy.82765/) - 3D Collision Library from TheSnidr.

[3D GameMaker Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=ojfN--tdSNM&list=PL_hT--4HOvrcML9uqHe4fwBVTm650Vy3V) - DragoniteSpam

[3D Collisions Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=o7kjtTEMpeU&list=PL_hT--4HOvrf_VYo26LNl3zN5uwfuC3CC) - DragoniteSpam

[3D Optimization Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=knfAZbJJKNY&list=PL_hT--4HOvrf_CJSA7fVU1tkjGVv5Sq2t) - DragoniteSpam

## Sprite Stacking ⏫

[Beginners Guide to Sprite Stacking](https://medium.com/@avsnoopy/beginners-guide-to-sprite-stacking-in-gamemaker-studio-2-and-magica-voxel-part-1-f7a1394569c0) - A primer on sprite stacking from Avis. Check out part 2 from dev_dwarf as well.

[Fauxton3D](https://gizmo199.itch.io/fauxton3d) - Sprite stacking engine.

[Sprite Stacking Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=VIDN-nG3EOU&list=PL3Kbpztq9qwT9MbW_k4yyJU__or1r8P2j) - Gizmo199

## Networking 🌐

[Warp](https://github.com/evolutionleo/Warp) - A feature-rich framework for multiplayer games, written in GMS2.3 and NodeJS.

[EZ Networking](https://jasontomlee.itch.io/easy-gms-networking-platformer-build) - Host/client implementation with a chat feature.

[Patchwire-GM](https://github.com/gm-core/patchwire-gm) - The network library from gm-core if you want to use this implementation without the entire gm-core suite.

[GMHandshake](https://gist.github.com/nkrapivin/c73f5a962466a4ecb63187a009a300d8) - A Gist demonstrating a network handshake.

[HTTP GML](https://github.com/Sidorakh/http.gml) - Recieve GET requests and upload files in GML.

## Integrations 🔌

[DHook](https://github.com/tabularelf/DHook) - Discord integration.

[GMS2_RPC](https://github.com/Mtax-Development/GMS2_RPC) - Another Discord integration.

[NekoPresence](https://marketplace.yoyogames.com/assets/9526/nekopresence) - Oops, all Discord integration.

[Dissonance](https://rousr.itch.io/dissonance) - Knock knock. Who's there? Discord integration.

[Steamworks.gml](https://github.com/YAL-GameMaker/steamworks.gml) - Various expansions to Steamworks SDK support in GameMaker: Studio / GMS2.

[GOG.gml](https://github.com/GameMakerDiscord/GOG.gml) - A native extension for GOG.com SDK support.

## Camera 🎥

[GMS2 Cameras: As Simple as Possible](https://www.youtube.com/watch?v=_g1LQ6aIJFk) - Pope's guide on GMS2's camera system.

[Camera System Guide](https://maddestudiosgames.com/gms2-meet-the-camera-system/) - Getting started with cameras in GMS2.

[Pixel Perfect Smooth Camera](https://github.com/YAL-GameMaker/pixel-perfect-smooth-camera) - An example of pixel-perfect yet smooth camera.

[Camera All-In-One](https://jasontomlee.itch.io/allinone-camera)💸 - Editor, screenshake, view-resizing, follow modes, screen effects, etc.

## Sequences ⏰

[Sequences Tutorial ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=WO6gzhrx5b8) - Shaun Spalding

[Making Splash Screen Sequences ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=hTh5UpFxx1E) - Mash Arcade

## Design 🖼️

[Making Attacks Feel Good ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=RWkMsD2WUz8) - Blobfish

## State Machines 🧠

[SnowState](https://github.com/sohomsahaun/SnowState) - Robust finite state machine.

[wFSM](https://mors-games.itch.io/wfsm) - Another Easy-to-use Finite State Machine library.

[True State](https://pixelatedpope.itch.io/truestate)💸 - Feature-rich finite state machine to handle complex objects.

## Others ❔ (need to organize)

[Video Player Extension](https://forum.yoyogames.com/index.php?threads/video-player-for-windows-macos-and-ubuntu.77882/) - Play videos.

[GMESCAPI](https://marketplace.yoyogames.com/assets/9529/gmescapi) - Webcam capture.

[Smile](https://github.com/zbanack/smile) - Sentiment analysis.

[Danmaku Project](https://github.com/OmegaX1000/DanmakuProject) - Bullet hell engine.

[OrbinautFramework](https://github.com/TrianglyRU/OrbinautFramework) - Accurate framework to make classic Sonic games.

[Dynamic Turn System](https://gentoogames.itch.io/turn-based-combat-system-for-gamemaker)

[Aquila](https://dragonite.itch.io/aquila) - A* Pathfinding.

[Grid-based Pathfinding Scripts](https://proton-squid.itch.io/pathfinding) - Flexible pathfinding system with 3 pathfinding algorithms.

[Cellular Automata](https://alessiogamedev.itch.io/gms-cellular-automata-algorithm) - Generates huge caves in a few hundred milliseconds.

[Trixscript](https://trixelized.itch.io/trixscript) - Juices up your game with useful functions.

[Mouse Trail Effect](https://all-x.itch.io/gms2-mouse-trail-effect) - Shows how to trace a line with primitives to create a colorful trail.

[Dynamic Splitscreen](https://maddestudios.itch.io/gms2-project-dynamic-splitscreen) - Local multiplayer split screen implementation that merges the camera when players are close.

[Wave Function Collapse](https://quadolorgames.itch.io/wfc-gml-demo) - Generates a random tile map.

[Top-Down Movement & Collision](https://pixelatedpope.itch.io/tdmc/devlog/156556/converting-tdmc-to-use-tiles)💸 - Robust object-based Collision System

[Starfield Generator](https://github.com/PixelProphecy/gml_starfield_generator) - A script to generate starfields in GameMaker's GML language.

## Software 💿

[YYP Maker](https://sahaun.itch.io/yyp-maker) - Makes yyp files for you.

[ASESync](https://sahaun.itch.io/asesync) - Automatically syncs aesprite files in GameMaker.

## Blogs 📝

[RefresherTowel](https://refreshertowelgames.wordpress.com/category/tutorial/) - Contains several posts on level generation.

[Tony Str](https://tonystr.net/articles)

[Katsaii](https://nuxiigit.github.io/content/blog/posts.html)

## Useful Extras ⚗️

[GMLScripts.com](https://www.gmlscripts.com/script/index) - Dozens of helper scripts, organized similarly to the official documentation.

[Voxeledphoton's FreeGMScripts](https://github.com/vphoton/FreeGMScripts) - Some might be out of date with 2.3+ syntax.

[GitHub Yacc to GML Fix](https://www.reddit.com/r/gamemaker/comments/n5m35l/a_simple_fix_for_github_incorrectly_detecting/)

[2.3 Syntax in Detail](https://yal.cc/gamemaker-2-3-syntax-in-details/) - A full guide of the latest syntax features/changes in GML from Yal.

[Dracula](https://github.com/dracula/gamemaker-studio) - Dark theme for the IDE.

[Source Control with Git & GameMaker ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=UZG-P68xWio&list=PLSFMekK0JFgzmyDxVxj5Cctafu5UX_vUC) - FriendlyCosmonaut

[Game Resolution & Aspect Ratio Management ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=_g1LQ6aIJFk&list=PLXkVsacazW2qvdnKNzgBLkUwlgi3FU-VO) - PixelatedPope

[GameMaker Garbage Collection](https://gist.github.com/DatZach/96a30d6ae4225f8ec152719e57aed26b) - How garbage collection works in GML.

[GM48 Resources](https://gm48.net/resources) - Free resources from the community to become better at GameMaker Studio, game development and game jams.

[GameMakerHow](https://gamemakerhow.com/) - Another great site that acts as a GameMaker Q&A repository for various questions you might ask in GMS2.

## Community 🌎

[GameMaker Forums](https://forum.yoyogames.com/index.php)

[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/gamemaker/) 
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gamemaker)

## Special Thanks 💖

JujuAdams, FaultyFunctions, Gleb Tsereteli, Shaun Spalding, DragoniteSpam, PixelatedPope, Tony Strømsnæs, HeartBeast, Xor, Gaming Reverends, Matharoo, YellowAfterlife, Gizmo199, Avis, Josh Wilson
