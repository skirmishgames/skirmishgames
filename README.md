# skirmishgames

Index page for skirmishgames.app. A single static page, served by GitHub Pages.

## Files

- `index.html`: the whole site. No build step.
- `CNAME`: tells GitHub Pages to serve this repo at skirmishgames.app. Do not delete it.

## Apps

Each app lives in its own repo and its own subdomain.

| App | Repo | Address |
| --- | --- | --- |
| 7TV Casting Office | 7TV-Casting-Office | 7tv.skirmishgames.app |
| Achtung Panzer! | Achtung-Panzer | achtungpanzer.skirmishgames.app |
| Black Powder Red Earth | bpre-force-builder | bpre.skirmishgames.app |
| Heroes System Tactical Scale | HSTS | hsts.skirmishgames.app |
| Pulp Alley | Pulp-Alley | pulpalley.skirmishgames.app |
| Rogue Warriors | Rogue-Warriors | roguewarriors.skirmishgames.app |

Keep the cards in alphabetical order. The "Tools made by other people" section at the bottom of `index.html` links to tools hosted elsewhere (Arsenal, Star Wars Imperial Assault, Star Wars Legion).

## Adding an app

1. In the app repo, open Settings, then Pages, and set the custom domain to the new subdomain.
2. At the DNS provider, add a CNAME record for the subdomain pointing to `skirmishgames.github.io`.
3. Add a card to `index.html`.
