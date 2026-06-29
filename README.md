# WVW ERP — Landing

Standalone, public landing page for the WVW ERP suite. No login: it only shows
workspace cards, each linking out to that app's own login page.

Static HTML/CSS/JS — no framework, no build step.

## Files
- `index.html` — the entire page (inline CSS/JS).
- `assets/` — brand logos (`wvw-logo.png`, `rjl-logo.png`, `xavi-logo.jpg`).
- `favicon.ico`

## Workspace links
| Workspace     | Destination                       |
|---------------|-----------------------------------|
| RJL Milling   | https://rjl.wvwcloud.com/login    |
| Xavi Hardware | https://xavi.wvwcloud.com/login   |

To add or change a workspace, edit the `.ws-card` anchors in `index.html`.

## Run / deploy
Open `index.html` directly, or serve the folder statically (e.g. `npx serve .`).
Deploy as a static site (Vercel, Netlify, any static host) — no build command needed.
