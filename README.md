# Theme Studio — Corresponding Source

This repository distributes the **corresponding source code** for the
third-party open-source themes and icon packs bundled in the Theme
Studio data pack (`themestudio-data.tspack`), as required by the GNU
General Public License v3 and the other licenses involved.

Download `themestudio-corrsrc-v1.0.0.tar.zst` from the
[Releases](../../releases) page. Inside:

- `MANIFEST.tsv` — upstream repo, URL, and full pinned commit per product
- `sources/` — one snapshot per upstream repository at the pinned commit
- `BUILD-FROM-SOURCE.md` — exact build/install commands and every
  modification Theme Studio applied
- `products.tsv` — audited per-product licence records
- `SHA256SUMS` — verify with `sha256sum -c SHA256SUMS`

These sources are distributed under the licenses of the components they
contain (see `licenses/` in the data pack and `THIRD-PARTY-NOTICES.txt`).
The Theme Studio EULA does **not** apply to this archive.

Contact: linuxtexcourse@gmail.com
