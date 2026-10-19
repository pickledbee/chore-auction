# The Chore Auction

Kids bid for chores. The lowest bid wins the job and earns those points when a parent checks the work.

Live app: https://pickledbee.github.io/chore-auction/

- Try the demo: https://pickledbee.github.io/chore-auction/#demo
- Set up a family: https://pickledbee.github.io/chore-auction/#setup
- Set up a kid's device with a join code: https://pickledbee.github.io/chore-auction/#join

This repository holds only the app page (index.html). Family data is never stored here.
It lives in a private Google Apps Script backend, with one private Google Sheet per family.
The demo runs entirely in the browser and sends nothing to the backend.

Security: strict Content-Security-Policy (only the page's own scripts run), no third-party
scripts or fonts (fonts are self-hosted under fonts/, SIL Open Font License), no referrer,
and family IDs live after the # so they are never sent to any web server.
