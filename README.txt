PERSONAL BASKETBALL SCOREKEEPER — ZERO-COST PWA

FILES
- index.html: the application
- manifest.webmanifest: Android install metadata
- sw.js: offline cache service worker

IMPORTANT
1. This is a first working version, not a certified official scoring system.
2. Data is stored in the browser's localStorage on this phone/browser.
3. Do not clear browser storage or uninstall/clear app data before exporting a backup.
4. CSV export contains per-player game statistics. It does not export team/player setup or all game metadata.
5. Game clock is a basic browser timer. Keep the app open and use an independent official clock as backup.
6. The app needs HTTPS hosting for PWA installation and service-worker offline caching. Opening index.html directly from Files will let you test it, but will not enable full PWA installation/offline caching.

FREE ANDROID INSTALLATION (GitHub Pages)
A. Create/sign in to a free GitHub account.
B. Create a new public repository, e.g. personal-basketball-scorekeeper.
C. Upload index.html, manifest.webmanifest, and sw.js to the repository root.
D. In repository Settings > Pages, select Deploy from a branch, choose main and /(root), then Save.
E. Wait for GitHub Pages to publish. Open the published https://...github.io/... address in Chrome on Android.
F. Chrome menu (⋮) > Install app or Add to Home screen > Install.
G. Open the installed app. Add teams and players before creating a game.

USING THE APP
1. Teams tab: add both teams.
2. Teams tab: add each player and jersey number to the correct team.
3. New Game tab: choose home and away teams and create the game.
4. Live tab: select a player; tap quick stat buttons or use Manual edit all stats.
5. Stats tab: see player averages and game history.
6. Export player stats CSV regularly. Import into Excel/Google Sheets.

CURRENT LIMITATIONS
- First version does not yet include substitution tracking, automatic player minutes, shot chart, play-by-play log, or a JSON restore workflow.
- Manual editing changes player totals; scoreboard is recalculated from made field goals and free throws.
- Quick stat buttons add made shots and attempts together. Missed-shot attempt buttons and undo for every stat are future improvements.
- Local-only data is not synced between devices.
