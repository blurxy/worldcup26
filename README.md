# worldcup26

The [2026 World Cup results archive](https://blurxy.net/worldcup26/) lists all 104 final scores and venue-local match dates in static HTML. The original match explorer is kept in `app/worldcup26/` (see `app/README.md`).

Built by Rafiul Bari ([blurxy.net](https://blurxy.net)). Split out of [`blurxy/blurxy.net`](https://github.com/blurxy/blurxy.net) (then named `blurxy-worldcup26`) on 2026-11-15 with its history.

Deploy: a Cloudflare Worker serving `public/` on the `blurxy.net/worldcup26*` routes (`wrangler.jsonc`). Every push to `main` deploys automatically through Cloudflare Workers Builds (`npx wrangler deploy`).
