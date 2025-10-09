# Data Analyst Portfolio

A professional portfolio website template for data analysts to showcase their work, skills, and experience.

## Features

- 🎨 Modern and responsive design
- 📱 Mobile-friendly navigation
- 🎯 Sections for About, Skills, Projects, and Contact
- ⚡ Smooth scrolling and animations
- 🎭 Easy to customize
- 🚀 Ready for GitHub Pages deployment

## How to Customize

### 1. Personal Information
Edit `index.html` and replace the following:
- **Your Name** - Replace all instances of "Your Name" with the actual name
- **Email** - Replace `your.email@example.com` with the actual email
- **LinkedIn** - Replace `linkedin.com/in/yourprofile` with the LinkedIn profile URL
- **GitHub** - Replace `github.com/yourusername` with the GitHub username

### 2. About Section
- Update the experience years, projects count, and tools mastered
- Modify the about text to reflect actual background and expertise

### 3. Skills
- Edit the skills cards in the Skills section to match actual skills
- Add or remove skill categories as needed

### 4. Projects
The template includes 4 sample projects. For each project, update:
- **Title** - Project name
- **Description** - Brief description of what the project does
- **Tags** - Technologies used
- **Links** - Replace `#` with actual links to live demos or GitHub repositories
- **Images** - Replace placeholder images with actual project screenshots

To add project images:
1. Create an `images` folder in the project directory
2. Add project screenshots (recommended size: 400x250px)
3. Replace the placeholder URLs:
   ```html
   <img src="images/project1.png" alt="Project 1">
   ```

### 5. Colors
To change the color scheme, edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #4A90E2;    /* Main brand color */
    --secondary-color: #50C878;   /* Accent color */
    --dark-color: #2C3E50;        /* Dark text */
    --light-color: #ECF0F1;       /* Light background */
}
```

## Deployment Options

### Option 1: GitHub Pages (Free & Recommended)

1. **Create a GitHub account** (if you don't have one): https://github.com/join

2. **Create a new repository**:
   - Go to https://github.com/new
   - Name it: `yourusername.github.io` (replace with actual username)
   - Make it public
   - Don't initialize with README

3. **Upload your files**:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**:
   - Go to repository Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/ (root)`
   - Save

5. **Access your site**: `https://yourusername.github.io`

### Option 2: Netlify (Free)

1. Go to https://www.netlify.com/
2. Sign up for free
3. Drag and drop your project folder
4. Your site will be live in seconds!

### Option 3: Vercel (Free)

1. Go to https://vercel.com/
2. Sign up with GitHub
3. Import your repository
4. Deploy automatically

## Adding Real Project Content

### For Tableau/Power BI Projects
1. Publish your dashboard to Tableau Public or Power BI Public
2. Get the embed code or public link
3. Update the "Live Demo" link in your project card

### For Python/R Projects
1. Create a Jupyter Notebook or R Markdown file
2. Upload to GitHub
3. Use nbviewer.jupyter.org or GitHub's built-in viewer
4. Link to the notebook in your project card

### For Data Visualizations
1. Export your visualizations as images
2. Add them to the `images` folder
3. Consider creating interactive versions with Plotly/D3.js

## Tips for Success

✅ **Add Real Projects**: Replace sample projects with 3-5 of your best work
✅ **Include Metrics**: Show impact (e.g., "Improved efficiency by 30%")
✅ **Write Clear Descriptions**: Explain the problem, solution, and results
✅ **Keep It Updated**: Add new projects regularly
✅ **Get Feedback**: Ask peers to review before publishing
✅ **Add Analytics**: Use Google Analytics to track visitors
✅ **SEO Optimization**: Update meta tags for better search visibility

## Additional Resources

- **Resume/CV**: Consider adding a downloadable PDF resume
- **Blog**: Add a blog section to share insights and tutorials
- **Testimonials**: Include recommendations from colleagues or clients
- **Certifications**: Display relevant certifications and courses

## Support

If you need help customizing or deploying your portfolio, feel free to reach out!

## License

This template is free to use for personal portfolios. No attribution required.

---

Good luck with your job search! 🚀
