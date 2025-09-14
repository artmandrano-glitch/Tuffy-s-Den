# NC State Athletics Fan Site (Pro Starter)

A polished, fast, mobile-first NC State fan site with search, featured posts, light/dark theme, PWA offline, share links, related posts, and more.

## Quick start
1. Open **index.html** to preview.
2. Add posts in **/posts** as JSON (see examples).
3. List them in **/posts/index.json**. The Home page shows featured (newest 3), category pages filter automatically.
4. Replace **SITE_URL** in `README.md` and regenerate `sitemap.xml` (or leave as-is for dev).
5. Deploy to Netlify / Cloudflare Pages / GitHub Pages (static, no build).

## Configure
- Theme toggle: handled in `assets/theme.js`
- Analytics: add your snippet in `assets/analytics.js`
- Newsletter: replace Formspree action in the footer of `about.html` and `footer` in templates
- Comments: add Giscus snippet to `post.html` inside `#comments`
- Service Worker: `service-worker.js` caches core assets

## Notes
Independent fan site. Not affiliated with North Carolina State University or the NCAA.
