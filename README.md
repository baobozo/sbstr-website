# SBSTR.com - Southbay Structure Website

Modern, responsive website for Southbay Structure, Inc. - a professional structural engineering firm serving North and South California.

## 🌟 Features

- **Modern Design**: Dark theme with gold accents, non-symmetrical layout
- **Fully Responsive**: Mobile-first approach, works on all devices
- **Four Main Pages**: Home, Services, Portfolio, Contact
- **Portfolio Filtering**: Interactive filtering by project category
- **No External Dependencies**: Pure HTML/CSS/JavaScript
- **Performance Optimized**: Fast loading, minimal assets
- **SEO Ready**: Semantic HTML, proper meta tags
- **Accessibility**: WCAG compliant, keyboard navigable

## 🏗️ Project Structure

```
sbstr-redesign/
├── site/                    # Website files
│   ├── index.html          # Homepage
│   ├── services.html       # Services page
│   ├── portfolio.html      # Portfolio with filtering
│   ├── contact.html        # Contact information
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   └── assets/
│       └── logo.png       # Company logo
├── assets/                  # Project assets
│   ├── reference-images/   # Design reference images
│   └── logo.png           # Original logo
├── wireframes/             # Design wireframes
│   └── index.html         # Interactive wireframe
└── documentation/          # Project documentation
```

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended)
1. Create a new GitHub repository
2. Push the `site/` folder to the repository
3. Go to Settings → Pages
4. Set source to `main` branch, `/site` folder
5. Your site will be available at `https://[username].github.io/[repository]/`

### Option 2: Netlify (Easiest)
1. Drag and drop the `site/` folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on every push

### Option 3: Traditional Hosting
1. Upload the `site/` folder to your web host
2. Configure domain DNS to point to the host
3. Update any absolute URLs if needed

## 🛠️ Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/sbstr-website.git
   cd sbstr-website
   ```

2. **Open in browser**
   ```bash
   open site/index.html
   ```
   Or use a local server:
   ```bash
   python3 -m http.server 8000
   ```

3. **Make changes**
   - Edit HTML files in `site/`
   - Edit CSS in `site/css/style.css`
   - Test locally before committing

## 📱 Responsive Breakpoints

- **Mobile**: 0-767px
- **Tablet**: 768-1023px  
- **Desktop**: 1024px+

## 🎨 Design System

### Colors
- Background: `#0a0a0a`
- Surface: `#1a1a1a`
- Text Primary: `#ffffff`
- Text Secondary: `#e0e0e0`
- Accent Gold: `#d4af37`
- Accent Gold Light: `#ffd700`

### Typography
- Headings: **Inter** (700 weight)
- Body: **Inter** (400 weight)
- Font sizes use REM units for scalability

### Components
- **Cards**: Glass effect with hover animations
- **Buttons**: Gradient backgrounds with hover effects
- **Navigation**: Sticky header with active states
- **Grid**: Non-symmetrical layout for visual interest

## 🔧 Maintenance

### Adding New Projects
1. Edit `portfolio.html`
2. Add new `.portfolio-item` div with `data-category` attribute
3. Include project image, title, description, and tags

### Updating Services
1. Edit `services.html`
2. Update service descriptions in the relevant sections
3. Add/remove service cards as needed

### Changing Content
- Company info: Update `contact.html` and footer
- Team information: Add `about.html` page if needed
- Contact details: Update in `contact.html` and footer

## 📄 License

© 2026 Southbay Structure, Inc. All rights reserved.

## 🙏 Credits

- **Design & Development**: Created for Southbay Structure, Inc.
- **Fonts**: Google Fonts (Inter)
- **Icons**: Emoji and custom CSS
- **Inspiration**: Modern web design trends 2024

## 📞 Support

For website issues or updates, contact:
- **Email**: info@sbstr.com
- **Phone**: 408-508-5595