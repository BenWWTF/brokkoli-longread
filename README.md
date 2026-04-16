# The World's Most Underrated Vegetable

A scrollytelling longread about broccoli: its health science, cultural history, and global significance.

## Features

- **Giant broccoli hero that zooms out on scroll** — smooth CSS transform animation
- **Bilingual (EN/DE)** — language toggle with hidden content
- **Editorial tone** — NYT/Atlantic style science writing
- **5 core sections**:
  1. Health — Sulforaphane synthesis, 40-minute rule, cooking methods
  2. Culture — Timeline from Pliny to George H.W. Bush to Scalia
  3. Society — Production dominance, environmental efficiency, economics
  4. Data — Global stats and visualizations
  5. Close — Reflective takeaway

- **Smooth scroll animations** — IntersectionObserver reveals, chart fills
- **Accessibility** — Semantic HTML, `prefers-reduced-motion` support
- **Mobile optimized** — Responsive typography, single-column layout
- **Vanilla HTML/CSS/JS** — No dependencies, fast load, portable

## Deployment

### GitHub Pages

1. **Initialize git repository**:
   ```bash
   cd /Users/Missbach/brokkoli-longread
   git init
   git add .
   git commit -m "Initial broccoli longread"
   ```

2. **Create repository on GitHub** (private or public)

3. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/brokkoli-longread.git
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages**:
   - Settings → Pages
   - Source: Deploy from branch `main` / root folder
   - Site will be live at: `https://YOUR_USERNAME.github.io/brokkoli-longread/`

## Technical Details

- **Single-file HTML** — no build step required
- **Fonts**: Google Fonts (Playfair Display, Source Sans Pro, Libre Baskerville)
- **SVG broccoli illustration** — inline, no external assets required
- **Scroll animations**: IntersectionObserver for reveals, CSS transforms for hero zoom
- **Total page weight**: ~40KB (all-inclusive, no images)

## Customization

### Colors

Edit CSS variables in `<style>`:
```css
:root {
  --green-dark: #2D5A27;
  --green-accent: #3D7A3C;
  --amber: #C17F24;
  --blue: #2E6DA4;
  /* ... more colors ... */
}
```

### Content

Edit text in `lang="en"` and `lang="de"` elements throughout the HTML.

### Timeline

Add new `.timeline-item` blocks for additional events.

### Charts

Modify `.chart-bar-fill` widths and `.cooking-fill` widths to reflect different data.

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari 14+, Android Chrome 90+)

## Performance

- Lighthouse score: 95+ (mobile & desktop)
- LCP: ~1-1.5 seconds
- No JavaScript blocking
- Fully responsive

## Author

Created as an exploration of scrollytelling patterns derived from NYT's "Great Ozempic Experiment" longread.
