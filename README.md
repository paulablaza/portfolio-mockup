# Portfolio — mock-up

A single-file portfolio: `index.html`. No build tools, no install. Double-click it and it opens in your browser.

## What's inside

- **Hero** — monogram + name pill, big headline, one button.
- **Tools strip** — Figma, Framer, VS Code, GitHub, Notion, Obsidian.
- **Services** — UX & UI, Web & Mobile, Design & Creative, Development.
- **CTA** — email / WhatsApp buttons + footer.
- **Motion** — word-by-word headline reveal, fade-up on scroll, hover lifts, thin scroll-progress bar, smooth anchor scrolling. All of it switches off automatically if someone's device has "reduce motion" on.

## What to change (search for these in index.html)

| What | Where |
| --- | --- |
| Name in the name pill | `Paul Ablaza` |
| Monogram | `>PA<` (two places: hero avatar + CTA badge) |
| Email | `hello@paulablaza.com` (three places, plus `EMAIL` in the script) |
| Social links | `href="#"` in the nav, CTA and footer |
| WhatsApp | `https://wa.me/63` → `https://wa.me/639XXXXXXXXX` |
| Headline | `Building digital things, learning in public.` (also in the `aria-label`) |
| Subline | `Student based in the Philippines...` |
| Page title / description | `<title>` and `<meta name="description">` |

Everything is plain HTML + CSS + about 60 lines of vanilla JavaScript. You can edit it in Notepad, VS Code, or Obsidian.

## Put it online (pick one)

### 1. Netlify Drop — fastest, ~1 minute
1. Go to `app.netlify.com/drop`.
2. Drag the whole `Portfolio` folder onto the page.
3. You get a free link like `paul-ablaza.netlify.app`. **No account needed to deploy** — you can claim the site by signing up afterwards.
4. To update: drag the folder again. To use your own domain: Site settings → Domain management.

Free tier is plenty for a portfolio.

### 2. GitHub Pages — free, good if you want a GitHub link anyway
1. Create a repo, e.g. `portfolio`.
2. Upload `index.html` (GitHub's web uploader works; no Git needed).
3. Repo → **Settings → Pages** → Source: **Deploy from a branch** → branch `main`, folder `/ (root)` → **Save**.
4. Live in ~1 minute at `yourusername.github.io/portfolio`.

Name the repo `yourusername.github.io` instead and it becomes `yourusername.github.io` with no subfolder.

### 3. Vercel or Cloudflare Pages
Same idea: connect a GitHub repo or drag-and-drop the folder. Both free, both give HTTPS + a free subdomain.

*(Netlify Drop and the GitHub Pages branch settings were checked against the live docs in Nov 2026.)*

### Custom domain
Buy one (`paulablaza.com`) at Cloudflare, Namecheap or Porkbun — usually around $10/year. Then add it in the host's domain settings. HTTPS is automatic on all three hosts above.

## Notes

- The Inter font loads from Google Fonts. Offline it falls back to your system font — still looks fine.
- No analytics, no cookies, no tracking. If you want visit counts later, a lightweight option is GoatCounter or Plausible.
- Want to add work samples later? Duplicate the services card and turn it into a 2–3 project grid — same card, same spacing.
