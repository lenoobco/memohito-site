# Memohito Landing Page

A modern, static landing page for the Memohito Chrome extension.

## 🚀 Quick Start

This is a static site with no build process required. Simply open `index.html` in your browser or deploy directly to hosting.

## 📦 Deployment to GitHub Pages

### Option 1: Deploy from main branch

1. Push this `site` folder to your GitHub repository
2. Go to your repository Settings → Pages
3. Set Source to `Deploy from a branch`
4. Select branch: `main` and folder: `/site`
5. Click Save

Your site will be available at: `https://yourusername.github.io/memohito-ext/`

### Option 2: Deploy to root of a separate repo

1. Create a new repository named `memohito` (or any name)
2. Copy the contents of this `site` folder to the root
3. Go to Settings → Pages
4. Select branch: `main` and folder: `/root`
5. Click Save

Your site will be available at: `https://yourusername.github.io/memohito/`

### Option 3: Using gh-pages branch

```bash
# From the site directory
git subtree push --prefix site origin gh-pages
```

## 🎨 Customization

### Update Links

1. **Chrome Web Store**: Update the "Add to Chrome" button URLs in `index.html` (currently shows alert)
2. **GitHub Repository**: Update GitHub links in the navigation and footer
3. **Social Links**: Add your social media or contact links in the footer

### Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #ec4899;
    /* ... other colors */
}
```

### Content

- Edit text in `index.html`
- Update features in the `.features-grid` section
- Modify steps in the `.how-it-works` section

## 📱 Features

- ✅ Fully responsive design
- ✅ Modern gradient effects
- ✅ Smooth scroll animations
- ✅ No build process needed
- ✅ SEO-friendly HTML structure
- ✅ Fast loading (no dependencies)
- ✅ Cross-browser compatible

## 📄 Files

- `index.html` - Main HTML structure
- `styles.css` - All styling
- `script.js` - Interactive features
- `README.md` - This file

## 🔧 Before Deployment

1. Update all placeholder links (GitHub URLs, Chrome Web Store URL)
2. Replace "yourusername" with your actual GitHub username
3. Add your extension icon/logo if available
4. Test responsive design on different devices
5. Update meta tags for SEO

## 📝 License

Match this with your main project license.
