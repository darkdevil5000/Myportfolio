# Portfolio Website

A clean, minimal, and responsive portfolio website built with HTML, CSS, and JavaScript.

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Stylesheet
├── js/
│   └── script.js       # JavaScript for interactions
├── assets/
│   └── images/         # Place your images here
└── README.md           # This file
```

## Sections

- **About Me**: Short professional summary
- **Education**: Academic background and qualifications
- **Achievements & Certifications**: Awards, certifications, and notable accomplishments
- **Skills**: Languages, frameworks, and tools
- **Projects**: Showcase of work with descriptions and links
- **Contact**: Email and social media links

## Customization Instructions

### 1. Personal Information
- Open `index.html` and replace:
  - "Your Name" in the header and footer with your actual name
  - The about section text with your professional summary
  - Email and social links in the contact section

### 2. Skills
- In `index.html`, update the skills lists under each category (Languages, Frameworks, Tools)
- Add or remove `<li>` items as needed

### 3. Projects
- Replace the placeholder project cards with your actual projects
- Update title, description, technologies, and links for each project
- Add more project cards by copying the existing structure

### 4. Styling
- Modify `css/style.css` to change colors, fonts, or layout
- The current theme uses a dark color scheme (#121212 background, #64b5f6 accent)

### 5. Images
- Place your profile picture or project screenshots in `assets/images/`
- Update image references in `index.html` if you add any

## Deployment Guide

### Option 1: Netlify (Drag-and-Drop)
1. Go to [netlify.com](https://netlify.com) and sign up for a free account
2. Drag and drop the entire `portfolio` folder onto the deployment area
3. Your site will be live at a randomly generated URL (e.g., `https://random-name.netlify.app`)
4. You can customize the domain later

### Option 2: Cloudflare Pages
1. Go to [pages.cloudflare.com](https://pages.cloudflare.com) and sign up
2. Connect your GitHub account (or upload manually)
3. Create a new project and select the `portfolio` folder
4. Deploy and get a free subdomain

### Option 3: Neocities
1. Go to [neocities.org](https://neocities.org) and create a free account
2. Upload the files from the `portfolio` folder using their web interface
3. Your site will be at `https://yourusername.neocities.org`

## Local Development
To view the site locally:
1. Open `index.html` in your web browser
2. Or use a local server: `python -m http.server 8000` then visit `http://localhost:8000`

## Features
- Responsive design (mobile and desktop)
- Smooth scrolling navigation
- Dark theme
- Hover effects and transitions
- Single-page layout
