# Global Home Health Care LLC — Website (Pure HTML)

**100% self-contained HTML files. No build tools, no frameworks, no separate CSS/JS files.**
Works directly on GitHub Pages — just upload and go.

---

## File Structure

```
global-hhc/
├── index.html              ← Home page
├── privacy-policy.html     ← Privacy policy
└── pages/
    ├── services.html       ← Services page
    ├── about.html          ← About Us page
    ├── careers.html        ← Job application + PDF generation ★
    ├── referral.html       ← Patient referral form + PDF ★
    └── contact.html        ← Contact form + Google Map
```

Each file contains all its own CSS and JavaScript inline — no external dependencies
except Google Fonts and the jsPDF library (loaded from CDN for PDF generation).

---

## Deploy to GitHub Pages

### Option A — GitHub Web Interface (easiest)
1. Go to github.com → **New repository** → name it `global-hhc`
2. Click **uploading an existing file**
3. Drag and drop the entire unzipped folder contents
4. Commit the files
5. Go to **Settings → Pages → Branch: main → Save**
6. Live at: `https://[your-username].github.io/global-hhc/`

### Option B — Git Command Line
```bash
cd global-hhc
git init
git add .
git commit -m "Launch Global Home Health Care website"
git branch -M main
git remote add origin https://github.com/[your-username]/global-hhc.git
git push -u origin main
```
Then enable GitHub Pages in repo Settings.

---

## Features

- 3D animated hero card with mouse-tilt effect
- Dual CTA buttons (Referral + Apply Now) on home page
- Full job application form → generates branded PDF on submit
- Patient referral form → generates HIPAA-labeled PDF on submit
- Sticky navbar with scroll effect + mobile hamburger menu
- Animated scrolling ticker banner
- Scroll-reveal animations on service cards
- Fully responsive (mobile, tablet, desktop)
- Google Fonts loaded via CDN (Playfair Display + DM Sans)
- jsPDF loaded via CDN for client-side PDF generation

---

## Contact Info

- **Phone:** (614) 495-8934
- **Email:** info@global-hhc.com
- **Address:** 1395 East Granville Road, Suite 302, Columbus, OH 43229
