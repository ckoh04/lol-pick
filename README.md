# League of Legends Team Maker

A browser-based 5v5 team builder for custom League of Legends games.

## What it does

- Add up to 10 players with summoner name, rank, and primary/secondary roles
- Build balanced teams based on rank strength, role coverage, and role preference satisfaction
- Generate random teams with one click
- Show quick stats (average/highest/lowest rank, rank spread)

## File

- `index.html` contains the full app (HTML, CSS, and JavaScript).

## How to run

1. Open `index.html` in any modern browser.
2. Add players and roles.
3. Click `Balance Teams` or `Random Teams`.

## Notes

- No backend required.
- Data is in-memory only and resets when the page is reloaded.

## AdSense Setup

1. In `index.html`, replace both `ca-pub-XXXXXXXXXXXXXXXX` values with your real AdSense publisher ID.
2. In `ads.txt`, replace `pub-0000000000000000` with the numeric part of your publisher ID.
3. Deploy with `ads.txt` at your site root (for example: `https://your-domain.com/ads.txt`).
