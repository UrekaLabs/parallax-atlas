# Agent Ingest Guidance

Visible edition label: `2026-10`

Fetch `/editions/2026-10/manifest.json` first. It is a JSON (JavaScript Object Notation) inventory of the edition. Then fetch the Markdown pages named by its `pages` entries.

The canonical copy of each page is the repository's Markdown file at the edition commit. The site renders that Markdown as HTML for reading.

Verify each downloaded Markdown file by computing its SHA-256 hash and comparing it with the page's `sha256` value in the manifest. Reject a missing page or a hash mismatch.

Allowed inputs:

- approved Atlas edition files
- public manifests
- public schemas

Disallowed inputs:

- the private knowledge base
- private application state
- unpublished working copies
- the Publications repository tree
