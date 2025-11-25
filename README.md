# Casual Skript Collection

A small collection of casual scripts I've been working on for the past 2–3 months on my minecraft server that has 6-10 daily players online at once.
Designed for Minecraft Java 1.21.8 — 1.21.10 (could possibly use on lower versions)
Paper-based server using the Skript as plugin.

- **Purpose**: add lightweight custom items, enchantments, boss-related mechanics and small quality-of-life features without heavy plugin overhead.
- **Status**: actively developed by me (personal project). Use at own risk and test on a staging server first.
- **Origin**: started as a small project to learn Java for university coursework.

**Compatibility**

- **Minecraft**: `1.21.8` — `1.21.10`
- **Server**: Paper/Spigot (Skript plugin required). Test your Skript/Paper versions if you see errors.

**Included scripts**

- `AOTV.sk`
- `artificialEnderdragonHeart.sk`
- `aShardOfDivineTime.sk`
- `customCrafting.sk`
- `customEnchants.sk`
- `enderDragonsHeart.sk`
- `godsClock.sk`
- `godsCrossbow.sk`
- `godscrossbowPillagers.sk`
- `godsFear.sk`
- `godsMushroom.sk`
- `godsWings.sk`
- `godwingsBarrier.sk`
- `goldenGlutony.sk`
- `mushroomsFollower.sk`
- `rankmenu-on-firstjoin.sk`
- `testing-drop.sk`

There is also an `-examples/` folder (disabled/prefixed with a hyphen in this workspace) with sample snippets and experimental features.

**Installation**

- Copy the scripts (the `.sk` files) into your server's `plugins\Skript\scripts\` folder.
- Reload Skript or the server to load the scripts. Example commands (run in server console or in-game with proper permissions):

```bat
rem Reload a single script (common aliases):
/sk reload <script>

rem Reload the entire Skript folder:
/sk reload all

rem Some installations use:
/skript reload <script>
/skript reload all
```

If you see parse errors on reload, check the server log and the top of the reported script for the problematic line.

**Usage & customization**

- Many scripts include variables or config comments at the top — edit those to customize names, item IDs, messages and behavior.
- If you want to disable a script temporarily, remove it from the `scripts/` folder or add a leading hyphen to its filename (if your workflow uses that convention).
- For cross-script dependencies, keep related scripts together so any required functions are available when Skript loads.

**Known issues & troubleshooting**

- Skript syntax and addon compatibility can vary by Skript version — if a script errors, first check your Skript and addon versions.
- If a script fails to load: 1) remove other recently added scripts, 2) reload one-by-one with `/sk reload <script>` to isolate the error.
- If something behaves unexpectedly, check server logs for stack traces and share them if you want help debugging.

**Changelog (summary)**

- **v0.29.3 — Working set (current)**: Initial public collection after ~2–3 months of development — focused on custom items/enchantments, boss heart and crossbow mechanics, small features (rank menu on join, drops testing).
- Compatibility target: Minecraft `1.21.8` — `1.21.10`.

**License & credits**

- Personal project. You may use and modify these scripts on your own server. If you redistribute or publish them, please mention the original author (me).

---

File location: `plugins\Skript\scripts\README.md`
