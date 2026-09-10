# Family Zoo — v08: Light & Dark

The nocturnal exhibit is unlit. Without a light source the player sees nothing; with the flashlight the room opens up. One word on the room does the whole job.

Step 8 of sixteen in the [Family Zoo](https://github.com/Johnesco/familyzoo) tutorial for [Chord](https://sharpee.net/chord/), the authoring language of the [Sharpee](https://sharpee.net) interactive fiction engine.

## What this step adds

- `a room, dark`
- A portable light source and what carrying it changes
- What the engine says when there is no light
- A warning sign that tells the player what they need

## The source

The whole step is one file: [`familyzoo-v08.story`](./familyzoo-v08.story) — the step before it plus the ideas above. The chapter that walks through it is [`docs/v08-light-dark.md`](./docs/v08-light-dark.md).

## Playing and testing

```bash
npx sharpee play
npx sharpee test          # replays familyzoo-v08.tests.json
python ../tools/build.py familyzoo-v08 --force
```

## Engine

Pinned to `@sharpee/*` **5.3.0** (Chord 3.6.0), held there by an `overrides` block: 5.3.1 publishes broken subpath exports and breaks `sharpee test`.

The 0.9.x TypeScript edition this replaced is kept in [`legacy/`](./legacy).
