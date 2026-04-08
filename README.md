# Dev. Nayeem Sheikh — Portfolio

Professional Python Developer portfolio website.
**Live on Vercel** — Dark & Neon theme.

---

## 🚀 Deploy to Vercel (3 Steps)

### Option A — GitHub (Recommended)
1. Create a GitHub account if you don't have one
2. Create a new repository: github.com → New → name it `nayeem-portfolio`
3. Upload ALL files from this folder to the repo
4. Go to **vercel.com** → Sign up with GitHub → **New Project**
5. Select your `nayeem-portfolio` repo → click **Deploy**
6. Done! Your site is live at `your-project.vercel.app`

### Option B — Vercel CLI
```bash
npm install -g vercel
cd nayeem-portfolio
vercel
```
Follow the prompts. Done!

---

## ✏️ CUSTOMIZE YOUR INFO

Search for `CUSTOMIZE:` in `index.html` to find all editable spots.

| What | Where in index.html |
|---|---|
| **Your photo** | Find `ring-placeholder` → delete it → uncomment `<img>` tag |
| **Email** | Replace all `your@email.com` |
| **WhatsApp** | Replace `8801XXXXXXXXX` with your number |
| **Telegram** | Replace `@yourusername` |
| **GitHub** | Replace `github.com/yourusername` |
| **LinkedIn** | Replace `linkedin.com/in/yourusername` |
| **Facebook** | Replace `facebook.com/yourusername` |
| **YouTube** | Replace `youtube.com/@yourusername` |
| **Fiverr** | Replace `fiverr.com/yourusername` |
| **Upwork** | Replace `upwork.com/yourusername` |
| **Stats** | Find `hero-stats` section |
| **CV file** | Put your `cv.pdf` in this folder |
| **Projects** | Find `proj-grid` section |

---

## 📸 Adding Your Photo

1. Put your photo file in this folder (e.g. `photo.jpg`)
2. Open `index.html`
3. Find this block:
   ```html
   <div class="ring-placeholder">...</div>
   <!-- <img src="photo.jpg" alt="Nayeem Sheikh" /> -->
   ```
4. DELETE the `ring-placeholder` div
5. UNCOMMENT the `<img>` line (remove `<!--` and `-->`)

---

## 📧 Formspree (Real Email from Contact Form)

1. Go to **formspree.io** → Free signup
2. Create a new form → copy the Form ID (looks like `xpwzabcd`)
3. In `index.html`, find the Formspree comment block in the JS
4. Uncomment it and replace `YOUR_FORM_ID` with your actual ID

---

## 📁 File Structure

```
nayeem-portfolio/
├── index.html        ← Main website (edit this)
├── vercel.json       ← Vercel config
├── vite.config.js    ← Build config
├── package.json      ← Dependencies
├── README.md         ← This file
└── public/           ← Put photo.jpg and cv.pdf here
    └── (empty)
```

---

Built with ♥ by Dev. Nayeem Sheikh | Bangladesh
