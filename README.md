# example008 Landing Page

A modern, responsive landing page built with Astro for the example008 product.

## Features

- ⚡ Built with Astro for optimal performance
- 📱 Fully responsive design
- 🎨 Modern UI with CSS Grid and Flexbox
- 🎯 Semantic HTML5 structure
- 🚀 Optimized for GitHub Pages deployment

## Project Structure

```
landing-page/
├── src/
│   ├── components/     # Reusable Astro components
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Features.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/        # Page layouts
│   │   └── BaseLayout.astro
│   └── pages/          # Page routes
│       └── index.astro
├── public/             # Static assets
├── astro.config.mjs    # Astro configuration
└── package.json
```

## Getting Started

### Prerequisites

- Node.js 18+ and npm

### Installation

```bash
cd landing-page
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

The site will be available at `http://localhost:4321`

### Build

Build the static site for production:

```bash
npm run build
```

The static files will be generated in the `docs/` directory, ready for GitHub Pages deployment.

### Preview

Preview the production build locally:

```bash
npm run preview
```

## Deployment to GitHub Pages

This project is configured to deploy to GitHub Pages:

1. The build output is set to `docs/` directory
2. Push your changes to the main branch
3. In your GitHub repository settings:
   - Go to Settings > Pages
   - Set Source to "Deploy from a branch"
   - Select the `main` branch and `/docs` folder
   - Save

The site will be available at: `https://mbarriosRojas.github.io/example008/`

## Technologies Used

- [Astro](https://astro.build/) - Static site generator
- HTML5 semantic elements
- CSS3 with custom properties (CSS variables)
- CSS Grid and Flexbox for layouts
- Responsive design with mobile-first approach

## License

All rights reserved.
