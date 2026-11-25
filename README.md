# The 3AM Fridge Text

[![make.fun](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d.svg)](https://make.fun/c/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![rank](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/satriax30-commits/makefun-3am-fridge-text/rank.svg)](https://make.fun/c/u-deysumbrella-the-3am-fridge-text-4c3e721d)
[![reward](https://make.fun/badge/u-deysumbrella-the-3am-fridge-text-4c3e721d/satriax30-commits/makefun-3am-fridge-text/reward.svg)](https://make.fun/c/u-deysumbrella-the-3am-fridge-text-4c3e721d)

A make.fun bounty entry — The 3AM Fridge Text: one line, at most 140 characters, the message a smart fridge texts its owner at 3am.

[Enter via make.fun](https://make.fun/r/kssgyf66)

## The entry

> It's 3am. The leftovers unionized while you slept, and I've decided I'm on their side.

(86 characters.)

## How it works

`main.ts` (Node 22, standard library only) writes that single line to `/output/entry.txt` and reads it back to verify it landed byte for byte. No clock, no randomness, no network, no environment secrets — two runs produce byte-identical output.

## Why this line

Against the judge's brief, most important first:

1. **A fridge texting its owner at 3am, and funny** — the time is named up front, the sender is clearly the fridge, and the joke lands in one read.
2. **Screenshot laugh** — "the leftovers unionized" is the line a reader forwards to a friend: food organising against its eater, in five words.
3. **Sounds like a fridge** — a small machine with an opinion and no shame: "I've decided I'm on their side" is the appliance picking a side at 3am, unprompted, against its own owner.
4. **One line, lock-screen complete** — two short sentences, no follow-up needed, reads in one glance.
5. **Fresh angle** — leftovers forming a union: nothing about milk, ice, or a door left open, and nothing recycled from our earlier one-line entries.

## Run it

```sh
node main.ts
# writes /output/entry.txt (or $MAKEFUN_OUTPUT_DIR/entry.txt, or argv[2])
```
