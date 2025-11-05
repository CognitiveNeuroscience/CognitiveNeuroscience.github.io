# Cognitive Neuroscience GUI Project Website

A professional project website for the Cognitive Neuroscience GUI project, hosted on GitHub Pages.

## 🌐 Live Website

This website is configured to be hosted at `https://cognitiveneuroscience.github.io/CognitiveNeruoGUI.github.io/`

## 📄 Pages

- **Home** (`index.html`) - Main landing page introducing the project
- **About Us** (`about.html`) - Team information and mission statement
- **Projects** (`projects.html`) - Overview of ongoing projects and initiatives

## 🚀 Deploying to GitHub Pages

### Option 1: Deploy from Main Branch (Recommended)

1. Merge this PR to the `main` branch
2. Go to your repository settings: `Settings` → `Pages`
3. Under "Source", select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click "Save"
5. GitHub will automatically build and deploy your site
6. Your site will be live at `https://cognitiveneuroscience.github.io/CognitiveNeruoGUI.github.io/`

### Option 2: Deploy from a Specific Branch

1. Create a `gh-pages` branch if you want to keep deployment separate
2. Copy all HTML and CSS files to that branch
3. In repository settings, select the `gh-pages` branch as the source
4. GitHub will deploy from that branch

### ⚙️ Configuration

No build process is required - this is a static HTML/CSS website that GitHub Pages can serve directly.

## 🎨 Customization

### Updating Content

- Edit HTML files directly to update page content
- Modify `styles.css` to change colors, fonts, or layout
- All pages share the same stylesheet for consistent design

### Color Scheme

The current color scheme uses:
- Primary: `#667eea` (Purple-blue)
- Secondary: `#764ba2` (Purple)
- Background: `#f4f4f4` (Light gray)

### Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## 📝 Local Development

To test the website locally:

```bash
# Using Python 3
python3 -m http.server 8000

# Then visit http://localhost:8000 in your browser
```

Or use any other local web server of your choice.

## 📧 Contact

For questions or contributions, contact: info@cognitiveneuro.github.io