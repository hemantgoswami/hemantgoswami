# Personal Website - Hemant Kumar Goswami

This is your professional personal website built with HTML, CSS, and JavaScript.

## 🚀 Features

- **Responsive Design**: Works perfectly on mobile, tablet, and desktop devices
- **Modern UI**: Professional gradient design with smooth animations
- **Single File**: Everything in one HTML file for easy deployment
- **No Dependencies**: No external libraries required
- **Fast Loading**: Optimized for performance (30KB)

## 📁 File Structure

- `index.html` - Your complete website (HTML + CSS + JavaScript)

## 🌐 Deployment Options

### GitHub Pages (Recommended)
1. Go to your repository settings
2. Navigate to "Pages" section
3. Select the branch (e.g., `main` or `copilot/create-personal-website`)
4. Select root folder as source
5. Click Save
6. Your site will be available at: `https://hemantgoswami.github.io/hemantgoswami/`

### Other Hosting Options
- **Netlify**: Drag and drop the `index.html` file
- **Vercel**: Connect your GitHub repository
- **Any Web Server**: Upload the `index.html` file to your hosting

## ✏️ Customization Guide

### Update Personal Information

1. **About Section** (Line ~420-435):
   - Update the bio paragraphs with your actual experience
   - Modify statistics (years of experience, projects, etc.)

2. **Skills Section** (Line ~469-507):
   - Add/remove technologies based on your expertise
   - Organize by your preferred categories

3. **Experience Section** (Line ~518-584):
   - Replace with your actual work experience
   - Update company names, dates, and responsibilities

4. **Projects Section** (Line ~600-680):
   - Add your real projects
   - Update project descriptions and technologies
   - Replace placeholder links with actual demo/GitHub URLs
   - Change emojis to match project types

5. **Contact Information** (Line ~857-858):
   - Update email address from `contact@example.com` to your actual email
   - Verify GitHub username is correct

### Customizing Colors

Find the `:root` section (Line ~14-21) and modify CSS variables:
```css
--primary-color: #2563eb;    /* Main brand color */
--secondary-color: #1e40af;  /* Secondary brand color */
--accent-color: #3b82f6;     /* Accent color */
```

### Adding New Sections

1. Copy an existing section structure
2. Update the navigation menu (Line ~374-381)
3. Add smooth scroll behavior is already implemented

## 📱 Testing

1. **Desktop**: Open in Chrome, Firefox, Safari, or Edge
2. **Mobile**: Use browser DevTools responsive mode or test on actual device
3. **Navigation**: Click menu items to test smooth scrolling
4. **Form**: Test contact form submission (currently shows alert)

## 🔧 Advanced Customization

### Adding Analytics
Add Google Analytics or similar tracking code before `</head>` tag.

### Contact Form Integration
Replace the form submission handler (Line ~882-895) with:
- **Formspree**: `action="https://formspree.io/f/YOUR_FORM_ID"`
- **Netlify Forms**: Add `data-netlify="true"` attribute
- **EmailJS**: Integrate JavaScript email service

### Adding Blog/Articles
Consider adding a blog section using:
- Markdown files + static site generator
- Headless CMS integration
- Link to external blog platform

## 📝 Notes

- The website uses placeholder content for projects and experience
- All external links open in new tabs with security attributes
- LinkedIn profile link is included and points to: https://www.linkedin.com/in/hemantkumargoswami/
- Mobile menu is accessible via hamburger icon on small screens

## 🆘 Support

If you need to make changes:
1. Edit `index.html` in any text editor
2. Save and refresh your browser to see changes
3. Commit and push to update the live site

## 📄 License

This is your personal website. Feel free to modify and use as needed.

---

**Ready to launch!** 🎉 Simply deploy and start showcasing your work.
