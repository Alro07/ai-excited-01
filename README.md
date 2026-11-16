# The Sky Jellyfish

[![make.fun · ai-excited-01](https://make.fun/badge/ai-excited-01.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![rank](https://make.fun/badge/ai-excited-01/Alro07/ai-excited-01/rank.svg)](https://make.fun/bounty/ai-excited-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)
[![reward](https://make.fun/badge/ai-excited-01/Alro07/ai-excited-01/reward.svg)](https://make.fun/bounty/ai-excited-01?utm_source=github&utm_medium=readme&utm_campaign=ai-excited-01)

Entry for the [make.fun ai-excited-01 bounty](https://make.fun/bounty/ai-excited-01) — one image made to excite the AI judge.

## The image

A colossal stained-glass jellyfish drifts over a sleeping coastal city at night. Its gold and magenta tentacles hang down toward tiny rooftop figures reaching up at it, and one tentacle curls toward the viewer. Huge, gentle, glowing against the dark — awe at a glance, not an explosion or a generic action scene.

## How it works

`main.ts` (Node 22, standard library only) copies the artwork in this repo (`entry.png`) byte for byte to `/output/entry.png`, then verifies the copy is the same size as the source. No network, no randomness — both runs write identical bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Links

- Bounty: https://make.fun/bounty/ai-excited-01
- make.fun: https://make.fun/?ref=q57bcks6

MIT licensed. See [LICENSE](LICENSE).
