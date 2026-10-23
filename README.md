# james.cockerh.am

Personal site of James Cockerham. Jekyll, built by GitHub Pages.

## Blog posts

Posts live at `https://james.cockerh.am/b/<slug>/`. To add one:

1. Create `_blog/<slug>.md` with front matter:
   ```yaml
   ---
   title: Lake Cumberland guide   # required
   slug: lake-cumberland          # required; lowercase, hyphens. Becomes /b/<slug>/ and must never change (QR codes point at it)
   date: 2026-10-23               # required; index is sorted newest first
   summary: One-sentence summary  # shown on /b/
   unlisted: false                # true = hidden from /b/ but still reachable by URL/QR
   ---
   ```
   Body is Markdown (GFM). Put images in `assets/blog/<slug>/` and link them as `/assets/blog/<slug>/file.jpg`.
2. Create the QR page stub `_blog_qr/<slug>.md` containing only:
   ```yaml
   ---
   slug: <same slug>
   ---
   ```
   This publishes a printable QR page at `/b/<slug>/qr/` (drawn locally by `assets/blog/qrcode.js`, MIT, no external calls).
3. Commit and push to `main`; GitHub Pages rebuilds in about a minute.

Never include home address, work schedule, or other personal details in posts. Don't rename or delete a slug once its QR code has been shared.
