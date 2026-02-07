# Vylos AI Support Site - Deployment Guide

## Files Created
- `index.html` - Main support page
- `privacy-policy.html` - Privacy policy page
- `DEPLOY.md` - This file

## Deploy to GitHub Pages (FREE Hosting)

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: **vylos-ai.github.io**
   - (The `.github.io` part is important!)
3. Make it **Public**
4. Click **Create repository**

### Step 2: Upload Files
1. In your new repo, click **"uploading an existing file"**
2. Drag and drop these files:
   - `index.html`
   - `privacy-policy.html`
3. Scroll down, add commit message: "Initial commit"
4. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. In your repo, go to **Settings** tab
2. Scroll down to **Pages** section (left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Select **main** branch, folder **/(root)**
5. Click **Save**

### Step 4: Wait & Get Your URL
- GitHub will build your site (takes 1-5 minutes)
- Your URL will be: **https://vylos-ai.github.io**

### Step 5: Test
- Visit https://vylos-ai.github.io in your browser
- Should see your support page
- Click Privacy Policy link to verify it works

## For App Store Connect

**Support URL to enter:**
```
https://vylos-ai.github.io
```

## Custom Domain (Optional)

If you want a custom domain later (like vylosai.com):
1. Buy domain from Namecheap/GoDaddy (~$12/year)
2. In GitHub Pages settings, add custom domain
3. Update DNS records
4. Your support URL becomes: https://vylosai.com

## Notes

- GitHub Pages is completely FREE
- Unlimited bandwidth
- SSL certificate included (HTTPS)
- Updates are instant (just push new files)

## Need to Update Content?

1. Go to your GitHub repo
2. Click on the file you want to edit
3. Click pencil icon (Edit)
4. Make changes
5. Scroll down, add commit message
6. Click **Commit changes**
7. Changes live in 1-2 minutes

---

**Your support site is ready to deploy!** 🚀
