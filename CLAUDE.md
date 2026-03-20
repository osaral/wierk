# wierk.com - Dictionary Landing Page

A single-page static site serving wierk.com - a Luxembourgish word definition page. Deployed on Firebase Hosting.

## What is this

wierk.com previously hosted Wierk SRL, a digital strategy consultancy now operating as **Altnota** at [altnota.com](https://altnota.com). This page now serves as a dictionary-style definition of the word "wierk" with a redirect notice to altnota.com.

## Stack

- Single `index.html` with inline CSS
- Firebase Hosting (project: `wierk-site`)
- Domain: wierk.com + www.wierk.com (DNS via GoDaddy)
- Google Analytics: G-SX537QD8SR (shared with altnota.com)

## Deploying

```bash
firebase deploy --only hosting
```

## Files

- `index.html` - the dictionary page
- `favicon.svg` - "w" letter favicon
- `robots.txt` - allow all crawlers
- `sitemap.xml` - single page sitemap
- `llms.txt` - AI agent context
- `.well-known/ai-plugin.json` - AI plugin metadata
- `firebase.json` - hosting config

## Related

- **Altnota repo**: github.com/osaral/altnota-root (`/Users/osaral/Documents/altnota`)
- **This repo**: github.com/osaral/wierk
- **Rename plan**: documented in altnota-root at `wierk-to-altnota-rename.md`

## Key facts

- Wierk = Luxembourgish word from Old High German "werc", Proto-Germanic *werka
- Company Wierk SRL (BE 1022.173.924) renaming to Altnota SRL effective 29 May 2026
