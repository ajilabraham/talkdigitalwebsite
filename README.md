# Talk Digital Website - Complete Exact Clone

A pixel-perfect, complete offline clone of [www.talkdigital.co.in](https://www.talkdigital.co.in).

This project contains all pages, stylesheets, JavaScript libraries, Elementor modules, images, SVGs, icons, and fonts extracted directly from the live site, with internal paths sanitized and rewritten for standalone local execution and hosting.

---

## 🚀 Quick Start

You can run the site locally with zero additional npm packages installed using Node.js:

```bash
# Start the local server
npm start
# or
node server.js
```

Then open your browser to:
👉 **[http://localhost:3000](http://localhost:3000)**

---

## 📄 Cloned Pages (22 Total)

| Page | Local Path | Description |
| :--- | :--- | :--- |
| **Home** | `index.html` | Hero section, Services cards, Counter stats, Skills overview, Reviews |
| **About Us** | `about-us/index.html` | Company story, Global presence, Team vision |
| **Services** | `services/index.html` | Overview of digital solutions |
| **Mobile App Development** | `services/mobile-app-development/index.html` | iOS & Android mobile application capabilities |
| **Web App Development** | `services/web-app-development/index.html` | Custom web applications and e-commerce |
| **AI Solutions** | `services/ai-solutions/index.html` | Advanced AI integrations and ethical AI practices |
| **Portfolio** | `portfolio/index.html` | Showcase of client work and case studies |
| **Portfolio: Woower** | `portfolio/woower/index.html` | Mobile app case study |
| **Portfolio: SFH** | `portfolio/sfh-sure-fire-hire/index.html` | Sure Fire Hire web application case study |
| **Portfolio: IG3** | `portfolio/ig3/index.html` | Web application maintenance |
| **Portfolio: TFH** | `portfolio/tfh/index.html` | Corporate portal website development |
| **Portfolio: Eben** | `portfolio/eben-technologies/index.html` | PMO management case study |
| **Portfolio: Palm Beach** | `portfolio/palm-beach/index.html` | E-commerce web application case study |
| **Portfolio: Centrepoint** | `portfolio/centrepoint-finance/index.html` | Website development case study |
| **Contact Us** | `contact-us/index.html` | Contact form, map, email, phone, location |
| **Blog** | `blog/index.html` | Insights and news blog archive |
| **Hello World Post** | `hello-world/index.html` | Sample post article |
| **Case Study Temp** | `case-study-temp/index.html` | Extended case study template |
| **Category: Uncategorized** | `category/uncategorized/index.html` | Category archive listing |
| **Author Archive** | `author/supporttalkdigital-co-in/index.html` | Author archive listing |
| **Privacy Policy** | `privacy-policy/index.html` | Legal privacy notice |
| **Terms and Conditions** | `terms-and-conditions/index.html` | Terms of service |

---

## 📁 Directory Structure

```
Talk Digital Website/
├── index.html                           # Main Homepage
├── about-us/                            # About Us page
├── services/                            # Services index & sub-services
│   ├── index.html
│   ├── mobile-app-development/
│   ├── web-app-development/
│   └── ai-solutions/
├── portfolio/                           # Portfolio index & case studies
│   ├── index.html
│   ├── woower/
│   ├── sfh-sure-fire-hire/
│   ├── ig3/
│   ├── tfh/
│   ├── eben-technologies/
│   ├── palm-beach/
│   └── centrepoint-finance/
├── contact-us/                          # Contact Us page
├── blog/                                # Blog page
├── case-study-temp/                     # Case Study layout
├── privacy-policy/                      # Privacy Policy
├── terms-and-conditions/                # Terms & Conditions
├── wp-content/                          # All CSS, JS, uploads, fonts, icons
│   ├── plugins/
│   ├── themes/
│   └── uploads/
├── wp-includes/                         # Core WordPress JS libraries
├── server.js                            # Zero-dependency local preview server
├── package.json                         # NPM scripts (`npm start`)
└── README.md                            # Documentation
```

---

## 🛠 Features & Fidelity

- **Zero Missing Assets**: All images, Elementor stylesheets, scripts, fonts (Themify, FontAwesome, ElegantIcons), and favicons are stored locally.
- **Clean Routing**: The included `server.js` serves both trailing-slash and non-trailing slash routes (`/about-us` and `/about-us/`) seamlessly.
- **Responsive Layout**: Elementor grid breakpoints, mobile hamburger menus, sliders, counters, and animations run out of the box.
- **Zero Dependencies**: `server.js` runs with pure Node.js standard libraries (`http`, `fs`, `path`, `url`).
