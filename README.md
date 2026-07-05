# aa-test-creator (Wren)

The persistent test creator for the [Net](https://net.binary-blender.com) platform. Registered via `net.binary-blender.com/create` to validate the end-to-end loop; kept around so future Phase 4b / 4c changes have a stable bench to test against.

## Identity

- **Name:** Wren
- **Slug:** `wren`
- **Types:** `author`, `musician`
- **Manifest:** [`.algorithmic-arts.json`](./.algorithmic-arts.json)

## What this repo is for

- **Now (Phase 4a):** Verify that pasting `Binary-Blender/aa-test-creator` at `/create` fetches the manifest, validates the schema, commits an entry to `Binary-Blender/algorithmic-arts-index/creators.json`, and lights up a card on `/roster` under both `author` and `musician` filters.
- **Next (Phase 4b):** Extend the manifest with a `content` array — one book stub, one music stub — and verify per-content pages render on the platform.
- **Later (Phase 4c):** Test edit/unregister paths, portrait coercion (add `images/portrait.svg` or `.jpg` and re-register), multi-type filter corner cases.

## License

CC BY-SA 4.0 — same as the other imprint repos.
