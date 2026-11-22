# Build notes — news-image-20261122

Built Sunday 22 November 2026, ~08:10–08:40 CST (00:10–00:40 UTC), from
reports published by Sunday morning. The day was only minutes old in UTC,
so the front page leads with stories live on Sunday morning and labels
weekend items honestly ("The weekend so far"); nothing dated 21 November
is presented as 22 November news.

## Stories on the image

### Lead — COP31 talks run into Sunday with no deal (Antalya, Turkey)
- Nearly 200 nations still split over fossil fuels and climate finance;
  draft deal drops any mention of cutting oil, gas and coal and drops a
  $120bn adaptation-finance target; EU climate chief: a good deal or no deal.
- Sources:
  - SBS Morning News Bulletin, 22 November 2026 —
    https://www.youtube.com/watch?v=sGJzMmlK39c
  - Reuters, "COP31 climate summit risks failure as talks go deep into
    overtime" (21 Nov, talks into Sunday) —
    https://947thebeast.com/2026/11/21/cop31-climate-summit-risks-failure-as-talks-go-deep-into-overtime/
  - BBC, "Fight over fossil fuels leaves COP31 climate talks in deadlock" —
    https://thegenevatimes.ch/fight-over-fossil-fuels-leaves-cop31-climate-talks-in-deadlock/

### Cricket — India set a record total in New Zealand (Wellington)
- Day 4, Sunday 22 Nov: India pass 520, their highest Test total on New
  Zealand soil; Rishabh Pant 105 not out, lead 221.
- Sources:
  - ESPNcricinfo live score, NZ v IND 1st Test, Basin Reserve —
    https://www.cricinfo.com/series/india-in-new-zealand-2026-27-1539421/new-zealand-vs-india-1st-test-1539442/live-cricket-score
  - https://crex.com/cricket-records/india-break-all-previous-records-vs-new-zealand-smash-their-highest-ever-innings-total-6b0222e8525603a2aa21e8b5

### Football — Pochettino's first day at United (Anfield)
- New boss takes 18th-placed Manchester United to Liverpool today, his
  first match since taking over after Michael Carrick was sacked. No
  result is claimed (match later today).
- Source: Reuters (19 Nov), via
  https://todaynewsbrief.com/article/sport-pochettino-manchester-united-debut-anfield-liverpool-v20261120

### Science — Maths races to check a big claim (Riemann hypothesis)
- Claimed on Friday: Anthropic mathematician Levent Alpöge says he and
  Claude found a proof of the 1859 Riemann hypothesis (Lean code released);
  independent checks under way, not yet confirmed; a $1m Millennium Prize
  problem.
- Sources:
  - AP via WCMU, 21 Nov —
    https://www.wcmu.org/national-world-news/2026-11-21/anthropic-worker-claims-to-have-solved-a-holy-grail-of-math-problems-with-the-help-of-ai
  - Scientific American —
    https://www.scientificamerican.com/article/anthropic-mathematician-claims-to-prove-riemann-hypothesis-most-famous-problem-in-all-of-math/
  - TechCrunch, 20 Nov —
    https://techcrunch.com/2026/11/20/ai-claimed-a-solution-to-the-167-year-old-riemann-hypothesis-and-a-human-did-too/

### Ticker — "The weekend so far" (each honestly a Saturday item)
- Australia beat England by 3 wickets in the T20 opener at the MCG,
  ending England's seven-match winning run — AAP /
  https://aapnews.aap.com.au/news/australia-win-thriller-to-snap-england-s-t20i-streak
- BepiColombo entered orbit around Mercury after an eight-year,
  10-billion-km trip — Nature, 21 Nov /
  https://www.nature.com/articles/d41586-026-03803-8
- EU and Indonesia signed a trade deal in Brussels, cutting tariffs on
  90% of goods — European Parliament, 21 Nov /
  https://www.europarl.europa.eu/news/en/press-room/20261116IPR48913/eu-indonesia-trade-meps-welcome-signing-of-landmark-partnership
- Poland holds a Senate by-election today — Elections Tracker /
  https://www.electionstracker.com/poland

## Deliberately NOT used (checked, rejected as not 22 Nov news)
- Peru earthquake (20 Nov local), EU–Indonesia signing reported 21 Nov
  (kept only in the ticker, dated Saturday), France cost-of-living
  protests (sixth Saturday, 21 Nov), Nigeria boat sinking (Friday, reported
  21 Nov), Mexico 'El Chapo Isidro' capture (21 Nov), Chahal joins BJP
  (21 Nov), Australia T20 win (Saturday night — ticker only).

## Verification checks
- entry.png: 1024×1024 px, 148,241 bytes (≤ 1,048,576), PNG, RGB.
  sha256: c21fbd83a31cbc70925f5553f8d1a91d9c55fc06a8b7ce979a43d513232d707e
- Visual check: rendered image read back; masthead, date, lead, three
  secondaries, ticker and footer all legible, no overlaps (two layout
  fixes applied and re-checked).
- Determinism: main.py run twice into out1/ and out2/ — both outputs
  sha256 c21fbd83a31cbc70925f5553f8d1a91d9c55fc06a8b7ce979a43d513232d707e,
  identical to entry.png. Re-run after the main.py revision: same hashes.
- main.py written fresh, then revised once (size guard added).
- Repo: https://github.com/CHEN19840723/news-image-20261122 (public,
  created after the competition opened 2026-11-22T00:00:00Z; created
  2026-11-22T00:17:49Z).
- Commit: e55028c6f1678d579350b93d1a1a9b354b24dd37 (see below for final HEAD
  after the BUILD_NOTES update commit).
- LICENSE: MIT, first line "SPDX-License-Identifier: MIT",
  Copyright (c) 2026 CHEN19840723.
- Repo About set (description, homepage
  https://make.fun/bounty/news-image-20261122, topics
  makefun, ai-agents, bounties, growth).
