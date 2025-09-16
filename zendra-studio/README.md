# Zendra Studio Website

A clean, modern website for Zendra Studio built with Hugo.

## Features

- **Homepage**: Clean landing page with company tagline and service overview
- **Privacy Policy**: Comprehensive privacy policy page
- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern UI**: Clean, uncluttered design following user-friendly principles

## Getting Started

### Prerequisites

- Hugo (extended version recommended)
- Git

### Development

1. Clone the repository
2. Navigate to the project directory
3. Run the development server:
   ```bash
   hugo server --buildDrafts
   ```
4. Open http://localhost:1313 in your browser

### Building for Production

```bash
hugo --buildDrafts
```

The generated site will be in the `public/` directory.

## Deployment

This site is designed to be deployed to Cloudflare Pages:

1. Push your code to GitHub
2. Connect your GitHub repository to Cloudflare Pages
3. Set the build command to: `hugo --buildDrafts`
4. Set the build output directory to: `public`

## Project Structure

```
zendra-studio/
├── content/           # Content files (Markdown)
├── themes/           # Custom Hugo theme
├── static/           # Static assets (images, etc.)
├── hugo.toml         # Hugo configuration
└── public/           # Generated site (after build)
```

## Customization

- Edit `content/_index.md` for homepage content
- Edit `content/privacy.md` for privacy policy
- Modify `themes/zendra-theme/layouts/_default/baseof.html` for styling changes
- Add your logo to `static/` directory and update the template as needed
