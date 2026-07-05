# Memory Card Game

A simple browser-based memory card matching game built with HTML, CSS, and JavaScript.

Play a classic concentration/memory match game by flipping cards and matching pairs. This project is a small, accessible, and easy-to-customize example of DOM manipulation and simple game logic.

## Demo

Open `index.html` in your browser to play locally, or host the project with any static file server.

## Features

- Flip cards to reveal their faces
- Match pairs to clear cards from the board
- Move counter and timer (if implemented in the project code)
- Responsive layout for desktop and mobile
- Simple, easy-to-read JavaScript logic suitable for learning and customization

## How to Play

1. Open `index.html` in your browser.
2. Click or tap a card to flip it.
3. Click or tap a second card to try to find the matching pair.
4. If the two cards match, they remain face-up; otherwise they flip back over.
5. Continue until all pairs are matched.

## Installation / Running Locally

Because this is a static site, you can run it directly from the file system or with a static server.

Option 1 — Open locally:
- Double-click `index.html` or open it from your browser (`File → Open File`), then navigate to the project's `index.html`.

Option 2 — Use a simple HTTP server (recommended for consistent behavior):

With Python 3:

```bash
# from the project root
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

With Node (http-server):

```bash
npm install -g http-server
http-server -c-1
# open the displayed URL in your browser
```

## Development

- Edit the HTML in `index.html` (or similar main HTML file).
- Edit styles in the CSS file(s) (commonly `styles.css` or `css/` folder).
- Edit game logic in the JavaScript file(s) (commonly `script.js` or `js/` folder).

Tips:
- Increase or decrease the number of card pairs by adjusting the card dataset in the JavaScript.
- Replace card faces (images or emojis) by editing the assets or arrays used by the game.

## File Structure (typical)

- index.html — main HTML file  
- css/ or styles.css — styling  
- js/ or script.js — game logic  
- assets/ — images and icons

Adjust these names to match the actual files in the repository.

## Accessibility

- Ensure cards are keyboard-focusable and operable via Enter/Space for better accessibility.
- Add ARIA attributes to convey state (e.g., `aria-pressed`, `aria-hidden`) if you modify the DOM structure.

## Customization

- Change card content (images, emojis, text) in the game data array.
- Update styles to change layout, animations, and color scheme.
- Add difficulty levels by changing the number of pairs or timing constraints.

## Contributing

Contributions, bug reports, and improvements are welcome. Please open an issue or submit a pull request explaining your changes.

## License

This project is provided under the MIT License. See `LICENSE` for details, or add one if not present.

## Credits

Created by jow5445.

---

Enjoy the game! Pull requests to improve UI, accessibility, testing, or features are appreciated.
