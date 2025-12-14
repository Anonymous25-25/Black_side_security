# CyberGuard - Professional Cybersecurity Website

A comprehensive, modern, and fully responsive cybersecurity website built with pure HTML, CSS, and JavaScript. Features a dark theme by default with a light theme toggle, smooth animations, and professional design.

## 🌟 Features

### Pages
1. **Home** - Modern landing page with hero section, services showcase, and statistics
2. **Articles** - Cybersecurity blog with 6+ detailed articles on various security topics
3. **Login** - Secure login page with password visibility toggle and social auth options
4. **Tools** - Showcase of popular cybersecurity tools with filtering functionality
5. **Portfolio** - Project showcase with filtering and modal views
6. **Dashboard** - Admin-style security dashboard with real-time charts and metrics
7. **Gallery** - Image gallery with lightbox functionality for cybersecurity visuals
8. **About** - Professional profile with skills, experience timeline, and certifications
9. **Contact** - Contact form with info cards and map placeholder

### Key Features
- ✅ **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- ✅ **Dark/Light Theme Toggle** - User preference saved in localStorage
- ✅ **Smooth Animations** - CSS transitions and hover effects throughout
- ✅ **Interactive Charts** - Dashboard with Chart.js for data visualization
- ✅ **Image Lightbox** - Gallery with full-screen image viewing
- ✅ **Form Validation** - Client-side validation on all forms
- ✅ **Filtering Systems** - Tools and Portfolio pages with category filtering
- ✅ **Modern UI/UX** - Clean, professional cybersecurity-themed design
- ✅ **Font Awesome Icons** - Over 100+ icons used throughout the site
- ✅ **Organized Code** - Well-commented and structured codebase

## 🚀 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables, Flexbox, and Grid
- **JavaScript (ES6+)** - Vanilla JS for all interactions
- **Chart.js** - Data visualization on dashboard
- **Font Awesome** - Icon library
- **LocalStorage API** - Theme persistence

## 📂 Project Structure

```
webapp/
├── public/
│   ├── index.html                 # Home page
│   ├── static/
│   │   ├── css/
│   │   │   └── styles.css        # Complete stylesheet (~2500 lines)
│   │   ├── js/
│   │   │   ├── main.js          # Core functionality (theme, navigation)
│   │   │   ├── articles.js       # Articles page functionality
│   │   │   ├── login.js          # Login form handling
│   │   │   ├── tools.js          # Tools filtering
│   │   │   ├── portfolio.js      # Portfolio filtering & modals
│   │   │   ├── dashboard.js      # Charts and dashboard logic
│   │   │   ├── gallery.js        # Lightbox functionality
│   │   │   └── contact.js        # Contact form handling
│   │   └── pages/
│   │       ├── articles.html     # Blog/Articles page
│   │       ├── login.html        # Secure login page
│   │       ├── tools.html        # Security tools showcase
│   │       ├── portfolio.html    # Projects portfolio
│   │       ├── dashboard.html    # Admin dashboard
│   │       ├── gallery.html      # Image gallery
│   │       ├── about.html        # About/Profile page
│   │       └── contact.html      # Contact page
├── .gitignore
└── README.md
```

## 🎨 Design Features

### Color Scheme (Dark Theme)
- **Background**: `#0a0e27` (Primary), `#151932` (Secondary)
- **Cards**: `#1a1f3a`
- **Text**: `#e4e6eb` (Primary), `#b0b3b8` (Secondary)
- **Accent**: `#667eea` to `#764ba2` (Gradient)
- **Success**: `#10b981`
- **Warning**: `#f59e0b`
- **Error**: `#ef4444`

### Typography
- Font Family: Inter, System fonts
- Heading Sizes: 2rem - 3.5rem
- Body Text: 1rem (16px)
- Line Height: 1.6

### Responsive Breakpoints
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## 📄 Pages Overview

### 1. Home Page (/)
- Hero section with gradient background
- Statistics cards (500+ systems protected, 1200+ vulnerabilities found)
- Services grid (6 services)
- Latest articles preview (3 articles)
- Full footer with links and social media

### 2. Articles Page (/static/pages/articles.html)
- 6 featured cybersecurity articles:
  - Zero-Day Vulnerabilities
  - Multi-Factor Authentication
  - Network Threat Detection
  - OWASP Top 10
  - Modern Encryption Standards
  - Social Engineering Defense
- Expandable content with "Read More" functionality
- Tags and metadata for each article

### 3. Login Page (/static/pages/login.html)
- Email and password fields
- Password visibility toggle
- "Remember me" checkbox
- Social login options (Google, GitHub)
- Security badges (SSL, 2FA, Biometric)
- Information panel with security notices

### 4. Tools Page (/static/pages/tools.html)
- 12 popular cybersecurity tools:
  - Nmap, Burp Suite, Wireshark, Metasploit
  - Aircrack-ng, John the Ripper, Nikto, OWASP ZAP
  - Sqlmap, Hashcat, Hydra, Snort
- Category filtering (Scanning, Exploitation, Analysis, Wireless)
- Difficulty indicators (Easy, Medium, Advanced)
- Feature lists and external links

### 5. Portfolio Page (/static/pages/portfolio.html)
- 9 security projects
- Category filtering (Pentesting, CTF, Audits, Research)
- Modal popups with project details
- Statistics (findings, dates, severity)

### 6. Dashboard Page (/static/pages/dashboard.html)
- Sidebar navigation
- 4 statistics cards (Systems, Vulnerabilities, Threats, Score)
- 2 interactive charts (Line chart, Doughnut chart)
- Recent activity feed (5 items)
- Critical alerts section
- System health metrics with progress bars

### 7. Gallery Page (/static/pages/gallery.html)
- 12 cybersecurity-themed items
- Gradient backgrounds with icons
- Lightbox functionality
- Keyboard navigation (arrows, escape)
- Full-screen image viewing

### 8. About Page (/static/pages/about.html)
- Professional profile section
- 4 statistics (Experience, Projects, Certifications, Vulnerabilities)
- 6 technical skills with progress bars
- Experience timeline (4 positions)
- 6 certifications (OSCP, CEH, CISSP, GPEN, GCIH, OSWE)

### 9. Contact Page (/static/pages/contact.html)
- Contact form (name, email, phone, subject, message)
- 4 contact info cards (Address, Phone, Email, Hours)
- Social media links
- Emergency contact section
- Map placeholder

## 🔧 JavaScript Functionality

### Theme Toggle (main.js)
- Switches between dark and light themes
- Saves preference to localStorage
- Updates theme icon (moon/sun)
- Applies to all pages consistently

### Mobile Navigation (main.js)
- Responsive hamburger menu
- Smooth slide-in animation
- Click outside to close

### Dashboard Charts (dashboard.js)
- Threat detection line chart (7 days)
- Vulnerability severity doughnut chart
- Responsive and interactive
- Dark theme compatible

### Gallery Lightbox (gallery.js)
- Click to open full-screen view
- Next/Previous navigation
- Keyboard controls
- Smooth transitions

### Form Handling (login.js, contact.js)
- Client-side validation
- Loading states
- Success/error messages
- Form reset after submission

### Filtering (tools.js, portfolio.js)
- Category-based filtering
- Smooth fade animations
- Active state indicators

## 🎯 Usage

### Running Locally
Simply open `public/index.html` in a web browser. No build process required!

```bash
# Option 1: Double-click index.html

# Option 2: Use a local server
cd webapp/public
python3 -m http.server 8000
# Open http://localhost:8000

# Option 3: Use Live Server (VS Code extension)
# Right-click on index.html and select "Open with Live Server"
```

### Customization

#### Change Colors
Edit CSS variables in `static/css/styles.css`:
```css
:root {
    --bg-primary: #0a0e27;
    --accent-primary: #667eea;
    /* etc. */
}
```

#### Add New Pages
1. Create HTML file in `static/pages/`
2. Copy navigation from existing page
3. Add link in navigation menu
4. Create corresponding JS file if needed

#### Modify Content
All content is in HTML files - simply edit the text, add images, or modify structure.

## 🌐 Deployment

This is a static website and can be deployed to any static hosting service:

- **Cloudflare Pages**: Drag and drop the `public/` folder
- **Netlify**: Connect Git repository or drag and drop
- **GitHub Pages**: Push to `gh-pages` branch
- **Vercel**: Import repository
- **AWS S3**: Upload files to S3 bucket with static hosting
- **Firebase Hosting**: Use Firebase CLI

### Build Directory
Deploy the `public/` directory as your site root.

## 🔒 Security Features

- All forms have client-side validation
- Password fields include visibility toggle
- Security notices on login page
- Professional security-themed design
- No external dependencies (except CDN libraries)

## 📱 Responsiveness

### Mobile (< 768px)
- Hamburger menu navigation
- Stacked layout for all grids
- Touch-friendly buttons
- Optimized font sizes

### Tablet (768px - 1199px)
- 2-column grids where appropriate
- Adjusted spacing
- Balanced layout

### Desktop (1200px+)
- Full multi-column layouts
- Hover effects
- Optimal reading width (1200px container)

## 🎨 Icons & Images

- **Font Awesome 6.4.0** - All icons via CDN
- **Gradient Backgrounds** - CSS gradients for visual elements
- **Icon-based Images** - Font Awesome icons used as placeholders

## 📊 Dashboard Charts

### Chart Types
- **Line Chart**: Threat detection over time (7 days)
- **Doughnut Chart**: Vulnerability severity breakdown

### Chart Data
- All data is static/demo data
- Can be easily replaced with real API calls
- Chart.js v4.x compatible

## 🎓 Learning Resources

This project demonstrates:
- Modern CSS techniques (Grid, Flexbox, Variables)
- Vanilla JavaScript best practices
- Responsive design principles
- Theme switching implementation
- Form handling and validation
- Chart.js integration
- Modal/Lightbox implementation
- Local storage usage

## 📝 License

This project is open source and available for educational and commercial use.

## 👨‍💻 Author

Built with ❤️ by CyberGuard Team

## 🤝 Contributing

Feel free to fork this project and customize it for your needs!

## 📞 Support

For questions or issues, please contact info@cyberguard.com

---

**Live Demo**: Deploy to see it in action!
**Last Updated**: December 2024
**Version**: 1.0.0
