# Digital Clock

## Project overview

This small project implements a digital clock using `index.html` and `script.js`. The clock shows hours, minutes and seconds and updates every second. It's ideal as a learning example for DOM manipulation and working with the JavaScript Date API.

## Features

- Real-time clock that updates every second
- Simple, dependency-free implementation (JS)
- Easy to customize (format, styles, 12/24-hour toggle)
- Works offline — just open `index.html` in any browser

## Files

- `index.html` — The main HTML file. Contains the markup and links to `script.js`.
- `script.js` — JavaScript that reads the current time and updates the DOM.

If you add CSS, images, or other assets, list them here.

## How to run

1. Clone or download this folder to your computer.
2. Open `index.html` in your browser (double-click or right-click → Open with → your browser).
3. The clock starts automatically.

Optional: run a lightweight local server (useful if you plan to extend the app):


## Customization

- Change the time format: edit `script.js` to switch between 12-hour and 24-hour formats, add AM/PM, or change leading-zero behavior.
- Styling: add a `styles.css` file and link it from `index.html` to change fonts, colors, and layout.
- Add features: alarm, stopwatch, world clocks, or date display.

## Small contract (inputs / outputs / errors)

- Input: none (reads user's system clock).
- Output: DOM updates (current time display).
- Error modes: none expected; if JavaScript is disabled the clock won't run. If the system clock is wrong, the display will reflect that.

## Edge cases to consider

- Browser with JavaScript disabled — provide a fallback static message in HTML.
- System time changes (timezone changes or manual clock edits) — clock will reflect new system time on next tick.
- Performance: extremely lightweight, negligible CPU usage.

## Troubleshooting

- If the clock does not appear, open the browser console (F12) and check for errors.
- Ensure `script.js` is referenced correctly in `index.html`.

## Contributing

1. Fork the repository or copy the folder.
2. Make changes and test locally.
3. Submit suggested changes by sharing files or a patch.

## License

This project can be used under an MIT-style license unless otherwise specified by the author. Add an explicit `LICENSE` file if you want to set a different license.

## Contact / Notes

If you want, I can:

- add a `styles.css` with a modern look,
- add 12/24-hour toggle and AM/PM support,
- add a small test page or accessibility improvements.

---
## Preview

[Digital Clock]( https://haseebjaved4212.github.io/Digital-Clock/)

