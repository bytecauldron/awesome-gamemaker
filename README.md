<p align="center">
    <a href="https://gamemaker.io/en/gamemaker"><img src="https://github.com/bytecauldron/awesome-gamemaker/raw/main/images/banner.png" /></a>
</p>

# Awesome GameMaker [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Made with GameMaker](https://img.shields.io/badge/Made%20with-GameMaker-000000.svg?style=flat&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAAZlBMVEX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2BrG8stAAAAIXRSTlMABg0OFBkfcn1%2Bf4CBgoOFhoeIiouWmNDa5ebp8PX2%2B%2F6o6Vq%2BAAAAY0lEQVR42k2OWQ6AIAwFn%2BIOioobrnD%2FS4o0EeanmQxNAdErRFTWtsFq6%2BiiZozz0CSnTjYBwo0RkF8DWDLf51Ni9K%2FYdq0Fy3KAfzk97M7goK1F%2F4rGH9Kk1OlboQtEDIrmC%2BU3CVxTr%2FRMAAAAAElFTkSuQmCC)](https://www.yoyogames.com/gamemaker)
An awesome list of 100+ libraries, snippets, guides, and projects for GameMaker Studio. 😎

## Legend

- 💸 - Paid Asset

## Contents

  - [🔥 Getting Started](#getting-started)
  - [🛠️ Utilities](#utilities)
  - [🐛 Debugging](#debugging)
  - [🕹️ Input Handling](#input-handling)
  - [📜 User Interface](#user-interface)
  - [💬 Localization](#localization)
  - [☄️ Physics](#physics)
  - [👾 Sprites](#sprites)
  - [🎵 Audio](#audio)
  - [🏔️ Levels](#levels)
  - [✨ Particles](#particles)
  - [💡 Lighting](#lighting)
  - [💎 Shaders](#shaders)
  - [👽 3D](#3d)
  - [⏫ Sprite Stacking](#sprite-stacking)
  - [🌐 Networking](#networking)
  - [🔌 Integrations](#integrations)
  - [🎥 Camera](#camera)
  - [⏰ Sequences](#sequences)
  - [🧠 State Machines](#state-machines)
  - [🧭 Pathing](#pathing)
  - [⚗️ Useful Extras](#useful-extras)
  - [📝 Blogs](#blogs)
  - [📺 YouTube](#youtube)
  - [🌎 Community](#community)

## Getting Started

- [GameMaker Manual](https://manual.yoyogames.com/#t=Content.htm)
- [GameMaker Release Notes](https://gms.yoyogames.com/ReleaseNotes.html)
- [GameMaker Marketplace](https://marketplace.yoyogames.com/)
- [Beginner GameMaker Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=nBCDzE9MDbk&list=PLPRT_JORnIur4v19PHXCtJ5P05vaokFdP) - Tutorials from Shaun Spalding. A comprehensive introduction to basic features of the IDE. Highly recommended to check out the full playlist if you're a complete beginner.
- [Advanced GameMaker Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=n8-MuIuOQFE&list=PL_hT--4HOvrfuDcYrTufdpgwoALAczPR2) - DragoniteSpam's tutorials dive into more advanced topics related to the GML language. They also have comprehensive 3D and shader introduction videos.

### General Recommendations

- Avoid the GameMaker Visual (Drag and Drop) feature. Learn the GameMaker Language (GML) instead.
- The native sprite editor is not very robust. Try [AESprite](https://www.aseprite.org/)💸.
- Don't be afraid to use other developer libraries. A lot of them are free for a reason. Just be mindful of the license.
- Updates to the IDE and runtime can break your game (like syntax changes to GML). If you are working in a group, make sure you are running on the same version of GMS and only update when given a fair warning. You can reinstall previous versions of your IDE at the GMS download page.
- Unless your game requires complex physics interactions, it's generally advised to avoid GameMaker's built-in physics system.
- Schedule routine backups for projects. If you are dealing with larger media files in your repo, try [Git LFS](https://git-lfs.github.com/).

## Utilities

- [gm-core](https://github.com/gm-core) - Foundational utility suite and a great starting point for new GameMaker projects. Comes with quality of life methods, networking tools, testing framework, delta timing, and more.

- [FAST](https://github.com/Hyomoto/FAST) - Flexible Assistant Toolkit. Similar to gm-core but comes with input and resolution handling.

- [Stitch](https://www.npmjs.com/package/@bscotch/stitch) - Pipeline Development Kit. Includes cross-project imports, batch-creating/updating sprites and sounds, texture page management, and more. Tested on Windows only.

- [Outside the Box](https://rousr.itch.io/outsidethebox) - More system-level utility tools. Includes saving/loading files outside of the GameMaker sandbox, toggling borderless/windowed modes at runtime, and querying detailed memory usage information.

- [DDDEditor](https://github.com/DragoniteSpam/DDDEditorGMS2) - General purpose game editor.

- [Iota](https://github.com/JujuAdams/iota) - Lightweight timestep library.

- [Stopwatch](https://github.com/Lojemiru/Stopwatch) - GameMaker alarm replacement.

- [wTimer](https://mors-games.itch.io/wtimer) - Robust alternative for alarms.

- [FrogAlarm](https://github.com/colmeye/FrogAlarms) - Another easy alternative to GameMaker alarms.

- [fuwafuwa](https://github.com/kemonologic/fuwafuwa) - Easy-to-use timer system.

- [Timer](https://github.com/nommiin/Timers) - Timer methods based on setTimeout and setInterval from JS.

- [Broadcast](https://github.com/JulianDicken/Broadcast) - Event Handling Library

- [EventGML](https://github.com/Soves/EventGML) - Lightweight and fast Node.js style Events Library.

- [Polarca](https://github.com/VitorEstevam/polarca) - Interpolation functions.

- [Twerp](https://pixelatedpope.itch.io/twerp) - Easing function similar to lerp().

- [Coroutines](https://github.com/JujuAdams/Coroutines) - Asynchronous functions for GameMaker.

- [gm-cadence](https://github.com/daikon-games/gm-cadence) - Schedule code to run at certain times and for certain durations, similar to Coroutines.

- [GML-OOP](https://github.com/Mtax-Development/GML-OOP) - A constructor library for operating the primary functionalities of GameMaker.

- [GML-Classes](https://github.com/Nikko-the-cat/GML-Classes) - Another project that adds OOP functionality to GameMaker.

- [Map](https://github.com/GameMakerDiscord/Map.gml) - Hash table implementations.

- [Matrices](https://github.com/JujuAdams/matrices) - A collection of matrix handling scripts.

- [gm-stream](https://github.com/daikon-games/gm-stream) - Data structure manipulation.

- [Promises](https://github.com/YAL-GameMaker/Promise.gml) - An adaptation of JavaScript Promises.

- [Destructors](https://github.com/DatZach/Destructors) - Allows you to use ds_* types such as lists and maps inside of structs.

- [SNAP](https://github.com/JujuAdams/SNAP) - Easy data format saving and loading. Please note that newer versions of GameMaker contain `json_parse` and `json_stringify`. However, if you are converting csv, ini, xml, etc, you may find this very useful.

- [Dynamo](https://github.com/JujuAdams/Dynamo) - Dynamic data loader.

- [LWO](https://github.com/tabularelf/lwo) - Lightweight objects using structs.

- [Gumshoe](https://github.com/JujuAdams/Gumshoe) - Simple deep file search function.

- [Lock And Key](https://github.com/AlubJ/Lock-And-Key) - String and file encryption.

- [Mathematical Scripts](https://adam-rumpf.itch.io/gamemaker-studio-2-mathematical-scripts) - A collection of math scripts.

- [Seedpod](https://github.com/daikon-games/gm-seedpod) - A collection of scripts to improve the GML programming experience.

- [Trixscript](https://trixelized.itch.io/trixscript) - Juices up your game with useful functions.

- [CoreExtension](https://github.com/blueburncz/CoreExtension) - A collection of CC0 programming libraries.

- [Voxeledphoton's FreeGMScripts](https://github.com/vphoton/FreeGMScripts) - Additional GML helper functions. Some may be out of date with 2.3+ syntax.

- [ForEach](https://github.com/KeeVeeGames/foreach.gml) - Adds a foreach implementation for arrays, ds_lists, ds_maps, ds_stacks, ds_queues, ds_priorities and structs.

- [DeepCopy](https://github.com/KeeVeeGames/DeepCopy.gml) - Deep clone class instances / constructed structs, anonymous structs and arrays nested in any order!

- [Motion Scripts](https://avis.itch.io/motion-scripts) - Provides replacement methods for built-in motion variables.

- [Cottonwool](https://github.com/JujuAdams/Cottonwool) - Safe surfaces without memory leaks.

- [zlib functions](https://yellowafterlife.itch.io/gamemaker-zlib) - Simple compression/decompression functions.

- [Window Taskbar](https://yellowafterlife.itch.io/gamemaker-window-taskbar) - Windows only. Flash the game window border and/or its taskbar button.

- [GMSDLL](https://github.com/YAL-GameMaker/GMSDLL) - A template project for building DLLs for GameMaker.

- [Extension Collection](https://samuel-venable.itch.io/gamemaker-extension-collection) - A suite of various extensions.

- [GMLodash](https://github.com/DatZach/GMLodash) - Functional programming in GML.

- [GML-Prelude](https://github.com/NuxiiGit/gml-prelude) - Another functional programming library for GML.

- [Wraptor](https://github.com/Gizmo199/Wraptor) - A library of wrapper functions.

- [Autoframer](https://github.com/mstop4/auto-framer) - Automatically handles resizing the game view across different display and window sizes.

- [GML+](https://xgasoft.itch.io/gmlp)💸 - a script collection with a goal to "fill the gaps" in GML.

- [GMLive](https://yellowafterlife.itch.io/gamemaker-live)💸 - Livecoding / interactive programming.

- [GMEdit](https://github.com/YellowAfterlife/GMEdit) - Code editor to use in conjunction with GameMaker.

- [YYP Maker](https://sahaun.itch.io/yyp-maker) - Makes `.yyp` files for you.

- [Rubber](https://github.com/GameMakerDiscord/Rubber) - Compile GameMaker projects via the command line. Here's a [great guide](https://www.patreon.com/posts/how-to-build-36556955) on how to use it.

## Debugging

- [rt-shell](https://github.com/daikon-games/rt-shell) - Easy to use in-game shell. Create your own commands, command meta data, command suggestions, history, etc.

- [Olympus](https://github.com/bscotch/olympus#readme) - Testing Framework.

- [Crispy](https://github.com/bfrymire/crispy) - Unit testing in GameMaker.

- [Snitch](https://github.com/JujuAdams/Snitch) - Crash and logging system.

- [DeerLog](https://mulfok.itch.io/gamemaker-deerlog) - Small log writer.

- [gms2-test](https://github.com/pmarincak/gms2-test) - Unit testing framework.

- [Meta](https://github.com/nommiin/meta) - Runtime asset inspector.

- [FPS Speedometer](https://dragonite.itch.io/fps-speedometer-for-gamemaker) - Pretty framerate display.

- [Duck](https://github.com/imlazyeye/duck) - A fast GML analyzer to enforce code styling and detect errors.

## Input Handling

- [Input](https://github.com/JujuAdams/input) - No nonsense gamepad/keyboard library.

- [XeroInput](https://www.reddit.com/r/gamemaker/comments/icoh6m/xeroinput_gms23_input_handler/) - Another library to handle multiple inputs for a single action.

- [InputCandy](https://github.com/LAGameStudio/InputCandy) - Similar to Input as it acts as a wrapper for SDL, but also provides testing, on-screen diagnostics, and some other UI components related to peripherals.

- [Good Vibes](https://github.com/mrdaneeyul/good-vibes) - Device vibration.

- [Mouse Queue](https://github.com/YAL-GameMaker/window_mouse_queue) - Tracks the Windows mouse pointer with high precision.

- [Native Cursors](https://yellowafterlife.itch.io/gamemaker-native-cursors)💸 - System-level custom cursors.

## User Interface

- [Scribble](https://github.com/JujuAdams/scribble) - Efficient multi-effects text renderer.

- [Scripture](https://pixelatedpope.itch.io/scripture)💸 - Another easy to use, highly compatible text renderer.

- [Chatterbox](https://github.com/JujuAdams/chatterbox) - Narrative scripting tool.

- [Textboxy](https://github.com/glitchroy/textboxy) - Simple textboxes.

- [Crochet](https://github.com/FaultyFunctions/Crochet) - An interactive dialogue editor for writers and programmers.

- [NotificationSystem](https://github.com/babaganosch/NotificationSystem) - Notifications in GameMaker.

- [YUI](https://github.com/shdwcat/YUI) - A UI system with live reloading, template system, data binding, and a drag and drop feature.

- [Stream](https://github.com/OmegaX1000/StreamUI) - An efficient Framework for Creating UI.

- [Bento](https://github.com/JujuAdams/bento) - Not released yet, but keeping an eye on it. It's Juju, so it's going to be good.

- [Guido](https://github.com/JujuAdams/Guido) - Simple immediate mode GUI framework.

- [GMUI-Framework](https://github.com/AlertStudios/GMUI-Framework) - A pure GML solution to structure and control your menus, drawing parallels to .NET UI.

- [GMS2-UI-Library](https://github.com/nabilatsoulcade/GMS2-UI-Library) - A Library Full of useful scripts for implementing your UI designs in GameMaker.

- [Emu UI](https://github.com/DragoniteSpam/Emu) - Common UI elements (text input, checkboxes, radio buttons, dialog boxes, etc).

- [Easy And Fast Menu](https://pkgames.itch.io/easy-and-fast-menus-for-gms-23) - Simple implementation to have a menu up and running in seconds. Seems like a great fit if you're not looking for a bigger solution like GMUI.

- [Pause Menu](https://jasontomlee.itch.io/pause-menu-gamemaker-1-2) - Another smaller implementation but has a cool animation between menu options.

- [Shampoo](https://zackbanack.itch.io/shampoo)💸 - GUIs using a markup-like language.

- [Magpie](https://dragonite.itch.io/magpie) - Generic Inventory System.

- [ImGuiGML](https://rousr.itch.io/imguigml) - DLL/GML wrapper of Dear ImGui.

- [GUI Framework](https://niris.itch.io/gui-framework) - GUI implementation from Niris Games.

- [Menu Tutorial ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=1ITZOrI2qkA&list=PLSFMekK0JFgx2vmcCnttxxhrNVTjUB8R1) - FriendlyCosmonaut.

- [Smart Clickable GUI ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=RbBgE3cUShc) - PixelatedPope.

- [RTS Selection Tool](https://gentoogames.itch.io/rts-selection-tool) - Mouse dragging feature to select pawns in an real-time strategy game.

## Localization

- [polyglot](https://github.com/daikon-games/polyglot) - Localization library.

- [gm-i18n](https://github.com/CreativeHandOficial/gm-i18n) - Internationalization of texts simply and quickly, using JSON files.

- [lexicon](https://github.com/tabularelf/lexicon) - Another localization solution focused on simplifying implementation.

- [GMLocalize](https://github.com/DragoniteSpam/GMLocalize2) - Not a full localization solution. Extracts text strings for localization from a GameMaker Studio 2 project and saves it to a JSON file.

- [Small Pentapop Localization Tool](https://github.com/AntonBergaker/small_pp_localization_tool) - Similar export tool to GMLocalize but exports to a csv.

## Physics

- [Loj Hadron Collider](https://github.com/Lojemiru/Loj-Hadron-Collider) - A robust, pixel-perfect collision engine.

- [On Slopes and Grids](https://forum.yoyogames.com/index.php?threads/on-slopes-and-grids-subpixel-perfect-topdown-movement-and-collision-line-without-objects.4073/) - A tutorial to implement 45° slopes.

- [GMS2 Platforming System](https://benal.itch.io/basic-modern-platforming-system) - GameMaker implementation by Ben Allen and an expansion on Shaun Spalding's original 1.4 platformer tutorial.

- [Inverse Kinematics Extension](https://github.com/tonystr/Inverse-Kinematics-Extension-for-Gamemaker) - A library for working with inverse kinematics.

- [Verlet Integration Library](https://jamjamteam.itch.io/verlet-integration-gamemake-studio-2) - Verlet integration by Sarek Lambert.

- [GMVerlet-Integration](https://github.com/tabularelf/GMVerlet-Integration) - Verlet integration example used for visuals.

- [Top-Down Movement & Collision](https://pixelatedpope.itch.io/tdmc/devlog/156556/converting-tdmc-to-use-tiles)💸 - Robust object-based collision system from the pope.

## Sprites

- [AESnips](https://github.com/angelwire/AESnips) - A sprite playback system.

- [phgen](https://github.com/squircledev/phgen) - Placeholder asset generation.

- [Disarm](https://github.com/NuxiiGit/disarm) - A spriter skeletal animation at runtime.

- [Spritely](https://github.com/bscotch/spritely) - Image correction and cleanup for 2D video game sprites.

- [PixelUpscaler](https://github.com/JujuAdams/Pixel-Art-Upscaling) - Pixel art upscaling shader for awkward resolutions for GameMaker.

- [ASESync](https://sahaun.itch.io/asesync) - Automatically syncs aesprite files in GameMaker.

## Audio

- [FMODGMS](https://github.com/mstop4/FMODGMS) - Supposedly this doesn't support everything FMOD has to offer and the project itself has been put on-hold. Keep in mind that GameMaker may be getting native FMOD support soon.

- [WWiseGMS2](https://github.com/alessandrofama/wwise-gms2) - Bindings for the WWise API. Windows only.

- [Echo/Delay Effect](https://madwolf-studios.itch.io/audio-echodelay-effect-for-gamemaker-studio-2)💸 - Optimized delay effect.

- [wavload](https://github.com/nkrapivin/wavload) - Demonstrates how to externally load .wav files.

- [SoLoud](https://github.com/jarikomppa/soloud) - Portable audio engine that "can" work with GMS with some limitations. See [here.](http://sol.gfxile.net/soloud/gamemaker_api.html)

- [audioExt](https://github.com/tabularelf/audioExt) - Sound External Loader/Unloader Manager.

- [ExternalAudio](https://github.com/NuxiiGit/ExternalAudio) - Load external .wav files at runtime.

## Levels

- [LDtk to GMS](https://shynif.itch.io/ldtk-to-gms) - LDtk Importer.

- [LDtkParser](https://github.com/evolutionleo/LDtkParser) - Advanced LDtk Importer.

- [Room Data Inspector](https://github.com/heygleeson/GM-RoomInspector) - Collects room data and stores it into a JSON for later use. 

- [Random Dungeon Generator](https://github.com/BlaXun/Random-Dungeon-Generator-GMS-2.3) - Combines user-defined chambers to create a dungeon.

- [Random Level Generator](https://github.com/GameMakerDiscord/random-level-gen-gms2) - A random level generation example (similar to Nuclear Throne) using GameMaker.

- [World Generator](https://github.com/kirillzhosul/world-generation) - 2D "Top Down" world generation / visualization.

- [Wave Function Collapse](https://quadolorgames.itch.io/wfc-gml-demo) - Generates a random tile map but not production ready in its current state.

- [Draw A Dungeon](https://gentoogames.itch.io/draw-a-dungeon-gamemaker) - Converts your room layouts into a randomized dungeon.

- [Destructible Terrain](https://github.com/niksudan/gms2-destructible-terrain) - An example of collidable, destructible terrain in GameMaker Studio using surfaces and grids.

- [Cellular Automata Caves](https://alessiogamedev.itch.io/gms-cellular-automata-algorithm) - Generates huge caves in a few hundred milliseconds.

## Particles

- [Particles Wrapper](https://github.com/GamemakerCasts/particles) - A simplistic particle system wrapper that is designed to make creating particles fun and easy.

- [Advanced Particles](https://limekys.itch.io/advanced-particle-system) - A particle implementation that comes with it's own delta timing methods.

## Lighting

- [Bulb](https://github.com/JujuAdams/Bulb) - 2D lighting and shadows.

- [Lighting System 2D](https://github.com/borup3/Lighting-System-2D) - Requires GameMaker 2.2+ according to the repo.

- [GameMaker Lighting Engine](https://github.com/bilouw/Gamemaker-Lighting-Engine) - Tile-based Lighting Engine that projects shadows.

- [Lighting Systems ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/playlist?list=PLYVea5brHS8YHECGPoEp4_gWU-k6nWzUy) - Very fast dynamic 2D lighting implementation from GrizzliusMaximus using shadow casting.

- [3D Fragment Point Lights](https://danieldavis.itch.io/ddg-point-light-shader-system)💸 - 3D point lights using shaders.

## Shaders

- [TransFX](https://short-bread.itch.io/transfx) - Transition Library.

- [BJRTFX](https://zikbakguru.itch.io/bjrtfx) - Zik's CRT Utility Shader

- [bktGlitch](https://odditica.itch.io/bktglitch) - Glitch shader.

- [H O R R I - F I](https://gizmo199.itch.io/horri-fi) - VHS Shader.

- [Cyberpunk Hologram Effect](https://gentoogames.itch.io/cyberpunk-hologram-effect) - Create and customize your own holographic effect using this easy-to-implement asset.

- [Depth Sorted Sillouettes](https://pixelatedpope.itch.io/depth-sorted-silhouette-example) - Example project to demonstrate shader-based depth sorting sillouettes. Tested on PC, Mac, HTML5, and Android.

- [GMShaders.com](https://gmshaders.com/) - Shader tutorials from Xor. Originally hosted at "xorshaders.com".

- [1PassBlur](https://github.com/XorDev/1PassBlur/wiki) - Blur Shader with adjustable radius.

- [Bokeh Blur](https://github.com/XorDev/Bokeh/wiki) - Extension of the 1PassBlur which provides a different look. Similar to a real lens blur. Although it's much slower than 1Pass or Dual-Kawase.

- [Dual-Kawase](https://github.com/XorDev/Dual-Kawase/wiki) - Blur Shader that limits radius but is very efficient.

- [Voronoi](https://github.com/XorDev/GMS-Voronoi-Pixels) - Sampled pixels on a Voronoi diagram.

- [Fire-Fun](https://github.com/XorDev/Fire-Fun/wiki) - Some fun magic fireballs.

- [Jump Flooding](https://terohannula.itch.io/jump-flooding-algorithm) - Jump Flooding Algorithm for GameMaker made with shaders.

- [Outline Shader](https://github.com/Grisgram/gml-outline-shader-drawer) - Outline shader.

- [Chameleon](https://github.com/Lojemiru/Chameleon) - Palette Swapper.

- [Xpanda](https://github.com/GameMakerDiscord/Xpanda) - Include code from external files in your shaders.

- [Shader Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=ch4BYqkL1w8&list=PL0kTSdIvQNCNE-BDKOlYu628AalMmXy_P) - Gaming Reverends.

- [Shader Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=a4S7LXx6-sQ&list=PL_hT--4HOvrdkihto8Xu7hhp1-5Gj8zsa) - DragoniteSpam.

## 3D

- [BBMOD](https://github.com/blueburn-cz/BBMOD) - 3D Rendering Solution. Comes with several modules to import obj, 3D camera setup, integration with ColMesh, and more.

- [dotobj](https://github.com/JujuAdams/dotobj) - Lightweight .obj/.mtl 3D model loader written in native GML.

- [Bronze Box](https://github.com/cicadian/Bronze-Box) - Example of how to build 3D world models from a 2D grid.

- [Camera3D](https://gizmo199.itch.io/camera3d) - Simple 3D camera setup.

- [Blender to GameMaker](https://github.cm/blender-to-gmstudio) - A collection of scripts to export and import Blender models to and from GameMaker.

- [Three Mice In a Trench Coat](https://github.com/XorDev/ThreeMiceInaTrenchcoat) - Source for a GameMaker 3D game.

- [sPart](https://marketplace.yoyogames.com/assets/7299/spart-3d-particle-system) - 3D Particle System from TheSnidr.

- [ColMesh](https://forum.yoyogames.com/index.php?threads/colmesh-3d-collisions-made-easy.82765/) - 3D Collision Library from TheSnidr.

- [Terrain Editor](https://dragonite.itch.io/terrain) - Terrain editor. Exports to gm models, obj, or vertex buffers.

- [Cardboard](https://github.com/JujuAdams/Cardboard) - Isometric 3D Renderer

- [Snowy Snow](https://dragonite.itch.io/snowy-snow) - 3D Snow Shader.

- [3D GameMaker Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=ojfN--tdSNM&list=PL_hT--4HOvrcML9uqHe4fwBVTm650Vy3V) - DragoniteSpam.

- [3D Collisions Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=o7kjtTEMpeU&list=PL_hT--4HOvrf_VYo26LNl3zN5uwfuC3CC) - DragoniteSpam.

- [3D Optimization Playlist ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=knfAZbJJKNY&list=PL_hT--4HOvrf_CJSA7fVU1tkjGVv5Sq2t) - DragoniteSpam.

## Sprite Stacking

- [Beginners Guide to Sprite Stacking](https://medium.com/@avsnoopy/beginners-guide-to-sprite-stacking-in-gamemaker-studio-2-and-magica-voxel-part-1-f7a1394569c0) - A primer on sprite stacking from Avis. Check out part 2 from dev_dwarf as well.

- [Fauxton3D](https://gizmo199.itch.io/fauxton3d) - Sprite stacking engine.

- [Sprite Stacking Tutorials ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=VIDN-nG3EOU&list=PL3Kbpztq9qwT9MbW_k4yyJU__or1r8P2j) - Gizmo199.

## Networking

- [Warp](https://github.com/evolutionleo/Warp) - A feature-rich framework for multiplayer games, written in GMS and NodeJS.

- [EZ Networking](https://jasontomlee.itch.io/easy-gms-networking-platformer-build) - Host/client implementation with a chat feature.

- [Patchwire-GM](https://github.com/gm-core/patchwire-gm) - The network library from gm-core if you want to use this implementation without the entire gm-core suite.

- [Colyseus](https://github.com/colyseus/colyseus-gml) - Multiplayer game client. Not ready for production use, but worth keeping an eye on.

- [GMHandshake](https://gist.github.com/nkrapivin/c73f5a962466a4ecb63187a009a300d8) - A Gist demonstrating a network handshake.

- [HTTP GML](https://github.com/Sidorakh/http.gml) - Recieve GET requests and upload files in GML.

- [GMNest](https://github.com/TimVN/GMNest) - Socket.IO extension for HTML5 games.

- [Multiplayer Networking Tutorial ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=NbsXRuNijlo&list=PLxaJReoxlrY_S4MrCYjzFCSrNX1TUX626) - Wizirdi

## Integrations

- [DHook](https://github.com/tabularelf/DHook) - Discord integration.

- [GMS2_RPC](https://github.com/Mtax-Development/GMS2_RPC) - Another Discord integration.

- [NekoPresence](https://marketplace.yoyogames.com/assets/9526/nekopresence) - Oops, all Discord integration.

- [Dissonance](https://rousr.itch.io/dissonance) - Knock knock. Who's there? Discord integration.

- [Steamworks.gml](https://github.com/YAL-GameMaker/steamworks.gml) - Various expansions to Steamworks SDK support in GameMaker: Studio.

- [GOG.gml](https://github.com/GameMakerDiscord/GOG.gml) - A native extension for GOG.com SDK support.

- [GMTwitch](https://github.com/GameMakerDiscord/GMTwitch) - Twitch integration.

## Camera

- [GameMaker Cameras: As Simple as Possible](https://www.youtube.com/watch?v=_g1LQ6aIJFk) - Pope's guide on GameMaker's camera system.

- [Camera System Guide](https://maddestudiosgames.com/gms2-meet-the-camera-system/) - Getting started with cameras in GameMaker.

- [Pixel Perfect Smooth Camera](https://github.com/YAL-GameMaker/pixel-perfect-smooth-camera) - An example of pixel-perfect yet smooth camera.

- [Dynamic Splitscreen](https://maddestudios.itch.io/gms2-project-dynamic-splitscreen) - Local multiplayer split screen implementation that merges the camera when players are close.

- [Camera All-In-One](https://jasontomlee.itch.io/allinone-camera)💸 - Editor, screenshake, view-resizing, follow modes, screen effects, etc.

## Sequences

- [Sequences Tutorial ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=WO6gzhrx5b8) - Shaun Spalding.

- [Making Splash Screen Sequences ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=hTh5UpFxx1E) - Mash Arcade.

## State Machines

- [SnowState](https://github.com/sohomsahaun/SnowState) - Robust finite state machine.

- [wFSM](https://mors-games.itch.io/wfsm) - Another Easy-to-use Finite State Machine library.

- [True State](https://pixelatedpope.itch.io/truestate)💸 - Feature-rich finite state machine to handle complex objects.

- [Pinocchio](https://github.com/JujuAdams/Pinocchio) - State-based animation system.

## Pathing

- [Aquila](https://dragonite.itch.io/aquila) - A* Pathfinding implementation.

- [A-Star-Pathing](https://github.com/helloalbertdang/A-Star-Pathing) - Another A* pathfinding implementation.

- [Grid-based Pathfinding Scripts](https://proton-squid.itch.io/pathfinding) - Flexible pathfinding system with 3 different algorithms.

## Useful Extras

- [Animated Flag](https://github.com/Grisgram/gml-animated-flag) - Vertex-animated flag.

- [Video Player Extension](https://forum.yoyogames.com/index.php?threads/video-player-for-windows-macos-and-ubuntu.77882/) - Play videos. However, the recent versions of GMS have video support now.

- [GMESCAPI](https://marketplace.yoyogames.com/assets/9529/gmescapi) - Webcam capture.

- [Smile](https://github.com/zbanack/smile) - Sentiment analysis.

- [Danmaku Project](https://github.com/OmegaX1000/DanmakuProject) - Bullet hell engine.

- [OrbinautFramework](https://github.com/TrianglyRU/OrbinautFramework) - Accurate framework to make classic Sonic games.

- [Dynamic Turn System](https://gentoogames.itch.io/turn-based-combat-system-for-gamemaker) - Great to use as a base for building turn based combat/gameplay.

- [Isometric Tactical RPG Framework](https://gentoogames.itch.io/isometric-tactical-rpg-framework) - Provides starter assets to create an isometric board game. Dynamic Turn System is included.

- [Mouse Trail Effect](https://all-x.itch.io/gms2-mouse-trail-effect) - Shows how to trace a line with primitives to create a colorful trail.

- [Starfield Generator](https://github.com/PixelProphecy/gml_starfield_generator) - A script to generate starfields in GameMaker's GML language.

- [CleanShapes](https://github.com/JujuAdams/Clean-Shapes) - Antialiased primitives library for GameMaker.

- [GMLScripts.com](https://www.gmlscripts.com/script/index) - Dozens of helper scripts, organized similarly to the official documentation.

- [GM48 Resources](https://gm48.net/resources) - Free resources from the community to become better at GameMaker Studio, game development and game jams.

- [GameMakerHow](https://gamemakerhow.com/) - Another great site that acts as a GameMaker Q&A repository for various questions you might ask in GameMaker.

- [obj_podcast](https://objpodcast.com/) - Gamedev-centered podcast featuring members of the GameMaker community.

- [Dracula Theme](https://github.com/dracula/gamemaker-studio) - Dark theme for the IDE.

- [2.3 Syntax in Detail](https://yal.cc/gamemaker-2-3-syntax-in-details/) - A full guide of the syntax features/changes in GML from Yal.

- [GameMaker Garbage Collection](https://gist.github.com/DatZach/96a30d6ae4225f8ec152719e57aed26b) - How garbage collection works in GML.

- [GitHub Yacc to GML Fix](https://www.reddit.com/r/gamemaker/comments/n5m35l/a_simple_fix_for_github_incorrectly_detecting/) - Tell GitHub your repo is all GML, not Yacc.

- [GameMaker Repo Badges](https://github.com/matthiaszarzecki/MadeWithGameMakerStudioBadges) - Fancy badges to add to your README files.

- [GameMaker Discord Community Github](https://github.com/GameMakerDiscord) - Have you made a gamemaker tool you want to share? Consider submitting it to the official Discord's GitHub.

- [Source Control with Git & GameMaker ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=UZG-P68xWio&list=PLSFMekK0JFgzmyDxVxj5Cctafu5UX_vUC) - FriendlyCosmonaut.

- [Game Resolution & Aspect Ratio Management ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=_g1LQ6aIJFk&list=PLXkVsacazW2qvdnKNzgBLkUwlgi3FU-VO) - PixelatedPope.

- [Setting up a Virtual Machine for GameMaker ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=cK5k1_zN4eM) - MicahTheManiac.

- [Making Attacks Feel Good ![YouTube](https://github.com/bytecauldron/awesome-gamemaker/raw/main/icons/youtube.png)](https://www.youtube.com/watch?v=RWkMsD2WUz8) - Blobfish.

## Blogs

- [RefresherTowel](https://refreshertowelgames.wordpress.com/category/tutorial/) - Contains several posts on level generation.

- [Tony Str](https://tonystr.net/articles) - Some great articles on working with json, regular expressions, and drawing circles in gml.

- [Katsaii](https://nuxiigit.github.io/content/blog/posts.html) - Some articles on more advanced gml topics.

## YouTube

- [Jordan Guillou](https://www.youtube.com/channel/UCBmOLRTaPrfOxnTqpCLrwdQ)

- [DragoniteSpam](https://www.youtube.com/c/DragoniteSpam)

- [Shaun Spalding](https://www.youtube.com/c/ShaunSpalding)

- [FriendlyCosmonaut](https://www.youtube.com/c/FriendlyCosmonaut)

- [PixelatedPope](https://www.youtube.com/c/PixelatedPope)

- [Xor](https://www.youtube.com/c/XorDev)

- [GamingEngineer](https://www.youtube.com/c/GamingEngineer)

- [TheSnidr](https://www.youtube.com/c/TheSnidr)

- [Peyton Burnham](https://www.youtube.com/channel/UCfh2Q3TsvlxM1S2GvXQ4eeQ)

- [Gaming Reverends](https://www.youtube.com/channel/UC7fkptPD1FHQyDc9Fnm9S_A)

- [Let's Learn This Together](https://www.youtube.com/c/LetsLearnThisTogether)

- [Matharoo](https://www.youtube.com/c/GameMakerStationMatharoo)

- [GravityShift Games](https://www.youtube.com/c/SlasherXGAMES/)

- [Slyddar](https://www.youtube.com/c/Slyddar/)

## Community

[![GameMaker Forums](https://img.shields.io/badge/Forums-6AA916?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAMAAAAolt3jAAAAZlBMVEX%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F%2BrG8stAAAAIXRSTlMABg0OFBkfcn1%2Bf4CBgoOFhoeIiouWmNDa5ebp8PX2%2B%2F6o6Vq%2BAAAAY0lEQVR42k2OWQ6AIAwFn%2BIOioobrnD%2FS4o0EeanmQxNAdErRFTWtsFq6%2BiiZozz0CSnTjYBwo0RkF8DWDLf51Ni9K%2FYdq0Fy3KAfzk97M7goK1F%2F4rGH9Kk1OlboQtEDIrmC%2BU3CVxTr%2FRMAAAAAElFTkSuQmCC&&logoColor=white)](https://forum.yoyogames.com/index.php)
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/gamemaker/)
[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/gamemaker)

## Footnotes

This is based on a list from [GameMaker Libraries](https://github.com/FaultyFunctions/GameMakerLibraries) and from Gleb Tsereteli's [Google Doc](https://docs.google.com/document/d/1wUm8FZPm8AKLZgC-P76TPJAMXs0EN2s5mJGvvUFwycw/edit). I just categorized it and added some additional links/details. If you need more general game development resources, check out [Awesome Gamedev](https://notabug.org/Calinou/awesome-gamedev) or [MagicTools](https://github.com/ellisonleao/magictools#readme).

*GameMaker® is the property of YoYo Games™. This list is not affiliated with YoYo Games.*

## Contributing

Have something awesome to share? Check out the [Contributing Guidelines](https://github.com/bytecauldron/awesome-gamemaker/blob/main/CONTRIBUTING.md).

## Special Thanks

JujuAdams, FaultyFunctions, Gleb Tsereteli, Shaun Spalding, DragoniteSpam, Nick Ver Voort, PixelatedPope, Tony Strømsnæs, HeartBeast, Xor, Gaming Reverends, Matharoo, YellowAfterlife, Gizmo199, Avis, Josh Wilson, Lojemiru

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [bytecauldron](http://github.com/bytecauldron) has waived all copyright and related or neighboring rights to this work.

![Keybindings](https://github.com/bytecauldron/awesome-gamemaker/raw/main/images/keybindings.png)
