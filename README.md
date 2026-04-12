# druidshape-data

Beast reference data for the [druidshape-py](https://github.com/belkira/druidshape-py) app.

Hosted here so the app can fetch content updates without needing a rebuild. The app will fall back to its bundled copy of these files if the network fetch fails.

## Files

- `beasts.json` — core 5e SRD beasts (94 entries)
- `volos.json` — Volo's Guide supplemental beasts (15 entries)

## Schema

See [the main repo](https://github.com/belkira/druidshape-py) for the Beast data structure. Briefly: each entry has `name`, `size`, `cr`, ability scores, movement speeds, `traits`, and `actions` (or `action` in volos.json). The app normalizes both.

## Credits

Original data: D&D 5e SRD (OGL 1.0a). Derived from the beast list maintained in [kufii/Druidshape-5e](https://github.com/kufii/Druidshape-5e).
