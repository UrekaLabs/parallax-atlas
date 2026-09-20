# Schema

Visible edition label: `2026-10`

The October contract surface is `manifest.schema.json`, a JSON (JavaScript Object Notation) Schema for manifest format `1`.

It validates the edition manifest at `/editions/2026-10/manifest.json`.

Consumers must reject a manifest whose `format` value they do not support. The schema requires every manifest field and rejects unrecognized fields.

Object and provenance schemas are planned for a later edition. `object.schema.json` and `provenance.schema.json` are not published in this edition.
