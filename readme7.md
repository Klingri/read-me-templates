# Project v1.0.0

**Project** is a responsive Bootstrap 5 Admin Template built with modern development tools.

**Latest Update (v1.0.0)**: Latest dependency updates including Bootstrap 5.3.8, comprehensive security updates, and modern tooling improvements ensuring optimal performance and maintainability.

**Looking for more premium admin templates?** Visit **[Thing](Link)** for a curated collection of high-quality admin dashboard templates for various frameworks and technologies.

**Performance Benefits**: Faster load times, smaller bundle size, modern ES6+ code, and zero jQuery overhead.

**[Complete Documentation](Link)** - Detailed setup guides, API reference, and examples

Preview of this awesome admin template available here: Link

# Preview

### Screenshots

**Light Mode:**
![Thing](Link)

**Dark Mode:**
![Thing](Link)

### Demo Site: [Here](Link)

## TOC
- [What's New in v2.8.1](#whats-new-in-v281)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing & Local Development](#installing--local-development)
- [Adminator for other platforms and frameworks](#adminator-for-other-platforms-and-frameworks)
- [Files/Folder Structure](#filesfolders-structure)
- [Deployment](#deployment)
- [Built With](#built-with)
- [Changelog](#changelog)
- [Authors](#authors)
- [License](#license)

## What's New in v2.8.1

### Latest Dependency Updates & Security Enhancements
- **Bootstrap 5.3.8**: Updated to latest Bootstrap version with bug fixes and improvements
- **Comprehensive Dependency Updates**: All dependencies updated to their latest stable versions
- **Enhanced ESLint Configuration**: Modern TypeScript ESLint support with zero linting errors
- **Security Updates**: All dependencies updated with zero vulnerabilities
- **Improved Build Performance**: Latest Webpack 5.101.3 with optimized build pipeline
- **Modern Tooling**: Updated Sass 1.92.0, Day.js 1.11.18, and enhanced development tools

### Previous Updates (v2.8.0)

### Dependency Modernization & Build System Enhancements
- **Webpack 5 Native Asset Modules**: Replaced deprecated file-loader with modern Webpack 5 asset handling
- **Updated Build Tools**: All build dependencies updated to latest stable versions
- **Cross-env v10**: Upgraded to latest version with ESM support and TypeScript improvements
- **Zero Build Warnings**: Fixed all import/export issues for cleaner builds
- **Security Updates**: Comprehensive dependency updates addressing all known vulnerabilities

### Technical Improvements
- Moved @babel/runtime to production dependencies for proper runtime support
- Updated TypeScript to v5.9.2 for enhanced type checking
- Updated ESLint to v9.33.0 with latest rules and fixes
- All FullCalendar components updated to v6.1.19
- Webpack updated to v5.101.0 with performance improvements

## What's New in v2.7.1

**jQuery-Free Release** - Complete removal of jQuery dependency with modern vanilla JavaScript:

### Major Performance Improvements
- **~600KB Bundle Reduction**: Eliminated jQuery and all jQuery-dependent plugins
- **Faster Load Times**: Native DOM manipulation for optimal performance
- **Smaller Bundle Size**: Significantly reduced JavaScript payload
- **Modern ES6+ Code**: Class-based architecture with modern JavaScript features

### jQuery Replacements (Zero Breaking Changes)
- **Chart.js**: Replaced jQuery Sparkline with Chart.js mini charts
- **HTML5 Date Pickers**: Enhanced native date inputs with Day.js support
- **Vanilla DataTables**: Custom table component with sorting and pagination
- **SVG Pie Charts**: Pure JavaScript circular progress indicators
- **Vector Maps**: JavaScript-based world map with markers and interactions
- **Vanilla Popovers**: Lightweight alternatives to Bootstrap JS components

### Technical Achievements
- **100% Vanilla JavaScript**: No jQuery dependency anywhere in the codebase
- **Component Architecture**: Modern class-based components (Sidebar, Charts, etc.)
- **Enhanced DOM Utilities**: jQuery-like functionality using native JavaScript
- **Mobile Optimized**: Touch-friendly interactions and responsive behavior
- **Theme Integration**: All new components fully support dark/light mode switching

### Previous Updates (v2.6.0 - Dark Mode System)

### Dark Mode Features
- **Smart Theme Toggle**: Bootstrap-based switch with sun/moon icons and intuitive labels
- **OS Preference Detection**: Automatically detects and applies your preferred color scheme  
- **Persistent Storage**: Remembers your theme choice across browser sessions
- **Instant Switching**: Real-time theme updates without page reload
- **Component Integration**: All charts, calendars, maps, and UI elements are theme-aware

### Technical Implementation
- **CSS Variables Architecture**: Comprehensive color system with semantic naming
- **Chart.js Integration**: Dynamic color schemes for all chart types
- **FullCalendar Support**: Dark-mode aware calendar with proper contrast
- **Vector Maps**: Custom color palettes for both light and dark themes
- **Component Compatibility**: Theme support across all interactive elements

### Previous Updates (v2.5.0)
- **Latest Dependencies**: All 22+ dependencies updated to latest versions  
- **Modern Build Tools**: webpack 5.99.9, webpack-dev-server 5.2.2
- **ESLint 9.x**: Migrated to modern flat config format
- **Enhanced CSS**: Latest Sass (1.89.2), PostCSS (8.5.6), Bootstrap (5.3.7)
- **Updated Components**: Chart.js 4.5.0, FullCalendar 6.1.17
- **Zero Vulnerabilities**: Complete security audit with all packages secure

## Getting Started

You can use **Project** in several ways:

### NPM Package Installation (Recommended)

Install the complete template as an npm package:

```bash
# Install via npm
npm install project

# Or install via yarn
yarn add project
```

**Package Information:**
- **Package Name**: `project`
- **Version**: 2.8.1 (Latest dependencies)
- **Size**: 5.7 MB (includes source + built assets)
- **Registry**: Link

**Usage after npm install:**
```bash
# Navigate to the package directory
cd node_modules/project

# Install development dependencies (if you want to customize)
npm install

# Start development server
npm start
```

**What's included in the npm package:**
- Complete source code (`src/` directory)
- Pre-built production assets (`dist/` directory)
- All dependencies and development tools
- Documentation (CLAUDE.md, CHANGELOG.md)
- Ready-to-use HTML templates

### Local Development Setup

For development and customization, clone the repository:

#### Prerequisites
  - **Node.js 18.12.0 or higher** (tested with Node.js 23.11.0)
  - **npm** (included with Node.js) or **Yarn**
  - **Git**

#### Installing & Local Development

```bash
# Clone the repository
git clone link

# Navigate to the project directory
cd project

# Install dependencies
npm install

# Start development server (available at http://localhost:4000)
npm start

# Alternative: Start with thing
npm run dev
```

### Quick Start Options

1. **Fastest**: Use prebuilt static assets from [releases](Link)
2. **Recommended**: Install via npm package for easy updates
3. **Development**: Clone repository for full customization

#### Development Commands

```bash
# Development server with hot reload
npm start

# Development server with thing
npm run dev

# Build for production (optimized)
npm run build

# Build for production (unminified)
npm run release:unminified

# Build for production (minified)
npm run release:minified

# Preview production build
npm run preview

# Lint JavaScript files
npm run lint:js

# Lint SCSS files  
npm run lint:scss

# Run all linters
npm run lint
```

## Dark Mode Usage

Adminator now includes a comprehensive dark mode system that works out of the box:

### Automatic Setup
- Dark mode is automatically initialized on page load
- Detects your OS preference (light/dark) on first visit
- Remembers your choice across browser sessions

### Theme Toggle
- Look for the **Light/Dark** toggle switch in the header navigation
- Click to instantly switch between light and dark themes
- Visual feedback with sun and moon icons

### For Developers

**[Complete Theme API Documentation →](Link)**

**Using the Theme API:**
```javascript
// Get current theme
const currentTheme = Theme.current(); // 'light' or 'dark'

// Switch themes programmatically
Theme.toggle();

// Set specific theme
Theme.apply('dark');

// Listen for theme changes
window.addEventListener('adminator:themeChanged', (event) => {
  console.log('Theme changed to:', event.detail.theme);
});
```

**CSS Variables for Custom Styling:**
```css
.my-component {
  background: var(--c-bkg-card);
  color: var(--c-text-base);
  border: 1px solid var(--c-border);
}
```

**Available CSS Variables:**
- `--c-bkg-body` - Main background
- `--c-bkg-card` - Card backgrounds  
- `--c-text-base` - Primary text color
- `--c-text-muted` - Secondary text color
- `--c-border` - Border colors
- `--c-primary` - Primary brand color

**[View Complete CSS Variables Reference →](Link)**

## Documentation

**[Complete Documentation Site](Link)** - Comprehensive guides and API reference

### Quick Links:
- **[Installation Guide](Link)** - Complete setup instructions
- **[Theme System](Link)** - Dark mode and theming
- **[API Reference](Link)** - JavaScript API documentation
- **[Examples](Link)** - Integration examples

## Project for other platforms and frameworks
* [Project right to left](Link) - Project modified to work with right to left languages like Persian and Arabic

## Files/Folders Structure

Here is a brief explanation of the template folder structure and some of its main files usage:

```
└── src                         # Contains all template source files.
│   └── assets                  # Contains JS, CSS, images and icon fonts.
│   │   └── scripts             # Contains all JavaScript files.
│   │   │   └── charts          # Chart.js, Sparkline & Pie Chart plugins init.
│   │   │   └── chat            # All chat app JS code.
│   │   │   └── constants       # Template constant values like color values.
│   │   │   └── datatable       # Date table plugin init.
│   │   │   └── datepicker      # Bootstrap datepicker init.
│   │   │   └── email           # All email app code.
│   │   │   └── fullcalendar    # Fullcalendar plugin init.
│   │   │   └── googleMaps      # Google maps API integration code.
│   │   │   └── masonry         # Masonry layout code.
│   │   │   └── popover         # Bootstrap popover plugin init.
│   │   │   └── scrollbar       # Perfect scrollbar plugin init.
│   │   │   └── search          # Topbar toggle search init.
│   │   │   └── sidebar         # Sidebar JS code.
│   │   │   └── skycons         # Animated icons plugin init.
│   │   │   └── utils           # Basic utils used for proper rendering.
│   │   │   └── vectorMaps      # Vector maps plugin init.
│   │   │   └── app.js          # Main application entry point.
│   │   │
│   │   └── static              # Contains the non-code files.
│   │   │   └── fonts           # Contains icon fonts.
│   │   │   └── images          # Contains all template images/svg.
│   │   │
│   │   └── styles              # Contains all SCSS files.
│   │       └── spec            # Contains custom SCSS files.
│   │       │   └── components  # Contains all template components.
│   │       │   └── generic     # Contains basic scaffolding styles.
│   │       │   └── screens     # Contains views specific styles.
│   │       │   └── settings    # Contains all template variables.
│   │       │   └── tools       # Contains all mixins.
│   │       │   └── utils       # Contains helper classes.
│   │       │   └── index.scss  # Indicator file.
│   │       │
│   │       └── vendor          # Contains all plugin files & custom styles.
│   │       └── index.scss      # Main style entry point.
│   │
│   └── *.html                  # All HTML template pages.
└── webpack                     # Contains Webpack configuration.
│   └── plugins                 # Contains all Webpack plugins config.
│   └── rules                   # Contains Webpack loaders config.
│   └── config.js               # Main Webpack configuration.
│   └── devServer.js            # Development server configuration.
│   └── manifest.js             # Build system constants.
│
└── .babelrc                    # Babel ES6 transpiler configuration.
└── .editorconfig               # Code editor consistency settings.
└── eslint.config.mjs           # ESLint 9.x flat configuration.
└── .gitattributes              # Git attributes configuration.
└── .gitignore                  # Git ignore patterns.
└── .stylelintrc.json           # SCSS/CSS linting configuration.
└── browserslist                # Supported browsers configuration.
└── CHANGELOG.md                # Version history and updates.
└── package.json                # Node.js package configuration.
└── README.md                   # This documentation file.
└── webpack.config.js           # Webpack entry configuration.
```

## Deployment

In deployment process, you have several commands:

1. **Production Build** - Generate optimized assets for production:
```bash
npm run build
```

2. **Production Preview** - Preview the production build locally:
```bash
npm run preview
```

3. **Custom Builds**:
```bash
# Unminified production build (for debugging)
npm run release:unminified

# Minified production build (smallest size)
npm run release:minified
```

The built files will be available in the `dist/` directory.

## Built With

### Core Framework & Build Tools
- [Bootstrap 5.3.8](Link) - Modern CSS framework
- [Webpack 5.101.3](Link) - Module bundler and build tool
- [Babel 7.28.x](Link) - JavaScript transpiler
- [Sass 1.92.0](Link) - CSS preprocessor
- [PostCSS 8.5.6](Link) - CSS transformations
- [ESLint 9.34.0](Link) - JavaScript linting (flat config)
- [Stylelint 16.23.1](Link) - CSS/SCSS linting

### UI Components & Charts
- [Chart.js 4.5.0](Link) - Modern charting library
- [FullCalendar 6.1.19](Link) - Interactive calendar
- [DataTables](Link) - Advanced table functionality
- [Easy Pie Chart](Link) - Animated pie charts
- [Perfect Scrollbar 1.5.6](Link) - Custom scrollbars

### JavaScript Libraries
- **[Chart.js 4.5.0](Link)** - Modern charting library (replaces jQuery Sparkline)
- **[jsvectormap 1.7.0](Link)** - Interactive vector maps (replaces jVectorMap)
- [Lodash 4.17.21](Link) - Utility library
- [Day.js 1.11.18](Link) - Modern 2KB date library (replaces Moment.js)
- [Masonry 4.2.2](Link) - Grid layouts
- **100% Vanilla JavaScript** - No jQuery dependency

### Icons & Fonts
- [Font Awesome](Link) - Icon library
- [Themify Icons](Link) - Additional icons
- [Roboto Font](Link) - Google Fonts

### Additional Plugins
- **HTML5 Date Inputs** - Enhanced native date pickers (replaces Bootstrap Datepicker)
- [Skycons](Link) - Animated weather icons
- [Load Google Maps API](Link) - Maps integration

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for detailed version history.

📚 **[Online Documentation](Link)** includes comprehensive guides for all features.

#### Latest Release: V 2.8.1 (2025-09-03)
- **Bootstrap 5.3.8** - Updated to latest Bootstrap version with bug fixes and improvements
- **Comprehensive Dependency Updates** - All dependencies updated to their latest stable versions
- **Enhanced ESLint Configuration** - Modern TypeScript ESLint support with zero linting errors
- **Security Updates** - All dependencies updated with zero vulnerabilities
- **Improved Build Performance** - Latest Webpack 5.101.3 with optimized build pipeline
- **Modern Tooling** - Updated Sass 1.92.0, Day.js 1.11.18, and enhanced development tools

#### Previous Releases
- **V 2.8.0**: Webpack 5 asset modules and dependency modernization
- **V 2.7.1**: 100% jQuery-Free with modern vanilla JavaScript
- **V 2.6.0**: Complete Dark Mode System with theme switching
- **V 2.5.0**: Updated all dependencies, ESLint 9.x, zero vulnerabilities
- **V 2.1.0**: Upgraded all dependencies
- **V 2.0.0**: Upgrade to Bootstrap 5
- **V 1.1.0**: Upgrade to webpack 5
- **V 1.0.0**: Initial Release

## Authors
[User](Link)

## Looking for More Admin Templates?

**Visit [Thing](Project)** - Your premier destination for high-quality admin dashboard templates:
- Premium and free admin templates for all major frameworks
- React, Vue, Angular, Bootstrap, and vanilla JavaScript templates
- Modern designs with dark mode support
- Comprehensive documentation and support
- Regular updates and new releases

## More Resources from Project
- [Thing](Link)
- [Thing](Link)
- [Thing](Link)
- [Thing](Link)
- [Thing](Link)
- [Thing](Link)
- [Thing](Link)

## License

Project is licensed under The MIT License (MIT). Which means that you can use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the final products. But you always need to state that User is the original author of this template.
