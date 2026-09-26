# Gopal's Portfolio Website

A creative, playful, and professional personal portfolio website built with modern minimalist design principles.

## Design Philosophy

This portfolio follows an editorial, Swiss-inspired design aesthetic with:
- **Soft pastel color palette** (lavender, green, pink, blue)
- **Bold Manrope typography** with tight line-heights
- **Thin black borders** instead of heavy shadows
- **Rounded geometric cards** with controlled border-radius
- **Hand-drawn SVG decorations** for personality
- **Large whitespace** for visual breathing room
- **Subtle hover animations** (200-400ms transitions)

## Features

- **Responsive design** - Works beautifully on desktop, tablet, and mobile
- **Smooth scrolling** navigation
- **Interactive elements** with hover effects and animations
- **Browser-window project cards** for software projects
- **Colorful skill cards** with pastel backgrounds
- **Process workflow** visualization
- **Clean navigation** with social links
- **Fade-in animations** on scroll

## Sections

1. **Hero** - Two-column layout with custom arched image frame
2. **About** - Introduction with statistics
3. **Projects** - Grid of project cards with browser-window design
4. **Skills** - Four colorful service cards
5. **Experience** - Work history
6. **Process** - 5-step workflow visualization
7. **Contact** - Call-to-action and social links

## Color Palette

- Primary background: `#E8E6FF` (Lavender)
- Secondary backgrounds: `#DCD5F5`, `#E5F6D5`, `#F8DDF0`, `#DDEEFF`
- Text: `#17171A` (Near Black)
- Border: `#1C1C1C`

## Typography

- **Headings**: Manrope (700 weight)
- **Body**: Inter (400-500 weight)
- **Navigation**: Inter (500 weight)

## File Structure

```
Portfolio-Website/
├── index.html          # Main HTML structure
├── styles.css          # All styling and design tokens
├── script.js           # Interactive JavaScript
├── context.md          # Project context and notes
└── README.md           # This file
```

## How to Use

1. **Open the website**: Simply open `index.html` in a web browser
2. **Customize content**: Edit the HTML to update:
   - Your name and bio
   - Project details
   - Skills and experience
   - Social links
3. **Add your photo**: Replace the placeholder in the hero section with your actual photo
4. **Deploy**: Upload to any static hosting service (Netlify, Vercel, GitHub Pages)

## Customization

### Updating Projects
Edit the `.project-card` sections in `index.html` to add your own projects:
- Update project name, description, and tech stack
- Add GitHub and live demo links
- Replace browser window content with actual screenshots

### Changing Colors
Modify CSS variables in `styles.css` under `:root`:
```css
--lavender: #e8e6ff;
--green: #e5f6d5;
--pink: #f8ddf0;
--blue: #ddeeff;
```

### Adjusting Typography
Change font weights and sizes in the CSS variables or individual sections.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- No external dependencies (except Google Fonts)
- Minimal JavaScript for interactions
- Optimized CSS with CSS variables
- Fast load times

## Future Enhancements

- Add actual project screenshots
- Implement dark mode toggle
- Add more hand-drawn decorations
- Include a blog section
- Add contact form functionality

## Credits

Design inspired by modern minimalist and editorial design principles.
Built with vanilla HTML, CSS, and JavaScript.

---

**© 2024 Gopal. Built with creativity and code.**
