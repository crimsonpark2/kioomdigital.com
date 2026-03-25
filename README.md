# Kioom Digital Website

Minimal, professional multi-page website for **Kioom Digital** — the mother company behind Lifetone.life, TradieHQ, and future online platforms.

## 📁 Project Structure

```
kioom-digital-website/
├── index.html      # Home / Landing page
├── about.html      # About the company
├── services.html   # Services offered
├── portfolio.html  # Project showcase (Lifetone, TradieHQ, etc.)
├── contact.html    # Contact form
├── css/
│   └── style.css   # All styling (minimal, bold accent)
├── js/
│   └── script.js   # Mobile menu & interactions
└── README.md       # This file
```

## 🎨 Design

- **Style**: Minimal with bold accent colors (purple/pink gradient)
- **Typography**: Inter (body) + Playfair Display (headings)
- **Inspiration**: Lifetone.life's bold visuals with professional polish
- **Responsive**: Fully mobile-friendly
- **Tech**: Pure HTML/CSS/JS (no frameworks)

## 🚀 Deploy to GitHub Pages (Free)

1. **Create a new GitHub repository**
   - Go to https://github.com/new
   - Repository name: `kioomdigital.com` (or `kioom-digital-website`)
   - Set to **Public** (required for free Pages)
   - Initialize with a README? No (we'll push existing)

2. **Push this folder to GitHub**
   ```bash
   cd /Users/aurora/.openclaw/workspace/kioom-digital-website
   git init
   git add .
   git commit -m "Initial commit: Kioom Digital website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/kioomdigital.com.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: `Deploy from a branch`
   - Branch: `main`, folder: `/ (root)`
   - Click Save

4. **Your site will be live at:**
   ```
   https://YOUR_USERNAME.github.io/kioomdigital.com/
   ```

## 🌐 Custom Domain (kioomdigital.com)

Once GitHub Pages is live:

1. In repo Settings → Pages → Custom domain
2. Enter: `kioomdigital.com`
3. Check "Enforce HTTPS"
4. Save

5. **Add DNS records at your domain registrar:**
   - Type: `A` | Name: `@` | Value: `185.199.108.153`
   - Type: `A` | Name: `@` | Value: `185.199.109.153`
   - Type: `A` | Name: `@` | Value: `185.199.110.153`
   - Type: `A` | Name: `@` | Value: `185.199.111.153`
   - Type: `CNAME` | Name: `www` | Value: `YOUR_USERNAME.github.io`

   (IPs are GitHub's servers; update if they change)

6. Wait 5-30 minutes for DNS propagation. HTTPS may take up to 24h.

## 🛠 Customize

- **Colors**: Edit CSS variables in `css/style.css` (root)
- **Text**: Edit HTML files directly
- **Images**: Replace gradient backgrounds with real images in `portfolio-image` divs
- **Contact form**: Currently shows alert only. To receive emails, connect a backend (Formspree, Formcarry, etc.) or use a serverless function.

## 📦 What's Missing (Optional)

- Real portfolio images (currently gradient placeholders)
- Backend for contact form (.Formspree free tier recommended)
- SEO enhancements (sitemap, structured data)
- Analytics (Google Analytics, Plausible)

## 📝 Notes

- ABN information appears as "Available upon request" — update when you have the number.
- Lifetone.life and TradieHQ links point to live sites; verify URLs.
- Mobile menu is simple JS; expand if needed.

---

**Made with 💜 by Kioom Digital**