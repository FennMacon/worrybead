# Worry Bead Records Website

A clean, modern website for Worry Bead Records, an independent record label based in Queens, New York.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Release Showcase**: Interactive Bandcamp embeds for album previews
- **Video Section**: YouTube videos and interactive experiences
- **Press Coverage**: Links to media coverage and reviews
- **Contact Information**: Social media links and email contact

## Pages

- `index.html` - Main website with releases, videos, press, and contact
- `huey.html` - Immersive full-screen interactive experience for Tuxis Giant's "Huey"

## Structure

```
worrybead/
├── index.html          # Main website
├── huey.html          # Interactive "Huey" experience page
├── styles.css         # Main stylesheet
├── img/              # Images and assets
│   ├── logo.jpg      # Logo (hands by Louis Roe)
│   ├── banner.jpeg   # Banner (stars by Sami Martasian)
│   └── favicon.ico   # Site favicon
├── README.md         # This file
└── .gitignore       # Git ignore rules
```

## Current Releases

1. **True Names: A Benefit for Trans Youth** (May 2025)
   - Compilation featuring 18 tracks
   - All profits donated to Trans Youth Emergency Project

2. **You Won't Remember This** by Tuxis Giant (August 15, 2025)
   - Themes of gender, memory, and growing into yourself

## How to Update

### Adding New Releases

1. Edit `index.html`
2. Add a new `.release-card` div in the `.releases-grid` section
3. Include Bandcamp embed and description
4. Update the release date

### Adding New Videos

1. Edit `index.html`
2. Add a new `.video-card` div in the `.videos-grid` section
3. Include YouTube embed or link to interactive experience

### Adding Press Coverage

1. Edit `index.html`
2. Add a new `.press-item` article in the `.press-grid` section
3. Include publication name, article title, and link

### Styling Changes

- Edit `styles.css` for visual updates
- The site uses a clean, minimal design with Inter font
- Colors: #333 (dark), #666 (medium), #f8f8f8 (light background)

## Contact

- **Email**: worrybeadrecs@gmail.com
- **Instagram**: [@worrybeadrecs](https://www.instagram.com/worrybeadrecs)
- **Twitter**: [@worrybeadrecs](https://x.com/worrybeadrecs)
- **Bandcamp**: [worrybeadrecs.bandcamp.com](https://worrybeadrecs.bandcamp.com)

## Art Credits

- Hands (logo): Louis Roe
- Stars (banner): Sami Martasian

---

Built with love in Queens, NY 🎵 