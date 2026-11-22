# McGill MMA Alumni Networking Event, Toronto: photo gallery

Static photo gallery for the McGill Desautels MMA alumni networking event (Toronto, Nov 18, 2026).

- `index.html` is the whole site (HTML, CSS, JS; GSAP, Lenis and JSZip load from public CDNs).
- `assets/` holds logos and ambassador / program-director headshots.
- `photos/photos.js` is the photo manifest. The image files themselves are **not** in this repo.
  The site expects `photos/thumb/`, `photos/preview/` and `photos/original/` to hold files named as in the manifest.

Deployed with Cloudflare Pages (`wrangler pages deploy`) from a local folder that includes the photos.
