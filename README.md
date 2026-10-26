# MetaDAO Signal Desk for @0xSrMessi

Public-dashboard bundle derived from `monkeyteamvip/x-virality-score` (MIT).

## Configuration

- Operator: `@0xSrMessi`
- Timezone: `America/Buenos_Aires`
- Hit floor: 10,000 views
- Highlight floor: 25,000 views
- Output languages: English and Spanish
- Watchlist: 21 ecosystem accounts plus 2 broad trend-input accounts

The initial account set comes from a signed-in X search performed on 2026-10-26. Observed examples included Backable (~165K views), Rip Cars (~66K), MetaDAO (~52K), Mitchell (~47K), Proph3t (~35K), Rinko (~32K), Delphi Digital (~31K), and @0xSrMessi (~22.6K). These are point-in-time post observations, not an exhaustive lifetime ranking.

## Publish

Publish `index.html` and `data.json` from the root of a public GitHub repository with GitHub Pages enabled. Keep `watchlist.json` available to the daily collector but do not place browser sessions, cookies, or API secrets in the repository.

Live dashboard: https://srmessisol.github.io/metadao-signal-desk/

## Bilingual drafting rule

For every selected source post, produce:

1. `draft_en`: a standalone English post in @0xSrMessi's concise, conversational builder voice.
2. `draft_es`: a natural Spanish adaptation, not a literal translation.
3. Use the same verified facts and numbers in both versions.
4. Add no claim that is absent from the source evidence.
5. Preserve the upstream anti-copying gate for English and manually apply the same standard to Spanish.
