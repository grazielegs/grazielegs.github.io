# Graziele Silva - QA Portfolio

A modern, responsive portfolio website built with Jekyll and deployed on GitHub Pages. Showcasing 9+ years of QA expertise across games, marketplaces, LiveOps & platform testing.

**Live Site:** https://grazielegs.github.io

## Features

✨ **Terminal Aesthetic**
- Dark theme with neon color accents (red, blue, yellow, green)
- Monospace typography (Courier New)
- "$ hello" heading with professional styling
- Bottom footer logo with electrical shock animation

🎮 **Interactive Elements**
- Multi-language support (English, Portuguese, German) with window control-style buttons
- Work tags with hover inversion effects
- Resume button linking to Google Drive
- Construction warning for Projects section
- Responsive contact buttons (Email, LinkedIn, GitHub)

📱 **Responsive Design**
- Desktop: Two-column layout (45% left, 55% right)
- Tablet (768px): Single column with adjusted typography
- Mobile (480px): Optimized spacing and button sizing

🌍 **Multi-Language Support**
- Language buttons styled as macOS controls (Yellow EN, Green PT, Red DE)
- Dynamic content translation
- Header and intro text in all three languages
- Description stays in English across all languages

## Tech Stack

- **Framework:** Jekyll 4.3+
- **Ruby Version:** 3.1.4
- **Hosting:** GitHub Pages
- **CSS:** Custom styling (900+ lines) with animations
- **Templating:** Liquid

## Installation & Setup

### Prerequisites
- Ruby 3.1.4 or higher
- Bundler gem

### Local Development

```bash
# Clone the repository
git clone https://github.com/grazielegs/grazielegs.github.io.git
cd grazielegs.github.io

# Install dependencies
bundle install

# Start development server
bundle exec jekyll serve

# Visit http://localhost:4000
```

## Project Structure

```
.
├── _layouts/
│   └── home.html          # Main layout template
├── _includes/
│   ├── header.html        # Page header
│   └── footer.html        # Page footer
├── assets/
│   └── css/
│       ├── style.css      # Main stylesheet (900+ lines)
│       └── ovelha.png     # Footer logo with shock animation
├── index.md               # Main page content with translations
├── _config.yml            # Jekyll configuration
└── Gemfile                # Ruby dependencies
```

## Content Editing

All text content is managed in `index.md`:

- **English:** Default content section
- **Portuguese:** `pt:` section
- **German:** `de:` section

Update any section to modify site content. The title, description, and all text fields support HTML and Markdown formatting.

## Customization

### Colors
Edit CSS variables in `style.css`:
- Primary: `#000000` (black)
- Secondary: `#ffffff` (white)
- Accent (red): `#ff0000`
- Blue: `#0055ff`
- Yellow: `#ffff00`
- Green: `#00dd00`

### Animations
- **Logo Shock:** 3-second electrical animation every 10 seconds
- **Tag Hover:** Color inversion effect

### Responsive Breakpoints
- Desktop: `1024px+`
- Tablet: `768px-1024px`
- Mobile: `<768px`

## Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch.

### GitHub Pages Settings
1. Go to repository Settings
2. Navigate to Pages (left sidebar)
3. Select: **Deploy from a branch**
4. Branch: `main` / Root folder `/`
5. Save

Changes take 1-2 minutes to appear live.

## Features Breakdown

### Expertise Topics
- Manual Testing (red)
- Web & Mobile Testing (blue)
- Agile & Scrum (yellow)
- Game QA (blue)
- LiveOps & Platform (red)
- Quality Control (green)
- Customer & Community Support (yellow)
- CMS & Discovery (green)

### Dynamic Content
- Experience calculation: Automatically calculates years from 2017
- Responsive translations: All text adapts to selected language
- Link management: Easy resume PDF or external link configuration

## License

Personal portfolio - © 2026 Graziele Silva

## Contact

- Email: grazielegalvaodasilva@gmail.com
- LinkedIn: [linkedin.com/in/graziele-g-130b09a0](https://www.linkedin.com/in/graziele-g-130b09a0/?locale=en_US)
- GitHub: [github.com/grazielegs](https://github.com/grazielegs)
