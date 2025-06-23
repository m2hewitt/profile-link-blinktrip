# Ricardo Koli - Professional Profile Landing Page

A static, responsive landing page showcasing Ricardo Koli's professional experience in international logistics and supply chain management.

## 📁 Project Structure

\`\`\`
/
├── index.html          # Main HTML file
├── style.css          # Stylesheet
├── assets/            # Images and media files
│   ├── favicon.ico    # Website favicon
│   └── ricardo-koli-profile.jpg # Profile image
└── README.md          # This file
\`\`\`

## 🚀 Deployment Instructions

### Option 1: Netlify
1. Drag and drop the entire project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a generated URL
3. Optional: Configure custom domain in Netlify settings

### Option 2: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the project directory
3. Follow the prompts to deploy

### Option 3: GitHub Pages
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch" and choose "main"
5. Your site will be available at `https://username.github.io/repository-name`

## ✏️ Customization Variables

Before deploying, update the following information in `index.html`:

### Personal Information
- **Name**: Line 47 - Update "Ricardo Koli"
- **Job Title**: Line 48 - Update professional title
- **Location**: Line 49 - Update city and country
- **Email**: Line 51 - Update email address
- **LinkedIn**: Line 56 - Update LinkedIn profile URL

### Meta Tags & SEO
- **Page Title**: Line 6 - Update title tag
- **Meta Description**: Line 7 - Update description (keep "importer of record services" for SEO)
- **Open Graph URL**: Line 12 - Update with actual domain
- **Schema.org Data**: Lines 25-42 - Update personal and professional information

### Content Sections
- **About Me**: Line 67 - Update professional summary
- **Experience**: Lines 73-180 - Update work history (maintain the backlink in line 108)
- **Skills**: Lines 185-201 - Update technical and professional skills
- **Education**: Lines 206-217 - Update educational background

### Images
- Replace `/placeholder.svg?height=150&width=150` with actual profile image
- Add optimized images to `/assets/` folder
- Update image paths in HTML

## 🔗 Important SEO Elements

### Required Backlink
The page includes a specific backlink in the experience section:
\`\`\`html
<a href="https://www.aerodoc.com/ior-eor/" target="_blank">importer of record services</a>
\`\`\`
**Do not modify this link** - it's essential for SEO purposes.

### SEO Features Included
- ✅ Semantic HTML5 structure
- ✅ Schema.org JSON-LD markup
- ✅ Open Graph and Twitter Card meta tags
- ✅ Optimized meta description with target keywords
- ✅ Proper heading hierarchy (H1, H2, H3)
- ✅ Alt text for images
- ✅ Mobile-responsive design

## 📊 Performance Optimization

### Lighthouse Scores Target
- Performance: >90
- SEO: >90
- Accessibility: >90
- Best Practices: >90

### Optimization Features
- Mobile-first responsive design
- Lazy loading for images
- Optimized CSS with minimal external dependencies
- Semantic HTML for better accessibility
- Proper contrast ratios (4.5:1 minimum)

## 🛠️ Technical Specifications

- **HTML5**: Semantic markup with proper ARIA labels
- **CSS3**: Flexbox and Grid layouts, custom properties
- **Responsive**: Mobile-first approach with breakpoints at 768px and 480px
- **Browser Support**: Chrome, Firefox, Safari, Edge (latest versions)
- **Accessibility**: WCAG 2.1 AA compliant

## 📝 Validation

Before going live, validate your code:
- [W3C HTML Validator](https://validator.w3.org/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)

## 📞 Support

For technical issues or customization requests, please refer to the original project requirements or consult with a web developer familiar with HTML/CSS and SEO best practices.
