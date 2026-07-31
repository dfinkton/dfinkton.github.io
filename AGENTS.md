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
- **42 Prayers for Peace Love and Liberation** - Prayer collection (2 PDF formats: standard and pocketbook; no full text on site)
- **Loving Attention Is All You Need** (Nov 2025) - Medium essay
- **God, Money, & Mind** (Mar 2025) - Medium essay
- **Embodied Emotional Intelligence** - 42-lesson curriculum in development (see dedicated section below)

## Embodied Emotional Intelligence (EEI) Project

**Quick reference:** When user says "EEI", this is the project. Working folder is `Embodied Emotional Intelligence/` (repo root, NOT under `content/`).

### The 42 are LESSONS, not essays

They were called essays until July 2026 and renamed deliberately — an essay is an author working something out, while these are structured, instructional, and meant to be re-run. Use "lesson" everywhere, internally and on the site. **Nothing under `content/essays/` or `content/embodied-emotional-intelligence/essays/` is part of this project** — those are genuinely essays and keep the name.

| Path | What it is | Part of EEI? |
|------|-----------|--------------|
| `Embodied Emotional Intelligence/` | **The 42-lesson curriculum. This is EEI.** Working drafts + notes, repo root. | Yes |
| `content/embodied-emotional-intelligence/eei/_index.md` | The published **introduction** to the curriculum | Yes — but see below |
| `content/embodied-emotional-intelligence/essays/` | "Other Emotional Essays" — 2 stubs linking to Medium | No |
| `content/essays/` | The 8 UBI/poverty essays | No |

Two more things that are **not** part of the 42, despite sitting in the same site section:

- **The introduction is not a template.** It is a single orienting piece that defines terms and lays out the four spirals. It uses organic headers and carries no citations. The 42 lessons use a fixed seven-section structure with citations throughout (`lesson-format.md`). Do not infer the lesson format from the introduction.
- **42 Prayers is a separate work.** It shares the site section and the number 42. It has nothing to do with the curriculum.

### Project Overview
A 42-lesson curriculum on embodied emotional intelligence maturing into emotional wisdom. Each lesson is a **workbook lesson** — it teaches one emotional capacity, backed by research cited throughout, and gives the reader a practice (usually several methods, ordered by effectiveness) for embodying it. Written for someone working on this themselves, or someone helping another person.

### Architecture
```
Embodied Emotional Intelligence/
├── eei-lesson-guide.md             # Curriculum overview, writing constraints, cross-references
├── lesson-format.md                # The 7-section structure every lesson follows
├── an-introduction-to-...md        # The introduction (already written, published)
├── notes/                          # One file per lesson (research notes)
│   ├── 01-focus-and-attention.md
│   ├── 02-emotional-awareness.md
│   ├── ...
│   └── 42-flourishing.md
└── lessons/                        # Completed drafts (ready to publish) — currently empty
```

**Current state:** the format is agreed and written down. Zero of the 42 are drafted. The introduction is published; nothing else in the curriculum is.

### Workflow for Writing a Lesson
1. Read `lesson-format.md` — the 7-section structure is fixed and applies to all 42
2. Load the note file: `notes/XX-lesson-name.md`
3. Read the research notes, cross-references, and honest notes
4. **Pass one** — write the draft for clarity. Full nuance, whatever vocabulary the idea needs. Do not simplify yet.
5. **Pass two** — go back and replace words a 7th-grade reader wouldn't know. Change words, never claims. See "Writing in two passes" in `lesson-format.md`.
6. Save completed draft to `lessons/XX-lesson-name.md`
7. When ready to publish: copy to `content/embodied-emotional-intelligence/eei/` with Hugo front matter, after clearing the `unverified:` list
8. Link it from the spiral lists in the introduction (`content/embodied-emotional-intelligence/eei/_index.md`) — that's the curriculum's navigation hub — and add it to `static/llms.txt`. Both are hand-maintained and drift silently.

### Lesson List (42 lessons in 6 parts)
**Part One — Attention and Observation:** Focus, Emotional Awareness, Observation, Gratitude, States of Mind, Rumination, Judgment
**Part Two — The Drives:** Fear/Anger, Anxiety, Shame, Boundaries, Sadness/Grief, Impermanence, Joy/Play, Care, Status, Sexual Attraction
**Part Three — The Choice:** Listening, Overriding, Breath, Distress Tolerance
**Part Four — Other People:** Touch, Co-regulation, Belonging, Talk About It, Stopping A Fight, De-escalation, Repair, Compassion, Sympathetic Joy
**Part Five — Conditions:** Sleep, Food/Water, Money, Substances, Movement, Nature
**Part Six — Design and Horizon:** Designing the Room, Dose/Difficulty, Turning It Up, Purpose/Storytelling, Mastery & Wisdom, Flourishing

### Key Writing Constraints
- **Structure is fixed:** Quotation → The Overview → The Challenge → The Benefit → The Practice → What to Expect → The Evidence. Same headers in all 42. Full spec in `lesson-format.md`.
- **Self-containment:** Each lesson must stand alone (2-3 sentences of re-grounding, terms defined even if defined elsewhere)
- **Division of labour:** Lessons 5, 6, 7, 9 all touch abstraction — keep separate
- **Series thesis:** Sensitivity without acceptance is worse than not sensing at all
- **No target length:** It depends on the topic. Never pad a thin section to match a fuller chapter.
- **Two passes:** Clarity first, vocabulary second — never both at once. 7th-grade *vocabulary* carrying adult *content*, not 7th-grade content. Pass two changes words, never claims; expect chapters to get longer, not shorter. "7th grade" is a heuristic for word choice, never a readability score to write toward.
- **Plain English:** Technical terms defined as used, except where the term *is* the concept — those get kept and taught. Link the study rather than printing effect sizes and confidence intervals.

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
│   │   ├── i-dream-of-village.md
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
│   └── embodied-emotional-intelligence/  # Emotional wisdom section
│       ├── _index.md                    # Landing page (links to 3 subsections)
│       ├── 42-prayers/                  # Prayer collection (PDF links only)
│       │   └── _index.md
│       ├── eei/                         # 42-lesson curriculum
│       │   ├── _index.md               # The introduction
│       │   └── (lessons published here)
│       └── essays/                      # Other emotional essays
│           ├── _index.md
│           ├── loving-attention-is-all-you-need.md
│           └── god-money-mind.md
├── Embodied Emotional Intelligence/  # EEI lesson curriculum (working docs, not published)
│   ├── eei-lesson-guide.md
│   ├── lesson-format.md
│   ├── an-introduction-to-embodied-emotional-intelligence.md
│   ├── notes/                        # 42 individual lesson note files
│   │   ├── 01-focus-and-attention.md
│   │   └── ... (42 total)
│   └── lessons/                      # Completed lesson drafts
├── static/                 # Static assets
│   ├── CNAME              # Custom domain for GitHub Pages
│   ├── robots.txt         # Crawler permissions (AI bots explicitly allowed)
│   ├── llms.txt           # LLM-friendly content index
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
- `/robots.txt` - Explicit permissions for AI crawlers (GPTBot, ClaudeBot, PerplexityBot, Google-Extended, etc.)
- No bulk/concatenated content files - per-book and whole-site versions were both tried and removed. They get truncated by AI tools and go stale fast since they're hand-maintained outside Hugo's build. Every book has its own `/full-text/` page instead, which stays current automatically.
- All inner pages have descriptive titles (book name + chapter/part)
- All inner pages have description front matter for SEO/LLM retrieval
- Full-text pages available for all 3 books
- Homepage includes "before you skim" guidance for AI tool usage
- "AI can make that better or worse" text on homepage links to Consensus Trap essay
- Deliberately no per-book llms-*.txt files - users can paste individual chapters or use PDFs directly; large concatenated files were getting truncated by AI tools

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

The site is live at https://darrylfinktonjr.com. For a detailed history of what's been built, see `git log` — this file documents current state and how to work in the repo, not a changelog.

## Open Ideas

- Explore open source book publishing platforms for wider distribution and AI accessibility (Pressbooks, PubPub, Archive.org integration, or a dedicated GitHub organization for book content). Goal: make the books more discoverable and accessible to AI tools.
- Google Search Console was submitted for this domain but verification status hasn't been rechecked recently. No verification file or meta tag currently exists anywhere in the repo, so if it was ever verified it was via a DNS TXT record (Cloudflare) rather than anything tracked here.

## Maintenance

- To add a new chapter: Create new `.md` file in appropriate book folder
- To edit content: Edit the corresponding `.md` file
- To update design: Modify theme files in `/themes/minimal-author/`
- To add images: Place in `/static/images/` and reference in Markdown
- **IMPORTANT**: The essays tab (`content/essays/_index.md`) has no manual list - the theme's `list.html` auto-generates it from the individual essay files, sorted by date. Only `content/_index.md` (homepage) has a hand-written essays list. When adding a new essay, give it a `date` in front matter (that's what controls its position on the essays tab) and separately add it to the homepage list yourself.
- **IMPORTANT**: `static/llms.txt` is also hand-maintained and not auto-generated - when adding or moving a page, update it too, or it will silently drift (this already happened once with stale Embodied Emotional Intelligence links).
- **IMPORTANT**: `public/` is gitignored and must never be committed. The GitHub Actions workflow (`.github/workflows/hugo.yml`) rebuilds Hugo from scratch from `content/`/`static/` on every push to `main` - the local `public/` folder is throwaway build output, not the source of what deploys. If a page is moved or removed, add an `aliases:` entry in its front matter (see existing examples in `content/books/end-poverty-make-trillions/`) so the old URL redirects instead of 404ing.
