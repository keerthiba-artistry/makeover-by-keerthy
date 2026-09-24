# Makeover by Keerthy - Keerthiba Artistry

Official luxury web application for **Makeover by Keerthy** (`Keerthiba Artistry`), Chennai's premier HD & Airbrush bridal makeup studio, organic mehendi, saree draping, and haute hairstyling.

---

## 🚀 Key Features & SEO Optimization

This website is engineered for maximum organic search dominance on Google & Search engines for high-intent local queries:

- **Target Keywords**:
  - `keerthiba`
  - `makeover in chennai`
  - `keerthy`
  - `makeover by keerthy`
  - `keerthiba artistry`
  - `best bridal makeup artist in chennai`
  - `hd bridal makeup chennai`
  - `airbrush makeup chennai`
- **Schema.org Structured Data (JSON-LD)**:
  - `WebSite` Schema (with alternate names `Keerthiba`, `Keerthy`, `Makeover in Chennai`, `Keerthiba Artistry`)
  - `Person` Schema (`Keerthiba Sathiyaa - Lead Stylist`)
  - `LocalBusiness` / `BeautySalon` Schema
  - `FAQPage` Schema
  - `BlogPosting` Schema
- **Technical SEO Assets**:
  - `sitemap.xml` with image extensions and change frequencies
  - `robots.txt` disallowing hidden directories and pointing to the sitemap
  - `CNAME` for custom domain binding (`keerthibaartistry.web.app`)
  - Open Graph & Twitter Card tags for social media link previews

---

## 🌐 Dual Deployment: GitHub Pages & Firebase Hosting

### 1. Deploying to GitHub Pages (Automated via GitHub Actions)
A custom workflow has been added at `.github/workflows/deploy.yml`.

To deploy to GitHub Pages:
1. Commit and push your changes to GitHub:
   ```bash
   git add .
   git commit -m "SEO optimization and GitHub Pages deployment setup"
   git push origin newUi  # or main / master
   ```
2. Go to your GitHub Repository:
   - Navigate to **Settings** > **Pages**
   - Under **Build and deployment** > **Source**, select **GitHub Actions**.
3. GitHub Actions will automatically build and deploy the website to GitHub Pages every time you push code!

---

### 2. Deploying to Firebase Hosting
Firebase Hosting is configured via `firebase.json` pointing directly to the root folder `.` (and synchronized with `public/`).

To deploy to Firebase:
1. Ensure you are logged into Firebase CLI:
   ```bash
   firebase login
   ```
2. Run the deployment command:
   ```bash
   firebase deploy --only hosting
   ```

---

## 📁 Repository Structure

```
makeover-by-keerthy/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions deployment workflow
├── image/                      # Portfolio & brand images
├── Video/                      # Client video reels
├── gif/                        # Micro-animation assets
├── index.html                  # Main landing page (SEO & Schema optimized)
├── blog.html                   # Bridal Beauty Journal & tips
├── styles.css                  # Custom styling & design system
├── sitemap.xml                 # XML sitemap for search crawlers
├── robots.txt                  # Search engine crawler instructions
├── CNAME                       # GitHub Pages custom domain file
├── firebase.json               # Firebase Hosting configuration
└── package.json                # Tailwind CSS build scripts
```

---
© 2026 **Makeover by Keerthy**. Designed for extraordinary brides.