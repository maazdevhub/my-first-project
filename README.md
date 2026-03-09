# 🎨 Maaz - Professional Portfolio Website

A modern, responsive, and fully functional portfolio website for graphic designers and web developers.

## ✨ Features

- **Light Theme** - Clean, professional, and easy to read
- **Fully Responsive** - Perfect on mobile, tablet, and desktop
- **Smooth Animations** - Elegant transitions and hover effects
- **Contact Form** - Integrated with FormSubmit service
- **Project Pages** - Detailed showcase of 3 different projects
- **Social Links** - Instagram, Facebook, X, WhatsApp, Email
- **SEO Optimized** - Proper meta tags and semantic HTML
- **Fast & Lightweight** - Pure HTML/CSS, no heavy dependencies
- **Mobile Friendly** - Touch-optimized navigation and buttons

## 📁 Files Included

```
portfolio/
├── index.html           ← Main portfolio page
├── project1.html        ← Portfolio Website project
├── project2.html        ← Social Media Templates project
├── project3.html        ← UI/UX Redesign project
├── thankyou.html        ← Form submission thank you page
└── README.md            ← This file
```

## 🚀 Quick Start

### Local Testing (Before Upload)

1. **Download all files** to a folder called `portfolio`
2. **Open `index.html`** in your web browser
3. **Click around** to test all buttons and links
4. Everything works locally except email form submission

### Deploy to GitHub Pages

#### Step 1: Create GitHub Repository
- Go to [github.com/new](https://github.com/new)
- Repository name: `portfolio`
- Choose "Public"
- Click "Create repository"

#### Step 2: Upload Files
- Click "Add file" → "Upload files"
- Select all 6 files from your computer
- Drag and drop them into GitHub
- Write commit message: "Add portfolio website"
- Click "Commit changes"

#### Step 3: Enable GitHub Pages
- Go to repository **Settings**
- Scroll to **"Pages"** section
- Source: select **"main"** branch
- Click **Save**

#### Step 4: Your Website is Live! 🎉
- Visit: `https://yourusername.github.io/portfolio/`
- Share the link everywhere!

---

## ⚙️ Customization Guide

### 1. Change Your Name & Intro
**File:** `index.html`  
**Find:** Line 244-246
```html
<h1>Muhammad Maaz</h1>
<p class="tagline">Graphic Designer & Web Developer</p>
<p class="subtitle">Creating beautiful designs & interactive experiences from Pakistan</p>
```

### 2. Update Contact Email
**File:** `index.html`  
**Find:** Line 736
```html
<form action="https://formsubmit.co/maaziqbal0987@gmail.com" method="POST">
```
Replace `maaziqbal0987@gmail.com` with your email

### 3. Update Social Media Links
**File:** `index.html`  
**Find:** Lines 768-782
```html
<a href="https://www.instagram.com/maaz_0951?igsh=ZGE4bXZ3MmNqYW00">Instagram</a>
<a href="https://www.facebook.com/share/1DPFhnjSM6/">Facebook</a>
<a href="https://x.com/MaazI43228">X</a>
<a href="https://wa.me/923142037831">WhatsApp</a>
<a href="mailto:maaziqbal0987@gmail.com">Email</a>
```

Update all URLs with your own social media profiles.

### 4. Customize About Section
**File:** `index.html`  
**Find:** Lines 259-262
```html
<p>Hi! I'm Muhammad Maaz Iqbal, a graphic designer and web developer...</p>
```

Write your own about text here.

### 5. Update Skills
**File:** `index.html`  
**Find:** Lines 270-293

Edit each skill card with your actual skills and tools.

### 6. Update Projects
**File:** `index.html`  
**Find:** Lines 299-326

Update project titles, descriptions, and tags.

### 7. Customize Colors
**File:** All HTML files  
**Find:** The `:root` CSS variables section (usually near the top)
```css
:root {
  --accent-orange: #ff6b35;    /* Main color */
  --bg-light: #f5f1ed;         /* Background */
  --text-dark: #1a1a1a;        /* Text color */
}
```

Change these hex colors to match your brand!

---

## 🔧 FormSubmit Setup (Important!)

Your contact form uses **FormSubmit** - a free service that sends emails without a backend.

### First Time Setup:
1. User fills out contact form on your website
2. Form tries to submit
3. **You'll receive an email** from FormSubmit asking to confirm
4. **Click the confirmation link** in that email
5. Now form submissions work perfectly! ✅

**Note:** Without confirming, form won't send. Do this once and you're done!

---

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS & Android)

---

## 🎯 All Buttons & Links

### Header Buttons
- **"View My Work"** → Scrolls to projects section
- **"Let's Talk"** → Scrolls to contact section

### Navigation
- **About** → About section
- **Skills** → Skills section
- **Work** → Projects section
- **Contact** → Contact form

### Project Buttons
- **Project 1** → project1.html
- **Project 2** → project2.html
- **Project 3** → project3.html

### Contact Section
- **Send Message** → Submits form, redirects to thankyou.html
- **Social Links** → Opens Instagram, Facebook, X, WhatsApp, Email

### Project Pages
- **Back to Portfolio** → Returns to index.html
- **Get In Touch** → Links to contact form

---

## 📊 Website Structure

```
index.html (Main Page)
├── Navigation
│   ├── About
│   ├── Skills
│   ├── Work
│   └── Contact
├── Header
│   ├── View My Work (→ #projects)
│   └── Let's Talk (→ #contact)
├── About Section
├── Skills Section (6 skills)
├── Projects Section
│   ├── Project 1 (→ project1.html)
│   ├── Project 2 (→ project2.html)
│   └── Project 3 (→ project3.html)
└── Contact Section
    ├── Contact Form (→ thankyou.html)
    └── Social Links (5 platforms)

project1.html, project2.html, project3.html
├── Navigation (Back to index.html)
├── Project Details
├── Content Sections
└── CTA (Get In Touch → #contact)

thankyou.html
└── Thank You Message
    ├── Back to Portfolio (→ index.html)
    └── Auto-redirect (5 seconds)
```

---

## 🔐 Security & Privacy

- ✅ **No backend server** - Only static HTML/CSS
- ✅ **No database** - Your data is safe
- ✅ **FormSubmit handles emails** - Professional service
- ✅ **No tracking** - Pure content delivery

---

## 💡 Tips & Tricks

### Add More Projects
1. Duplicate `project1.html`
2. Save as `project4.html`
3. Update content
4. Add button in `index.html` projects section linking to `project4.html`

### Change Theme Colors
All colors are in the `:root` CSS variables - change them once and update everywhere!

### Faster Loading
- Images compressed automatically by browser
- No heavy JavaScript frameworks
- Pure HTML/CSS = blazing fast ⚡

### SEO Improvements
- Update meta descriptions in each file
- Add your real name and skills
- Use keywords in project descriptions
- Add schema markup (advanced)

---

## 🐛 Troubleshooting

### Form Not Submitting
- Check email is correct in `index.html`
- Check confirmation email from FormSubmit
- Confirm the activation link

### Website Not Showing
- Check GitHub Pages is enabled (Settings → Pages)
- Wait 2-5 minutes for deployment
- Check repository is public
- Clear browser cache (Ctrl+Shift+Delete)

### Links Not Working
- Check file names match exactly (case-sensitive)
- Verify links use correct file paths
- Check no extra spaces in URLs

### Styling Looks Off
- Clear browser cache
- Try different browser
- Check CSS variables are correct
- Make sure all files are in same folder

---

## 📈 Next Steps

1. ✅ Customize with your information
2. ✅ Test locally in browser
3. ✅ Upload to GitHub
4. ✅ Enable GitHub Pages
5. ✅ Share your portfolio URL
6. ✅ Keep updating with new projects!

---

## 🎓 Learning Resources

- [HTML Basics](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Guide](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [GitHub Pages Documentation](https://pages.github.com/)
- [FormSubmit Documentation](https://formsubmit.co/)

---

## 📞 Support

For issues:
1. Check this README first
2. Review HTML/CSS in your files
3. Check browser console for errors
4. Test in different browser

---

## 📄 License

This template is free to use and modify for your portfolio. No attribution required!

---

## 🙌 Ready to Go!

Your professional portfolio is complete and ready to impress! 

**Share it with:**
- ✅ LinkedIn
- ✅ Twitter/X
- ✅ Job applications
- ✅ Email signature
- ✅ Business cards

Good luck with your portfolio! 🚀

---

**Created:** 2026  
**Last Updated:** 2026  
**Version:** 1.0
