# Davonte Lynton — Portfolio Site

> **Live Site:** [https://The-Code-Labz.github.io](https://The-Code-Labz.github.io)

A clean, professional portfolio website built with [Hugo](https://gohugo.io/) and the [hugo-profile](https://github.com/gurusabarish/hugo-profile) theme. Automatically deployed to GitHub Pages via GitHub Actions on every push to `main`.

---

## 👤 About This Portfolio

This site serves as an online resume and professional presence for **Davonte Lynton**, a Medical Records & Customer Service Specialist based in Las Vegas, NV.

It highlights:
- 3+ years of HIPAA-compliant medical records experience
- Multi-platform CRM proficiency (Salesforce, Zendesk)
- High-speed data entry (75+ WPM, 99%+ accuracy)
- Professional history across healthcare and customer service roles

---

## 🗂 Site Sections

| Section | Description |
|---|---|
| **Hero** | Name, title, contact links, and profile photo |
| **About Me** | Professional summary and core skills list |
| **Experience** | Work history timeline (Datafied → Amazon → Walgreens → CVS) |
| **Education** | GED, HIPAA Training, CPR & First Aid certification |
| **Achievements** | Key career highlights with descriptive images |
| **Contact** | Direct email button |

---

## 🛠 Tech Stack

| Tool | Purpose |
|---|---|
| [Hugo](https://gohugo.io/) | Static site generator |
| [hugo-profile](https://github.com/gurusabarish/hugo-profile) | Resume-focused theme |
| [GitHub Pages](https://pages.github.com/) | Free hosting |
| [GitHub Actions](https://github.com/features/actions) | Auto-deploy on push |

---

## 📁 Project Structure

```
/
├── hugo.yaml              # All site content and configuration
├── themes/
│   └── hugo-profile/      # Theme files (do not edit directly)
├── layouts/
│   └── partials/          # Local overrides for theme compatibility
├── static/                # Static assets (images, favicon)
└── .github/
    └── workflows/
        └── hugo.yml       # GitHub Actions deployment workflow
```

---

## ✏️ How to Update Content

All content lives in a single file: **`hugo.yaml`**

### Update your job experience
Find the `experience:` section and edit the relevant `job`, `company`, `date`, and `content` fields.

### Add a new certification
Go to the `education:` section and add a new item block:
```yaml
- title: "Your Certification Name"
  school:
    name: "Issuing Organization"
    url: ""
  date: "2025"
  content: "Brief description."
```

### Change your profile photo
Update the `image:` field under both `hero:` and `about:` with a new image URL.

### Update contact info
Edit the `email:` field under `contact:` and the `url:` values under `socialLinks:`.

---

## 🚀 Deployment

Every push to the `main` branch automatically triggers a GitHub Actions build. The site rebuilds and goes live within **2–3 minutes**.

No manual build steps are required.

---

## 📬 Contact

**Davonte Lynton**
- Email: [dlynton01@gmail.com](mailto:dlynton01@gmail.com)
- Phone: (714) 631-7304
- GitHub: [github.com/The-Code-Labz](https://github.com/The-Code-Labz)
