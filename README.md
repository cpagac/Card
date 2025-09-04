# 💼 Digital Business Card

A modern, responsive digital business card built with pure HTML, CSS, and JavaScript. Perfect for networking, sharing contact information, and creating a professional online presence.

## ✨ Features

- **🎨 Modern Design** - Clean, professional layout with gradient backgrounds and smooth animations
- **📱 Fully Responsive** - Looks great on desktop, tablet, and mobile devices
- **🔗 Interactive Links** - Direct links to email, website, LinkedIn, and GitHub
- **📄 vCard Download** - One-click contact saving to address books
- **📋 Resume Download** - Easy access to PDF resume
- **⚡ Fast Loading** - Pure HTML/CSS/JS with no external dependencies
- **🎯 SEO Friendly** - Optimized meta tags and semantic HTML

## 🚀 Live Demo

Visit the live demo at: [card.colemanpagac.com](https://card.colemanpagac.com)

## 🛠 Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with flexbox, gradients, and animations
- **JavaScript** - vCard generation and download functionality
- **Google Fonts** - Inter font family for typography

## 📁 Project Structure

```
digital-business-card/
├── index.html              # Main HTML file
├── Coleman_Pagac_Resume.pdf # Resume file (add your own)
├── README.md               # This file
└── preview.png            # Screenshot for documentation
```

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/digital-business-card.git
   cd digital-business-card
   ```

2. **Add your resume**
   - Replace `Coleman_Pagac_Resume.pdf` with your own resume file
   - Keep the same filename or update the link in the HTML

3. **Deploy**
   - Upload to any web hosting service
   - Works with GitHub Pages, Netlify, Vercel, or traditional hosting

## 🎨 Customization

### Personal Information
Update the following sections in `index.html`:

```html
<!-- Name and titles -->
<h1 class="name">Your Name</h1>
<div class="title">Your Title</div>
<div class="subtitle">Your Specialties</div>

<!-- Contact links -->
<a href="mailto:your-email@domain.com">
<a href="https://yourwebsite.com">
<a href="https://linkedin.com/in/yourprofile">
<a href="https://github.com/yourusername">
```

### Colors and Styling
Modify CSS variables in the `<style>` section:

```css
/* Main gradient colors */
background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 50%, #6c757d 100%);

/* Card header gradient */
background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 30%, #6c757d 60%, #343a40 90%, #1e2124 100%);
```

### vCard Information
Update the vCard data in the JavaScript section:

```javascript
const vCardData = `BEGIN:VCARD
VERSION:3.0
FN:Your Full Name
N:LastName;FirstName;;;
ORG:Your Company
TITLE:Your Job Title
EMAIL;TYPE=INTERNET;TYPE=HOME:your-email@domain.com
URL:https://yourwebsite.com
URL;TYPE=LinkedIn:https://linkedin.com/in/yourprofile
URL;TYPE=GitHub:https://github.com/yourusername
END:VCARD`;
```

## 🌐 Subdomain Suggestions

Popular subdomain options for hosting:
- `card.yourdomain.com`
- `me.yourdomain.com` 
- `about.yourdomain.com`
- `contact.yourdomain.com`
- `bio.yourdomain.com`

## 📱 Mobile Optimization

The card is fully responsive and includes:
- Touch-friendly button sizes
- Optimized typography scaling
- Proper viewport configuration
- Mobile-specific hover states

## 🔧 Browser Compatibility

- ✅ Chrome/Chromium 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance

- **Lightweight** - Single HTML file under 10KB
- **Fast Loading** - No external dependencies except Google Fonts
- **Optimized Images** - SVG icons for crisp display at any size
- **Efficient CSS** - Minimal, optimized stylesheets

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Design inspired by modern business card layouts
- Icons from Google Material Design
- Typography using Google Fonts (Inter)

## 📧 Contact

Coleman Pagac - [contact@colemanpagac.com](mailto:contact@colemanpagac.com)

Project Link: [https://github.com/cpagac/digital-business-card](https://github.com/cpagac/digital-business-card)

---

⭐ **If this helped you create an awesome digital business card, please give it a star!**