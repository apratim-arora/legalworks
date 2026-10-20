# Talent LegalWorks – Complete Static Website

Ready-to-deploy single-page site for Cloudflare Pages.

**Email:** talentlegalworks@gmail.com  
**Contact form:** Tally form (https://tally.so/r/RWGK7v) already embedded

---

## Folder contents
```
talent-legalworks/
├── index.html          ← main page (form + email already updated)
├── css/styles.css
├── js/main.js
├── assets/
│   ├── logo.svg
│   ├── hero-bg.jpg
│   ├── about-team.jpg
│   ├── service-translate.jpg
│   ├── service-proofread.jpg
│   ├── service-draft.jpg
│   └── service-compliance.jpg
└── README.md
```

---

## How to deploy on Cloudflare Pages (simplest way)

### Option A – Direct Upload (fastest, no Git needed)
1. Zip the entire `talent-legalworks` folder.
2. Go to https://dash.cloudflare.com → **Workers & Pages**.
3. Click **Create** → **Pages** → **Upload assets**.
4. Project name: `talentlegalworks` (recommended).
5. Drag & drop the unzipped folder contents (or the zip).
6. Click **Deploy site**.
7. Live URL will be:  
   **https://talentlegalworks.pages.dev**

### Option B – Connect GitHub (better for future edits)
1. Create a new GitHub repository and upload all files from this folder.
2. Cloudflare Pages → Create → Connect to Git → select the repo.
3. Framework preset: None / empty.  
   Build command: leave blank.  
   Output directory: leave blank or `/`.
4. Deploy.

---

## What’s already done
- Modern clean design with parallax hero
- All four services listed
- About section with your dual-team story (retired professionals + young graduates)
- Tally contact form fully embedded
- Email links set to talentlegalworks@gmail.com
- Mobile responsive + smooth animations

## Replacing images
Just put a new file in `assets/` with the same name (any extension: .jpg / .png / .webp works). The site will load it automatically.

That’s it — zip and upload!
