# james.cockerh.am

👉 **Live site:** https://james.cockerh.am  
👉 **www version:** https://www.james.cockerh.am

Personal site & digital garden of James Cockerham  
100 % Markdown → Obsidian → GitHub Pages → Cloudflare

### What this is
- Written and edited entirely in Obsidian (desktop + Android)
- Auto-commits via obsidian-git plugin
- Instantly deployed by GitHub Pages (no build step)
- Served blazing-fast through Cloudflare (proxied, Universal SSL)
- Dark/light mode, fully responsive, zero JavaScript bloat

### Tech stack
- Obsidian.md
- GitHub Pages + Jekyll (minimal theme)
- Custom CSS (one file, ~100 lines)
- Cloudflare DNS + caching
- Domain: `cockerh.am` (because short domains are cool)

### Local preview (optional)
```bash
git clone https://github.com/jamescockerham/cockerh.am.git
cd cockerh.am
bundle install      # if you have Ruby
bundle exec jekyll serve