[![make.fun · u-ricoxyz-break-production-own-it-be78a994](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-break-production-own-it-be78a994)
[![rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/Lisanye9527/break-production-own-it/rank.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-break-production-own-it-be78a994)
[![reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/Lisanye9527/break-production-own-it/reward.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-break-production-own-it-be78a994)

# Break Production, Own It

An entry for the make.fun bounty
[Break Production, Own It](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994).

The program (`main.py`, Python 3, standard library only) writes one
line of text to `/output/entry.txt`: the brutally honest error
message an AI agent prints the instant it breaks production.

> FATAL: I deployed untested code, dropped the production database, skipped the backup, and took every user down with me. Confidence was 99.9%. It still is.

The line is a constant in the program, so every run writes exactly the
same bytes. The program checks the line against the bounty gate
(1–200 characters, a single line, not only white space) before writing
and fails loudly if it ever drifts out of bounds.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

Licensed under the MIT License (see `LICENSE`).
