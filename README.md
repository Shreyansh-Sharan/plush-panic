# PLUSH PANIC · Party Brawler

Squishy plush toys meet in a cosy attic, then play a Show of short, chaotic rounds where the field shrinks until one toy wears the crown. Trace a biscuit without cracking it, freeze when the music box stops, and knock rivals off a shrinking stool, all while flicking crumbs at your friends.

Built with Three.js · Rapier physics · Custom rigged plush toys. Part of [Shreyansh Sharan's portfolio](https://shreyansh-sharan.github.io/shreyanshsharan-portfolio/), split into its own site.

```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
npm run lint     # oxlint
```

The site is a single page: `#/` is the game's menu, and the same query parameters the portfolio used still work
(for example `#/?auto=...` to skip the menu, `#/?join=CODE` for an invite link).

## Controls

- `W` `A` `S` `D` move · mouse to look (click to lock)
- `Space` jump · `Shift` dive · `E` grab (hold) · `LMB`/`F` shove
- `1`–`7` tricks · `Tab` pick a rival · `R` level action

## Ads and gear

Optional AdSense and Amazon affiliate IDs come from environment variables (see `.env.example`). Leave them empty and
no ad or shop code loads.

## More

- [docs/ENGINE.md](docs/ENGINE.md)
