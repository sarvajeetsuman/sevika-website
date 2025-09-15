# 🚀 Deploy Sevika HMS Website to GitHub Pages

## Quick Deployment Guide

### Step 1: Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name: `sevika-website` or `sevika-hms-website`
4. Make it **Public** (required for free GitHub Pages)
5. Click "Create repository"

### Step 2: Upload Website Files
```bash
# Option A: Using Git (if you have Git installed)
git init
git add .
git commit -m "Initial Sevika HMS website"
git branch -M main
git remote add origin https://github.com/yourusername/sevika-website.git
git push -u origin main

# Option B: Using GitHub Web Interface
# 1. Click "uploading an existing file"
# 2. Drag all website files to the upload area
# 3. Commit changes
```

### Step 3: Enable GitHub Pages
1. Go to repository **Settings**
2. Scroll to **Pages** section
3. Source: **Deploy from a branch**
4. Branch: **main** (or master)
5. Folder: **/ (root)**
6. Click **Save**

### Step 4: Get Your Privacy Policy URL
Your website will be available at:
```
https://yourusername.github.io/sevika-website/
```

**Privacy Policy URL for Google Play Store:**
```
https://yourusername.github.io/sevika-website/privacy.html
```

### Step 5: Update Google Play Console
1. Go to **Policy → App content → Privacy Policy**
2. Enter your privacy policy URL
3. Save changes
4. Upload your updated AAB with version code 2

## Alternative: Netlify (Even Easier)

### Quick Netlify Deployment
1. Go to [Netlify.com](https://netlify.com)
2. Sign up for free account
3. Drag your `sevika-website` folder to Netlify
4. Get instant URL like: `https://amazing-site-name.netlify.app`
5. Privacy Policy URL: `https://amazing-site-name.netlify.app/privacy.html`

## Custom Domain (Optional)
If you own `sevika.online`:
1. Add CNAME record: `www` → `yourusername.github.io`
2. In GitHub Pages settings, add custom domain: `sevika.online`
3. Privacy Policy URL becomes: `https://sevika.online/privacy.html`

## ✅ Verification Checklist
- [ ] Website loads correctly
- [ ] Privacy policy page accessible
- [ ] All links work
- [ ] Mobile responsive
- [ ] Contact information updated
- [ ] Privacy policy URL added to Play Store

**Your Sevika HMS website is ready for the world! 🌍**
