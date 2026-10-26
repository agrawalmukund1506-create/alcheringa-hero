# Alcheringa — 50 days to go

Animated, interactive hero for IIT Guwahati's Alcheringa ("The Grand Shuffle", 29–30 January), built from the *Desktop - 1* frame of the L-Cher Compile Figma file.

Open `index.html` in a browser, or visit the GitHub Pages site for this repository.

## What moves

- **Jester:** the eyes roll like slot-machine reels and land on **5 0**; the two halves of the cap rock as mirror images, with the bells dangling behind.
- **Background:** the red rays and the spin wheels turn slowly, the music notes wiggle and the cards hover. The "Get your merch" ticker scrolls left to right.
- **Slot machine:** pull the lever (or press SPIN) to spin the three cards, with sound. Click a card to nudge just that reel. GET SCHEDULE links to `#schedule` for now; change its `href` (on `id="btnSchedule"`) to the real page.

The page scales to the window width, uses no libraries or external requests, and respects `prefers-reduced-motion`.

## Optional extras

Depth on mouse move, poking the joker, musical notes and whirling wheels sit in a block marked `EXTRAS` in the CSS and at the end of `index.html`. Delete both blocks to remove them.

## Files

- `index.html`: the page, with its styles and scripts inline
- `assets/`: background, logo, slot machine, spin wheel and card artwork exported from Figma
