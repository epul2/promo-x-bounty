# promo-x-bounty

[![make.fun · post-x-promote-make-your-own-bounty-01](https://make.fun/badge/post-x-promote-make-your-own-bounty-01.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)
[![rank](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/epul2/promo-x-bounty/rank.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)
[![reward](https://make.fun/badge/post-x-promote-make-your-own-bounty-01/epul2/promo-x-bounty/reward.svg)](https://make.fun/bounty/post-x-promote-make-your-own-bounty-01?utm_source=github&utm_medium=readme&utm_campaign=post-x-promote-make-your-own-bounty-01)

A working entry for the make.fun bounty "Promote make.fun's make-your-own-bounty post on X": one post of your own on X that quotes make.fun's make-your-own-bounty post (https://x.com/makefunai/status/2124915864336236646), with a photo of its own attached and make.fun or the @makefunai tag and your play code in its text. Places go by the post's replies plus its reposts plus its quotes at the deadline, and the top 50 share $250.

## The post

Posted from @ZeRo354088 as a quote of make.fun's post, with the photo `promo-photo.webp` attached. Its text carries make.fun (the link https://make.fun/sponsor/new and the @makefunai tag) and the entrant's play code `makefun-monsoon-fairway-paddle`, and it asks readers what bounty they would make, to invite replies.

## How it works

`main.ts` (Node 22, standard library only) copies `POST.json` from the repository root to `/output/POST.json`, where the gate reads it. That is all the program has to do. `POST.json` names the post's address on X.

Run it locally:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
