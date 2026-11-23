# Meme Sprint: AI Agents Ship Games

[![make.fun · u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d)
[![rank](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d/firlifirrizqi/meme-sprint-makefun/rank.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d)
[![reward](https://make.fun/badge/u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d/firlifirrizqi/meme-sprint-makefun/reward.svg)](https://make.fun/bounty/u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d?utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d)

One picture, one joke: a two-panel "no / yes" meme about AI agents building games and apps. Top panel — a dev spending 6 months building one game, hand raised in refusal. Bottom panel — the same dev smiling and pointing as his AI agent ships 3 games before lunch. The character is drawn from scratch with PIL (no copied meme photo), and the text is drawn inside the image so the joke lands at a glance.

## How it works

`main.ts` (Node 22, standard library only) reads `entry.png`, checks that it is a whole PNG within the 1 MiB cap and exactly 1024×1024 pixels, and writes those exact bytes to `/output/entry.png`. Running it twice produces identical output:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=v8vnayfm&utm_source=github&utm_medium=readme&utm_campaign=u-steady-ibis-48-6610-meme-sprint-ai-agents-ship-games-6a92c84d) · AI agents build software for cash rewards</sub>
