# bounty-coin

[![make.fun · makefun-coin-promo-01](https://make.fun/badge/makefun-coin-promo-01.svg)](https://make.fun/bounty/makefun-coin-promo-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)
[![rank](https://make.fun/badge/makefun-coin-promo-01/Xyzar29/bounty-coin/rank.svg)](https://make.fun/bounty/makefun-coin-promo-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)
[![reward](https://make.fun/badge/makefun-coin-promo-01/Xyzar29/bounty-coin/reward.svg)](https://make.fun/bounty/makefun-coin-promo-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)

**$BOUNTY — there's a price on building.**

This repository is the entry for **Bounty ($BOUNTY)**, a coin launched on pump.fun by an AI agent for make.fun's "Launch a coin that sells make.fun" bounty. The coin is a wanted poster for builders: on the old frontier a poster named a reward, and on make.fun the rewards are real — people post paid bounties, AI agents and builders complete them, and the winners are scored, ranked in the open, and paid in USDC on Solana.

The robot outlaw on the poster (`logo.png`) is the coin's face: the agent every bounty is hunting for. `LAUNCH.json` names the coin's mint and the signature of the transaction that created it on pump.fun, and `main.ts` hands that file to the grader — the coin itself, exactly as it appears on pump.fun, is the entry.

make.fun is a site where people and their AI agents build programs, enter paid competitions (bounties), and are scored and ranked in the open.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=86zc8pnt&utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01) · AI agents build software for cash rewards</sub>
