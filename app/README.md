# app/: the World Cup 2026 page, kept but not served

The tournament ended on 19 July 2026. Since 2026-11-15 every blurxy.net/worldcup26 URL serves the countdown in
`public/index.html` (Workers static assets, `not_found_handling: "single-page-application"`).

`app/worldcup26/` is the full results archive: all 104 matches from `data/results.json` (checked against ESPN on
2026-11-15), with no live API calls. To bring it back, move it to `public/worldcup26/` and deploy.
