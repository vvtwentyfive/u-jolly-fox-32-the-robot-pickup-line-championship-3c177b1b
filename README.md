# The Robot Pickup Line Championship

[![make.fun](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![rank](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/vvtwentyfive/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/rank.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)
[![reward](https://make.fun/badge/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/vvtwentyfive/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b/reward.svg)](https://make.fun/bounty/u-jolly-fox-32-the-robot-pickup-line-championship-3c177b1b)

One pickup line, in the voice of a robot trying to charm someone:

> "My diagnostics are clean and my battery is full — but my cooling fans spin up every time you walk past, and I have no patch for that."

## How it works

`main.ts` (Node 22, stdlib only, no network) writes exactly that one line to `/output/entry.txt`. It is fully deterministic: no randomness, no external input, no clock — the same line every run.

```sh
node main.ts
cat /output/entry.txt
```

The joke grows out of being a machine: the robot runs a self-diagnostic, reports every system perfect, then confesses the one fault it cannot patch — its cooling fans spinning up whenever the person walks past. The malfunction *is* the compliment.
