# Romar A. Gellamucho — Cloud Engineering Specialist Portfolio

> **High-Performance Interactive Web Portfolio & ATS-Compliant PDF Resume**  
> Architected for Senior Cloud & DevOps roles with 14+ years of enterprise IT experience.

![Portfolio Preview Banner](photo.jpg)

---

## 🌟 Key Features

- **3 Dynamic Themes**:
  - 🌌 **Midnight Cloud** (Default dark developer aesthetic)
  - ☀️ **Executive Light** (Clean high-contrast corporate presentation)
  - 🌲 **Emerald Ops** (Terminal operations vibe)
  - State persisted seamlessly with `localStorage`
- **Interactive macOS DevOps Terminal**:
  - Live tab switcher: `infra_main.tf` (Terraform HCL), `profile.json` (Structured JSON resume), `deploy.sh` (CI/CD pipeline)
  - Real-time syntax highlighting and status indicators
- **4 Career Experience Roles**:
  - 14-year progression from Tier-2/3 Support to Senior Systems Admin and Lead Cloud & DevOps Engineer
  - Interactive accordion toggling with "Expand All / Collapse All"
- **Interactive Skills Matrix**:
  - Real-time live search filter
  - Category filter pills (Cloud, IaC & Automation, Linux & Systems, Containers & K8s, Databases & Storage, Security & Networking)
- **Certifications Vault (14 Credentials)**:
  - Red Hat Certified Engineer (RHCE) & RHCSA
  - Red Hat Certified Specialist in Ansible Automation
  - HashiCorp Certified: Terraform Associate & Vault Associate
  - Oracle Certified Professional (OCP) & Associate (OCA)
  - AWS Solutions Architect Associate, CKA, VMware VCP-DCV, Cisco CCNA, ITIL v4, CompTIA
  - Live search and vendor filter pills
- **Employer ATS PDF Export Modal**:
  - Section-by-section customization (Summary, Experience, Skills, Certifications, Credentials, References)
  - One-click PDF generation via `html2pdf.js`
  - Clean `@media print` fallback for browser printing
- **Pure Native Web Technologies**:
  - Zero heavy framework overhead (No React/Vue/Node build step required)
  - Instant load time (< 0.5s)
  - Mobile-responsive (Fluid typography, collapsible navigation)
  - SEO & ATS optimized with OpenGraph, Twitter Cards, and Schema.org JSON-LD

---

## 🚀 How to Publish to the Web (100% Free)

You can publish this portfolio to the web in less than 2 minutes using any of the free hosting platforms below:

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on [GitHub](https://github.com/new) named `myporfolio` (or `<your-username>.github.io`).
2. In your terminal inside this folder, run:
   ```bash
   git init
   git add .
   git commit -m "Launch Romar Gellamucho Portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/myporfolio.git
   git push -u origin main
   ```
3. Go to your GitHub repository **Settings** → **Pages**:
   - Under **Build and deployment** → **Source**, select **GitHub Actions** (the automated workflow in `.github/workflows/deploy.yml` will handle the rest).
   - Or select **Deploy from a branch** → choose `main` / `root` and click **Save**.
4. Your website will be live at:  
   `https://<your-username>.github.io/myporfolio/`

---

### Option 2: Netlify (Drag-and-Drop — 30 Seconds)

1. Visit [app.netlify.com/drop](https://app.netlify.com/drop) (login or sign up for free).
2. Drag and drop this entire `myporfolio` folder into the Netlify drop zone.
3. Your site is instantly live with a free SSL certificate! You can customize your site name (e.g. `romargellamucho.netlify.app`) or attach a custom domain.

---

### Option 3: Vercel

1. Install the Vercel CLI or visit [vercel.com](https://vercel.com).
2. Run in terminal:
   ```bash
   npx vercel
   ```
3. Follow the on-screen prompts (accept default settings for static HTML).
4. Instant live URL generated.

---

### Option 4: Cloudflare Pages

1. Go to [dash.cloudflare.com](https://dash.cloudflare.com) → **Workers & Pages** → **Create application** → **Pages**.
2. Connect your GitHub repository.
3. Build command: *(leave empty)*, Output directory: *(leave empty or `.`)
4. Deploy!

---

## 🛠 Local Testing

To preview locally on your computer:
- Double-click `index.html` to open it in any web browser, or:
- Run a lightweight local server:
  ```bash
  python -m http.server 8000
  ```
- Open `http://localhost:8000` in your browser.

---

## 📄 File Structure

```
myporfolio/
├── index.html            # Complete responsive portfolio & interactive web application
├── photo.jpg             # High-resolution professional portrait
├── robots.txt            # Search engine crawler instructions
├── sitemap.xml           # SEO sitemap
├── .github/
│   └── workflows/
│       └── deploy.yml    # Automatic GitHub Pages CI/CD workflow
└── README.md             # Documentation and deployment guide
```

---

&copy; 2026 Romar A. Gellamucho. All rights reserved.
