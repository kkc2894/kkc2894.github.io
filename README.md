# Komal Kumari - Academic Website

A professional academic website for Komal Kumari, PhD student in Computer Science at New Jersey Institute of Technology, specializing in secure data processing and information-theoretic security.

## 🌟 Features

- **Modern Design**: Clean, professional layout optimized for academic presentation
- **Responsive**: Fully responsive design that works on all devices
- **Performance Optimized**: Fast loading with optimized CSS and JavaScript
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessible**: WCAG compliant with proper ARIA labels and keyboard navigation

## 📁 Project Structure

```
komal-website/
├── index.html          # Main website file
├── style.css           # Stylesheet with modern design system
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites
- A GitHub account
- Git installed on your computer (optional, can use GitHub web interface)
- A text editor (VS Code, Atom, etc.) for customization

## 📊 Website Sections

1. **Hero Section**: Introduction with name, title, and research focus
2. **About**: Personal background and research interests
3. **Research Areas**: Key research domains with visual icons
4. **Publications**: Academic publications with links and descriptions
5. **Experience**: Education and professional timeline
6. **Contact**: Contact information and academic profiles

## 🎯 Step-by-Step Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface (Easiest)

1. **Create a New Repository**
   - Go to [GitHub](https://github.com) and sign in
   - Click the "+" icon in the top right corner
   - Select "New repository"
   - Name it `your-username.github.io` (replace `your-username` with your actual GitHub username)
     - Example: If your username is `komal123`, name it `komal123.github.io`
   - Make sure it's set to "Public"
   - Check "Add a README file"
   - Click "Create repository"

2. **Upload Website Files**
   - In your new repository, click "uploading an existing file"
   - Upload the following files:
     - `index.html`
     - `style.css`
     - `script.js`
   - Add a commit message like "Initial website upload"
   - Click "Commit changes"

3. **Enable GitHub Pages**
   - Go to your repository settings (Settings tab)
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Website**
   - Your website will be available at: `https://your-username.github.io`
   - It may take 5-10 minutes to go live initially

### Method 2: Using Git Command Line

1. **Create Repository on GitHub**
   - Follow step 1 from Method 1 above

2. **Clone and Setup Locally**
   ```bash
   # Clone your repository
   git clone https://github.com/your-username/your-username.github.io.git
   
   # Navigate to the directory
   cd your-username.github.io
   
   # Copy the website files into this directory
   # (copy index.html, style.css, script.js here)
   
   # Add files to git
   git add .
   
   # Commit changes
   git commit -m "Initial website upload"
   
   # Push to GitHub
   git push origin main
   ```

3. **Enable GitHub Pages**
   - Follow steps 3-4 from Method 1 above

### Method 3: Custom Domain (Optional)

If you want to use a custom domain (like `komal-kumari.com`):

1. **Purchase a Domain**
   - Buy a domain from providers like GoDaddy, Namecheap, etc.

2. **Configure DNS**
   - In your domain provider's DNS settings, add these records:
   ```
   Type: CNAME
   Name: www
   Value: your-username.github.io
   
   Type: A
   Name: @
   Values: 185.199.108.153
           185.199.109.153
           185.199.110.153
           185.199.111.153
   ```

3. **Configure GitHub**
   - Go to repository Settings → Pages
   - Add your custom domain in the "Custom domain" field
   - Wait for DNS verification (can take 24-48 hours)

## ✏️ Customization Guide

### Basic Information Updates

1. **Personal Information** (in `index.html`):
   ```html
   <!-- Update these sections -->
   <h1>Your Name</h1>
   <p>your-email@university.edu</p>
   <p>Your Institution Name</p>
   ```

2. **Research Interests** (in `index.html`):
   ```html
   <!-- Update the research interests list -->
   <li>Your Research Area 1</li>
   <li>Your Research Area 2</li>
   ```

3. **Publications** (in `index.html`):
   ```html
   <!-- Add your publications -->
   <h3>Your Publication Title</h3>
   <p class="authors"><strong>Your Name</strong>, Co-authors</p>
   <p class="venue">Conference/Journal Name</p>
   ```

### Styling Customization

1. **Colors** (in `style.css`):
   ```css
   :root {
     --primary-color: #your-color;
     --secondary-color: #your-color;
   }
   ```

2. **Fonts** (in `style.css`):
   ```css
   /* Change the Google Fonts import */
   @import url('https://fonts.googleapis.com/css2?family=Your-Font:wght@300;400;600&display=swap');
   ```

### Adding New Sections

1. **Add HTML structure** in `index.html`
2. **Add corresponding CSS** in `style.css`
3. **Update navigation** links if needed

## 🔧 Advanced Features

### Analytics Integration
Add Google Analytics by including this in the `<head>` section:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

### Contact Form Integration
Consider using services like:
- Formspree
- Netlify Forms
- Google Forms

### SEO Optimization
The website includes:
- Meta tags for social sharing
- Structured data for search engines
- Semantic HTML structure
- Fast loading times

## 🛠️ Maintenance

### Regular Updates
1. **Publications**: Add new publications as they're published
2. **Experience**: Update with new positions, awards, etc.
3. **Contact Info**: Keep contact information current

### Performance Monitoring
- Use Google PageSpeed Insights to monitor performance
- Check mobile responsiveness regularly
- Validate HTML and CSS periodically

## 📞 Support and Troubleshooting

### Common Issues

1. **Website Not Loading**
   - Check if GitHub Pages is enabled in repository settings
   - Ensure files are in the root directory
   - Wait 5-10 minutes after initial setup

2. **CSS Not Loading**
   - Verify file paths in `index.html`
   - Check for typos in filenames
   - Clear browser cache

3. **Custom Domain Issues**
   - Verify DNS settings with your domain provider
   - Check CNAME file in repository
   - Wait 24-48 hours for DNS propagation

### Getting Help
- GitHub Pages Documentation: https://pages.github.com/
- GitHub Community Forum: https://github.community/
- Web development communities on Stack Overflow

## 📄 License

This website template is free to use and modify for academic purposes.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements.

---

**Note**: Remember to replace placeholder information with your actual details before deploying!

## 🎉 Congratulations!

Once deployed, your professional academic website will be live and accessible worldwide. This creates a strong online presence for your academic career and makes it easy for collaborators, employers, and the research community to find and learn about your work.

**Next Steps After Deployment:**
1. Share your website URL on your email signature
2. Add the link to your CV/resume
3. Include it in conference presentations and papers
4. Update academic profiles (Google Scholar, ORCID, etc.) with your website link
5. Regularly update with new publications and achievements

Good luck with your academic website!