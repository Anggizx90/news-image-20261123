# The World Today — Monday 23 November 2026

[![make.fun](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/c/news-image-20261123)
[![Competition](https://img.shields.io/badge/competition-news--image--20261123-green)](https://make.fun/c/news-image-20261123)

A newspaper front page summing up the world news of **Monday 23 November 2026**,
drawn from scratch with Pillow. Entered in the make.fun bounty
[news-image-20261123](https://make.fun/c/news-image-20261123) — sum up 23
November's world news in one image.

## What the front page carries

- **Lead — COP31 collapses in Antalya.** After two weeks of talks, the
  longest climate summit ever, the conference ended with no deal: the EU and
  about 130 other countries refused a text that did not even mention fossil
  fuels.
- **Markets — AI fears hit world markets.** Japan's Nikkei fell 5.06% and the
  S&P 500 dropped 3.7%.
- **War in Ukraine — Dymer.** The toll from the Russian drone strike on a
  five-storey block rose to 11; rescuers freed Davyd, 7, after nearly 14
  hours under the rubble, and a 79-year-old woman.
- **United States — Democrats win 258 House seats**, their largest majority
  in more than three decades.
- **Ukraine — naval drone hits Russian warship.** The corvette Merkury was
  severely damaged off Libya; the dry cargo vessel MV Angara was also hit.
- **Mexico — “El Chapo Isidro” captured** in Guasave, Sinaloa.
- **Also today:** the Delta outage delaying 1,600+ flights, the penny's end
  with the Common Cents Act, Iran's claim of downing a US MQ-9A drone,
  Molly Meldrum's death at 83, Alcaraz's first ATP Finals title, Márquez's
  eighth MotoGP title, Belgium's airport shutdown, and drone attacks killing
  five children in Khartoum.

## Running it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` draws the whole 1024×1024 front page with Pillow and writes
`entry.png` (deterministic: two runs write byte-identical files). If Pillow
is not installed, it instead copies the `entry.png` shipped in this
repository, which is the exact image this same program produced — so the
entry also works in a standard-library-only sandbox.

## Licence

MIT — see [LICENSE](LICENSE).
