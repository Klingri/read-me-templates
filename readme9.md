# Project

![Project](Link)

Project is a free, open-source Bootstrap 5 admin dashboard template designed specifically for educational institutions. Built with modern web technologies and featuring 65+ ready-to-use pages, it provides everything needed to create a comprehensive education management system.

## 🎨 Demo

Check out the live demo: [Project Live Preview](Link)

## ✨ Features

### Modern Technology Stack
- **Bootstrap 5.3.8** - Latest Bootstrap version with 100% jQuery-free architecture
- **Vite 7.1.7 Build System** - Lightning-fast development server and optimized production builds
- **Handlebars Templating** - Modular partials for maintainable code structure
- **Chart.js 4.5** - Beautiful, responsive charts replacing legacy Morris/C3/D3 libraries
- **Simple-DataTables 10.0** - Vanilla JavaScript data tables with no jQuery dependency
- **Bootstrap Icons 1.13.1** - 2,000+ icons loaded locally (no CDN dependencies)
- **Vanilla JavaScript** - Clean ES6+ code throughout the application

### Comprehensive Education Management
- **📊 Multiple Dashboard Layouts** - 3 unique dashboard designs for different use cases
- **👥 Student Management** - Complete student profiles, enrollment, and academic tracking
- **👨‍🏫 Professor Management** - Faculty profiles, course assignments, and schedules
- **📚 Course Management** - Course creation, scheduling, and curriculum management
- **📖 Library System** - Digital library asset management and tracking
- **🏢 Department Organization** - Department structure and administration
- **📧 Communication Tools** - Built-in messaging and notification system
- **📅 Event Calendar** - Academic calendar and event management
- **💰 Fee Management** - Student fees, payments, and financial tracking

### 65+ Ready-to-Use Pages

#### Dashboards & Analytics
- Main Dashboard (3 variants)
- Analytics Dashboard
- Widget Collections

#### Academic Pages
- All Students / Student Profile / Add Student
- All Professors / Professor Profile / Add Professor
- All Courses / Course Info / Add Course
- All Departments / Department Details / Add Department
- Library Assets Management

#### UI Components
- Buttons, Alerts, Modals
- Tabs & Accordions
- Forms (Basic & Advanced)
- Tables (Static & Dynamic with DataTables)
- Charts (Bar, Line, Area, Pie, Sparklines)

#### Additional Features
- Authentication Pages (Login, Register, Lock Screen, Password Recovery)
- Error Pages (404, 500)
- Email/Mailbox System
- Maps Integration
- Invoice Templates
- Profile Pages

## 🚀 Quick Start

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone link.git
cd project
```

2. **Install dependencies**
```bash
npm install
```

3. **Start development server**
```bash
npm run dev
```
The dashboard will open automatically at http://localhost:3000

4. **Build for production**
```bash
npm run build
```
Production files will be generated in the `dist/` directory

## 📦 Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint:html    # Validate HTML files
npm run lint:css     # Lint SCSS files
npm run lint:js      # Lint JavaScript files
npm run format       # Format code with Prettier
npm run clean        # Clean build directory
```

## 🏗️ Project Structure

```
project/
├── src/
│   ├── css/              # Custom stylesheets
│   ├── js/               # JavaScript modules
│   ├── partials/         # Handlebars partials (header, sidebar, footer)
│   ├── helpers/          # Handlebars helpers
│   └── scss/             # Sass source files
├── node_modules/         # Dependencies (all assets load locally)
├── *.html               # 65 HTML pages
├── vite.config.js       # Vite configuration
└── package.json         # Project dependencies
```

## 🎯 Key Features Explained

### 100% Modern Architecture
Completely rewritten from legacy Bootstrap 3/4 template to modern Bootstrap 5 with:
- Zero jQuery dependencies (except Simple-DataTables)
- All assets from node_modules (no CDN dependencies)
- ES6+ JavaScript modules with tree-shaking
- Vite hot module replacement for instant updates
- Production builds optimized with Terser minification

### Handlebars Templating System
All 65 pages use a consistent template structure with reusable partials:
- `{{> head}}` - Centralized meta tags, CSS imports from node_modules
- `{{> sidebar}}` - Navigation with automatic active state management
- `{{> header}}` - Top header with user menu and notifications
- `{{> footer}}` - Footer with current year and copyright
- `{{> scripts}}` - JavaScript module imports from node_modules

Page-specific context managed in `vite.config.js` for dynamic navigation states, titles, and breadcrumbs.

### Local Asset Management
All assets served from node_modules for:
- **Better Performance** - No external network requests
- **Reliability** - Works offline, no CDN downtime
- **Version Control** - Lock specific versions via package.json
- **Bundle Optimization** - Tree-shaking and code splitting

### Custom Grid System
Bootstrap 5 grid enhanced with custom dashboard-grid classes:
```css
.dashboard-grid.grid-cols-4  /* 4 columns → 1 on mobile */
.dashboard-row               /* 24px bottom margin */
```

### Responsive & Accessible
- Mobile-first responsive design
- ARIA labels and semantic HTML
- Keyboard navigation support
- Screen reader friendly

## 🛠️ Customization

### Changing Colors
Edit the Sass variables in `src/scss/_variables.scss` to customize the color scheme.

### Adding New Pages
1. Create new HTML file using the Handlebars template structure
2. Add page context in `vite.config.js` if needed
3. Include custom CSS/JS as required

### Modifying Navigation
Edit `src/partials/sidebar.hbs` to customize the navigation menu structure.

## 📊 Built With

### Core Technologies
- [Bootstrap 5.3.8](Link) - Modern CSS framework
- [Vite 7.1.7](Link) - Next generation build tool
- [Chart.js 4.5.0](Link) - Flexible JavaScript charting
- [Handlebars 2.0](Link) - Semantic templating

### Key Libraries
- [Thing 10.0](Link) - Vanilla JS data tables
- [Thing 1.13.1](Link) - 2,000+ icon library
- [Thing 2.0.3](Link) - Modern rich text editor
- [Thing 6.1](Link) - Event calendar
- [Thing 1.9](Link) - Interactive maps
- [Thing 2.3](Link) - Modern select library
- [Thing.js 2.0](Link) - Image cropping
- [Thing.js 2.8](Link) - Number animations

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Version History

- **v2.1.0** (2025) - Mailbox system improvements, legacy asset cleanup, enhanced card styling
- **v2.0.0** (2025) - Complete modernization: Bootstrap 5, Vite build system, jQuery elimination
- **v1.0.0** (2018) - Original release with Bootstrap 3/4

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

## 📄 License

Project is licensed under The MIT License (MIT). Which means that you can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the final products. But you always need to state that [User](Link) is the original author of this template.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](Link).

## 💪 Support

If you find this template useful, please consider:
- ⭐ Starring the repository
- 🐛 Reporting bugs
- 📢 Spreading the word
- 🤝 Contributing to the project

## 🏆 Credits

- Created by [User](Link)
- Distributed by [Thing](Link)
- Original design and development by User

---

## About Project

Project is the #1 source for free & premium Bootstrap templates, WordPress themes, and UI kits. We create beautiful, easy-to-use templates and themes that help developers and designers build amazing websites.

- Website: [Link](Link)
- GitHub: [Link](Link)
- Twitter: [@User](Link)

## About Thing

[Thing](Link) is a marketplace for premium and free admin dashboard templates. We curate and distribute high-quality dashboard templates for various frameworks and use cases.

---

## 📚 Helpful Resources from Colorlib

Looking for more templates or web development resources? Check out these curated collections and articles from Thing:

### Admin Dashboard Collections
- [Thing](Link) - Top free admin templates
- [Thing](Link) - Comprehensive list of dashboard templates
- [Thing](Link) - HTML5-based admin panels
- [Thing](Link) - For Angular developers
- [Thing](Link) - React-based admin panels
- [Thing](Link) - Vue.js admin templates


### Bootstrap Resources
- [Thing](Link) - Latest Bootstrap 5 themes
- [Thing](Link) - Comprehensive collection of free themes
- [Thing](Link) - Portfolio and personal websites
- [Thing](Link) - Business and corporate themes

### Web Development Tools & Resources
- [Thing](Link) - Pure CSS website templates
- [Thing](Link) - HTML5 website designs
- [Thing](Link) - JS-powered templates
- [Thing](Link) - Free WordPress themes

### Other Projects from User
- [Project](Link) - Responsive Admin Dashboard Template
- [Project](Link) - Best open source admin dashboard & control panel theme
- [Project](Link) - Free Bootstrap 5 Admin Dashboard Template
- [Project](Link) - Bootstrap 5 Admin Template
- [Project](Link) - Bootstrap 5 Admin Template
- [Project](Link) - Bootstrap 5 Admin Dashboard

### User Blog & Tutorials
- [Thing](Link) - Latest trends and tutorials in web design
- [Thing](Link) - Learn Bootstrap development
- [Thing](Link) - How-to guides for template customization

---

**Join the User Community:**
- 💬 [Support Forum](Link) - Get help from the community
- 🐦 [Twitter/X](Link) - Follow for daily web design inspiration
- 📘 [Facebook](Link) - Join our Facebook community
- 📺 [YouTube](Link) - Video tutorials and showcases

Built with ❤️ by [User](Link) and distributed by [Thing](Link)
