# Tally Calculator

A calculator built for narrow pop-up windows and the Samsung Edge panel. Works offline once installed.

**Open it:** https://dexxta18.github.io/tally-calculator/

## Features

- Paper tape of past calculations: tap one to reuse it, hold it to label, edit, copy or delete
- Live result while you type, swipe the display to delete a digit, hold ⌫ to clear
- Phone-style percent (`200+10%` = 220) and scientific keys behind `f(x)`
- Converter: live currency rates with an optional rate of your own, plus length, weight, temperature, area, volume, speed, data and time
- Tools: tip and bill split, discount with VAT, percentages, profit margin, days between dates
- Light, dark or system theme; vibration and click sound

## Install on a Galaxy phone

1. Open the link above in Chrome, then ⋮ → **Add to home screen → Install**.
2. **Settings → Display → Edge panels → Panels → Apps → Edit**, add **Tally**.
3. Swipe in the Edge panel and drag Tally onto the screen to open it as a pop-up window.

Your tape and settings are stored on your phone only.

## Files

`index.html` is the whole app (HTML, CSS and JavaScript in one file). `sw.js` provides offline support and `manifest.webmanifest` makes it installable. After editing `index.html`, change the build id on the first lines of `sw.js` so installed copies pick up the update.
