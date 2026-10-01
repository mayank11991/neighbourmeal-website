# NeighbourMeal Website

Static landing page for Stripe Connect verification and marketing.

## Deploy to GitHub Pages

1. **Create a new repo** (or use existing):
   ```bash
   git init
   git add .
   git commit -m "Initial landing page"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/neighbourmeal-website.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repo Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` / `/ (root)`
   - Save

3. **Your site will be live at**: `https://YOUR_USERNAME.github.io/neighbourmeal-website/`

4. **Custom domain** (optional): Add `CNAME` file with your domain, configure DNS.

## Stripe Connect

Use this URL in Stripe Dashboard → Connect → Settings → Branding → **Website**.

## Update Google Play Link

Replace the `href` in `index.html`:
```html
<a class="play-badge" href="https://play.google.com/store/apps/details?id=com.neighbourmeal.app">
```

## Colours (match app)

- Primary: `#2E7D32` (green)
- Dark: `#1B5E20`
- Light: `#4CAF50`
- Accent: `#FF9800` (orange)
- Background: `#F1F8E9` (light green tint)

Dark mode auto-switches via `prefers-color-scheme`.