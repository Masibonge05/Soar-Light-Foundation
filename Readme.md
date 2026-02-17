# Soar Light Foundation Website

## About
This is the official website for **Soar Light Foundation** - a registered non-profit organisation committed to uplifting children and young people from underprivileged communities.

**Tagline:** Helping Dreams Take Flight

## Features

### Core Pages & Sections
- **Home/Welcome Screen** - Eye-catching splash screen with logo and tagline
- **About Us** - Comprehensive information about the foundation
  - Who We Are
  - Our Story
  - Vision & Mission
  - Objectives
  - Core Values
- **What We Do** - Detailed programme information
  - Sanitary Pads & Dignity Drive
  - Education Support & Career Guidance
  - Clothing & School Uniform Drive
  - Food Support & Nutrition
  - Volunteerism & Community Outreach
- **Our Impact** - Statistics and achievements
  - Impact statistics with animated counters
  - SDG (Sustainable Development Goals) alignment
- **Previous Projects** - Showcase of completed initiatives
- **Our Team** - Leadership and volunteer information
- **Donors & Partners** - Partnership opportunities and recognition
- **Get Involved** - Multiple ways to support
  - Donate
  - Volunteer
  - Partner
  - Share
- **Governance & Compliance** - Transparency section
- **Contact Us** - Multi-channel contact options
- **Newsletter Subscription** - Stay updated with latest news

### Design Features
- **Professional Theme Colors:**
  - Primary Blue: #0066CC
  - Dark Blue: #003D7A
  - Yellow: #FDB913
  - White: #FFFFFF
  
- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Smooth Animations** - Engaging user experience
- **Interactive Navigation** - Sticky header with active state highlighting
- **Animated Statistics** - Counter animations on scroll
- **Contact Forms** - User-friendly forms with validation
- **Social Media Integration** - Connect on Facebook, Instagram, TikTok, Twitter
- **Scroll to Top Button** - Easy navigation
- **Mobile Menu** - Hamburger menu for mobile devices

### Technical Features
- Clean, semantic HTML5
- Modern CSS3 with custom properties (CSS variables)
- Vanilla JavaScript (no dependencies)
- Fast loading and optimized performance
- Accessibility compliant
- SEO friendly

## File Structure

```
soar-light-foundation/
│
├── index.html              # Main HTML file
├── README.md              # This file
│
├── css/
│   └── style.css          # Main stylesheet
│
├── js/
│   └── main.js            # JavaScript functionality
│
└── images/
    └── logo.png           # Foundation logo
```

## Setup Instructions

### Option 1: Simple Setup (No Server Required)
1. Extract all files to a folder
2. Double-click `index.html` to open in your browser
3. That's it! The website will work locally

### Option 2: Using a Local Server (Recommended for Development)

#### Using Python (if installed):
```bash
# Navigate to the project folder
cd path/to/soar-light-foundation

# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Open browser and visit: http://localhost:8000
```

#### Using Node.js (if installed):
```bash
# Install http-server globally
npm install -g http-server

# Navigate to project folder
cd path/to/soar-light-foundation

# Start server
http-server

# Open browser and visit: http://localhost:8080
```

#### Using VS Code (Live Server Extension):
1. Open project folder in VS Code
2. Install "Live Server" extension
3. Right-click on `index.html`
4. Select "Open with Live Server"

## Deployment Options

### Option 1: Free Hosting Platforms

#### GitHub Pages (Recommended)
1. Create a GitHub account (if you don't have one)
2. Create a new repository: `soar-light-foundation`
3. Upload all files to the repository
4. Go to Settings > Pages
5. Select branch: main, folder: / (root)
6. Click Save
7. Your site will be live at: `https://yourusername.github.io/soar-light-foundation`

#### Netlify
1. Create account at netlify.com
2. Drag and drop your project folder to Netlify
3. Get instant live URL
4. Optional: Connect custom domain

#### Vercel
1. Create account at vercel.com
2. Import your project
3. Deploy with one click
4. Get live URL instantly

### Option 2: Paid Hosting

#### Shared Hosting (Recommended for Small Organizations)
- **Providers:** Bluehost, SiteGround, HostGator, DreamHost
- **Cost:** $3-10/month
- **Process:**
  1. Purchase hosting plan
  2. Upload files via FTP or cPanel File Manager
  3. Point your domain to the files
  
#### VPS Hosting (For More Control)
- **Providers:** DigitalOcean, Linode, Vultr
- **Cost:** $5-20/month
- **Requires:** Some technical knowledge

### Domain Name
- Purchase from: Namecheap, GoDaddy, Google Domains
- Cost: $10-15/year
- Recommended: soarlightfoundation.org or soarlightfoundation.co.za

## Customization Guide

### Updating Content

#### Changing Text Content
- Open `index.html`
- Find the section you want to edit
- Update the text between the HTML tags
- Save the file

#### Changing Colors
- Open `css/style.css`
- Find the `:root` section at the top
- Modify the color variables:
```css
:root {
    --primary-blue: #0066CC;      /* Change primary blue */
    --dark-blue: #003D7A;         /* Change dark blue */
    --primary-yellow: #FDB913;    /* Change yellow */
    /* ... more colors */
}
```

#### Adding Images
1. Add your image to the `images/` folder
2. In HTML, reference it like:
```html
<img src="images/your-image.jpg" alt="Description">
```

#### Updating Logo
- Replace `images/logo.png` with your new logo
- Keep the same filename or update references in HTML

### Adding New Sections
1. Copy an existing section structure from `index.html`
2. Modify the content
3. Add corresponding styles in `css/style.css`
4. Update navigation menu if needed

## Contact Form Setup

The contact form currently shows a success message and logs data to console. To make it functional:

### Option 1: Email Service (Recommended for Non-Profits)

#### Using Formspree (Free for up to 50 submissions/month)
1. Visit formspree.io
2. Create a free account
3. Create a new form
4. Copy your form endpoint
5. Update the form in `index.html`:
```html
<form id="contact-form" action="https://formspree.io/f/YOUR-FORM-ID" method="POST">
```

#### Using EmailJS (Free tier available)
1. Visit emailjs.com
2. Create account and service
3. Add EmailJS library to your HTML
4. Configure in `js/main.js`

### Option 2: Server-Side Solution
- Requires backend (PHP, Node.js, etc.)
- Recommended if you have web hosting with server-side support

## Social Media Links

Update social media links in `index.html`:
```html
<!-- Find this section and update href attributes -->
<div class="social-links">
    <a href="https://facebook.com/yourpage" class="social-link facebook">
    <a href="https://instagram.com/yourhandle" class="social-link instagram">
    <a href="https://tiktok.com/@yourhandle" class="social-link tiktok">
    <a href="https://twitter.com/yourhandle" class="social-link twitter">
</div>
```

## Banking Details

Update banking details for donations in `index.html`:
```html
<!-- Find the donate section and update -->
<div class="bank-details">
    <p><strong>Account Name:</strong> Soar Light Foundation</p>
    <p><strong>Bank:</strong> [Your Bank Name]</p>
    <p><strong>Account Number:</strong> [Your Account Number]</p>
    <p><strong>Branch Code:</strong> [Your Branch Code]</p>
</div>
```

## SEO Optimization

### Update Meta Tags
In `index.html`, update the meta tags:
```html
<meta name="description" content="Your updated description">
<meta name="keywords" content="your, keywords, here">
```

### Add Google Analytics (Optional)
1. Create Google Analytics account
2. Get tracking code
3. Add before `</head>` in `index.html`

## Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Tips
- Optimize images (use tools like TinyPNG)
- Enable caching if using a server
- Consider using a CDN for Font Awesome

## Maintenance

### Regular Updates
- Update project information regularly
- Add new projects to the Projects section
- Keep impact statistics current
- Update team information

### Backup
- Keep regular backups of all files
- Use version control (Git) for tracking changes

## Support & Help

### Resources
- HTML: w3schools.com/html
- CSS: w3schools.com/css
- JavaScript: javascript.info

### Getting Help
For technical support or customization help, contact your web developer or:
- Hire on Fiverr/Upwork
- Post on Stack Overflow
- Contact local web development communities

## License & Credits

### Design & Development
- Custom designed for Soar Light Foundation
- Built with modern web technologies
- Font Awesome for icons
- Google Fonts (Poppins & Playfair Display)

### Usage Rights
This website is designed specifically for Soar Light Foundation. 
All rights reserved.

## Contact Information

**Soar Light Foundation**
- **Location:** South Africa
- **Phone:** +27 63 913 4155
- **Email:** chipunzalight@gmail.com

---

## Quick Start Checklist

- [ ] Update all placeholder text with actual content
- [ ] Replace or verify logo
- [ ] Update banking details for donations
- [ ] Add social media links
- [ ] Update contact information
- [ ] Test all forms
- [ ] Test on mobile devices
- [ ] Set up form submission (Formspree/EmailJS)
- [ ] Purchase domain name
- [ ] Deploy to hosting
- [ ] Set up SSL certificate (HTTPS)
- [ ] Submit to Google Search Console
- [ ] Test all links
- [ ] Create backup

---

**Version:** 1.0  
**Last Updated:** February 2025  
**Status:** Production Ready

For questions or support, contact your web administrator.

---

*Empowering Lives, Illuminating Hope* 🕊️# Soar-Light-Foundation
# Soar-Light-Foundation
