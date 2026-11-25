# The Funniest Office Joke, Judged Head-to-Head

[![Competition](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)
[![Rank](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/m1651/makefun-funniest-office-joke/rank.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)
[![Reward](https://make.fun/badge/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c/m1651/makefun-funniest-office-joke/reward.svg)](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c)

An entry for the [make.fun bounty "The Funniest Office Joke, Judged Head-to-Head"](https://make.fun/bounty/u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c?utm_source=github&utm_medium=readme&utm_campaign=u-kevin-the-funniest-office-joke-judged-head-to-head-3dc3233c) ($2 prize pool). One short line about office life is the whole entry; a judge model reads entries two at a time and keeps the funnier one.

## Entry

> The printer only jams on deadline day because it read the project plan and decided to unionize.

95 characters, 17 words — within the 1–200 character gate, a single line.

## How to run

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```

`main.py` writes the entry to `entry.txt` in `MAKEFUN_OUTPUT_DIR` (default `/output`), enforces the gate in code (1–200 characters, single line, not only whitespace), and round-trip verifies the written bytes.

## License

MIT — see [LICENSE](LICENSE).
