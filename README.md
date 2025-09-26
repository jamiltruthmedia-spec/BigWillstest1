# Big Will's Kitchen Website

NYC-style bodega serving the best Philly cheesesteak, wings, and comfort food in Lockport, NY.

## 🍕 About

Big Will's Kitchen brings authentic NYC bodega vibes to Lockport, NY. We're half kitchen, half store - serving up the best Philly cheesesteaks, wings, and comfort food you'll find in Western New York.

## 🚀 Live Website

- **Production:** https://bigwillskitchen.com
- **Staging:** https://big-wills-kitchen.vercel.app

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
- **Hosting:** Vercel
- **Version Control:** GitHub
- **Design:** Inspired by Watson's Chicken design system

## 📁 Project Structure

```
big-wills-kitchen/
├── website/                 # Main website files
│   ├── index.html          # Homepage
│   ├── assets/             # Static assets
│   │   ├── css/           # Stylesheets
│   │   ├── js/            # JavaScript files
│   │   └── images/        # Images and media
│   ├── sitemap.xml        # SEO sitemap
│   └── robots.txt         # Search engine directives
├── business-data/          # Business information (private)
├── vercel.json            # Vercel configuration
├── package.json           # Project dependencies
└── README.md              # This file
```

## 🎯 SEO Features

- **Local SEO:** Optimized for Lockport, NY searches
- **Schema Markup:** Restaurant and local business structured data
- **Mobile-First:** Responsive design for all devices
- **Fast Loading:** Optimized for Core Web Vitals
- **Social Media:** Open Graph and Twitter Card meta tags

## 🚀 Deployment

### Prerequisites
- Node.js (for Vercel CLI)
- Git
- Vercel account

### Deploy to Vercel

1. **Install Vercel CLI:**
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel:**
   ```bash
   vercel login
   ```

3. **Deploy:**
   ```bash
   vercel --prod
   ```

### GitHub Integration

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

2. **Connect to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Import project from GitHub
   - Select your repository
   - Deploy automatically

## 📱 Features

- **Responsive Design:** Mobile-first approach
- **Fast Loading:** Optimized assets and code
- **SEO Optimized:** Local search optimization
- **Accessibility:** WCAG compliant
- **Social Integration:** Facebook and Instagram links
- **Online Ordering:** DoorDash integration

## 🎨 Design System

Inspired by Watson's Chicken design with adaptations for Big Will's Kitchen:

- **Primary Color:** Gold (#d4af37)
- **Typography:** Inter font family
- **Layout:** Clean, minimal design
- **Components:** Card-based layout for locations

## 📊 Analytics

The website is configured for:
- Google Analytics (when added)
- Google Search Console
- Vercel Analytics

## 🔧 Development

### Local Development

```bash
# Clone repository
git clone https://github.com/yourusername/big-wills-kitchen.git

# Install dependencies
npm install

# Start development server
vercel dev
```

### Adding New Pages

1. Create new HTML file in `website/` directory
2. Follow the design system template
3. Update navigation in `index.html`
4. Add to sitemap.xml
5. Deploy to Vercel

## 📞 Contact

- **Phone:** (716) 727-0011
- **Address:** 39 Locust St, Lockport, NY 14094
- **Email:** info@bigwillskitchen.com

## 📄 License

MIT License - see LICENSE file for details

---

*Built with ❤️ for Big Will's Kitchen*
