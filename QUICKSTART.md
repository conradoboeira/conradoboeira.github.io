# Quick Start Guide

## Your new Jekyll-based academic website is ready!

Your site is built with the **Academic Pages** Jekyll theme, which provides a professional, responsive design perfect for showcasing your academic work, research, and CTF writeups.

### What's been set up:

✅ **Navigation**: CV, Publications, CTF Writeups, and Blog pages  
✅ **Professional sidebar**: Space for profile image and links  
✅ **Content structure**: Organized folders for publications, portfolio items, and blog posts  
✅ **Jekyll configuration**: Ready to customize with your information  

### Next Steps:

1. **Update your profile** - Edit `_config.yml` to add:
   - Your name and bio
   - Email and social media links
   - Academic profiles (Google Scholar, ORCID, etc.)
   - Add a profile picture to `images/profile.png`

2. **Add your actual CV** - Edit `_pages/cv.md`:
   - Replace template sections with your education, experience, and skills
   - Or add a link to download your CV PDF

3. **Add publications** - Create files in `_publications/`:
   - Example: `2024-01-my-first-paper.md`
   - Include title, abstract, venue, and link to paper

4. **Add CTF writeups** - Create files in `_portfolio/`:
   - Example: `2024-01-ctf-challenge.md`
   - Document the challenge, solution, and techniques

5. **Add blog posts** - Create files in `_posts/`:
   - Example: `2024-01-15-my-first-post.md`
   - Format: YYYY-MM-DD-title.md

6. **Test locally** (optional):
   - Install Ruby/Bundler
   - Run `bundle install && bundle exec jekyll serve`
   - Visit http://localhost:4000

7. **Deploy**:
   - Push changes to GitHub
   - Your site will be live at https://conradoboeira.github.io

### File Structure

```
├── _config.yml              # Main configuration (EDIT THIS!)
├── _data/navigation.yml     # Menu items
├── _pages/                  # Static pages (CV, Publications, etc.)
├── _publications/           # Your research papers
├── _portfolio/              # CTF writeups and projects
├── _posts/                  # Blog posts
├── _includes/               # Theme components
├── _layouts/                # Page templates
├── _sass/                   # Theme styling
├── assets/                  # CSS, JS, fonts
├── Gemfile                  # Ruby dependencies
└── README.md               # This file
```

### Customization Tips

- **Change site theme**: Edit `site_theme` in `_config.yml` (options: default, air, sunrise, mint, dirt, contrast)
- **Add social icons**: Fill in URLs in `_config.yml` author section
- **Modify sidebar**: Edit `_includes/author-profile.html`
- **Change colors/fonts**: Edit `_sass/_themes.scss`

### Need Help?

- Academic Pages Documentation: https://academicpages.github.io
- Jekyll Documentation: https://jekyllrb.com
- YAML Front Matter Guide: https://jekyllrb.com/docs/front-matter/

Enjoy your new website! 🎉
