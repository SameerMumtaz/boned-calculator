# 🚗 Vehicle Cost of Ownership Calculator

A comprehensive web app to calculate the true cost of owning a vehicle, including depreciation, financing, lease comparison, and credit impact analysis.

## ✨ Features

- **Cost of Ownership Calculator** - Real depreciation curves, financing analysis, equity tracking
- **Lease Calculator** - Compare lease vs buy options
- **Credit Score Impact** - See how credit affects rates and total cost
- **Vehicle Comparison** - Compare up to 3 vehicles side-by-side
- **Smart Suggestions** - AI-powered lease recommendations based on your scenario
- **30 Brands, 475 Trims** - Real 2026 MSRP data from Edmunds
- **Mobile Optimized** - Works perfectly on phones, tablets, and desktop
- **Installable (PWA)** - Add to home screen like a native app

---

## 🚀 Quick Deploy to GitHub Pages (FREE)

### Step 1: Create GitHub Account
Go to [github.com](https://github.com) and sign up (free)

### Step 2: Create New Repository
1. Click the `+` icon (top right) → "New repository"
2. Name it: `car-calculator` (or whatever you want)
3. Make it **Public**
4. ✅ Check "Add a README file"
5. Click **Create repository**

### Step 3: Upload Files
1. Click **Add file** → **Upload files**
2. Drag these 3 files into the browser:
   - `Will-this-car-bone-me-v2.0.html`
   - `manifest.json`
   - `service-worker.js`
3. Rename `Will-this-car-bone-me-v2.0.html` to `index.html` (IMPORTANT!)
4. Click **Commit changes**

### Step 4: Enable GitHub Pages
1. Go to **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under "Source": Select **main** branch
4. Click **Save**
5. Wait 1-2 minutes

### Step 5: Done! 🎉
Your site will be live at:
```
https://your-username.github.io/car-calculator/
```

---

## 🌐 Alternative Hosting Options

### Netlify (Easiest - Drag & Drop)
1. Go to [netlify.com](https://netlify.com)
2. Sign up (free)
3. Drag the 3 files into the upload area
4. Done! Live in 30 seconds

### Vercel (Fast CDN)
1. Go to [vercel.com](https://vercel.com)
2. Sign up (free)
3. Click "New Project"
4. Upload files or connect GitHub repo
5. Deploy

### Cloudflare Pages (Free + Fast)
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Sign up (free)
3. Connect GitHub or upload files
4. Deploy

---

## 📱 PWA Features

### Install on iPhone
1. Open in Safari
2. Tap Share button (box with arrow)
3. Scroll down → "Add to Home Screen"
4. Tap "Add"
5. App icon appears on home screen!

### Install on Android
1. Open in Chrome
2. Tap menu (3 dots)
3. Tap "Install app" or "Add to Home screen"
4. App installed!

### Install on Desktop
1. Open in Chrome/Edge
2. Look for install icon (⊕) in address bar
3. Click it
4. App installed!

---

## 🛠️ Files Included

- `index.html` (rename from Will-this-car-bone-me-v2.0.html) - Main app
- `manifest.json` - PWA configuration
- `service-worker.js` - Offline support & caching

---

## 📊 Optional: Add Analytics

If you want to track usage (optional), add this before `</head>`:

```html
<!-- Google Analytics (Optional) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

Replace `G-XXXXXXXXXX` with your Google Analytics ID from [analytics.google.com](https://analytics.google.com)

---

## 🎯 Sharing Your Calculator

### Get People to Use It:

**Reddit:**
- r/personalfinance
- r/cars
- r/askcarsales
- r/whatcarshouldIbuy

**Social Media:**
- Twitter/X: Share with #CarBuying #PersonalFinance
- Facebook: Car enthusiast groups
- TikTok: Short demo videos

**SEO:**
- Wait 1-2 weeks for Google to index
- Share link in relevant forums
- Write a blog post about it

---

## 🔧 Updating Your Calculator

### GitHub Pages:
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make changes
5. Click "Commit changes"
6. Wait 1-2 minutes → live!

### Netlify/Vercel:
1. Upload new files
2. Instantly live!

---

## 💡 Tips for Success

✅ **Share the direct link** - Don't make people search for it
✅ **Demo with examples** - Show real scenarios (RAV4 vs Camry)
✅ **Explain the value** - "See if you're losing money on your car"
✅ **Keep it updated** - Fix bugs quickly, add features based on feedback
✅ **Make it your own** - Add your name/brand if you want credit

---

## 📝 License

Free to use for educational purposes. Help people make better financial decisions! 🚗💰

---

## 🆘 Need Help?

**Common Issues:**

**"Page not found"**
- Did you rename file to `index.html`?
- Did you enable GitHub Pages in Settings?
- Wait 2-3 minutes after deploying

**"Manifest 404 error"**
- Make sure `manifest.json` is in same folder as `index.html`

**"Not installable"**
- Must be served over HTTPS (GitHub Pages does this automatically)
- Clear browser cache and try again

---

## 🎉 You're Done!

Your calculator is now live and helping people make smarter car buying decisions.

Share it, get feedback, iterate, and watch it help thousands of people! 🚀
