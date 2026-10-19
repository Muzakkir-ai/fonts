# Canonical names for qiraat SVGs

These folders distinguish the **qari** (imam), **rawi** (transmitter), and **common** printed marks.

- `qari/<qariId>.svg` — one imam SVG for each of the ten qurra.
- `rawi/<qariId>-<rawiSlug>.svg` — two transmitter SVGs per imam, distinguishing names shared across imams.
- `common/riwayah.svg`, `common/imam.svg`, `common/shatbiyah.svg`, `common/durrah.svg` — common SVG words and route marks.
- `reading-catalog.json` — authoritative Arabic spelling and stable IDs; Zite uses the same catalog.

Special cases:
- **الدوري** of Abu Amr: `rawi/abiamr-duri.svg`; same internal narrator as حفص الدوري.
- **حفص الدوري** of al-Kisai: `rawi/kisai-hafsduri.svg`.
- **خلف** of Hamzah (rawi): `rawi/hamza-khalaf.svg`.
- **خلف العاشر** (qari): `qari/khalaf.svg`.

Old SVG filenames remain available at the root of this directory for existing consumers. Use the canonical folders in new code.

Do not alter Arabic sanad texts to rename filenames; this is only a file/identifier standardization.
