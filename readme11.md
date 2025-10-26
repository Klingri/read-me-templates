# Project - Modern Website

> Project Description

**🎉 Version 3.1.0 Release** - Updated to Bootstrap 5.3.8 with all dependencies upgraded to their latest versions, improved chart handling, and legacy code cleanup.

![Thing](Link)

**[🚀 View Live Demo](Link)**

[![License: MIT](Link)](https://opensource.org/licenses/MIT)
[![Bootstrap](Link)](https://getbootstrap.com)
[![Node.js](Link)](https://nodejs.org)

## ✨ Features

### 🎨 **Modern Design System**
- **Bootstrap 5.3.8** - Latest version with all modern utilities
- **CSS Custom Properties** - Full theme customization support
- **Dark/Light Mode** - Seamless theme switching with localStorage persistence
- **Responsive First** - Mobile-optimized layouts across all devices
- **Modern Typography** - Inter font family for enhanced readability

### 🚀 **Advanced Technology Stack**
- **Alpine.js 3.15.0** - Lightweight reactive framework for modern interactions
- **ES6+ JavaScript** - Modern JavaScript with modules and async/await
- **Vite 7.1.7** - Lightning-fast development and optimized production builds
- **SCSS Architecture** - Organized, scalable stylesheet structure with Sass 1.93.2
- **Bootstrap Icons 1.13.1** - 1,800+ high-quality SVG icons
- **ApexCharts 5.3.5** - Advanced charting library
- **Font Awesome 7.0.1** - Additional icon library

### 📊 **Comprehensive Dashboard Pages**
- **📈 Analytics Dashboard** - Charts, KPIs, and data visualization
- **👥 User Management** - Complete CRUD operations with modern forms
- **📦 Product Management** - E-commerce ready product listings
- **🛒 Order Management** - Order tracking and status management
- **📁 File Manager** - Modern file browser with upload/download
- **📅 Calendar** - Full-featured event management
- **💬 Messages** - Chat interface with real-time styling
- **📊 Reports** - Data tables with filtering and export
- **⚙️ Settings** - Comprehensive admin configuration
- **🔒 Security** - User permissions and security settings
- **❓ Help & Support** - FAQ, documentation, and support tickets

### 🛠️ **Developer Experience**
- **Hot Module Replacement** - Instant development feedback
- **TypeScript Ready** - Full TypeScript support (optional)
- **Component Architecture** - Modular, reusable JavaScript components
- **Modern Build Pipeline** - Optimized assets with automatic minification
- **Developer Tools** - Source maps, linting, and debugging support

## 🚀 Quick Start

### Prerequisites
- **Node.js 18+** (recommend using [nvm](Link))
- **npm** or **yarn** package manager

### Installation

```bash
# Clone the repository
git clone link.git project
cd project

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

### 📁 Project Structure

```
project/
├── src-modern/                 # Modern source files
│   ├── *.html                 # Page templates
│   ├── scripts/               # JavaScript modules
│   │   ├── components/        # Page-specific components
│   │   ├── utils/            # Utility functions
│   │   └── main.js           # Application entry point
│   ├── styles/               # SCSS stylesheets
│   │   ├── abstracts/        # Variables, mixins, utilities
│   │   ├── components/       # UI component styles
│   │   ├── layout/          # Layout-specific styles
│   │   ├── pages/           # Page-specific styles
│   │   └── themes/          # Theme variants
│   └── assets/              # Static assets
├── dist-modern/             # Production build output
├── node_modules/           # Dependencies
├── package.json           # Project configuration
├── vite.config.js         # Build configuration
└── README.md              # This file
```

## 🎯 Available Scripts

```bash
# Development
npm run dev          # Start development server with HMR
npm run dev:host     # Start dev server accessible on network

# Production
npm run build        # Create optimized production build
npm run preview      # Preview production build locally

# Maintenance
npm run clean        # Clean build artifacts
```

## 🎨 Customization

### Theme Customization

Edit `src-modern/styles/scss/abstracts/_variables.scss`:

```scss
// Brand Colors
$primary: #6366f1;    // Your brand primary color
$secondary: #64748b;  // Secondary color
$success: #10b981;    // Success state color

// Typography
$font-family-sans-serif: "Inter", system-ui, sans-serif;
$font-size-base: 0.9rem;

// Spacing & Layout
$border-radius: 0.75rem;
$box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1);
```

### Adding New Pages

1. Create HTML file in `src-modern/`
2. Add corresponding SCSS in `src-modern/styles/scss/pages/`
3. Create JavaScript component in `src-modern/scripts/components/`
4. Register in `src-modern/scripts/main.js`

### Component Development

```javascript
// src-modern/scripts/components/example.js
import Alpine from 'alpinejs';

document.addEventListener('alpine:init', () => {
  Alpine.data('exampleComponent', () => ({
    // Component state and methods
    init() {
      console.log('Example component initialized');
    }
  }));
});
```

## 🆕 What's New in v3.1.0

### Latest Updates (September 2025)
- ✅ **Bootstrap 5.3.8** - Latest framework version
- ✅ **All Dependencies Updated** - Every package upgraded to latest stable version
- ✅ **ApexCharts 5.3.5** - Major version upgrade with enhanced features
- ✅ **Font Awesome 7.0.1** - Major version upgrade with new icons
- ✅ **Chart Overflow Fix** - Improved responsive chart rendering
- ✅ **Legacy Code Cleanup** - Removed all Bootstrap 3 remnants
- ✅ **Enhanced Documentation** - Added CLAUDE.md for AI-assisted development

## 🌟 Key Improvements in v3.0

### From v2.x to v3.0
- ✅ **Bootstrap 3 → Bootstrap 5** - Complete framework upgrade
- ✅ **jQuery → Alpine.js** - Modern, lightweight reactive framework  
- ✅ **LESS → SCSS** - More powerful styling with better tooling
- ✅ **Gulp → Vite** - Lightning-fast build system with HMR
- ✅ **ES5 → ES6+** - Modern JavaScript with modules and async/await
- ✅ **Old Icons → Bootstrap Icons** - 1,800+ modern SVG icons
- ✅ **Static → Interactive** - Rich, app-like user interactions
- ✅ **Fixed → Responsive** - Mobile-first, adaptive layouts
- ✅ **Basic → Advanced** - Professional dashboard features

### Performance Improvements
- **90%+ Lighthouse Score** - Optimized for Core Web Vitals
- **Tree Shaking** - Only load code you actually use
- **Code Splitting** - Lazy load components for faster initial loads
- **Asset Optimization** - Automatic image and CSS optimization
- **Modern Bundle** - ES6+ for modern browsers with optimal tree-shaking

## 🛡️ Browser Support

- **Chrome** 90+
- **Firefox** 88+  
- **Safari** 14+
- **Edge** 90+

*IE11 is not supported.*

## 📚 Documentation & Resources

- **[Live Demo](Link)** - See the template in action
- **[Component Documentation](./docs/components.md)** - Detailed component guides
- **[Customization Guide](./docs/customization.md)** - Theme and styling customization
- **[Deployment Guide](./docs/deployment.md)** - Production deployment instructions

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](./CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE.md](LICENSE.md) file for details.

```
Copyright (c) 2025 User

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
```

## 🙏 Credits & Attribution

### Core Technologies
- **[Bootstrap 5](Link)** - The world's most popular CSS framework
- **[Alpine.js](Link)** - Lightweight reactive framework
- **[Vite](Link)** - Next generation frontend tooling
- **[Bootstrap Icons](Link)** - Official Bootstrap icon library

### Design Resources
- **[Inter Font](Link)** - Modern typeface designed for computer screens
- **[Heroicons](Link)** - Additional beautiful hand-crafted SVG icons

## 👥 About the Authors

**[User](Link)** - The most popular source for free WordPress themes and HTML templates.

**[User](Link)** - Project maintainer and founder of Project.

## 🔗 Related Projects

- **[Thing](Link)**
- **[Thing](Link)**
- **[Thing](Link)**

---

**⭐ Star this repository if you found it helpful!**

*Built with ❤️ by the User*
