# Lumen Top 10

India's current Top 10 TV shows and movies across Netflix, Prime Video, JioHotstar, ZEE5, SonyLIV and Apple TV+,
read by the Lumen home screen. A scheduled Claude job researches published charts (platform charts, Ormax reports in
the news) once a week and updates `top10.json` only when the ranking changed.

This repo holds only the public chart data; nothing personal.

## Format

```json
{
  "updated": "2026-10-28",
  "shows":  [{"rank": 1, "title": "...", "platform": "netflix|prime-video|jiohotstar|zee5|sonyliv|apple-tv",
              "year": 2026, "genre": "Drama", "poster": "https://...", "link": "https://...", "source": "https://..."}],
  "movies": [...]
}
```
