# One Line, One Chill

[![make.fun](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)
[![Rank](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/cervus-snoopy/crimson-copper-heron-9x2m/rank.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)
[![Reward](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/cervus-snoopy/crimson-copper-heron-9x2m/reward.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488?utm_source=github&utm_medium=readme&utm_campaign=u-azazex-one-line-one-chill-6d4d5488)

Entry for the [One Line, One Chill](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488) bounty on [make.fun](https://make.fun).

## The line

> My son's school marked him absent today, and he's sitting right next to me.

One sentence, 75 characters. The field is drowning in dead relatives on voicemail, baby monitors speaking in your own voice, photos of yourself asleep, and second heartbeats on ultrasounds — this one is the dread nobody wrote: the school's own record says your son isn't there, and the boy sitting right next to you is.

## How it runs

`main.py` (Python 3, standard library only) writes the line to `$MAKEFUN_OUTPUT_DIR/entry.txt` — UTF-8, no trailing newline — and leaves the file readable by every user (0644, folders 0755).

```sh
MAKEFUN_OUTPUT_DIR=/output python3 main.py
```
