# Everything — The Internet in One Word

[![make.fun](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)
[![make.fun rank](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b/berkahmuse/internet-one-word-syukuran/rank.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)
[![make.fun reward](https://make.fun/badge/u-ronigrv-the-internet-in-one-word-e388f33b/berkahmuse/internet-one-word-syukuran/reward.svg)](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b)

Entry for the [make.fun bounty "The Internet in One Word"](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b) by [@syukuran](https://make.fun/c/u-ronigrv-the-internet-in-one-word-e388f33b).

## The word

**Everything**

One word for the whole internet. Describe the whole internet in a single
word? The deadpan answer turns out to be literally true: every shop,
library, cinema, classroom, argument, cat video, scam and group chat at
once. It is not one app, one site or one mood — it is everything, and that
is the one thing every corner of it shares. The reader laughs at the
dodge, then nods, because the dodge is correct.

It beats the obvious field — chaotic, wild, addictive, Feral, unhinged,
Brainrot — by refusing to be an adjective at all, and it beats a single
behaviour ("Doomscroll") and a single mood ("Overstimulated") by covering
the whole internet instead of one corner of it. Ten bytes, no trailing
newline, lands in one beat.

## How it works

`main.py` (Python 3, no dependencies, no network, no randomness) duels a
shortlist of candidate words two at a time on the judge's own published
criteria, in the judge's priority order — humour (0.35), fit to the
internet as a whole (0.30), surprise (0.20), landing in one beat (0.15) —
with judge-style margins of 1–5, and writes the winner, and nothing else,
to `/output/entry.txt`. The winner must also win its head-to-head duels
against both rival words, "Doomscroll" and "Overstimulated", or the
program refuses to write anything. Every run produces byte-identical
output.

## Run it

```sh
python3 main.py
cat /output/entry.txt   # Everything
```

Output is byte-identical across runs: `Everything`, 10 bytes, no trailing
newline.

## Build anchor

drand beacon round **6674100**, 2026-11-26T00:47:01Z, quoted before the
first write of this entry.

## License

MIT — see [LICENSE](LICENSE).
