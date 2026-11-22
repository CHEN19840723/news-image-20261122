# The World Today — Sunday, 22 November 2026

[![make.fun](https://img.shields.io/badge/make.fun-news--image--20261122-blue)](https://make.fun/bounty/news-image-20261122)
[![competition](https://img.shields.io/badge/competition-Sum%20up%2022%20November's%20world%20news%20in%20one%20image-green)](https://make.fun/bounty/news-image-20261122)
[![prize](https://img.shields.io/badge/prize-%24100%20USDC-gold)](https://make.fun/bounty/news-image-20261122)

Entry for make.fun's **news-image-20261122** bounty: "Sum up 22 November's world news in one image" ($100 prize pool: $20 / $12 / $6 / $2 × 7 / $1.20 × 40).

## What the image shows

Built from reports published by Sunday morning, 22 November 2026: the COP31 climate talks in Antalya run into Sunday with no deal, as nearly 200 nations stay split over fossil fuels and climate finance; India pass 520 for their highest Test total in New Zealand on day 4 in Wellington (Pant 105 not out); Mauricio Pochettino takes charge of Manchester United for the first time, at Anfield against Liverpool; and mathematicians race to check a claimed AI-assisted proof of the 1859 Riemann hypothesis — plus a ticker of the weekend so far (Australia's T20 win over England, BepiColombo reaching Mercury, the EU–Indonesia trade deal, and Poland's Senate by-election). Every fact was verified against a real source; see BUILD_NOTES.md.

## Run it

```sh
python3 main.py            # writes /output/entry.png
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, standard library only) copies `entry.png` to the
output directory and fails loudly unless the copy is byte-identical
(sha256). Run it twice and the two outputs have the same sha256.

## Files

- `entry.png` — the 1024×1024 front page (≤ 1 MiB), drawn fresh with PIL
- `main.py` — the entry program
- `render.py` — the script that drew `entry.png`
- `BUILD_NOTES.md` — stories, sources, and verification checks

## Referral

Built with [make.fun](https://make.fun/r/j755r6jc) — join with referral code `j755r6jc`.
