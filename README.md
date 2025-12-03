# Nicholas - Academic Portfolio Website

A modern, professional academic website built for GitHub Pages showcasing PhD research in Geospatial Information Science.

## 🌟 Features

- **Modern, Professional Design**: Clean, academic-focused layout with professional color scheme
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Research Showcase**: Dedicated sections for dissertation work, projects, and methodology
- **Teaching Portfolio**: Highlights TA experience and educational contributions
- **Publications Section**: Ready for your academic publications and conference presentations
- **Contact Integration**: Professional contact information and social links
- **Smooth Animations**: Subtle scroll animations and hover effects
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 🚀 Quick Setup on GitHub Pages

### Step 1: Create a GitHub Account
If you don't have one already, create a free account at [github.com](https://github.com)

### Step 2: Create Your Repository
1. Click the "+" icon in the top right corner of GitHub
2. Select "New repository"
3. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
4. Make it **Public**
5. Check "Add a README file"
6. Click "Create repository"

### Step 3: Upload Your Website Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop the `index.html` file from this folder
3. In the commit message box, write "Add initial website"
4. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. In your repository, click the "Settings" tab
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

### Step 5: Access Your Live Site
After a few minutes, your site will be available at: `https://yourusername.github.io`

## 🎨 Customization Guide

### Essential Personalizations

1. **Update Contact Information** (lines 400-430):
   ```html
   <a href="mailto:your.email@utdallas.edu">your.email@utdallas.edu</a>
   <a href="https://github.com/yourusername">github.com/yourusername</a>
   <a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a>
   ```

2. **Add Your Name** (multiple locations):
   - Update the hero section with your full name
   - Update the navigation logo
   - Update publication author names

3. **Update Research Description**:
   - Modify the dissertation research card to reflect your specific focus
   - Update the research methods tags
   - Add your own project descriptions

4. **Add Your Publications**:
   - Replace placeholder publications with your actual work
   - Update author names and venues
   - Add links to papers when available

### Advanced Customizations

1. **Add Your Photo**:
   ```html
   <!-- Replace the icon with an actual image -->
   <div class="profile-img">
       <img src="your-photo.jpg" alt="Your Name" style="width: 100%; height: 100%; border-radius: 50%; object-fit: cover;">
   </div>
   ```

2. **Update Colors** (CSS variables at the top):
   ```css
   :root {
       --primary-color: #1a4d72;    /* Main blue color */
       --accent-color: #e8954a;     /* Orange accent */
       /* Modify these to match your preferences */
   }
   ```

3. **Add More Sections**:
   - Awards and honors
   - Software/tools you've developed
   - Media coverage of your research
   - Professional service

## 📱 Mobile Optimization

The site is fully responsive and includes:
- Mobile-optimized navigation
- Touch-friendly buttons and links
- Optimized font sizes for mobile reading
- Proper viewport handling

## 🔧 Technical Features

- **Pure HTML/CSS/JavaScript**: No build process needed
- **Fast Loading**: Optimized images and minimal dependencies
- **Accessibility**: Proper semantic HTML and ARIA labels
- **Cross-browser Compatible**: Works in all modern browsers
- **SEO Friendly**: Structured data and meta tags

## 📈 Adding Google Analytics (Optional)

To track visitors, add this code before the closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=YOUR-GA-ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'YOUR-GA-ID');
</script>
```

## 🎯 Tips for Academic Websites

1. **Keep it Updated**: Regularly update with new publications, presentations, and projects
2. **Professional Photos**: Use high-quality, professional headshots
3. **Clear Research Description**: Make your research accessible to both experts and general audiences
4. **Contact Information**: Always include multiple ways to reach you
5. **Mobile-First**: Many people will view your site on mobile devices
6. **Link Everything**: Link to your papers, GitHub repos, and institutional profiles

## 🔄 Regular Maintenance

### Monthly:
- Check all links are working
- Update recent publications
- Add new teaching experiences

### Semester:
- Update research progress
- Add new projects or collaborations
- Refresh course TA information

### Annually:
- Update CV/resume download
- Refresh profile photo if needed
- Review and update research interests

## 🤝 Getting Help

- **GitHub Pages Documentation**: [docs.github.com/pages](https://docs.github.com/pages)
- **HTML/CSS Resources**: [MDN Web Docs](https://developer.mozilla.org)
- **Academic Website Examples**: Look at other PhD students' sites in your field

## 🚀 Going Further

Once your basic site is working, consider:
- Adding a blog section for research updates
- Creating project pages with detailed case studies
- Adding an interactive map of your research locations
- Integrating with academic social networks (ResearchGate, Academia.edu)
- Setting up a custom domain name

---

**Good luck with your website! Remember to customize the content to reflect your unique research and personality.**