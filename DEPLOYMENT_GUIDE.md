# Mazahir Sally – Civil Engineering Portfolio & Client Portal

Your client portal is now completely ready for production deployment.

## 📁 Project Structure

```text
company-site/
├── index.html            (Complete interactive single-page app)
├── netlify.toml          (Security headers, caching rules)
├── robots.txt            (SEO search engine indexing instructions)
├── sitemap.xml           (Search engine sitemap)
└── assets/
    └── mazahir-sally.jpg (Professional profile image)
```

---

## 🚀 Step 1: Connect Email Alerts (Free Formspree in 2 Minutes)

Both forms on the website (the 3-step Project Inquiry & Quick Message) are set up to dispatch requests directly to Formspree, with automatic WhatsApp failover.

1. Go to **[formspree.io](https://formspree.io)** and create a free account.
2. Click **+ New Form**, enter the name (e.g. `Mazahir Sally Inquiries`), and set the target notification email to `msmmazahir@gmail.com`.
3. Copy your unique Form ID (looks like `mwpkqvyo` or similar).
4. Open [`company-site/index.html`](file:///d:/Ayman%20Files/Dad%20Cv/company-site/index.html) and search for:
   ```javascript
   const FORMSPREE_ID = 'YOUR_FORMSPREE_ID';
   ```
   Replace `'YOUR_FORMSPREE_ID'` with your copied Form ID.

*(Note: Even before adding your Formspree ID, if anyone submits the form, it gracefully detects and redirects their structured inquiry straight to WhatsApp: `+94 777 802 855`)*

---

## 🌐 Step 2: Publish Online for Free with Netlify

### Option A: Drag & Drop (Zero installation required)
1. Visit **[app.netlify.com/drop](https://app.netlify.com/drop)**.
2. Drag and drop the whole `company-site` folder into the drop zone in your browser.
3. In under 15 seconds, Netlify will assign your website a live HTTPS URL (e.g., `https://mazahir-sally.netlify.app`).

### Option B: GitHub + Netlify (Continuous Deployment)
1. Push the `company-site` directory to a GitHub repository.
2. Link Netlify to your GitHub repo to have your site automatically update whenever you commit changes.

---

## 🎯 Step 3: Custom Domain (Optional)
In Netlify's **Domain Management** settings, you can attach any custom domain (e.g. `mazahirsally.lk` or `mazahirsally.com`) with automated free SSL certificates.
