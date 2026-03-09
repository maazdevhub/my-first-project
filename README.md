# 🎨 Maaz - Portfolio Website

A modern, clean, and professional portfolio website showcasing graphic design and web development work.

## ✨ Features

- **Clean Light Theme** - Easy to read with professional design
- **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- **Smooth Animations** - Subtle, elegant transitions and hover effects
- **Contact Form** - Integrated contact form with FormSubmit
- **Social Links** - Direct links to GitHub, LinkedIn, Instagram, and Email
- **SEO Optimized** - Meta tags and proper structure
- **Fast & Lightweight** - Pure HTML/CSS, no heavy dependencies

## 📁 Files

```
.
├── index.html          # Main portfolio page
├── thankyou.html       # Thank you page (form submission)
└── README.md           # This file
```

## 🚀 Quick Start

### Local Testing
1. Download all files to a folder
2. Open `index.html` in your browser
3. Everything will work locally (except form submission)

### GitHub Pages Deployment

1. **Create a GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it: `portfolio` (or any name you prefer)
   - Click "Create repository"

2. **Upload files to GitHub**
   - Click "Add file" → "Upload files"
   - Upload `index.html` and `thankyou.html`
   - Commit the files

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "GitHub Pages" section
   - Select "main" branch as source
   - Click Save

4. **Your website is live!**
   - Visit: `https://yourusername.github.io/portfolio/`

## ⚙️ Customization

### Update Your Information

Open `index.html` and find these lines to update:

**Line 203-204** - Your GitHub profile:
```html
<a href="https://github.com/yourusername" target="_blank">
```

**Line 205-206** - Your LinkedIn profile:
```html
<a href="https://linkedin.com/in/yourusername" target="_blank">
```

**Line 207-208** - Your Twitter/X profile:
```html
<a href="https://twitter.com/yourusername" target="_blank">
```

**Line 209-210** - Your Instagram profile:
```html
<a href="https://instagram.com/yourusername" target="_blank">
```

**Line 211-212** - Your Email address:
```html
<a href="mailto:maaziqbal0987@gmail.com">
```

### Update Contact Form Email

**Line 180** - Change email where form submissions go:
```html
<form action="https://formsubmit.co/your-email@gmail.com" method="POST">
```

**Line 197** - Update thank you page redirect URL:
```html
<input type="hidden" name="_next" value="https://yourusername.github.io/portfolio/thankyou.html">
```

### Customize Colors

Edit the CSS variables in `index.html` (around line 25):

```css
:root {
  --accent-orange: #ff6b35;    /* Main accent color */
  --bg-light: #f5f1ed;         /* Light background */
  --text-dark: #1a1a1a;        /* Text color */
  --text-muted: #666666;       /* Muted text */
}
```

### Update Projects

Find the "Featured Work" section (around line 320) and update:
- Project titles
- Descriptions
- Tags
- Links

Example:
```html
<div class="project-card">
  <h3>Your Project Name</h3>
  <p>Description of your project...</p>
  <div class="project-tags">
    <span class="tag">Tag1</span>
    <span class="tag">Tag2</span>
  </div>
  <button class="primary small">View Project →</button>
</div>
```

## 📧 Form Submission

The contact form uses [FormSubmit](https://formsubmit.co) - a free service that requires no backend.

**How it works:**
1. User fills out form
2. Message sent to your email
3. User redirected to thank you page
4. First submission needs email confirmation (one-time)

## 🎨 Design Highlights

- **Typography** - Outfit (headings) + Inter (body) for professional look
- **Color Palette** - Light cream background with orange accents
- **Spacing** - Generous padding and margins for clean look
- **Animations** - Smooth hover effects and page load animations
- **Mobile First** - Optimized for all screen sizes

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🔧 Technical Details

- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, animations
- **Vanilla JavaScript** - Minimal, for thank you page redirect
- **No Dependencies** - Pure frontend code
- **Fast** - All assets load instantly

## 💡 Tips

1. **Add a profile picture** - Add an image in the About section
2. **Update project links** - Make buttons link to actual projects
3. **Custom domain** - GitHub Pages supports custom domains
4. **Backup** - Keep a copy of files locally
5. **Update regularly** - Add new projects as you complete them

## 🐛 Troubleshooting

**Form not working?**
- Check email address is correct
- Check redirect URL is correct
- Confirm FormSubmit activation email

**Website not showing?**
- Check GitHub Pages is enabled
- Wait 2-5 minutes for deployment
- Check repository is public
- Check correct URL: `https://yourusername.github.io/portfolio/`

**Styling looks off?**
- Clear browser cache (Ctrl+Shift+Delete)
- Try different browser
- Check all CSS is loaded

## 📄 License

Free to use and modify for your portfolio. No attribution required.

## 🎯 Next Steps

1. ✅ Fork/download this repository
2. ✅ Update personal information
3. ✅ Upload to GitHub
4. ✅ Enable GitHub Pages
5. ✅ Share your portfolio URL
6. ✅ Keep updating with new projects

---

**Happy coding! 🚀**

For more help, visit [GitHub Pages Documentation](https://pages.github.com)
