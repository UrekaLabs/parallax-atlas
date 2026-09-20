# Manifest

Visible edition label: `2026-10`

The edition manifest is a JSON (JavaScript Object Notation) file at `/editions/2026-10/manifest.json`.

It contains:

- the edition ID and manifest format number;
- the approval-set hash and source cutoff commit;
- candidate, passed, and published page counts;
- the correction policy and patch root; and
- a page list with each public ID, title, repository path, public URL, SHA-256 hash, rights statement, provenance, and topic assignments.

A page's `sha256` value is the hash of its Markdown file in the repository at the edition's commit. The site's HTML is a rendering of that Markdown, not the object whose hash appears in the manifest.

The correction fields point to `/corrections-removal/` and the visible patch roots under `/editions/2026-10-patch-N/`.
