# Comfort Umoren-Olorunnisommo - Academic Website

Personal academic website featuring research, publications, and projects in journalism and media studies.

## Structure

- `index.html` - Main profile page
- `styles.css` - Styling and responsive design
- `404.html` - Custom 404 error page
- `_config.yml` - GitHub Pages configuration

## About

This website showcases research interests in digital media, civic engagement, information environments, digital activism, and political communication. It includes academic publications, journalism work, and projects related to media and social change.

## Styling

The website uses a professional academic color scheme with:
- Primary color: Deep blue (`#1a5276`)
- Accent color: Gold (`#f39c12`)
- Responsive design for mobile, tablet, and desktop

To customize colors, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #1a5276;
    --secondary-color: #2471a3;
    --accent-color: #f39c12;
    /* ... */
}
```

## Hosting

This site is automatically hosted on GitHub Pages at:
https://comfortumoreno.github.io/comfortumoreno

The `docs/` folder is the source for GitHub Pages. Any changes pushed to `main` will automatically update your site.

## Add More Pages

To add new pages (e.g., a blog or CV):

1. Create a new `.html` file in the `docs/` folder
2. Add a navigation link in `index.html`
3. Use the same HTML structure and `styles.css` for consistency

## Local Testing

To test locally, you can use Python's built-in server:

```bash
cd docs
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.
