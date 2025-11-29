# IXECA Website

A dark, cyberpunk-themed documentation site for hosting the IXECA ΔFIELD.CODEX.

## Features

- **Dark Theme**: Cyberpunk aesthetic with glowing accents
- **Table of Contents**: Collapsible sidebar with hierarchical navigation
- **Search**: Real-time search with highlighted results
- **Responsive**: Works on desktop and mobile devices
- **Download**: Direct download button for the markdown file
- **Smooth Scrolling**: Easy navigation between sections

## Files

- `index.html` - Main website file (standalone, contains all CSS/JS)
- `IXECA.md` - Your complete IXECA document
- `README.md` - This file

## Local Testing

To test the website locally:

1. Open `index.html` in a modern web browser
2. Or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a new GitHub repository
2. Upload `index.html` and `IXECA.md`
3. Go to Settings → Pages
4. Select "Deploy from branch" → main branch
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)
1. Drag and drop the folder to [netlify.com/drop](https://app.netlify.com/drop)
2. Site goes live instantly
3. Get a custom domain or use the free Netlify subdomain

### Option 3: Vercel (Free)
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the folder
3. Follow prompts for deployment

### Option 4: Simple Web Host
Upload both files to any web hosting service (shared hosting, VPS, etc.)

## Customization

### Colors
Edit the CSS variables in `index.html`:
```css
:root {
    --bg-primary: #0a0a0f;      /* Main background */
    --bg-secondary: #12121a;    /* Secondary background */
    --text-primary: #e0e0f0;    /* Main text */
    --accent-primary: #6060ff;  /* Accent color */
    --accent-glow: #8080ff;     /* Glow effect */
}
```

### Font
Change the font-family in the body style:
```css
body {
    font-family: 'Courier New', 'Consolas', monospace;
}
```

### Title
Edit line 47 in `index.html`:
```html
<h1>╔═══════╗ IXECA ╚═══════╝</h1>
```

## Browser Support

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## License

Your content, your license.
