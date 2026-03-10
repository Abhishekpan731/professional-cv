# 🚀 Deployment Guide - Professional CV Website

## Quick Start: Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. **Repository name:** `professional-cv`
3. **Description:** "Professional CV/Resume Website - Senior Software Developer"
4. **Visibility:** ✅ Public (required for free GitHub Pages)
5. **DO NOT** check "Initialize with README"
6. Click **"Create repository"**

### Step 2: Push Code to GitHub

```bash
# Add remote repository (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/professional-cv.git

# Push code
git branch -M main
git push -u origin main
```

**Authentication:** If prompted, use a Personal Access Token (Settings → Developer settings → Personal access tokens)

### Step 3: Enable GitHub Pages

1. Go to your repository: `https://github.com/YOUR_USERNAME/professional-cv`
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source":
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Live CV

Your CV will be available at:
```
https://YOUR_USERNAME.github.io/professional-cv/
```

---

## 📄 Generate PDF Version

### Method 1: Browser Print (Recommended)

#### Using Chrome/Edge:
1. Open `index.html` in browser
2. Press `Cmd + P` (Mac) or `Ctrl + P` (Windows)
3. **Destination:** Save as PDF
4. **Settings:**
   - Paper: A4
   - Margins: Default
   - Scale: 100%
   - Background graphics: ✅ Enabled
5. Save as: `Abhishek_Pandey_CV.pdf`

#### Using Safari:
1. Open `index.html` in Safari
2. Press `Cmd + P`
3. Click **PDF** dropdown (bottom left)
4. Select **Save as PDF**
5. Save as: `Abhishek_Pandey_CV.pdf`

### Method 2: Online Tools

1. Go to [html2pdf.com](https://html2pdf.com) or [pdfcrowd.com](https://pdfcrowd.com)
2. Upload `index.html`
3. Download the generated PDF

---

## 🔧 Troubleshooting

### Issue: Git push requires authentication

**Solution:** Create a Personal Access Token
1. GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Generate new token (classic)
3. Select scopes: `repo` (all)
4. Copy the token
5. Use token as password when pushing

### Issue: GitHub Pages not working

**Solution:**
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for deployment status
- Ensure repository is Public
- Verify branch is set to `main` and folder to `/`

### Issue: PDF looks different from browser

**Solution:**
- Ensure "Background graphics" is enabled
- Use Chrome/Edge for best results
- Check print preview before saving
- Try adjusting scale to 90-95% if content is cut off

---

## 📱 Share Your CV

Once deployed, share your CV using:

**Live Website:**
```
https://YOUR_USERNAME.github.io/professional-cv/
```

**LinkedIn:** Add to "Featured" section or "About"

**Email Signature:**
```
View my CV: https://YOUR_USERNAME.github.io/professional-cv/
```

**Job Applications:** Include both the live URL and PDF attachment

---

## 🔄 Update Your CV

To update your CV after deployment:

```bash
# Make changes to index.html
# Then commit and push

git add index.html
git commit -m "Update CV with new experience/certifications"
git push origin main
```

Changes will be live in 1-2 minutes!

---

## ✅ Checklist

- [ ] Created GitHub repository
- [ ] Pushed code to GitHub
- [ ] Enabled GitHub Pages
- [ ] Verified live URL works
- [ ] Generated PDF version
- [ ] Tested PDF formatting
- [ ] Updated LinkedIn with CV link
- [ ] Saved PDF for job applications

---

**Need Help?** Contact: abhishekbit731@gmail.com

