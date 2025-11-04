# Portfolio GitHub Pages

A clean, modern portfolio page with links to your professional resources and social media profiles.

## 🚀 Quick Setup

### Option 1: Create a New Repository

1. Create a new repository on GitHub named `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
2. Upload the `index.html` file to the repository
3. Go to Settings → Pages
4. Under "Source", select the `main` branch
5. Your site will be live at `https://yourusername.github.io`

### Option 2: Use a Project Repository

1. Create a new repository with any name (e.g., `portfolio`)
2. Upload the `index.html` file to the repository
3. Go to Settings → Pages
4. Under "Source", select the `main` branch
5. Your site will be live at `https://yourusername.github.io/portfolio`

## ✏️ Customization

Edit the `index.html` file to personalize your portfolio:

### Update Your Information

1. **Profile Initial**: Change `MP` in the profile circle to your initials
2. **Name**: Replace "Your Name" with your actual name
3. **Subtitle**: Update "Developer | Designer | Creator" with your title/roles
4. **Links**: Update all placeholder URLs with your actual social media and website links:
   - GitHub: `https://github.com/yourusername`
   - LinkedIn: `https://linkedin.com/in/yourusername`
   - Twitter: `https://twitter.com/yourusername`
   - Email: `your.email@example.com`
   - Website: `https://yourwebsite.com`
   - Blog: `https://medium.com/@yourusername`

### Add or Remove Links

To add a new link, copy this template and paste it in the `.links` section:

```html
<a href="YOUR_URL_HERE" class="link-item" target="_blank" rel="noopener noreferrer">
    <span class="link-icon">🔗</span>
    <span class="link-text">Link Name</span>
    <span class="link-arrow">→</span>
</a>
```

Replace the emoji icon and text as needed. You can remove any links you don't need.

### Change Colors

The gradient colors can be customized in the CSS:
- Background gradient: Change `#667eea` and `#764ba2`
- Hover effects: Change `#667eea` in the `.link-item:hover` section

## 📱 Features

- ✅ Fully responsive design
- ✅ Modern gradient background
- ✅ Smooth hover animations
- ✅ Mobile-friendly
- ✅ No external dependencies
- ✅ Fast loading
- ✅ SEO-friendly

## 🌐 Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## 📄 License

Feel free to use this template for your own portfolio!

## 🤝 Contributing

This is a simple template, but feel free to fork and customize it to your needs!

---

Made with ❤️ for GitHub Pages
