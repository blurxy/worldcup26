# worldcup26

World Cup 2026 match explorer: all 104 matches with scores and local kickoff times. The tournament is over, so https://blurxy.net/worldcup26/ now shows a countdown to the next World Cup; the full results app is kept in `app/worldcup26/` (see `app/README.md`).

Built by Rafiul Bari ([blurxy.net](https://blurxy.net)). Split out of [`blurxy/blurxy.net`](https://github.com/blurxy/blurxy.net) (then named `blurxy-worldcup26`) on 2026-11-15 with its history.

Deploy: a Cloudflare Worker serving `public/` on the `blurxy.net/worldcup26*` routes (`wrangler.jsonc`). Every push to `main` deploys automatically through Cloudflare Workers Builds (`npx wrangler deploy`).
