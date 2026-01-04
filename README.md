# Thai Le's Blog

A personal blog created with Astro, featuring a clean and modern design for sharing posts about web development, technology, and more.

## 🚀 Features

- **Fast Performance**: Built with Astro for optimal speed and performance
- **Blog Posts**: Write posts in Markdown with MDX support
- **RSS Feed**: Automatic RSS feed generation for content syndication
- **SEO Friendly**: Built-in sitemap and SEO optimization
- **Responsive Design**: Clean, modern design that works on all devices
- **Type Safe**: TypeScript for better development experience

## 🛠️ Tech Stack

- [Astro](https://astro.build) - Static Site Generator
- [MDX](https://mdxjs.com/) - Enhanced Markdown
- TypeScript - Type Safety
- RSS - Content Syndication

## 📦 Project Structure

```
/
├── public/              # Static assets (images, favicon)
├── src/
│   ├── components/      # Reusable Astro components
│   ├── content/         # Blog posts and content collections
│   │   └── blog/        # Blog post markdown files
│   ├── layouts/         # Page layouts
│   └── pages/           # Page routes
│       ├── index.astro  # Homepage
│       ├── about.astro  # About page
│       ├── blog/        # Blog pages
│       └── rss.xml.js   # RSS feed
├── astro.config.mjs     # Astro configuration
└── package.json
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/thai2902/thaile-blog.git
cd thaile-blog
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The site will be available at `http://localhost:4321`

## 📝 Commands

| Command           | Action                                       |
|-------------------|----------------------------------------------|
| `npm install`     | Install dependencies                         |
| `npm run dev`     | Start local dev server at `localhost:4321`   |
| `npm run build`   | Build production site to `./dist/`           |
| `npm run preview` | Preview build locally before deploying       |

## ✍️ Adding Blog Posts

Create a new `.md` file in `src/content/blog/` with the following frontmatter:

```markdown
---
title: 'Your Post Title'
description: 'A brief description of your post'
pubDate: 'Jan 01 2024'
heroImage: '/blog-placeholder-1.jpg'
---

Your content here...
```

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!