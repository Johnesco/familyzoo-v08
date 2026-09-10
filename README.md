# Family Zoo — v08 — Light & Dark

Adds a pitch-black nocturnal exhibit reachable only after finding and switching on a flashlight in the supply room. Introduces darkness as a room property and light sources as the gating mechanism.

Step 8 of the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial — a progressive walkthrough of the [Sharpee](https://sharpee.net) TypeScript interactive fiction engine, from a single room to a full multi-file story.

## What this step teaches

- isDark flag on RoomTrait
- LightSourceTrait with brightness and isLit
- SwitchableTrait for on/off toggles
- The flashlight pattern combining three traits
- Alternative patterns for always-on, consumable, and adjustable lights

## Playing

Open `play.html`, or preview the folder:

```bash
python -m http.server 8000 --directory familyzoo-v08
```

## Building

This is a **frozen 0.9.x TypeScript version**. The built player in this folder is the published artifact; it is re-laid from `browser/` by the workspace build:

```bash
python ../tools/build.py familyzoo-v08
python C:/code/ifhub/tools/ship.py familyzoo-v08
```

The authoring tree for every version lives in the [familyzoo](https://github.com/Johnesco/familyzoo) repo.
