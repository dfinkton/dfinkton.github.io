# Darryl Finkton Jr. - Author Website

## Project Overview

A modern, readable website showcasing the writings of Darryl Finkton Jr. The site is optimized for both human readers and AI accessibility, featuring three complete books organized into digestible chapters.

## Goals

- **Human-readable**: Clean, modern design with excellent typography and navigation
- **AI-readable**: Semantic HTML, structured data, clear content hierarchy
- **Accessible**: Fast loading, mobile-friendly, screen-reader compatible
- **Maintainable**: Easy to add/edit content without touching code
- **Discoverable**: SEO-optimized with proper metadata and sitemaps

## Content

### Books (3 complete)

1. **Have One Kid: How We Can Overcome Environmental Collapse and Capitalism Without a Violent Uprising** (July 2026)
   - Chapter 1: The One Child Revolution
   - Chapter 2: Too Many People (Simplified Version)
   - Chapter 2.1: Too Many People (Detailed Version)
   - Chapter 3: Slaves to Growth
   - Chapter 4: Bankruptcy Is Better Than Starving
   - Chapter 5: Will The Empire Strike Back?

2. **End Poverty. Make Trillions.** (February 2023)
   - Part I
   - Part II
   - Part III
   - Part IV

3. **The Language of Liberation: A Story and a Critique** (June 2024)
   - Single work (not yet split into chapters)

### Essays (8 essays on Medium)
- Loving Attention Is All You Need (Nov 2025)
- I Dream of Village (Mar 2025)
- God, Money, & Mind (Mar 2025)
- It Pays To End Poverty (Apr 2024)
- UBI and the Environmental Crisis (Mar 2024)
- What's the Right Amount of UBI? (Mar 2024)
- How Do We Pay for Universal Basic Income (UBI)? (Feb 2024)
- Using my Jesus year to End Poverty. Make Trillions. (Jan 2022)

### Peer-Reviewed Articles (7 articles on PubMed)
Medical research articles on infant mortality, fetal development, and health outcomes.

### Videos
- Informational videos on poverty and UBI
- Mini-documentaries on community initiatives

### Children's Books (3 books)
1. **What Do You Need?** - [Buy](https://shop.ingramspark.com/b/084?params=uTyv5jLNI9IthSdGxN5Ze5LDdFgAHHVSjqc9HZYJZC3)
2. **I'm Sorry I Hurt You** - [Buy](https://shop.ingramspark.com/b/084?params=v5XwIMrNlH4bEp9NxlN2TJ2LOKPaZpUrza4pvyBbjiZ)
3. **Thank You for the Love Glasses** - [Buy](https://shop.ingramspark.com/b/084?params=3rR0dsiYrf8tHAW0cKMW5iAqVVRMZQT13B2NpVjRlKH)

## Tech Stack

### Static Site Generator: Hugo
- Fast build times
- Excellent SEO out of the box
- Simple Markdown content management
- Built-in support for taxonomies, menus, sitemaps
- No JavaScript required for core functionality

### Hosting: GitHub Pages
- Free hosting for static sites
- Automatic deployment from repository
- Custom domain support
- SSL included

### Theme: Custom Minimal Theme
- Clean, readable typography
- Responsive design
- Semantic HTML5
- Structured data (JSON-LD)
- RSS feed
- Sitemap.xml

## Folder Structure

```
dfjrwebsite/
├── AGENTS.md                 # This file - project documentation
├── README.md                 # User-facing documentation
├── config.toml              # Hugo configuration
├── content/                 # All content in Markdown
│   ├── _index.md           # Homepage
│   ├── about.md            # About the author
│   ├── books/              # Books organized by title
│   │   ├── have-one-kid/
│   │   │   ├── _index.md   # Book overview
│   │   │   ├── chapter-01.md
│   │   │   ├── chapter-02-simplified.md
│   │   │   ├── chapter-02-detailed.md
│   │   │   ├── chapter-03.md
│   │   │   ├── chapter-04.md
│   │   │   └── chapter-05.md
│   │   ├── end-poverty-make-trillions/
│   │   │   ├── _index.md
│   │   │   ├── part-01.md
│   │   │   ├── part-02.md
│   │   │   ├── part-03.md
│   │   │   └── part-04.md
│   │   └── language-of-liberation/
│   │       ├── _index.md
│   │       └── full-text.md
│   ├── essays/             # Essays (links to Medium or full text)
│   │   ├── _index.md
│   │   └── ...
│   ├── articles/           # Peer-reviewed articles
│   │   ├── _index.md
│   │   └── ...
│   ├── videos/             # Video content
│   │   ├── _index.md
│   │   ├── informational.md
│   │   └── documentaries.md
│   └── childrens-books/    # Children's books (future)
│       └── _index.md
├── static/                 # Static assets (images, PDFs, etc.)
│   ├── images/
│   │   ├── author.jpg
│   │   └── book-covers/
│   └── files/
│       └── pdfs/          # Original PDFs for download
├── themes/                 # Hugo themes
│   └── minimal-author/    # Custom minimal theme
│       ├── layouts/
│       │   ├── _default/
│       │   │   ├── baseof.html
│       │   │   ├── single.html
│       │   │   ├── list.html
│       │   │   └── home.html
│       │   ├── partials/
│       │   │   ├── header.html
│       │   │   ├── footer.html
│       │   │   ├── head.html
│       │   │   └── navigation.html
│       │   └── shortcodes/
│       └── static/
│           ├── css/
│           │   └── style.css
│           └── js/
│               └── main.js
├── data/                   # Site data files
│   ├── books.toml         # Book metadata
│   ├── essays.toml        # Essay metadata and links
│   └── articles.toml      # Article metadata and links
└── public/                 # Generated site (gitignored)
```

## Content Strategy

### Book Organization
Each book will be split into chapters using Hugo's content organization:
- Book-level `_index.md` contains book overview, cover image, purchase links
- Individual chapter files contain the actual content
- Automatic table of contents generation
- Previous/Next navigation between chapters

### Content Format
- All content written in Markdown for easy editing
- Front matter includes: title, weight (for ordering), description, date
- Structured data added via Hugo templates
- Images stored in `/static/images/` with descriptive filenames

## SEO & AI Optimization

### Structured Data
- JSON-LD for books, chapters, and author
- Schema.org markup for Book, Chapter, Person
- Open Graph tags for social sharing
- Twitter Cards

### Accessibility
- Semantic HTML5 elements
- Proper heading hierarchy
- Alt text for all images
- ARIA labels where needed
- Keyboard navigation support

### Performance
- Minimal JavaScript
- Optimized images
- Fast page loads
- Mobile-first responsive design

## Deployment Workflow

1. Edit content in `/content/` directory
2. Test locally with `hugo server`
3. Commit changes to GitHub
4. GitHub Actions automatically builds and deploys to GitHub Pages
5. Site live at custom domain

## Next Steps

1. ~~Extract text from PDFs and convert to Markdown chapters~~ (Complete)
2. ~~Set up Hugo with custom theme~~ (Complete)
3. ~~Create initial content structure~~ (Complete)
4. ~~Add book cover images~~ (Complete)
5. Configure GitHub Pages deployment
6. Test locally and refine design
7. Launch site

## Completed Work

- Extracted all 3 books from PDFs
- Split "Have One Kid" into 6 chapters + endnotes
- Split "End Poverty. Make Trillions." into 4 parts
- "The Language of Liberation" kept as single full text
- Created content structure with _index.md files for each section
- Captured all links from Google Site (books, essays, articles, videos, children's books)
- Built Hugo theme with clean, modern design optimized for readability
- Implemented responsive CSS with mobile-first approach
- Added JSON-LD structured data for SEO
- Created navigation system with chapter prev/next links
- Added book cover images for all 3 books
- Site builds successfully with 27 pages

## Maintenance

- To add a new chapter: Create new `.md` file in appropriate book folder
- To edit content: Edit the corresponding `.md` file
- To update design: Modify theme files in `/themes/minimal-author/`
- To add images: Place in `/static/images/` and reference in Markdown
