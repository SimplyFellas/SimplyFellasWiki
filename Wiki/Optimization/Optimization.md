<link rel="stylesheet" href="../Styles/Stylesheet.css">

<div class="wiki-content">

<a href="../README.md" class="nav-back">← Back to Wiki Home</a>

# Optimization

SimplyFellas includes various mods that optimize the performance of your game and enhance your technical experience. The pack is fully optimized from the ground up to provide smooth gameplay even with nearly 200 mods installed.

## About

There are several mods that reduce memory usage such as FerriteCore, Fix GPU Memory Leak, and ModernFix. There are several mods that improve rendering performance such as Sodium, Colorwheel, and ImmediatelyFast. There is also a ton of optimizations made to rendering by Smooth Chunk Save, Chunk Sending, and Concurrent Chunk Management. Together, these optimization mods ensure that SimplyFellas runs smoothly and efficiently.

---

## Rendering Optimizations

### Sodium

Most compatible rendering optimization mod which greatly improves frame rates and micro-stutter. Sodium is the cornerstone of rendering performance, providing significant FPS improvements while maintaining full compatibility with other mods.

<img src="Sodium.png" alt="Sodium" class="inline-image">

### Sodium Extra

Brings tons of additional settings to Sodium, allowing you to tweak your graphical settings even further. Provides advanced configuration options for fine-tuning your rendering performance.

### Sodium Leaf Culling

This mod culls out (unrenders) leaves that you cannot see. Greatly improves performance due to leaves being transparent and often covering large areas.

### Sodium Shadowy Path Blocks

Reintroduces vanilla-like smooth lighting to non-full blocks such as dirt paths, improving visual quality while maintaining performance.

### Entity Culling

This mod culls out (unrenders) entities that you cannot see. Uses async path tracing to hide tiles/entities for better performance. Essential for maintaining good FPS when there are many entities nearby.

<img src="EntityCulling.png" alt="Entity Culling" class="inline-image">

### ImmediatelyFast

Speeds up the immediate rendering mode in Minecraft. Optimizes all immediate rendering implementations, providing performance improvements across the board.

### Colorwheel & Colorwheel Patcher

Colorwheel optimizes Iris shaders with Flywheel (Create's backend mod). Colorwheel Patcher patches various shader packs to work with Flywheel, ensuring shader compatibility with Create mod.

<img src="CreateFPS.png" alt="Create Better FPS" class="inline-image">
<img src="CreateShaders.png" alt="Create Shaders" class="inline-image">
<img src="CreateShaders2.png" alt="Create Shaders 2" class="inline-image">

---

## Create-Specific Optimizations

### Create: Better FPS

This mod improves your FPS with Create while using shader packs. Essential for maintaining performance when using Create mods with shaders enabled.

### Create: Smart Bounds

Improves the Create mod's entity render bounds, providing better performance while rendering multiple contraptions. Optimizes Create's rendering to reduce performance impact.

<img src="SmartBounds.png" alt="Create Smart Bounds" class="inline-image">

---

## Memory Optimizations

### FerriteCore

Optimizes memory usage by a ton. Useful for both client/server installations. Reduces memory footprint significantly, allowing you to run more mods or increase render distance.

### ModernFix

Reduces memory usage and fixes many vanilla Minecraft bugs. Provides general optimizations and bug fixes that improve overall game stability and performance.

### Fix GPU Memory Leak

Fixes memory leaks on the client such as GL_OUT_OF_MEMORY, GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT, and GL_INVALID_FRAMEBUFFER_OPERATION. Prevents GPU memory issues that can cause crashes or performance degradation.

---

## Chunk & World Optimization

### Concurrent Chunk Management (C2ME)

This mod improves the chunk performance of Minecraft by better threading and scaling the workload of vanilla chunk generation. Dramatically improves world generation and chunk loading performance.

<img src="C2ME.png" alt="C2ME" class="inline-image">

### Smooth Chunk Save

Saves chunks continuously over time, reducing server lag from saving too many chunks at once. Prevents lag spikes from chunk saving operations.

### Chunk Sending

This mod optimizes the chunk sending packets through sorting and distribution over time. Improves multiplayer performance by optimizing how chunks are sent to clients.

---

## AI & Physics Optimizations

### AI Improvements

This mod upgrades the logic of AI in favor of low-level modifications that provide extra performance. Improves mob AI performance without changing behavior, making the game run smoother with many entities.

### Lithium

Improves a number of systems such as physics, AI, block ticking, etc. without changing the behavior of the game. Provides comprehensive game engine optimizations.

---

## Network Optimizations

### Krypton FNP

Optimizes the entire Minecraft networking stack. Implements RecastLib and optimizes client/server networking. Essential for smooth multiplayer performance.

<img src="Krypton.png" alt="Krypton" class="inline-image">

### Disconnect Packet Fix

Fixes the "error sending packet clientbound" error that frequently spams the console on Vanilla 1.21.1. Prevents console spam and potential connection issues.

---

## Quality of Life Optimizations

### Fast Boot

This mod decreases the amount of time it takes to boot the game by delaying data conversion and processing. Significantly reduces startup time.

### Borderless Window

This mod allows your game to run in an optimized borderless fullscreen mode. Provides better performance than windowed mode while maintaining the convenience of alt-tabbing.

### NoChatReports

Makes the chat unreportable which removes Microsoft's ability to track and moderate you. Also provides a small performance benefit by reducing chat processing overhead.

<img src="NoChatReports.png" alt="NoChatReports" class="inline-image">

### Too Fast

Removes the console log spam about players moving too fast. Prevents console spam that can impact performance.

---

## Performance Results

With all these optimization mods working together, SimplyFellas delivers excellent performance even with nearly 200 mods installed. You can expect smooth gameplay, high frame rates, and efficient memory usage.

<img src="FPSExample.png" alt="FPS Performance Example" class="inline-image">

---

## Image Gallery

<div class="image-gallery">
    <div class="gallery-item">
        <img src="C2ME.png" alt="C2ME">
    </div>
    <div class="gallery-item">
        <img src="CreateFPS.png" alt="Create Better FPS">
    </div>
    <div class="gallery-item">
        <img src="CreateShaders.png" alt="Create Shaders">
    </div>
    <div class="gallery-item">
        <img src="CreateShaders2.png" alt="Create Shaders 2">
    </div>
    <div class="gallery-item">
        <img src="EntityCulling.png" alt="Entity Culling">
    </div>
    <div class="gallery-item">
        <img src="FPSExample.png" alt="FPS Example">
    </div>
    <div class="gallery-item">
        <img src="Krypton.png" alt="Krypton">
    </div>
    <div class="gallery-item">
        <img src="NoChatReports.png" alt="NoChatReports">
    </div>
    <div class="gallery-item">
        <img src="SmartBounds.png" alt="Smart Bounds">
    </div>
    <div class="gallery-item">
        <img src="Sodium.png" alt="Sodium">
    </div>
</div>

---

<div class="credits-section">

## Credits & Attributions

### Authors

* **AI Improvements**: [QueenOfMissiles](https://curseforge.com/members/queenofmissiles)
* **Borderless Window**: [nimueller](https://curseforge.com/members/nimueller)
* **Smooth Chunk Save / Chunk Sending / Fix GPU Memory Leak**: [someaddon](https://curseforge.com/members/someaddon)
* **Concurrent Chunk Management (C2ME)**: [ishlandmc](https://curseforge.com/members/ishlandmc)
* **Create: Better FPS**: [moepus](https://curseforge.com/members/moepus)
* **Create: Smart Bounds**: [LiukRast](https://curseforge.com/members/liukrast)
* **Disconnect Packet Fix**: [ascpixi](https://curseforge.com/members/ascpixi)
* **Entity Culling**: [tr7zw](https://curseforge.com/members/tr7zw)
* **Fast Boot**: [dnlayu](https://curseforge.com/members/dnlayu)
* **FerriteCore**: [malte0811](https://curseforge.com/members/malte0811)
* **ImmediatelyFast**: [RalphiMC](https://curseforge.com/members/raphimc)
* **Krypton FNP**: [04find](https://curseforge.com/members/04find)
* **Lithium / Sodium**: [JellySquid](https://curseforge.com/members/jellysquid)
* **Sodium Extra**: [FlashyReese](https://curseforge.com/members/flashyreese)
* **Sodium Leaf Culling**: [Txni](https://curseforge.com/members/txni)
* **Sodium Shadowy Path Blocks**: [Rynnavinx](https://curseforge.com/members/rynnavinx)
* **Colorwheel & Colorwheel Patcher**: [djefrey](https://curseforge.com/members/djefrey)
* **ModernFix**: [embeddedt](https://curseforge.com/members/embeddedt)
* **NoChatReports**: [Aizistral](https://curseforge.com/members/aizistral)
* **Too Fast**: [Noobanidus](https://curseforge.com/members/noobanidus)

### Mods

#### Rendering Optimizations
* [Sodium](https://curseforge.com/minecraft/mc-mods/sodium) - Most compatible rendering optimization mod which greatly improves frame rates and micro-stutter
* [Sodium Extra](https://curseforge.com/minecraft/mc-mods/sodium-extra) - Brings tons of additional settings to Sodium, allowing you to tweak your graphical settings even further
* [Sodium Leaf Culling](https://curseforge.com/minecraft/mc-mods/sodium-leaf-culling) - Culls out (unrenders) leaves that you cannot see, greatly improving performance
* [Sodium Shadowy Path Blocks](https://curseforge.com/minecraft/mc-mods/sodium-shadowy-path-blocks) - Reintroduces vanilla-like smooth lighting to non-full blocks such as dirt paths
* [Entity Culling](https://curseforge.com/minecraft/mc-mods/entityculling) - Culls out (unrenders) entities that you cannot see using async path tracing
* [ImmediatelyFast](https://curseforge.com/minecraft/mc-mods/immediatelyfast) - Speeds up the immediate rendering mode in Minecraft
* [Colorwheel](https://curseforge.com/minecraft/mc-mods/colorwheel) - Optimizes Iris shaders with Flywheel (Create's backend mod)
* [Colorwheel Patcher](https://curseforge.com/minecraft/mc-mods/colorwheel-patcher) - Patches various shader packs to work with Flywheel

#### Create-Specific Optimizations
* [Create: Better FPS](https://curseforge.com/minecraft/mc-mods/create-better-fps) - Improves your FPS with Create while using shader packs
* [Create: Smart Bounds](https://curseforge.com/minecraft/mc-mods/create-smart-bounds) - Improves the Create mod's entity render bounds, providing better performance while rendering multiple contraptions

#### Memory Optimizations
* [FerriteCore](https://curseforge.com/minecraft/mc-mods/ferritecore) - Optimizes memory usage by a ton, useful for both client/server installations
* [ModernFix](https://curseforge.com/minecraft/mc-mods/modernfix) - Reduces memory usage and fixes many vanilla Minecraft bugs
* [Fix GPU Memory Leak](https://curseforge.com/minecraft/mc-mods/fix-gpu-memory-leak) - Fixes memory leaks on the client such as GL_OUT_OF_MEMORY, GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT, and GL_INVALID_FRAMEBUFFER_OPERATION

#### Chunk & World Optimization
* [Concurrent Chunk Management (C2ME)](https://curseforge.com/minecraft/mc-mods/c2me) - Improves the chunk performance of Minecraft by better threading and scaling the workload of vanilla chunk generation
* [Smooth Chunk Save](https://curseforge.com/minecraft/mc-mods/smooth-chunk-save) - Saves chunks continuously over time, reducing server lag from saving too many chunks at once
* [Chunk Sending](https://curseforge.com/minecraft/mc-mods/chunk-sending-forge-fabric) - Optimizes the chunk sending packets through sorting and distribution over time

#### AI & Physics Optimizations
* [AI Improvements](https://curseforge.com/minecraft/mc-mods/ai-improvements) - Upgrades the logic of AI in favor of low-level modifications that provide extra performance
* [Lithium](https://curseforge.com/minecraft/mc-mods/lithium) - Improves a number of systems such as physics, AI, block ticking, etc. without changing the behavior of the game

#### Network Optimizations
* [Krypton FNP](https://curseforge.com/minecraft/mc-mods/krypton-fnp) - Optimizes the entire Minecraft networking stack, implements RecastLib and optimizes client/server networking
* [Disconnect Packet Fix](https://curseforge.com/minecraft/mc-mods/disconnect-packet-fix) - Fixes the "error sending packet clientbound" error that frequently spams the console on Vanilla 1.21.1

#### Quality of Life Optimizations
* [Fast Boot](https://curseforge.com/minecraft/mc-mods/fastboot) - Decreases the amount of time it takes to boot the game by delaying data conversion and processing
* [Borderless Window](https://curseforge.com/minecraft/mc-mods/borderless) - Allows your game to run in an optimized borderless fullscreen mode
* [NoChatReports](https://curseforge.com/minecraft/mc-mods/no-chat-reports) - Makes the chat unreportable which removes Microsoft's ability to track and moderate you
* [Too Fast](https://curseforge.com/minecraft/mc-mods/too-fast) - Removes the console log spam about players moving too fast

</div>

</div>
