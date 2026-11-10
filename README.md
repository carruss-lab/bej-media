# BEJ media

Public video files for The Black Executive Journal social posts.

- `videos/2026-11-reboucas/` — André Rebouças lead-in (Yesterday's Architects). Full article: https://www.blackexecutivebrief.com/andre-reboucas-the-engineer-who-wrote-the-concession-law-then-built-a-port-company-under-it/
- `videos/2026-11-mason/` — Biddy Mason: From Enslaved Midwife to Los Angeles Landowner (Yesterday's Architects). Full article: https://www.blackexecutivebrief.com/biddy-mason-from-1700-mile-trek-in/
- `videos/2026-11-mcworter/` — Frank McWorter: He Bought His Wife First, Then Platted a Town (Yesterday's Architects). Full article: https://www.blackexecutivebrief.com/frank-mcworter-the-developer-who-bought-his-wife-first-and-platted-a-town-to-pay-for-the-rest/

## Yesterday's Architects on the BEJ Global 24/7 live stream

Every `videos/YYYY-MM-<slug>/` folder with a `<name>-16x9.mp4` airs on the live stream, rotating through the blocks
(bej-top-of-the-hour, `architectsEpisode`). **When you publish a new episode, add `meta.json` to its folder** so the
stream's YouTube title and description name it properly:

```json
{
  "title": "Frank McWorter: He Bought His Wife First, Then Platted a Town | Yesterday's Architects",
  "lede": "One or two sentences, the same as the YouTube description's opening.",
  "url": "https://www.blackexecutivebrief.com/<article-slug>/",
  "series": "Yesterday's Architects",
  "hashtags": ["#YesterdaysArchitects", "#BlackBusinessHistory"],
  "posted": true
}
```

If `meta.json` is missing, the stream falls back to this README's line for the folder (`` `videos/<folder>/` — <title> (Yesterday's Architects). Full article: <url> ``), so add that line too.
