# 💍 Santh & Raji — Wedding Invitation Website

## 🌐 Deploy to Vercel (Step-by-Step)

### Option 1: Drag & Drop (Easiest — No coding needed)

1. Go to **https://vercel.com** and sign up / log in (free)
2. From your dashboard, click **"Add New → Project"**
3. Click **"Upload"** or drag-and-drop the entire `wedding-santh-raji` folder
4. Click **"Deploy"**
5. Your site will be live at something like: `https://santh-raji-wedding.vercel.app` 🎉

---

### Option 2: GitHub + Vercel (Recommended for updates)

1. Create a free account at **https://github.com**
2. Create a new repository called `santh-raji-wedding`
3. Upload the files (`index.html`, `vercel.json`) to the repo
4. Go to **https://vercel.com**, click **"Add New → Project"**
5. Connect your GitHub account and select the `santh-raji-wedding` repo
6. Click **"Deploy"**
7. Every time you update the file on GitHub, the website auto-updates!

---

### Option 3: Vercel CLI

```bash
npm install -g vercel
cd wedding-santh-raji
vercel
```

---

## 📧 RSVP Email Setup (Important!)

The RSVP form uses **Formspree** to send responses to `nirmalraj@dbcyelagiri.edu.in`.

To activate it:
1. Go to **https://formspree.io** and sign up (free)
2. Create a new form → set email to `nirmalraj@dbcyelagiri.edu.in`
3. Copy your form ID (looks like `xkgweqpb`)
4. In `index.html`, find this line:
   ```
   action="https://formspree.io/f/xkgweqpb"
   ```
5. Replace `xkgweqpb` with your actual Formspree form ID
6. You're done! All RSVP submissions will be emailed to you.

---

## 📸 Adding Real Couple Photos

To replace the illustrated avatars with real photos:

1. Upload photos to the same folder (e.g., `groom.jpg`, `bride.jpg`)
2. In `index.html`, find the `<div class="photo-avatar photo-avatar-groom">` section
3. Replace the `<svg>...</svg>` inside with:
   ```html
   <img src="groom.jpg" style="width:100%;height:100%;object-fit:cover;">
   ```
4. Do the same for the bride's frame

---

## 📅 Wedding Details
- **Reception:** Saturday, 11th April 2026 — 6:00 PM — RVK Mahal, Polur
- **Wedding:** Sunday, 12th April 2026 — 6:00 AM — RVK Mahal, Polur
- **Venue:** RVK Mahal, Polur, Thiruvannamalai District, Tamil Nadu
- **RSVP to:** nirmalraj@dbcyelagiri.edu.in
