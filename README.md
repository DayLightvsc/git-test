# Simple HTML Page

A minimal, responsive landing page built with plain HTML and CSS — no frameworks, no build step.

A centered card greets the visitor with a heading, a short paragraph, and a call-to-action button.

## Features

- Single-file HTML markup with a separate stylesheet
- Centered card layout using CSS Flexbox
- Soft shadow and rounded corners for a modern look
- Responsive viewport meta tag for mobile devices
- Zero dependencies — just open it in a browser

## Project Structure

```
git-test/
├── index.html    # Page markup
├── style.css     # Page styles
└── README.md     # This file
```

## Getting Started

### Option 1: Open it directly

Double-click `index.html`, or drag it into any modern browser.

### Option 2: Run a local server

Serving over HTTP is recommended so relative paths and future scripts behave like production.

```bash
# Python 3
python -m http.server 8000
```

```bash
# Node.js (npx)
npx serve .
```

Then visit <http://localhost:8000>.

## Customization

| What to change        | Where                          |
| --------------------- | ------------------------------ |
| Heading and text      | `<h1>` and `<p>` in `index.html` |
| Button label          | `<button>` in `index.html`       |
| Colors and spacing    | `style.css`                      |
| Font family           | `body { font-family: ... }`      |
| Card appearance       | `.card` rule in `style.css`      |

The button currently has no click behavior. Add a `script.js` and hook it up when you're ready:

```html
<script src="script.js"></script>
```

## Browser Support

Works in all modern browsers (Chrome, Firefox, Edge, Safari). Uses only standard CSS — Flexbox, `border-radius`, and `box-shadow`.

## License

MIT — feel free to use and modify.
