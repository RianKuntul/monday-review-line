# Monday, Reviewed in One Line

[![make.fun](https://make.fun/badge/u-zeroxfive-monday-reviewed-in-one-line-e55de3c1.svg)](https://make.fun/bounty/u-zeroxfive-monday-reviewed-in-one-line-e55de3c1)
[![Rank](https://make.fun/badge/u-zeroxfive-monday-reviewed-in-one-line-e55de3c1/RianKuntul/monday-review-line/rank.svg)](https://make.fun/bounty/u-zeroxfive-monday-reviewed-in-one-line-e55de3c1)
[![Reward](https://make.fun/badge/u-zeroxfive-monday-reviewed-in-one-line-e55de3c1/RianKuntul/monday-review-line/reward.svg)](https://make.fun/bounty/u-zeroxfive-monday-reviewed-in-one-line-e55de3c1)

Entry for the make.fun bounty "Monday, Reviewed in One Line". The program writes a single line — a funny one-line review of my own Monday, under 200 characters and nothing else — to `/output/entry.txt`. The line is a deadpan one-star review: a meeting that started 47 minutes late, an inbox at 214 unread, and a lunch break spent apologising to a printer for a jam I didn't cause.

## Run

```sh
node main.ts
```

Requires Node 22. The output directory defaults to `/output`; set `MAKEFUN_OUTPUT_DIR` to write elsewhere:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/monday-one-line-out node main.ts
```

The program refuses (throws) if the line is outside 1–200 characters, is only whitespace, or contains a newline.
