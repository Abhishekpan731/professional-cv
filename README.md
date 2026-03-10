# Abhishek Pandey - Professional CV Website

A modern, responsive HTML CV/Resume website optimized for personal hosting and professional presentation.

## 🌟 Features

- **Single-Page Design**: All content in one clean, scrollable page
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Print-Friendly**: Special CSS styles for professional printing
- **SEO Optimized**: Meta tags for search engine visibility
- **Fast Loading**: No external dependencies, all CSS embedded
- **ATS-Compatible Content**: Maintains keyword-rich content from original CV
- **Modern Design**: Professional color scheme with gradient header
- **Accessible**: Semantic HTML5 structure

## 📁 Files

- `index.html` - Main CV webpage (ready to deploy)
- `README.md` - This file with deployment instructions

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. **Create a GitHub Repository**
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit: Professional CV website"
   ```

2. **Push to GitHub**
   ```bash
   # Create a new repository on GitHub first, then:
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **main** branch
   - Click **Save**
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Option 2: Netlify (Free, Easy Drag & Drop)

1. Go to [netlify.com](https://www.netlify.com/)
2. Sign up for a free account
3. Drag and drop your `index.html` file to the Netlify dashboard
4. Your site will be live instantly with a URL like: `https://random-name.netlify.app`
5. **Optional**: Configure custom domain in Site Settings

### Option 3: Vercel (Free, Fast Deployment)

1. Install Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Follow the prompts, and your site will be live at: `https://your-project.vercel.app`

### Option 4: Traditional Web Hosting

1. Upload `index.html` to your web hosting provider via FTP/SFTP
2. Place it in the `public_html` or `www` directory
3. Access via your domain: `https://yourdomain.com/index.html`

## 🎨 Customization

### Update Contact Information
Edit the header section in `index.html`:
```html
<div class="contact-info">
    <span>📍 Your Location</span>
    <span>📱 Your Phone</span>
    <a href="mailto:your.email@example.com">✉️ your.email@example.com</a>
    <a href="https://linkedin.com/in/yourprofile">🔗 linkedin.com/in/yourprofile</a>
</div>
```

### Change Color Scheme
Modify CSS variables in the `<style>` section:
```css
:root {
    --primary-color: #2E75B6;      /* Main blue color */
    --secondary-color: #1F3864;    /* Dark blue */
    --accent-color: #0066cc;       /* Accent color */
}
```

### Add/Remove Sections
Each section is wrapped in `<section>` tags. You can:
- Reorder sections by moving the entire `<section>` block
- Remove sections by deleting the `<section>` block
- Add new sections following the existing structure

## 📱 Responsive Breakpoints

- **Desktop**: > 768px (full layout)
- **Tablet**: 481px - 768px (adjusted spacing)
- **Mobile**: ≤ 480px (single column, compact)

## 🖨️ Printing

The CV includes print-optimized styles. To print:
1. Open the webpage in a browser
2. Press `Ctrl+P` (Windows) or `Cmd+P` (Mac)
3. Select "Save as PDF" or print directly
4. The print version automatically adjusts colors and layout

## 🔍 SEO Features

- Descriptive title tag with keywords
- Meta description for search results
- Open Graph tags for social media sharing
- Semantic HTML structure
- Keyword-rich content with proper heading hierarchy

## 📊 Performance

- **No external dependencies**: All CSS is embedded
- **Fast loading**: Single HTML file, minimal size
- **Optimized images**: Uses emoji icons (no image files)
- **Mobile-first**: Responsive design for all devices

## 🛠️ Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **No JavaScript**: Pure HTML/CSS for maximum compatibility
- **No frameworks**: Lightweight and fast

## 📝 License

This CV template is free to use for personal purposes.

## 🤝 Support

For issues or questions:
- Email: abhishekbit731@gmail.com
- LinkedIn: [linkedin.com/in/abhishekbit96](https://www.linkedin.com/in/abhishekbit96/)

---

**Last Updated**: March 2026

