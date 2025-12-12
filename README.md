# CLI-Chat Website

Modern landing page for CLI-Chat, built with vanilla HTML, CSS, and JavaScript.

## Features

- 🎨 Modern, minimalist design inspired by gymbo.benkohler.de
- 🌓 Dark/Light mode toggle
- 📱 Fully responsive
- ⚡ Smooth animations and transitions
- 🎭 Glassmorphism effects
- 📋 Copy-to-clipboard functionality
- 🚀 Zero dependencies, pure vanilla JS

## Design Elements

- **Orange gradient accent** (#FF6B00 to #FF4500)
- **Dual-theme system** with automatic persistence
- **Glassmorphism cards** with backdrop blur
- **Large, bold typography** for hierarchy
- **Floating animations** and scroll effects
- **Terminal preview** with syntax highlighting

## Structure

```
cli-chat-website/
├── index.html      # Main HTML file
├── styles.css      # All styles with CSS variables
├── script.js       # Theme toggle and interactivity
└── README.md       # This file
```

## Deployment

### Option 1: GitHub Pages

1. Create a new repository on GitHub
2. Push this directory to the repository
3. Go to Settings → Pages
4. Select branch `main` and folder `/` (root)
5. Your site will be live at `https://username.github.io/repo-name`

### Option 2: Vercel

1. Install Vercel CLI: `npm install -g vercel`
2. Run `vercel` in this directory
3. Follow the prompts
4. Your site will be deployed instantly

### Option 3: Netlify

1. Drag and drop this folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Your site will be live immediately

### Option 4: Static hosting

Upload `index.html`, `styles.css`, and `script.js` to any web server.

## Local Development

Simply open `index.html` in your browser. No build process required!

For a local server:
```bash
python3 -m http.server 8000
# Or
npx serve .
```

Then visit `http://localhost:8000`

## Customization

All colors and styles are defined as CSS variables in `styles.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #FF6B00, #FF4500);
    --bg-primary: #ffffff;
    --text-primary: #000000;
    /* ... */
}
```

Change these to customize the color scheme.

## Links

- npm Package: https://www.npmjs.com/package/@bnjkhr/cli-chat-client
- GitHub Repository: https://github.com/bnjkhr/cli-chat
- Inspiration: https://gymbo.benkohler.de

## License

MIT
