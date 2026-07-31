# Whitespace - SaaS Landing Page

A modern, responsive SaaS landing page built with HTML, CSS, and JavaScript. This is a recreation of the popular Whitespace design template.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading and optimized
- 🎭 Smooth animations and transitions
- 🚀 Interactive elements
- 💫 Parallax effects
- 🔄 Animated progress bars
- 📋 Multiple sections (Hero, Features, Pricing, Testimonials, etc.)

## Sections Included

1. **Navigation** - Fixed navigation with mobile hamburger menu
2. **Hero Section** - Compelling headline with interactive dashboard preview
3. **Features** - Project management, collaboration, and extension features
4. **Customization** - Theme and settings showcase
5. **Pricing** - Three-tier pricing plan with highlighted popular option
6. **Testimonials** - Customer reviews and social proof
7. **Call-to-Action** - App download buttons and final CTA
8. **Footer** - Links, social media, and company info

## Quick Start

### Option 1: Using Node.js (Recommended)
```bash
# Install dependencies
npm install

# Start development server
npm start
```

### Option 2: Direct File Opening
Simply open `index.html` in your web browser.

### Option 3: Using Python
```bash
# Python 3
python -m http.server 3000

# Python 2
python -m SimpleHTTPServer 3000
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6+)** - Interactive functionality
- **Google Fonts** - Inter font family
- **Font Awesome** - Icons

## Customization

### Colors
The main color scheme uses:
- Primary: `#4F46E5` (Indigo)
- Secondary: `#1a1a1a` (Dark)
- Background: `#ffffff` (White)
- Gray: `#6b7280` (Medium gray)

### Fonts
- **Primary Font**: Inter (Google Fonts)
- **Fallback**: System fonts for optimal loading

### Sections
Each section is modular and can be easily customized:
- Update content in `index.html`
- Modify styles in `style.css`
- Add functionality in `script.js`

## Deployment

### Vercel (Fixed for 404 Error!)

**Step-by-Step Vercel Deployment:**

1. **Go to [vercel.com](https://vercel.com) and login**
2. **Click "New Project"**  
3. **Import from GitHub:** `saqlain-076/whitepace-landing-page`
4. **Project Settings:**
   - Framework Preset: `Other`
   - Build Command: (leave empty)
   - Output Directory: (leave empty) 
   - Install Command: `npm install` (optional)
5. **Click "Deploy"**

**The `vercel.json` file ensures:**
- ✅ All routes serve the `index.html`
- ✅ No 404 errors on page refresh
- ✅ Proper SPA routing

**If still getting 404:**
- Refresh the Vercel project page
- Check deployment logs for errors
- Ensure `index.html` is in root directory ✅

### Alternative Deployments

**GitHub Pages:**
1. Settings → Pages → Source: Deploy from branch `main`

**Netlify:**
1. Drag & drop the project folder to netlify.com
2. Or connect GitHub repo with default settings

### Test Locally
```bash
npm start
# Opens http://localhost:3000
```

## Troubleshooting Vercel

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized images and assets
- Lazy loading for better performance
- Minified CSS and JavaScript (in production)
- Progressive enhancement approach

## Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)

### Netlify
1. Connect your GitHub repository
2. Set build command: `npm run build`
3. Set publish directory: `/`

### Vercel
1. Connect your GitHub repository
2. Deploy with default settings

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

- Design inspired by the Whitespace SaaS template
- Icons by Font Awesome
- Fonts by Google Fonts

## Support

If you encounter any issues or have questions, please open an issue on the GitHub repository.

---

Made with ❤️ for the SaaS community