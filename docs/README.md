# Grayshift Documentation

This directory contains the complete HTML documentation for the Grayshift front-end component library.

## Structure

```
docs/
├── index.html                 # Main documentation homepage
├── getting-started/           # Getting Started guides
│   ├── introduction.html      # Introduction to Grayshift
│   ├── installation.html      # Installation instructions
│   └── quick-start.html       # Quick start guide
├── components/                # Component documentation
│   ├── buttons.html          # Button components
│   ├── forms.html            # Form controls
│   ├── cards.html            # Card components
│   ├── navbar.html           # Navigation bar
│   ├── dropdown.html         # Dropdown menus
│   └── modal.html            # Modal dialogs
├── layout/                    # Layout documentation
│   ├── containers.html       # Container system
│   └── grid.html             # Grid system
├── utilities/                 # Utilities documentation
│   └── helpers.html          # Helper classes and utilities
├── examples/                  # Example pages
│   └── showcase.html         # Component showcase
├── css/                       # Grayshift CSS files
├── js/                        # Grayshift JavaScript files
└── assets/                    # Documentation assets
```

## Viewing the Documentation

### Local Development

1. Open `docs/index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python
   cd docs
   python3 -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server docs
   ```
3. Navigate to http://localhost:8000

### Hosting

The documentation can be hosted on any static file hosting service:
- GitHub Pages
- Netlify
- Vercel
- Any web server

Simply upload the entire `docs/` directory.

## Features

- **Comprehensive Coverage**: Complete documentation for all Grayshift components
- **Interactive Examples**: Live component examples with code snippets
- **Responsive Design**: Documentation site is fully responsive
- **Easy Navigation**: Sidebar navigation and breadcrumbs
- **Searchable**: Well-structured HTML for easy searching
- **Copy-Paste Ready**: All code examples are ready to use

## Pages Overview

### Getting Started
- **Introduction**: Overview of Grayshift, key features, and browser support
- **Installation**: Download and installation instructions
- **Quick Start**: Get up and running quickly with basic examples

### Components
- **Buttons**: All button styles, sizes, and states
- **Forms**: Form controls, inputs, checkboxes, and input groups
- **Cards**: Card components with various layouts
- **Navbar**: Responsive navigation bars
- **Dropdown**: Dropdown menus and button dropdowns
- **Modal**: Modal dialogs and their variations

### Layout
- **Containers**: Container system for responsive layouts
- **Grid System**: 12-column responsive grid with breakpoints

### Utilities
- **Helpers**: Utility classes for spacing, display, flexbox, text, and more

### Examples
- **Showcase**: Real-world examples combining multiple components

## Contributing

To update the documentation:

1. Edit the HTML files in the `docs/` directory
2. Keep consistent styling and structure
3. Test on multiple browsers and devices
4. Ensure all links work correctly

## License

The documentation is released under the same MIT License as Grayshift.
