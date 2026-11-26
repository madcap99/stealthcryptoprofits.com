# Stealth Crypto Profits

Landing page for **Stealth Crypto Profits**, a private crypto trading community: live signals, market intelligence, a trading academy and a members-only community.

Static pages: `index.html` (home), `terms.html` (Terms of Service) and `privacy.html` (Privacy Policy) with no build step and no dependencies apart from Google Fonts (Space Grotesk, Inter, JetBrains Mono).

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, then select `main` and `/ (root)`.
4. The included `CNAME` file points the site at **stealthcryptoprofits.com**. At your domain registrar, add these DNS records:
   - `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` record for `www` → `<username>.github.io`
5. Back in **Settings → Pages**, tick **Enforce HTTPS** once the certificate is issued (can take up to an hour).

## Placeholders to replace before launch

Search `index.html` for `[` to find them all:

| Placeholder | Replace with |
|---|---|
| ~~`[YOUR_HANDLE]`~~ | Done: @MyStealthCrypto |
| ~~Members / rating~~ | Done: 600+ traders, 4.6+ rating |
| ~~Prices~~ | Done: $99 quarterly, $349 annual, $949 lifetime |
| ~~Checkout links~~ | Done: Quarterly, Annual and Lifetime Whop checkouts |

## Legal pages: fill in before launch

In `terms.html` and `privacy.html` (operator: Botanico Enterprises Inc., Delaware law). All placeholders are filled. Have a lawyer review both pages before launch.

## Colours

| Role | Hex |
|---|---|
| Background | `#FFFFFF` / `#F3F6FB` |
| Main text (dark blue) | `#0B2A5B` |
| Secondary text | `#3B5278` |
| Accent / buttons | `#1D4ED8` |

## Disclaimer

Content is for educational and informational purposes only and is not financial advice. Crypto assets are highly volatile. Past performance does not guarantee future results.
