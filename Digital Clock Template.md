# Digital Clock Template

This template replicates the visual design from [time-online.netlify.app](https://time-online.netlify.app/), featuring a beautiful digital clock interface with a modern, clean aesthetic perfect for business use.

## Files Included

- `index.html` - Complete HTML file with embedded CSS (standalone version)
- `index_clean.html` - Clean HTML file with external CSS reference
- `styles.css` - Separate CSS file for better organization
- `README.md` - This documentation file

## Features

### Visual Design
- **Gradient Background**: Beautiful purple-to-white gradient
- **3D Card Effect**: Each digit displayed in a card with shadows and depth
- **Responsive Design**: Adapts to mobile and tablet screens
- **Modern Typography**: Clean, professional fonts
- **Hover Effects**: Subtle animations on card hover

### Layout
- **Centered Design**: Content centered both horizontally and vertically
- **Variable Heights**: Cards have different heights for visual rhythm
- **Flexible Grid**: Responsive layout that works on all screen sizes

### Customization Options
- **Real-time Clock**: Optional JavaScript to show current time
- **Easy Styling**: Well-organized CSS for easy customization
- **Color Scheme**: Simple to modify colors and gradients
- **Typography**: Easy to change fonts and sizes

## Usage

### Basic Setup
1. Download all files to your project directory
2. Open `index_clean.html` in a web browser
3. Customize the content and styling as needed

### For Real-time Clock
Uncomment these lines in the JavaScript section:
```javascript
updateClock();
setInterval(updateClock, 1000);
```

### Customization

#### Change Colors
Edit the CSS variables in `styles.css`:
- Background gradient: Modify the `linear-gradient` in `body`
- Card colors: Adjust `background` in `.digit-card`
- Text colors: Change `color` in `.digit` and `.title`

#### Modify Layout
- Card sizes: Adjust `width` and `height` in `.digit-card` selectors
- Spacing: Change `gap` in `.clock-container`
- Responsive breakpoints: Modify `@media` queries

#### Update Content
- Title: Change the text in `<h1 class="title">`
- Numbers: Modify the content in `.digit` elements
- Small numbers: Update `.small-numbers` and `.bottom-numbers` content

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## Technical Details

### CSS Features Used
- Flexbox for layout
- CSS Grid for responsive design
- Backdrop filters for glass effect
- CSS transforms for animations
- Media queries for responsiveness

### Performance
- Lightweight design (no external dependencies)
- Optimized CSS for fast loading
- Minimal JavaScript for optional features

## Business Use Cases

This template is perfect for:
- Corporate websites
- Team dashboards
- Time tracking applications
- Modern landing pages
- Digital displays
- Business presentations

## License

This template is provided as-is for your business use. Feel free to modify and customize according to your needs.

## Support

For customization help or questions about implementation, refer to the well-commented CSS and HTML code included in the files.

