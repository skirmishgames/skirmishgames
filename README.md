# skirmishgames

Index page for skirmishgames.app. A single static page, served by GitHub Pages.

## Files

- `index.html`: the whole site. No build step.
- `CNAME`: tells GitHub Pages to serve this repo at skirmishgames.app. Do not delete it.

## Apps

Each app lives in its own repo and its own subdomain.

| App | Repo | Address |
| --- | --- | --- |
| Rogue Warriors Quartermaster | Rogue-Warriors-Quartermaster | roguewarriors.skirmishgames.app |
| 7TV Casting Office | 7TV-Casting-Office | 7tv.skirmishgames.app |
| Pulp Alley | Pulp-Alley | pulpalley.skirmishgames.app |
| Breacher | breacher | breacher.skirmishgames.app |

## Adding an app

1. In the app repo, open Settings, then Pages, and set the custom domain to the new subdomain.
2. At the DNS provider, add a CNAME record for the subdomain pointing to `justadude-g.github.io`.
3. Add a card to `index.html`.
