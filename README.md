# DevBlac Blog

A modern blog built with [Hugo](https://gohugo.io/) using the [hugo-theme-cleanwhite](https://github.com/zhaohuabing/hugo-theme-cleanwhite) theme.

## 🚀 Quick Start

### Prerequisites

- [Hugo](https://gohugo.io/installation/) (version 0.148.1 or later)
- [Git](https://git-scm.com/)

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/devblac/devblac.github.io.git
   cd devblac.github.io
   ```

2. **Initialize submodules:**
   ```bash
   git submodule update --init --recursive
   ```

3. **Start the development server:**
   ```bash
   hugo server --buildDrafts
   ```

4. **Open your browser and navigate to:** `http://localhost:1313`

## 📝 Content Management

### Creating a New Blog Post

```bash
hugo new content/post/my-new-post.md
```

This will create a new post with the following front matter:
```toml
+++
date = '2025-07-23T17:55:18-03:00'
draft = true
title = 'My New Post'
+++
```

### Publishing a Post

To publish a post, change `draft = true` to `draft = false` in the front matter.

### Content Structure

- `content/post/` - Blog posts
- `content/about.md` - About page
- `static/` - Static assets (images, files, etc.)
- `layouts/` - Custom layout files (optional)

## 🎨 Customization

### Site Configuration

Edit `hugo.toml` to customize:
- Site title and description
- Social media links
- Navigation menu items
- Theme parameters

### Adding Images

1. Place images in the `static/img/` directory
2. Reference them in your content: `![Alt text](/img/your-image.jpg)`

### Custom CSS/JS

Add custom stylesheets or scripts by editing the `custom_css` and `custom_js` parameters in `hugo.toml`.

## 🚀 Deployment

### GitHub Pages (Automatic)

This blog is configured for automatic deployment to GitHub Pages using GitHub Actions. Simply push your changes to the `main` or `master` branch, and the site will be automatically built and deployed.

### Manual Deployment

To build the site manually:

```bash
hugo --gc --minify
```

The generated site will be in the `public/` directory.

## 📁 Directory Structure

```
devblac.github.io/
├── .github/workflows/    # GitHub Actions workflows
├── content/              # Content files
│   ├── post/            # Blog posts
│   └── about.md         # About page
├── static/              # Static assets
├── themes/              # Hugo themes
├── hugo.toml           # Site configuration
└── README.md           # This file
```

## 🔧 Theme Features

The CleanWhite theme includes:

- **Responsive Design** - Works on all devices
- **Syntax Highlighting** - Beautiful code blocks
- **Social Media Integration** - Links to your profiles
- **SEO Optimized** - Good search engine visibility
- **Fast Loading** - Optimized performance
- **Disqus Comments** - Enable by adding your Disqus shortname
- **Google Analytics** - Track your visitors

## 📖 Useful Commands

```bash
# Create new content
hugo new content/post/my-post.md

# Start development server
hugo server --buildDrafts

# Build for production
hugo --gc --minify

# Check Hugo version
hugo version

# Update theme
git submodule update --remote themes/hugo-theme-cleanwhite
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📄 License

This blog is open source and available under the [MIT License](LICENSE).

## 🆘 Support

- [Hugo Documentation](https://gohugo.io/documentation/)
- [CleanWhite Theme Documentation](https://github.com/zhaohuabing/hugo-theme-cleanwhite)
- [Markdown Guide](https://www.markdownguide.org/)

---

**Happy blogging!** 🎉 