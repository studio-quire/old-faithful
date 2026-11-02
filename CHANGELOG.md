# Changelog

Old Faithful's releases, newest first. Each has its own version number, carried by Old Faithful's mods, its pack and
its server package, and names the Pure Faithful release it's built on, whose mods and LWJGL are inside the pack as
that release has them; [Pure Faithful's changelog](https://github.com/studio-quire/pure-faithful/blob/main/CHANGELOG.md)
covers those. Entries say what a player or server owner notices.

## 0.1.0 (2026-11-02)

The first release of Old Faithful, for Windows, on Pure Faithful 0.1.2.

- Fixes for beta 1.7.3's own clear mistakes, each on a switch in `config/oldfaithful-fixes.properties`: mining and
  tools (a tool's last use, wooden slabs, tools slow on their own materials), items and crafting (the furnace's lava
  bucket, shift-click crafting, pick block, a crash on bad slab and dye items), the world (water washing items away,
  slimes, mobs through walls, saddles, minecarts and items, fishing, getting out of boats), redstone (repeaters,
  clocks that stop on reload, torch burnout), the screen and sound (the grey sky with a chest open, the cursor's
  item, fence undersides, sliders, footsteps after stairs and more) and multiplayer (ghost blocks, mob jitter,
  players unseen after a teleport, the order chunks arrive in, the mining pause, blank signs, frozen entities after
  a respawn, players turned a few degrees off).
- Lighting as beta's own rule says it should be: no dark pockets under overhangs or at chunk edges, lava from world
  generation lit; existing worlds heal as they load.
- Options: a settings screen (Options > Old Faithful...) for every switch, a field-of-view slider, the GUI at Normal
  on a first start, Quit Game on the title screen, and the window maximised the first time and remembered after.
- "Old Faithful 0.1.0" on the title screen, under beta's version line.
