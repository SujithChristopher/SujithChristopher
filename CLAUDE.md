# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal portfolio website repository for Sujith Christopher, a computational researcher. The repository contains both a static portfolio website and a GitHub profile README.

## Repository Structure

- `index.html` - Main portfolio website (Bootstrap-based single-page application)
- `README.md` - GitHub profile README with professional summary and skills
- `assets/` - Static assets for the portfolio website
  - `bootstrap/` - Bootstrap CSS and JS files
  - `fonts/` - Font Awesome icons
  - `js/freelancer.js` - Custom JavaScript for navigation and scroll behavior
  - `img/` - Portfolio images and profile pictures

## Key Components

### Portfolio Website (`index.html`)
- Single-page Bootstrap application with sections: Portfolio, About, Contact
- Uses Bootstrap 5 for responsive design
- Custom JavaScript handles navbar collapse and scroll-to-top functionality
- Modal dialogs for portfolio project details
- Contact form (currently non-functional, placeholder only)

### GitHub Profile README
- Professional summary highlighting 7+ years in computational research
- Organized technical skills with visual badges
- GitHub stats displayed horizontally with responsive design
- Focus areas: Computer Vision, Healthcare Applications, Bioengineering

## Development Notes

### Website Maintenance
- The portfolio website is a static site - no build process required
- Simply open `index.html` in a browser to preview changes
- Images should be placed in `assets/img/` directory
- Custom styling can be added to the existing Bootstrap theme

### README Updates
- Profile README uses GitHub-flavored markdown
- GitHub stats are fetched dynamically via github-readme-stats API
- Skill badges use shields.io for consistent branding
- Mobile-responsive design with horizontal stats layout on desktop

### Content Customization
- Update portfolio projects by modifying the modal content in `index.html`
- Replace placeholder images in `assets/img/portfolio/`
- Modify professional summary in README.md to reflect current focus areas
- Update contact information and social links as needed

## Repository Purpose

This repository serves dual purposes:
1. **GitHub Profile**: The README.md displays on the GitHub profile page
2. **Portfolio Website**: Hosted via GitHub Pages or similar static hosting

Both components should maintain consistency in professional presentation and contact information.