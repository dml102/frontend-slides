# 📄 Resume Maker

Create beautiful, professional HTML resumes in minutes — no design skills required.

Choose from 3 stunning design styles, customize your information, and download as HTML or PDF.

---

## ✨ Features

✅ **3 Professional Design Styles**
- Professional Blue — Corporate, formal, traditional
- Creative Colorful — Modern, playful, designer-friendly
- Modern Dark — Tech-forward, minimalist, hacker aesthetic

✅ **Easy Editing**
- Beautiful form interface
- Add/remove work experience entries
- Add/remove skills
- All changes reflected instantly

✅ **No Dependencies**
- Single HTML file
- Works offline
- No installation needed
- No build tools required

✅ **Export Options**
- Download as HTML (ready to share or customize)
- Download as PDF (for printing or email)
- Browser localStorage saves your work

✅ **Fully Responsive**
- Desktop, tablet, mobile optimized
- Print-friendly styling
- Looks great on any screen

---

## 🚀 Quick Start

### 1. Open the Resume
```bash
# Simply open resume.html in your browser
# No setup needed!
open resume.html
```

Or drag the file into your browser window.

### 2. Choose a Style
Click one of the three style buttons at the top:
- **Professional Blue** — For corporate/formal roles
- **Creative Colorful** — For creative/design roles
- **Modern Dark** — For tech/startup roles

Your choice is automatically saved!

### 3. Edit Your Info
Click the **✏️ Edit** button to:
- Enter your name, email, phone
- Write a professional summary
- Add work experience (company, title, dates, description)
- List your skills
- Click **Save Changes**

### 4. Download
When you're ready:
- **📥 Download PDF** — Prints to PDF for email/printing
- **💾 Download HTML** — Saves as standalone HTML file you can share or customize

---

## 📋 What's Included

```
resume-maker/
├── resume.html          # Main file (open this in browser)
├── README.md            # This file
├── RESUME_STYLES.md     # Design system documentation
└── .gitignore           # Git ignore file
```

That's it! Just one HTML file to edit.

---

## 🎨 Design Styles Explained

### Professional Blue
**Use for:** Banking, law, consulting, corporate
- Dark navy sidebar on left
- Structured layout
- Classic, authoritative feel
- Contact info + skills on left, experience on right

### Creative Colorful
**Use for:** Design, art, marketing, startup
- Gradient purple header
- Two-column flexible layout
- Modern, playful typography
- Skills section with accent bars

### Modern Dark
**Use for:** Software engineering, product, tech
- Dark background with bright green accents
- Terminal-inspired aesthetic
- Minimal, clean design
- Code-style section headers

See `RESUME_STYLES.md` for full style documentation.

---

## 💾 Local Storage

Your resume data is automatically saved to your browser's local storage:
- Your chosen style preference persists across sessions
- Your resume data is saved after each edit
- Data is stored locally on your device (not uploaded anywhere)

To clear saved data:
```javascript
// Open browser console (F12) and run:
localStorage.clear()
```

---

## 📥 Exporting

### Download as PDF
1. Click **📥 Download PDF**
2. Browser print dialog opens
3. Choose "Save as PDF"
4. Click "Save"

The PDF will match your chosen style perfectly and includes all formatting.

### Download as HTML
1. Click **💾 Download HTML**
2. File downloads as `[Your-Name]-resume.html`
3. Open in any browser
4. Ready to share, print, or customize further

---

## ✏️ Customizing the Code

### Change a Style Color
Open `resume.html` in a text editor and find the CSS section. Look for:

**Professional Blue:**
```css
.resume-wrapper.professional-blue .sidebar {
    background-color: #1e3a5f;  /* Change this color */
}
```

**Creative Colorful:**
```css
.resume-wrapper.creative-colorful .header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* Change these colors */
}
```

**Modern Dark:**
```css
.resume-wrapper.modern-dark {
    background-color: #1a1a1a;  /* Dark background */
    color: #e0e0e0;             /* Text color */
}
.resume-wrapper.modern-dark .name {
    color: #00ff00;             /* Accent color */
}
```

### Add Your Own Style
1. Copy one of the existing style sections in CSS
2. Give it a new class name: `.resume-wrapper.my-new-style`
3. Customize colors and fonts
4. Add a render function in the JavaScript
5. Add a button in the toolbar

See `RESUME_STYLES.md` for detailed customization guide.

### Change Sample Data
In the JavaScript section, find:
```javascript
let resumeData = {
    fullName: 'Alex Johnson',
    email: 'alex@example.com',
    // ... update this data
}
```

---

## 🔗 Sharing Your Resume

### Via HTML File
```bash
# Download as HTML
# Send the .html file directly
# Recipient opens it in any browser
```

### Via PDF
```bash
# Download as PDF
# Send the .pdf file
# Works with any email/messaging app
```

### Via Link (if hosting online)
```bash
# Upload the HTML file to GitHub Pages, Vercel, Netlify, etc.
# Share the URL
# Anyone can view/download with one click
```

---

## 🌐 Browser Support

Resume Maker works in:
- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

Local storage is supported in all modern browsers.

---

## 🐛 Troubleshooting

### "Changes aren't saving"
- Check that localStorage is enabled in your browser
- Try clearing browser cache and refreshing
- Make sure you click "Save Changes" in the Edit modal

### "PDF downloads but looks weird"
- Try different browser (some have better print support)
- Adjust margins in print dialog
- Use Chrome for best print results

### "I lost my data"
- Data is saved in localStorage — check if you cleared cookies
- If using incognito/private mode, data doesn't persist
- Switch to regular browsing mode or use incognito only for single session

### "Style colors don't look right"
- Try refreshing the page (Ctrl+R or Cmd+R)
- Switch to a different style and back
- Clear localStorage (see "Local Storage" section above)

---

## 📝 Tips for Best Results

1. **Keep descriptions concise** — 1-2 sentences per job
2. **Use action verbs** — "Led", "Increased", "Developed", "Managed"
3. **Quantify achievements** — "Increased sales by 45%" not "Increased sales"
4. **Match style to industry** — Creative roles use Creative style, tech use Modern Dark
5. **Test print/PDF** — Always preview before sending
6. **Use consistent date format** — "Jan 2022 - Present" or "January 2022 - Now"

---

## 📚 Learning Resources

- **CSS Customization:** See comments in `<style>` section of resume.html
- **JavaScript Logic:** See comments in `<script>` section
- **Design System:** Read `RESUME_STYLES.md` for detailed style documentation

---

## 📄 License

MIT — Feel free to use, modify, and share this project.

---

## 🎓 Educational Purpose

This project demonstrates:
- ✅ HTML/CSS/JavaScript fundamentals
- ✅ Responsive web design
- ✅ Browser local storage API
- ✅ DOM manipulation
- ✅ Form handling
- ✅ File download/export
- ✅ CSS design systems

Perfect for learning full-stack web development basics!

---

## 🤝 Contributing

Have ideas for improvements?
1. Fork the repository
2. Make your changes
3. Test thoroughly
4. Submit a pull request

Suggestions for new features:
- [ ] More design styles
- [ ] Photo/avatar upload
- [ ] Multiple resume templates
- [ ] Export to Markdown
- [ ] Import from LinkedIn

---

## ❓ FAQ

**Q: Is my data private?**
A: Yes! All data stays on your device. Nothing is uploaded to any server.

**Q: Can I edit the HTML directly?**
A: Absolutely! Open the downloaded HTML file in any text editor and customize.

**Q: Can I use this for multiple resumes?**
A: Yes! Each browser session can have different data. Download HTML files for each version.

**Q: What if I'm not a tech person?**
A: No problem! You don't need to edit code. Just use the Edit button to change your info.

**Q: Can I add a photo?**
A: Currently no, but you can edit the HTML to add an image URL if you know HTML.

**Q: What's the best style?**
A: Choose the one that matches your industry:
  - Corporate → Professional Blue
  - Creative → Creative Colorful
  - Tech → Modern Dark

---

**Happy resume making! 🚀**

