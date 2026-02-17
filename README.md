# Vintage Newspaper Layout

A clean, vintage-styled newspaper HTML template with classic multi-column layout and modern CSS styling.

## Project Structure

```
newspaper/
├── index.html              # Home page
├── newspaper.html          # Main newspaper layout
├── README.md              # This file
└── assets/
    └── styles.css         # Stylesheet for newspaper
```

## Features

- **Authentic Newspaper Design** — Classic multi-column layout mimicking traditional print newspapers
- **Responsive Layout** — Adapts to different screen sizes
- **Vintage Styling** — Paper-like background with bordered sections and classic typography
- **Multi-Column Support** — 4-5 column layouts with flexible widths
- **Header Section** — Black banner with featured title and masthead
- **Portrait Section** — Portrait image with caption and lead text
- **Body Columns** — Main content organized in distinct columns
- **Special Report Box** — Highlighted news boxes for important announcements

## Files

### `newspaper.html`
Main newspaper page with complete layout:
- Top header section (black banner + masthead)
- Middle section (portrait + lead columns)
- 5-column body section with featured content

### `assets/styles.css`
Stylesheet containing:
- Vintage paper background colors
- Classic serif typography
- Border and layout styles
- Responsive media queries

### `index.html`
Home page / landing page

## Usage

1. **Open in Browser** — Simply open `newspaper.html` in any modern web browser
2. **Replace Images** — Update the image source paths to use your own images
3. **Edit Content** — Modify the text in each column as needed
4. **Customize Colors** — Edit CSS variables in `assets/styles.css` to change colors and styling

## Customization

### Change Paper Background
Edit the background color in the main `<body>` style attribute or in CSS:
```css
background: #f5f0e8; /* Paper color */
```

### Modify Column Widths
Adjust the `width` percentages in column divs:
```html
<div style="width:22%; ...">  <!-- Main Column -->
```

### Update Typography
Change font families in the body or specific elements:
```html
font-family: Georgia, 'Times New Roman', serif;
```

## Responsive Behavior

The layout uses flexbox for responsive design:
- **Desktop (1200px+)** — Full 5-column layout with borders
- **Tablet (900px-1199px)** — Flexible column arrangement
- **Mobile (<900px)** — Column stacking (vertical layout)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Notes

- All styling is inline for portability
- CSS rules are in `assets/styles.css`
- RTL language support can be added by changing `dir="ltr"` to `dir="rtl"` in the HTML tag
- Images should be placed in an `assets/` folder or use absolute URLs

---

**Last Updated:** February 2026
