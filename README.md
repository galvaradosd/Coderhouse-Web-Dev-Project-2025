# New World Radio

A static website for New World Radio built with HTML and Sass. Features program listings, schedules, and event information.

## 🚀 Quick Start

1. Install dependencies:
```bash
npm install
```

2. Run Sass compiler:
```bash
# One-off compile
npx sass assets/sass/styles.scss assets/css/styles.css --no-source-map

# Watch mode
npx sass --watch assets/sass:assets/css --no-source-map
```

3. Open `index.html` in your browser or use Live Server

## 📁 Project Structure

```
├── assets/
│   ├── css/           # Compiled CSS
│   ├── images/        # Images and media
│   └── sass/          # Sass source files
│       ├── abstracts/ # Variables, mixins, functions
│       ├── base/      # Base styles
│       ├── components/# Reusable components
│       ├── layout/    # Layout components
│       ├── pages/     # Page-specific styles
│       └── responsive/# Media queries
├── public/           
│   └── radio-shows/   # Program pages
└── index.html         # Main entry point
```

## 🛠 Development

- HTML: Static pages in root and `public/` directory
- Styles: Sass files in `assets/sass/`, compiled to `assets/css/styles.css`
- Images: Store in `assets/images/` using relative paths

### Style Guidelines

- Use Sass module system (`@use`) for imports
- Access variables as `variables.$variable-name`
- Keep paths relative to root (e.g., `./assets/images/`)
- Use existing class naming conventions

## 🧩 Components

- Header (`nwr-header`)
- Hero section
- Program cards
- Live player
- Footer

## 📱 Responsive Design

Breakpoints defined in `assets/sass/abstracts/_variables.scss`:
- Mobile: Default
- Tablet: 768px
- Desktop: 1024px
- Large Desktop: 1440px

## 🔍 Scripts

No npm scripts defined - use npx commands directly:
```bash
npx sass assets/sass/styles.scss assets/css/styles.css --no-source-map
```

## 📝 License

Private project - All rights reserved
