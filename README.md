# routeback.xyz

The Routeback landing page: one self-contained `index.html` (no build step), hosted on GitHub Pages
from this repo's `main` branch, with the custom domain in `CNAME`.

## Edit
- **In the browser:** open `index.html` on github.com → pencil icon → edit → "Commit changes".
  The live site updates in about a minute.
- **Locally:** edit `index.html`, open it in a browser to check, then `git commit -am "…" && git push`.

Inside `index.html`:
- the contact links are marked `<!-- CONTACT -->` (mailto:hello@routeback.xyz today);
- colours are in the `:root` block at the top of the `<style>`;
- every section is marked `<!-- SECTION: … -->`.

## Domain (one-time, at the registrar of routeback.xyz)
| Type | Name | Value |
|---|---|---|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | luishsr.github.io |

Then, once GitHub shows the certificate as issued (Settings → Pages), tick "Enforce HTTPS".
