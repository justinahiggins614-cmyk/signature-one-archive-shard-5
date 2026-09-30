# signature-one-archive-shard-5

Frozen storage shard for Manon's Signature Spec Catalog (Pending Patents).

- Holds spec chunks `data/volumes/specs-c00811.jsonl.gz` … `specs-c00940.jsonl.gz`
  (JAH-SPEC-121501 … JAH-SPEC-141000 — 19,500 original draft specs).
- Served to the main catalog page at
  https://justinahiggins614-cmyk.github.io/signature-one-archive/specs.html
  via its `data/index/shards.json` registry; the page fetches this repo's
  `data/index/specs.idx.json.gz` and resolves chunks through this repo's
  Pages base URL.
- Do not edit: shard repos are append-only frozen storage. New chunks always
  land in the main `signature-one-archive` repo.
