# MazeScroll

## Overview

MazeScroll is a compact roguelike deck-builder MVP that features pre-populated dungeon floors, hero archetypes, and JSON-driven content. Each run traverses a small grid with a single entry and exit, culminating in a boss encounter that awards sigils and card upgrades.

## Getting Started

- **Prerequisites**
  - Node.js 18+ (for future React/Phaser frontend integration)
  - npm or yarn
- **Install**
  - `npm install`
- **Run**
  - Client/bootstrap scripts will be added once the frontend scaffold is committed.

## Data Directory

- **Heroes** `data/heroes/`
  - `hero_sword_fighter.json`
  - `hero_dreamcaster.json`
  - `hero_axe_wielder_dwarf.json`
  - `hero_elf_archer.json`
- **Cards** `data/cards/`
  - `dreamcaster.json`
  - `sword_fighter.json`
  - `axe_wielder_dwarf.json`
  - `elf_archer.json`
- **Planned** directories: `data/floors/`, `data/rooms/`, `data/monsters/`, `data/sigils/`, `data/story/`, `data/mini_games/`

## Roadmap

- **Phase 1**: Populate floor/room JSON, implement dungeon generator, and wire hero/card loaders.
- **Phase 2**: Integrate Phaser scene with React shell; hook combat, sigil rewards, and card upgrades.
- **Phase 3**: Add multi-floor progression, boss minion factories, and transformation mechanics.

## Contributing

- Use feature branches; open PRs against `main`.
- Keep JSON schemas aligned with the documented hero/monster/card formats in `plans/`.
- Add tests or validation scripts when introducing new data files.
