# Conrad Boeira's Personal Website

This is my academic portfolio website built with Jekyll and the Academic Pages template.

## Features

- **CV Page** - My curriculum vitae with education, experience, and skills
- **Publications** - My research papers and academic work
- **CTF Writeups** - Detailed solutions and analyses of CTF challenges  
- **Blog** - Technical posts on cybersecurity topics
- **Professional Profile Sidebar** - Links to academic profiles, social media, and contact info

## Setup Instructions

### Local Development

1. Install Ruby and Bundler (if not already installed)
2. Clone this repository and navigate to it
3. Install dependencies: `bundle install`
4. Serve locally: `bundle exec jekyll serve`
5. Visit `http://localhost:4000` in your browser

### Customization

Edit these files to personalize your site:

**Configuration:**
- `_config.yml` - Main site settings, author information, and site metadata
- `_data/navigation.yml` - Navigation menu items

**Content:**
- `_pages/about.md` - Homepage content
- `_pages/cv.md` - Your CV
- `_publications/` - Add your research papers here
- `_portfolio/` - Add your CTF writeups here  
- `_posts/` - Add blog posts here

**Profile:**
- Add a profile image: `images/profile.png` (update path in _config.yml)

## Adding Content

### Add a Publication
Create a new file in `_publications/` (e.g., `2024-01-my-paper.md`):

```yaml
---
title: "Paper Title"
collection: publications
permalink: /publication/2024-01-my-paper
excerpt: 'Brief description'
date: 2024-01-15
venue: 'Journal Name'
paperurl: 'https://link-to-paper.com'
citation: 'Your citation format'
category: 'manuscripts'
---
```

### Add a CTF Writeup
Create a new file in `_portfolio/` (e.g., `2024-01-challenge-name.md`):

```yaml
---
title: "Challenge Name - CTF"
collection: portfolio
permalink: /portfolio/2024-01-challenge
excerpt: 'Brief description of the challenge'
date: 2024-01-10
---
```

### Add a Blog Post
Create a new file in `_posts/` (e.g., `2024-01-05-my-post.md`):

```yaml
---
title: "Blog Post Title"
collection: posts
type: post
permalink: /posts/2024/01/my-post/
date: 2024-01-05
categories:
  - blog
tags:
  - Tag1
  - Tag2
---
```

## Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch.

## License

This site uses the [Academic Pages](https://github.com/academicpages/academicpages.github.io) template.