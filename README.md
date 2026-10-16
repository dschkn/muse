# Muse

A quiet spatial canvas for thoughts. One HTML file, no dependencies or accounts.

## Use
- Double-click blank canvas to create a note; type directly.
- Drag notes by their margins.
- Drag the blank canvas to pan; scroll to pan; Ctrl/Cmd + wheel or +/- to zoom.
- Use **Export** to download a JSON backup.
- Notes and viewport save automatically in this browser's localStorage.

## Deployment
Serve the repository's `index.html` as a static file from `https://boatbehind.online/muse/` (Caddy: `handle_path /muse/* { root * /var/www/muse; file_server }`). Preserve any existing site's Caddy config. GitHub push alone does not configure your VPS.

## Caveats
Data is local to each browser, not synchronized. Back up important notes using Export. No analytics, account, or network requests.
