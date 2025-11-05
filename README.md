# Academic Research Website Template

A clean, professional, and lightweight website template for professors and research groups.

## 🎨 Design Features

- **Light Color Theme**: Professional white background with blue/teal accents
- **Fully Responsive**: Works on desktop, tablet, and mobile
- **Modern Layout**: Clean grids and card-based design
- **Smooth Animations**: Fade-in effects and smooth scrolling
- **Easy to Customize**: Simple HTML structure with clear sections

## 📁 Files Included

- `index.html` - Main website structure
- `style.css` - All styling and colors
- `script.js` - Interactive features
- `README.md` - This file

## 🚀 Quick Start

1. **Open `index.html` in a text editor**
2. **Replace placeholder content** with your information
3. **Add your photo**: Replace the profile image section
4. **Save and open** `index.html` in a browser

## ✏️ How to Customize

### Change Colors
Edit the `:root` section in `style.css`:
```css
--color-primary: #1565C0;        /* Main blue color */
--color-secondary: #00897B;      /* Teal accent */
--color-accent: #FF7043;         /* Orange highlights */
```

### Add Your Content

#### 1. Hero Section (Top)
- Replace "Professor Name" with your name
- Add your research title
- Update statistics (publications, projects, team size)

#### 2. Research Areas
- Change the 4 research cards
- Update icons (find more at: fontawesome.com/icons)
- Add your research descriptions

#### 3. Projects
- Add ongoing and completed projects
- Include funding info, dates, descriptions
- Add links to project websites

#### 4. Publications
- List your papers by year
- Add badges: Journal, Conference, Book Chapter
- Include DOI links and PDFs

#### 5. Team
- Add PhD students, Masters students
- List alumni with current positions
- Include collaborators

#### 6. Contact
- Update email, phone, office address
- Add Google Maps embed for location
- Customize office hours

### Add Your Photo
Replace this line in `index.html`:
```html
<div class="profile-image">
    <!-- Add: <img src="your-photo.jpg" alt="Your Name"> -->
</div>
```

## 🎯 Color Scheme

| Color | Usage | Hex Code |
|-------|-------|----------|
| White | Background | #FFFFFF |
| Light Gray | Secondary BG | #F8F9FA |
| Navy Blue | Primary | #1565C0 |
| Teal | Secondary | #00897B |
| Coral | Accent | #FF7043 |
| Dark Gray | Text | #2C3E50 |

## 📱 Sections Included

1. **Navigation Bar** - Sticky menu with links
2. **Hero Section** - Introduction with stats and profile
3. **News Updates** - Latest achievements and news
4. **Research Areas** - 4 main research themes
5. **Projects** - Ongoing and completed work
6. **Publications** - Filterable list by type
7. **Team** - Students, alumni, collaborators
8. **Contact** - Email, office, collaboration info
9. **Footer** - Quick links and social media

## 🔧 Advanced Customization

### Add New Sections
Copy any section structure and modify:
```html
<section id="new-section" class="custom-section">
    <div class="container">
        <h2>Section Title</h2>
        <!-- Your content here -->
    </div>
</section>
```

### Modify Layouts
Change grid columns in `style.css`:
```css
.research-grid {
    grid-template-columns: repeat(3, 1fr); /* 3 columns instead of 4 */
}
```

### Add Icons
Use Font Awesome icons (already included):
```html
<i class="fas fa-flask"></i>        <!-- Flask -->
<i class="fas fa-brain"></i>        <!-- Brain -->
<i class="fas fa-graduation-cap"></i> <!-- Graduation -->
```

Find more at: https://fontawesome.com/icons

## 📤 Publishing Your Website

### Option 1: GitHub Pages (Free)
1. Create GitHub account
2. Create repository named: `username.github.io`
3. Upload files
4. Visit: `https://username.github.io`

### Option 2: Google Sites
1. Copy content sections
2. Paste into Google Sites editor
3. Customize using their interface

### Option 3: University Server
1. Get server access from IT department
2. Upload files via FTP
3. Follow university hosting guidelines

## 💡 Tips

- **Keep it updated**: Regularly add new publications and news
- **Optimize images**: Compress photos before uploading
- **Use clear titles**: Make it easy to find information
- **Link to profiles**: Add Google Scholar, ResearchGate links
- **Mobile-friendly**: Always test on phone/tablet

## 🆘 Need Help?

Common issues:
- **Styles not working?** Make sure `style.css` is in the same folder
- **Links broken?** Check that all `href` attributes are correct
- **Layout broken?** Verify closing tags in HTML
- **Icons not showing?** Internet connection needed for Font Awesome

## 📋 Checklist

Before publishing:
- [ ] Update all placeholder text
- [ ] Add your photo
- [ ] List all publications
- [ ] Add team members
- [ ] Update contact information
- [ ] Test all links
- [ ] Check on mobile device
- [ ] Proofread content
- [ ] Add Google Analytics (optional)

## 🎓 Template Structure

```
Your Website/
│
├── index.html          (Main page)
├── style.css           (All styles)
├── script.js           (Interactions)
├── README.md           (This file)
│
├── images/             (Create this folder)
│   ├── profile.jpg
│   └── project-images/
│
└── files/              (Create this folder)
    └── publications/
```

## 🌟 Good Luck!

Your professional academic website is ready to customize. Take your time, add your content section by section, and don't hesitate to experiment with the design!

---

**Last Updated**: November 2025
**Template Version**: 1.0
