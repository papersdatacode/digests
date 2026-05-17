🇬🇧 English | [🇷🇺 Русский](README.ru.md)

# Papers.Data.Code

Daily signal from the ML noise.

We automatically track, score, and publish the best papers, repositories, and datasets from the ML world — every day.

Selected, not collected.

## What we do

Our pipeline scans arXiv, GitHub, Hugging Face, and Kaggle daily, 
scores each item, and publishes the top picks. No hype, no noise. 
Just signal.

## What we cover

| Type     | Sources                  |
|----------|--------------------------|
| Papers   | arXiv                    |
| Repos    | GitHub                   |
| Datasets | Hugging Face, Kaggle     |

## Where to follow

- 📄 Daily feed: [@papersdatacode](https://t.me/papersdatacode)
- 📈 Digests: [@papersdatacode_digests](https://t.me/papersdatacode_digests)
- 🐦 Twitter: [@papersdatacode](https://twitter.com/papersdatacode)
- 🌐 Russian: [@papersdatacode_ru](https://t.me/papersdatacode_ru) · [@papersdatacode_digests_ru](https://t.me/papersdatacode_digests_ru)

## Why it's different

PDC combines automated scoring with quality filters and ranks each 
work across weekly, monthly, quarterly, and yearly horizons — so 
you see what actually holds momentum, not just what's new.

## How rankings work

Each work is ranked by an internal score across multiple horizons.
Top picks at one level pull into the next: weekly winners pool 
into monthly, monthly into quarterly, quarterly into yearly.

## Structure of this repo

- `digests/[year]/weekly/` — weekly Top 3 (papers, repos, datasets) and recap with TL;DR and Trends
- `digests/[year]/monthly/` — monthly rankings, recap, and tracking metrics for top picks
- `digests/[year]/quarterly/` — quarterly rankings and recap
- `digests/[year]/yearly/` — year-end rankings and recap
- `digests/ru/[year]/...` — Russian digests in the same structure

Each period has paired files: main digest with top 3 by category 
and a recap with TL;DR and Trends.

File naming: date-first for chronological sorting (e.g. `2026-05-10-W19.md`).

## License

MIT for metadata. Original papers and code retain their respective licenses.

## Contact

📧 papers.data.code@gmail.com