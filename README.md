# ThroneVerse Studios - Static Website

A complete static website for ThroneVerse Studios and their flagship game "Kenyan Thrones".

## 📁 File Structure

```
throneverse_static/
├── index.html          # Main homepage (entry point)
├── style.css           # Complete stylesheet
├── script.js           # All JavaScript functionality
├── assets/
│   ├── favicon.svg     # Site favicon
│   └── trailer-poster.svg  # Video thumbnail placeholder
└── fonts/              # (Empty - uses Google Fonts CDN)
```

## 🚀 Quick Start

### Option 1: Open Directly
Simply double-click `index.html` to open in your browser. Works completely offline!

### Option 2: Local Server (Recommended)
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# PHP
php -S localhost:8000
```
Then visit `http://localhost:8000`

### Option 3: Deploy to GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" → "main" → "/ (root)"
5. Your site will be live at `https://yourusername.github.io/repository-name/`

## 🎨 Customization

### Adding Real Images
Replace the placeholder divs in `index.html` with actual images:

```html
<!-- Current placeholder -->
<div class="placeholder-image kingdoms">
    <span>🏔️</span>
</div>

<!-- Replace with -->
<img src="assets/your-image.jpg" alt="Description">
```

### Adding the Trailer Video
1. Export your trailer as `kenyan-thrones-trailer.mp4`
2. Place it in the `assets/` folder
3. The video player will automatically detect it

### Updating Content
- **Text**: Edit directly in `index.html`
- **Colors**: Modify CSS variables in `style.css` (lines 15-30)
- **Fonts**: Currently uses Google Fonts (Cinzel + Inter)

## 📱 Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Smooth scroll navigation
- ✅ Animated counters
- ✅ Video player with custom controls
- ✅ Mobile hamburger menu
- ✅ Form validation
- ✅ Toast notifications
- ✅ Loading screen
- ✅ Scroll animations
- ✅ Particle effects
- ✅ Works offline
- ✅ SEO optimized

## 🔧 Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 📄 License

© 2025 ThroneVerse Studios. All rights reserved.

---

**Made with ❤️ in Nairobi, Kenya**
