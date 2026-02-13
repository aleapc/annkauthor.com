# Ann K. Author Website

A minimalist, static author website for Ann Katherine Keller (Ann K.), author of The Rooms Trilogy.

## Files

```
Website/
├── index.html          # Main multi-section website
├── index-onepage.html  # Simplified single-scroll version
├── style.css           # Stylesheet for main site
├── author-photo.jpg    # [Add your author photo here]
├── first-rooms-cover.jpg    # [Add book cover here]
├── rooms-between-cover.jpg  # [Add book cover here]
└── README.md           # This file
```

## Typography

The site uses Google Fonts:
- **Cormorant Garamond** - Elegant serif for headings and literary text
- **Inter** - Clean sans-serif for body text

## Color Palette

- Background: `#FAFAF8` (warm off-white)
- Text: `#2C2C2C` (soft black)
- Muted text: `#5A5A5A`
- Borders: `#E0DED8`

---

## Free Deployment Options

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub account** at github.com (if you don't have one)

2. **Create a new repository**
   - Go to github.com and click "New repository"
   - Name it `annk-author` (or any name you prefer)
   - Make it Public
   - Click "Create repository"

3. **Upload your files**
   - Click "uploading an existing file"
   - Drag all files from the Website folder (index.html, style.css, images, etc.)
   - Click "Commit changes"

4. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

5. **Access your site**
   - Your site will be live at: `https://[your-username].github.io/annk-author/`
   - It may take a few minutes to deploy

**Custom Domain (Optional):**
- In Settings > Pages, enter your custom domain
- Add a CNAME record with your domain registrar pointing to `[username].github.io`

---

### Option 2: Netlify (Free Tier)

1. **Create a Netlify account** at netlify.com

2. **Deploy via drag-and-drop**
   - Go to netlify.com/drop
   - Drag your entire Website folder onto the page
   - Done! Netlify will give you a random URL like `random-name-123.netlify.app`

3. **Customize your URL**
   - Go to Site settings > Domain management
   - Click "Options" next to your Netlify subdomain
   - Choose "Edit site name" to get: `annk-author.netlify.app`

4. **Custom Domain (Optional)**
   - In Domain management, click "Add custom domain"
   - Follow Netlify's instructions to configure DNS

---

### Option 3: Local Hosting (For Preview)

To preview locally before deploying:

**Using Python (if installed):**
```bash
cd "C:\Users\aapc_\OneDrive\Desktop\Rooms Trilogy\Website"
python -m http.server 8000
```
Then open: `http://localhost:8000`

**Using Node.js (if installed):**
```bash
npx serve "C:\Users\aapc_\OneDrive\Desktop\Rooms Trilogy\Website"
```

**Simply open the file:**
- Double-click `index.html` to open in your default browser
- Note: Some features may not work perfectly without a server

---

## How to Replace Images

### Author Photo

1. Prepare your image:
   - Recommended size: 800x1000 pixels (portrait orientation)
   - Format: JPG or PNG
   - Professional, literary aesthetic (muted tones work well)

2. Save the image as `author-photo.jpg` in the Website folder

3. The site will automatically display it (fallback placeholder will disappear)

### Book Covers

1. Prepare your cover images:
   - Recommended size: 400x600 pixels (2:3 ratio)
   - Format: JPG

2. Save as:
   - `first-rooms-cover.jpg`
   - `rooms-between-cover.jpg`

---

## How to Edit Content

### Updating Text

Open `index.html` in any text editor (Notepad, VS Code, etc.):

**To change the tagline:**
```html
<p class="hero__tagline">Your new tagline here.</p>
```

**To edit the biography:**
Find the `<section class="about">` and edit the `<p>` paragraphs inside.

**To update book descriptions:**
Find `<article class="book">` sections and edit the `<p class="book__synopsis">` content.

**To change the contact email:**
```html
<a href="mailto:your-email@domain.com">your-email@domain.com</a>
```

### Updating the Quote

Find the hero quote section:
```html
<div class="hero__quote">
  <p>"Your quote here."</p>
</div>
```

---

## Choosing Between Versions

- **index.html** - Full multi-section site with navigation, ideal for desktop and complete author presence
- **index-onepage.html** - Simplified single-scroll version, all content on one page with embedded styles, ideal for a minimal approach

To use the single-page version as your main site, either:
- Rename `index-onepage.html` to `index.html`
- Or configure your hosting to serve `index-onepage.html` as the default

---

## Domain Name Suggestions

Consider these domain options:

1. **annkauthor.com** - Professional, clear
2. **annkwrites.com** - Active, writer-focused
3. **theroomstrilogy.com** - Series-branded

Check availability at namecheap.com or your preferred registrar.

---

## Technical Notes

- Pure HTML + CSS (no build process required)
- Fully responsive (mobile, tablet, desktop)
- Minimal JavaScript (only for mobile nav toggle)
- Fast loading, no external dependencies except Google Fonts
- Semantic HTML for accessibility and SEO

---

## Support

For issues with:
- **GitHub Pages**: docs.github.com/pages
- **Netlify**: docs.netlify.com
- **HTML/CSS editing**: Search for specific changes needed

---

*Website designed for Ann K., author of The Rooms Trilogy*
