# Ovaro Chula Chicken — menu link

Live at **https://ovaro-menu.joypatel041994.workers.dev** (hosted on Cloudflare, auto-deployed from this repo).

This exact link is printed as a QR code on the visiting cards and flex banners. To keep those QR codes working:
- never rename or delete this repo or the Cloudflare project `ovaro-menu`;
- never change the Cloudflare account's workers.dev subdomain (`joypatel041994`);
- keep the file name `menu.pdf`.

## Updating the menu
Replace `menu.pdf` with the new menu (same file name) and commit to `main`. Cloudflare redeploys in ~1 minute; every printed QR shows the new menu. Nothing else needs to change.

On GitHub web: open `menu.pdf` → ⋯ → Delete file → Commit, then "Add file → Upload files" → drop the new `menu.pdf` → Commit.

(GitHub Pages is also on for this repo, but it redirects to the personal domain joypatel.me, so it is NOT the printed link.)
