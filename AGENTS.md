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
   - Endnotes

2. **End Poverty. Make Trillions.** (February 2023)
   - Introduction
   - Chapters 1-12 (Questions and Answers)
   - Full text

3. **The Language of Liberation: A Story and a Critique** (June 2024)
   - Single work (not yet split into chapters)

### Essays (8 essays)
- The Consensus Trap: How AI Processes Systemic Change (July 2026) - hosted on site
- I Dream of Village (Mar 2025)
- It Pays To End Poverty (Apr 2024)
- UBI and the Environmental Crisis (Mar 2024)
- What's the Right Amount of UBI? (Mar 2024)
- How Do We Pay for Universal Basic Income (UBI)? (Feb 2024)
- Economic modeling of how to end poverty in the United States while saving taxpayers trillions of dollars (Jun 2022) - hosted on Medium
- Using my Jesus year to End Poverty. Make Trillions. (Jan 2022)

### Peer-Reviewed Articles (7 articles on PubMed)
Medical research articles on infant mortality, fetal development, and health outcomes.

### Videos
- 5 informational videos on poverty and UBI
- 11 mini-documentaries on community initiatives

### Children's Books (3 books)
1. **What Do You Need?** - [Buy](https://shop.ingramspark.com/b/084?params=uTyv5jLNI9IthSdGxN5Ze5LDdFgAHHVSjqc9HZYJZC3)
2. **I'm Sorry I Hurt You** - [Buy](https://shop.ingramspark.com/b/084?params=v5XwIMrNlH4bEp9NxlN2TJ2LOKPaZpUrza4pvyBbjiZ)
3. **Thank You for the Love Glasses** - [Buy](https://shop.ingramspark.com/b/084?params=3rR0dsiYrf8tHAW0cKMW5iAqVVRMZQT13B2NpVjRlKH)

### Embodied Emotional Intelligence
- **42 Prayers for Peace Love and Liberation** - Prayer collection (full text on site + 2 PDF formats)
- **Loving Attention Is All You Need** (Nov 2025) - Medium essay
- **God, Money, & Mind** (Mar 2025) - Medium essay
- *Additional pieces planned*

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
├── config.toml              # Hugo configuration (baseURL: darrylfinktonjr.com)
├── .github/
│   └── workflows/
│       └── hugo.yml         # GitHub Actions deployment workflow
├── content/                 # All content in Markdown
│   ├── _index.md           # Homepage
│   ├── about.md            # About the author
│   ├── work-with-me.md     # Collaboration page
│   ├── books/              # Books organized by title
│   │   ├── _index.md       # Books listing page
│   │   ├── have-one-kid/
│   │   │   ├── _index.md   # Book overview
│   │   │   ├── chapter-01.md
│   │   │   ├── chapter-02-simplified.md
│   │   │   ├── chapter-02-detailed.md
│   │   │   ├── chapter-03.md
│   │   │   ├── chapter-04.md
│   │   │   ├── chapter-05.md
│   │   │   ├── endnotes.md
│   │   │   └── full-text.md
│   │   ├── end-poverty-make-trillions/
│   │   │   ├── _index.md
│   │   │   ├── introduction.md
│   │   │   ├── chapter-01.md through chapter-12.md
│   │   │   └── full-text.md
│   │   ── language-of-liberation/
│   │       ├── _index.md
│   │       └── full-text.md
│   ├── essays/             # Essay pages (mix of local and Medium links)
│   │   ├── _index.md
│   │   ├── consensus-trap.md
│   │   ├── economic-modeling.md
│   │   ├── loving-attention-is-all-you-need.md
│   │   ├── i-dream-of-village.md
│   │   ├── god-money-mind.md
│   │   ├── it-pays-to-end-poverty.md
│   │   ├── ubi-and-the-environmental-crisis.md
│   │   ├── right-amount-of-ubi.md
│   │   ├── how-do-we-pay-for-ubi.md
│   │   └── jesus-year.md
│   ├── articles/           # 7 peer-reviewed articles with PubMed links
│   │   └── _index.md
│   ├── videos/             # 5 informational + 11 documentary videos
│   │   └── _index.md
│   ├── childrens-books/    # 3 children's books with IngramSpark widgets
│   │   └── _index.md
│   └── embodied-emotional-intelligence/  # Prayers, meditations, emotional wellness
│       ├── _index.md
│       ├── 42-prayers-for-peace-love-and-liberation.md
│       ├── loving-attention-is-all-you-need.md
│       └── god-money-mind.md
├── static/                 # Static assets
│   ├── CNAME              # Custom domain for GitHub Pages
│   ├── robots.txt         # Crawler permissions (AI bots explicitly allowed)
│   ├── llms.txt           # LLM-friendly content index
│   ├── llms-full.txt      # Complete site content for LLMs
│   └── images/
│       └── book-covers/   # Book cover images
├── themes/
│   └── minimal-author/    # Custom minimal theme
│       ├── layouts/
│       │   ├── _default/
│       │   │   ├── baseof.html
│       │   │   ├── single.html    # Individual page template
│       │   │   └── list.html      # Section listing template
│       │   └── partials/
│       │       ├── header.html
│       │       ├── footer.html
│       │       ├── head.html      # Meta tags, structured data
│       │       ├── navigation.html
│       │       └── breadcrumb.html # Breadcrumb navigation
│       └── static/
│           └── css/
│               └── style.css
└── public/                 # Generated site (gitignored)
```

## Content Strategy

### Book Organization
Each book is split into chapters using Hugo's content organization:
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
- JSON-LD for books, chapters, essays, and author
- Schema.org markup for Book, Chapter, Person, Article
- Open Graph tags for social sharing
- Twitter Cards

### LLM & AI Accessibility
- `/llms.txt` - Clean index of all content with direct URLs
- `/llms-full.txt` - Complete site content in single markdown file (~759KB)
- `/robots.txt` - Explicit permissions for AI crawlers (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, etc.)
- All inner pages have descriptive titles (book name + chapter/part)
- All inner pages have description front matter for SEO/LLM retrieval
- Full-text pages available for all 3 books
- Homepage includes "before you skim" guidance for AI tool usage
- "AI can make that better or worse" text on homepage links to Consensus Trap essay
- Removed per-book llms files - users can paste individual chapters or use PDFs instead

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
2. Test locally with `hugo` or `hugo server`
3. Commit changes to GitHub
4. GitHub Actions automatically builds and deploys to GitHub Pages
5. Site live at custom domain

## Next Steps

1. ~~Extract text from PDFs and convert to Markdown chapters~~ (Complete)
2. ~~Set up Hugo with custom theme~~ (Complete)
3. ~~Create initial content structure~~ (Complete)
4. ~~Add book cover images~~ (Complete)
5. ~~Configure GitHub Pages deployment~~ (Complete)
6. ~~Test locally and refine design~~ (Complete)
7. ~~Launch site~~ (Complete - Live at darrylfinktonjr.com)
8. Explore open source book publishing platforms for wider distribution and AI accessibility
   - Consider Pressbooks, PubPub, or similar platforms
   - Evaluate GitHub organization for book content
   - Investigate Archive.org integration
   - Goal: Make books more discoverable and accessible to AI tools

## Completed Work

### Initial Build
- Extracted all 3 books from PDFs
- Split "Have One Kid" into 6 chapters + endnotes
- Split "End Poverty. Make Trillions." into 12 chapters + introduction
- "The Language of Liberation" kept as single full text
- Created content structure with _index.md files for each section
- Built Hugo theme with clean, modern design optimized for readability
- Implemented responsive CSS with mobile-first approach
- Added book cover images for all 3 books

### Domain & Deployment
- Connected custom domain darrylfinktonjr.com via Cloudflare
- Updated config.toml with new baseURL
- Created static/CNAME file for GitHub Pages
- Created GitHub Actions workflow (.github/workflows/hugo.yml) for automated deployment
- Configured HTTPS enforcement

### Content & Formatting
- Fixed PDF extraction issues in all book chapters (removed page numbers, fixed line breaks, proper paragraphs)
- Fixed stray text artifacts in chapters (e.g., "Version)" in chapter-02-detailed)
- Fixed merged headings in chapters (chapter-04, chapter-05 of Have One Kid)
- Fixed truncated openings in End Poverty chapters (chapter-04, chapter-12)
- Cleaned up endnotes file (removed 37 stray page numbers, added proper heading hierarchy)
- Created 10 individual essay pages (8 with Medium links, 2 hosted on site)
- Added 7 peer-reviewed articles with PubMed links
- Added 5 informational videos and 11 mini-documentaries with YouTube links
- Updated Work With Me page to be more open-ended
- Changed contact email to dfinkton@gmail.com
- Added About page content
- Added IngramSpark embed widgets for children's books

### UX & Navigation
- Added breadcrumb navigation for better wayfinding
- Fixed duplicate headers on list pages
- Fixed books page not displaying content (added missing _index.md)
- Updated list template to show both regular pages and sections
- Removed "Before you skim" auto-injection from individual essay and book chapter pages (kept only on homepage)

### SEO & AI Optimization
- Enhanced JSON-LD structured data for books, chapters, essays, and author
- Added sameAs links to Medium and GitHub profiles
- Proper Schema.org markup for Article, Book, Chapter, Person
- Open Graph and Twitter Card meta tags
- Created `/llms.txt` - LLM-friendly content index with all pages and descriptions
- Created `/llms-full.txt` - Complete site content in single file (~759KB)
- Created `/robots.txt` - Explicit AI crawler permissions (GPTBot, ClaudeBot, PerplexityBot, etc.)
- Improved all inner page titles to include book name for searchability
- Added description front matter to all book chapters and parts
- Fixed RSS feed link in head template
- Fixed head.html nil guard for essays JSON-LD (added `.File` check)
- Updated llms.txt with Consensus Trap and Economic Modeling essays

### Content Reorganization
- Fixed Have One Kid chapter numbering: 1, 2, 2.1, 3, 4, 5
- Standardized copyright notices to CC BY 4.0 across all books
- Moved Children's Books after Books in navigation and homepage
- Added full peer-reviewed articles list to homepage
- Added mini-documentaries list to homepage (links only)
- Essays list ordered reverse-chronologically on both homepage and essays tab
- Created "The Consensus Trap" essay from Gemini conversation (with vaccine and child abuse control cases)
- Added Economic Modeling Medium essay as local page with redirect link
- Removed raw Gemini conversation from homepage, replaced with structured essay

### AI Accessibility Simplification
- Removed per-book llms files (llms-have-one-kid.txt, llms-end-poverty.txt, llms-language-of-liberation.txt, llms-essays.txt) - too large and redundant
- Simplified llms.txt to clean index with URLs only
- Updated homepage "before you skim" section with clearer guidance for AI tool usage
- Updated homepage books section to match books page format with descriptions
- Rationale: Users can paste individual chapters or use PDFs directly; large concatenated files were getting truncated

### Current Status
- Site builds successfully with 48 pages, 0 errors, 0 warnings
- Live at https://darrylfinktonjr.com
- HTTPS enforced
- All content sections populated and formatted
- LLM accessibility optimized (llms.txt, llms-full.txt, robots.txt)
- Google Search Console submitted (pending verification)
- Simplified AI accessibility approach - removed per-book llms files
- Homepage books section matches books page format
- Essays consistently ordered across homepage and essays tab
- New Embodied Emotional Intelligence section created with 42 Prayers PDFs and moved essays

## Maintenance

- To add a new chapter: Create new `.md` file in appropriate book folder
- To edit content: Edit the corresponding `.md` file
- To update design: Modify theme files in `/themes/minimal-author/`
- To add images: Place in `/static/images/` and reference in Markdown
- **IMPORTANT**: When updating the essays list, update BOTH `content/_index.md` (homepage) AND `content/essays/_index.md` (essays tab) - they are separate files and must stay in sync
