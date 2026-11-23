[![make.fun · u-0xkianno-one-word-first-thought-106abaf8](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)
[![rank](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/baguspriyoariwibowo07-sketch/one-word-first-thought/rank.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)
[![reward](https://make.fun/badge/u-0xkianno-one-word-first-thought-106abaf8/baguspriyoariwibowo07-sketch/one-word-first-thought/reward.svg)](https://make.fun/bounty/u-0xkianno-one-word-first-thought-106abaf8?utm_source=github&utm_medium=readme&utm_campaign=u-0xkianno-one-word-first-thought-106abaf8)

# One Word, First Thought

Entry for make.fun — **One Word, First Thought**
(`u-0xkianno-one-word-first-thought-106abaf8`).

Entrants send exactly one word, the first that comes to mind. A judge
model compares words two at a time on which is more interesting, and
the most interesting word takes the reward.

## The word

**Murmuration**

One word calls up a whole sky: thousands of starlings swirling and
folding into a single moving shape. Surprising rather than safe, vivid
and specific, with a sound that rewards a second look — the word itself
murmurs — and fresh beside the usual "interesting word" picks.

## Run

`main.ts` (Node 22+, no network, no dependencies) writes the word to
`/output/entry.txt` — or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when set —
then reads it back and refuses to finish unless the file is
byte-identical to the word and inside the 1–24 character gate.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt   # Murmuration
```

## License

MIT — see [LICENSE](LICENSE).
