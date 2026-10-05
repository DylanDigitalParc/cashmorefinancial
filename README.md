[README.md](https://github.com/user-attachments/files/33061529/README.md)
# Cashmore Financial Group: homepage concept v2

A static, no-build homepage concept for Randy Cashmore's redesign.

`index.html` is fully self-contained: the CSS and JavaScript are inside it. It works on its own, from GitHub Pages, or double-clicked from your desktop. Only the optional logo file and photos live outside it.

## Preview locally
Open `index.html` in a browser. No server needed.

## Publish a review link with GitHub Pages
1. Push this folder to a GitHub repo.
2. Repo **Settings > Pages**.
3. Source: **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After about a minute the site is live at `https://<user>.github.io/<repo>/`.

Tip: use a private repo plus a Pages link only if your plan supports private Pages. Otherwise keep the repo public and add `<meta name="robots" content="noindex">` to `index.html` so the concept does not get indexed.

## What's in the concept
- Full-width video banner (drop `assets/hero.mp4` in; a turf-and-goalpost scene shows until then), with a pause button
- A book teaser in the banner, then a full feature on *Financial Chalk Talk* with the interactive "play" diagram
- Three key services (annuities, life insurance, gold and silver) plus long-term care, Roth check and LegalShield
- About Randy, speaking and media, how it works, FAQ, LegalShield band, contact form (front end only)
- Football as texture: yard-line strip, mowing stripes, goalpost, chalk X's and O's, football-lace bullets, scoreboard card

## Copy
Full draft copy for every planned page, a voice guide, SEO titles and descriptions, and compliance guardrails live in `copy/site-copy.md`. Items tagged **[confirm]** need Randy or compliance before launch.

## Assets
See `assets/README.txt`. Every slot has a designed fallback and swaps to the real file when it exists.

## Replace before this goes anywhere near launch
| Placeholder | What's needed |
|---|---|
| `assets/logo.png` | The current logo file. Until it exists the page loads the logo from the live site, then falls back to text. |
| Portrait, softball, lager, sideline | Photos (dashed boxes). No ties. Randy's wife is a professional photographer. |
| Book cover | Real cover art. The CSS cover is a stand-in. |
| Risk check button | Link to Randy's preferred risk and Roth conversion tool (not Riskalyze). Name not yet confirmed. |
| YouTube and Rumble | Channel URLs and video embeds. |
| Blog links | Real post URLs. |
| LegalShield link | Randy's referral link, then build the full landing page. |
| Footer disclosure | Final language from Signal and the insurance carriers. |
| Contact form | Wire to Contact Form 7 / Flamingo on WordPress, or a form service. |

Every placeholder link carries a `data-todo` attribute that says what it needs. Search the project for `data-todo` to list them.

## Claims to confirm with Randy
- How Randy is paid (the FAQ says he may receive commissions from insurance companies and will explain before you decide).
- Sample speaking topics, which are drawn from the book's chapters.
- The metals "sell" line, which depends on his local vendor arrangement.
- "Within sight of 300 career wins" (he said he is six wins short).
- The silver quarter story. Randy quoted a dollar value on the call. It is left out on purpose until he confirms it.
- Insurance advertising rules still apply after the securities license is dropped. Check with Signal and the carriers.

## Design tokens
Colors, fonts and spacing live at the top of the `<style>` block in `index.html`, under `:root`.
Fonts (Zilla Slab, Figtree, Caveat) load from Google Fonts.
