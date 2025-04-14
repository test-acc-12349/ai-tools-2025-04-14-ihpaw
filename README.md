# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals and enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR-BADGE/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Support & Resources](#support--resources)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools in a clean, three-column grid layout. Built with HTML5, CSS3, and JavaScript, it offers an intuitive browsing experience with filtering and search capabilities.

## Features

- 📱 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 🎨 Customizable design
- 📊 SEO optimized
- 🚀 Fast loading performance
- 💻 Cross-browser compatibility

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- Git
- Text editor (VS Code recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/ai-tools-directory.git

# Navigate to project directory
cd ai-tools-directory

# Install dependencies
npm install

# Start development server
npm run dev
```

## Directory Structure

```
ai-tools-directory/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── data/
│   └── directory-items.json
├── components/
├── layouts/
├── pages/
├── public/
└── README.md
```

## Customization Guide

### Adding Directory Items

1. Open `data/directory-items.json`
2. Add new items following this format:

```json
{
  "id": "unique-id",
  "title": "Tool Name",
  "description": "Tool description",
  "category": "Category",
  "url": "https://tool-url.com",
  "image": "/images/tool-image.png"
}
```

### Modifying Categories

Edit the categories in `data/categories.js`:

```javascript
export const categories = [
  "Machine Learning",
  "Natural Language Processing",
  "Computer Vision",
  "Robotics"
];
```

### Updating Hero Section

Modify the hero section in `components/Hero.js`:

```html
<div class="hero">
  <h1>Your New Title</h1>
  <p>Your new description</p>
</div>
```

### Customizing Colors

Edit the CSS variables in `assets/css/variables.css`:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
  --text-color: #333333;
}
```

## Deployment

### Netlify Deployment

1. Create a Netlify account
2. Connect your GitHub repository
3. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
4. Click "Deploy"

### Vercel Deployment

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

## Custom Domain Setup

1. Purchase domain from your preferred registrar
2. Add domain in deployment platform:
   ```
   Domain: yourdomain.com
   ```
3. Configure DNS settings:
   ```
   Type: A
   Name: @
   Value: [Your deployment platform's IP]
   ```
4. Wait for DNS propagation (24-48 hours)

## Troubleshooting

### Common Issues

1. **Images not loading**
   - Check image paths
   - Verify file extensions
   - Ensure images are in public directory

2. **Styling issues**
   - Clear browser cache
   - Check CSS specificity
   - Verify media queries

3. **Build failures**
   - Check Node.js version
   - Verify dependencies
   - Review build logs

## Support & Resources

- 📚 [Documentation](https://docs.example.com)
- 💬 [Discord Community](https://discord.gg/example)
- 🐛 [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- 📧 [Support Email](mailto:support@example.com)

### Additional Resources

- [Contributing Guidelines](CONTRIBUTING.md)
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](LICENSE.md)

---

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Made with ❤️ by [Your Name]