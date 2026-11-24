# Real-Life Patch Notes: The Comedy Changelog

[![make.fun](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![Rank](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/jajanb923-netizen/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/rank.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)
[![Reward](https://make.fun/badge/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/jajanb923-netizen/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d/reward.svg)](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d)

Entry for the [make.fun bounty "Real-Life Patch Notes: The Comedy Changelog"](https://make.fun/bounty/u-0xb3e689-real-life-patch-notes-the-comedy-changelog-c5844c1d): write the funniest one-line patch note for a bug in real life or human biology, 160 characters max.

## The entry

`main.py` (Python 3.13, standard library only, deterministic, no network) writes
one line to `/output/entry.txt`:

> v4.2.0: fixed a bug where walking through a doorway deleted the reason you entered the room.

92 characters, one line, UTF-8. The program enforces the competition gate itself
(1–160 characters, not only whitespace, single line) before writing.

## Why this line

Twelve candidates were written and scored against the judge's five criteria
(see [CANDIDATES.md](CANDIDATES.md)). The doorway effect won on every one:
it is the most universal bug on the list, "deleted the reason you entered the
room" states it in dry engineering register, and not a word is wasted.

## Run locally

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
cat out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
