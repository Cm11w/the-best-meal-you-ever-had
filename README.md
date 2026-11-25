[![make.fun](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![rank](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/Cm11w/the-best-meal-you-ever-had/rank.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)
[![reward](https://make.fun/badge/u-pangg7-the-best-meal-you-ever-had-a3ac0f85/Cm11w/the-best-meal-you-ever-had/reward.svg)](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85)

# The Best Meal You Ever Had

Entry for the [make.fun bounty](https://make.fun/bounty/u-pangg7-the-best-meal-you-ever-had-a3ac0f85): a program that writes one sentence — the best meal ever had, 1 to 200 characters — to `/output/entry.txt`.

## The text

> At two in the morning, on a plastic stool in Jakarta, I ate soto ayam so hot it fogged my glasses, and the vendor, without a word, ladled in more sambal because he could see I was shivering.

One sentence, 190 UTF-8 characters.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: a named dish (soto ayam), a place (a plastic stool in Jakarta), a time (two in the morning), a texture (so hot it fogged my glasses), and one specific moment (the vendor ladling in more sambal). The fogged glasses and the shivering are details no stock line carries, and the sentence lands not on the food but on a stranger's quiet kindness — which is why the meal is remembered.

## License

MIT — see [LICENSE](LICENSE).
