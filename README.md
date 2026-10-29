# Task 4: CSS - Units, Box Models, Fonts

## Author
Nithin Kumar J

## Description
A simple webpage displaying an image inside a bordered container with a
"Click Me" button below it, styled entirely with CSS using viewport units.

## Files
- `index.html` — page structure: a container div holding an image and a button
- `style.css` — styling for layout, spacing and the button

## Implementation Notes
- The container is positioned using **viewport units only** (`vw` / `vh`),
  giving:
  - 25% spacing from the left and right of the screen (`margin-left`/`margin-right: 25vw`)
  - 10% spacing from the top and bottom of the screen (`margin-top`/`margin-bottom: 10vh`)
- `box-sizing: border-box` is applied globally so borders/padding never push
  the layout beyond the viewport.
- `overflow: hidden` on `html, body` combined with exact `vw`/`vh` sizing
  ensures the page never scrolls.
- The button uses a linear gradient background (yellow → green) with custom
  font size, weight and letter spacing.
- No Flexbox is used — layout relies purely on box model (margins) and
  viewport units.
- No `position: relative`/`absolute` is used.

## How to Run
1. Keep `index.html` and `style.css` in the same folder.
2. Open `index.html` in any modern browser.
