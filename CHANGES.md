# Voin.Studio v2

Drop these files into the repo root, replacing what is there.

Delete from the repo (no longer used):
me.html, work-*.html, shot-*.webp, gsap.min.js

New files: site.css, site.js, site.webmanifest, icon-192.png, icon-512.png, apple-touch-icon-dark.png
Old URLs (me.html, work-*.html) redirect via vercel.json.

Icons: the installed set is "Ripple". To switch, copy a different `*-favicon.svg` from the icons pack over favicon.svg
and the matching PNGs over apple-touch-icon.png, icon-192.png, icon-512.png and favicon-48.png.

When you bump site.css or site.js, change `?v=2` in the four HTML files so browsers fetch the new copy.
