# NOTICE — Font Assets License

The three WOFF2 font files in this directory (`public/fonts/*.woff2`) are
**not** covered by this repository's Apache License 2.0 (see the repo root
`LICENSE` and `docs/principles/core-principles.md`'s "Open Source Licensing"
section, which covers the application's *code* only). These font files
carry the SIL Open Font License, described below.

## Source

- **Atkinson Hyperlegible** (`atkinson-hyperlegible-400.woff2`,
  `atkinson-hyperlegible-700.woff2`) — designed by the Braille Institute of
  America and Applied Design Works, purpose-built for letterform
  disambiguation and low-vision / early-reader legibility. Upstream:
  https://www.brailleinstitute.org/freefont/ and
  https://github.com/googlefonts/atkinson-hyperlegible.
- **Fraunces** (`fraunces-900.woff2`) — designed by Phaedra Charles, Flavia
  Zimbardi, and David Jonathan Ross for Undercase Type. Upstream:
  https://github.com/undercasetype/Fraunces.

Both were fetched once from the Fontsource CDN
(https://fontsource.org/fonts) — a mirror of the upstream OFL sources — and
committed here as static assets. This is the offline-first pattern
`docs/design/visual-language-v1.md` requires: no build-time font fetch, no
runtime CDN request.

## License

SIL Open Font License 1.1 — see `atkinson-hyperlegible-OFL.txt` and
`fraunces-OFL.txt` alongside for the two upstream OFL copies (identical
license text, distinct copyright holders).

License URI (canonical): https://openfontlicense.org/

Under this license, these font files:

- **may** be freely used, studied, modified, and redistributed
- **may** be embedded and distributed with any software (including
  proprietary software) — the fonts themselves do not become GPL/AGPL/etc.
  by embedding
- **may not** be sold on their own (an independent commercial product
  consisting solely of the fonts)
- **must** retain the OFL copyright and license notice when redistributed
  (satisfied by `*-OFL.txt` alongside)
- **must** be renamed if a Reserved Font Name is set on the modified
  version (neither Atkinson Hyperlegible nor Fraunces asserts a Reserved
  Font Name in their upstream OFL, per this directory's OFL files — no
  rename required for unmodified redistribution)

The OFL is more permissive than the CC BY-NC-SA that governs the ARASAAC
symbols in `public/symbols/`, so nothing in this notice restricts usage
already permitted by that adjacent license.

## Required attribution

The OFL requires the upstream copyright notice be retained (see the two
`*-OFL.txt` files). No user-facing credit in the running application is
required by the OFL — but Wren surfaces a short credit in caregiver edit
mode alongside the existing ARASAAC symbol attribution, so caregivers can
reach both this notice and the two upstream OFL files from wherever the
app itself is distributed and used.
