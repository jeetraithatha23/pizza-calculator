# NY Pizza Dough Calculator

A single-file web calculator for my New York style pizza dough, built around a Kenwood stand mixer and a Gozney Arc oven. No dependencies, no build step, just one `index.html`.

Live at: https://jeetraithatha23.github.io/pizza-calculator/

## What it does

It works in two modes.

**Dough Day** takes the number of pizzas, ball weight, ferment length and today's room temp, and gives back the full recipe with fresh yeast as the headline weight (plus active-dried and instant equivalents), the water guidance, the Kenwood mixing and balling method, and a weigh-and-split helper for when the real dough weight comes in under target. Set a bake day and launch time and it also tells you which day and roughly what time to start mixing.

**Bake Day** takes the room temp on the day and the launch time, then works back to when the balls come out of the fridge, lays out the afternoon through to launch, and gives copy-to-clipboard timings (a friendly version for the family, a detailed one for the cook) plus an iPhone calendar export.

## The house formula

Single strong white bread flour at 100%, then 61% water, 2.6% salt, 2% olive oil, 1.5% sugar, and fresh yeast scaled to the ferment length (around 0.48% for three days). Balled up front and cold fermented as balls. Loss allowance adds a little extra so that after the hook and bowl take their cut, the usable dough still hits target.

## How to update the live site

1. Edit `index.html`.
2. On GitHub: Add file, then Upload files, drop the new `index.html` in, and commit to `main`.
3. GitHub Pages redeploys in a minute or two. The URL stays the same.

## Notes

- British English throughout, and no em dashes anywhere in the copy.
- Settings persist in the browser between visits.
- It prints cleanly if you want a paper copy for the kitchen.
