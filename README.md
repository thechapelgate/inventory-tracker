# CareStock – assisted living supply tracker

## Files
- `carestock.html` – the full app (one self-contained page).
- `example-items.json` – the 18 example supplies used in the demo.

## Important: where it works
The live version on claude.ai is the one that saves data, knows who is signed in,
records who changed what, and reads receipts with Claude. Those features come from
claude.ai itself.

If you open `carestock.html` directly from your computer, the screens and math all work,
but nothing is saved after you close the page, there are no logins, and receipt scanning
is hidden. To run it on your own server with saving and logins, a developer would need to
replace the storage calls (`db`, `user`, `sample`, `assets`) with your own backend.
