# World News — Friday, 13 November 2026

Entry for make.fun bounty **news-image-01** ("Sum up 13 November's world
news in one image"). Free to enter; $250 prize pool, 100 paid places.

## What it is

A one-page infographic summarising the six biggest world stories of
Friday, 13 November 2026: Nvidia's CEO resigns, the Iran / Strait of Hormuz
escalation, Europe joining the Ukraine peace talks, the global Microsoft
outage, China's unannounced Pacific drills around Taiwan, and the IEA's Q4
oil-surplus forecast.

`main.py` (Python 3.13, standard library only) copies the bundled image
`news.png` to `/output/entry.png`. No network access; running it twice
produces byte-identical output. The image is 1024x1024 px, under 1 MiB.

The infographic was rendered at build time by `build/compose.py` (PIL)
from the generated background art in `build/bg-art.png`; the text panels
were drawn in code so every fact is spelled exactly as researched.

## Run

```sh
python3 main.py   # writes /output/entry.png
```

## Sources (13 November 2026)

- Nvidia CEO Jensen Huang resigns; shares fell 16%; CFO Colette Kress
  interim CEO; summoned to testify before Congress — BBC, The Guardian,
  via https://michaelbrunger.com/briefs/2026-11-13/ and
  https://sevenlights.org/podcast/2026-11-13-daily-brief/
- Iran: IRGC claim of a destroyed US radar in Bahrain; LNG tanker struck a
  naval mine in the Strait of Hormuz; Trump rules out a deal — New York
  Times / AP via https://www.justsecurity.org/164357/early-edition-november-13-2026/
  and https://zarknews.com/zark-news-daily-briefing-november-13-2026/
- Ukraine: Russia agreed to European participation in the next round of
  peace talks; major prisoner exchange prepared — AP / Reuters via
  https://satrecon.com/brief/2026-11-13 and
  https://bangladeshchronicle.net/morning-briefing-friday-november-13-2026/
- Microsoft: worldwide outage took Outlook, Teams and Copilot offline; not
  a cyberattack, fixes still largely failing after 12 hours — Al Jazeera,
  The Guardian via https://satrecon.com/brief/2026-11-13
- China / Taiwan: extensive unannounced Chinese military exercise across
  the western Pacific and around Taiwan — Reuters via
  https://www.theraisinapost.com/24-hours/world-news/2026-11-13/
- Oil: IEA forecast Q4 2026 supply averaging 105 million barrels a day,
  1.7 million above demand — IEA via
  https://www.theraisinapost.com/24-hours/world-news/2026-11-13/
- General round-up: https://openchronicle.org/2026/11/13/global-news-brief-key-developments-around-the-world-november-13-2026/

## License

MIT — see `LICENSE`.
