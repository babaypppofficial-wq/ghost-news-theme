# Ghost News Theme

A professional, modern news theme for Ghost CMS optimized for content publishing, journalism, and blog platforms.

## Features

✨ **Modern Design**
- Clean, professional layout ideal for news websites
- Responsive design that works on all devices
- Dark mode ready with CSS variables

📱 **Responsive & Mobile-First**
- Fully responsive grid layouts
- Touch-friendly navigation and buttons
- Optimized for mobile, tablet, and desktop viewing

📚 **Content-Focused**
- Large, readable typography
- Excellent contrast and spacing
- Focus on readability with proper line-height

🎨 **Customizable**
- Easy-to-modify CSS variables
- Flexible color scheme
- Customizable featured sections

🔍 **SEO Optimized**
- Semantic HTML structure
- Proper heading hierarchy
- Schema.org markup support

⚡ **Performance**
- Lightweight CSS with no frameworks
- Optimized image handling
- Fast loading times

## Installation

1. **Download the theme**
   - Clone this repository or download as ZIP

2. **Create a ZIP file**
   - Compress the entire theme folder

3. **Upload to Ghost**
   - Go to Settings > Design > Upload theme
   - Select the ZIP file and click Upload

4. **Activate the theme**
   - The theme will appear in your theme list
   - Click Activate to set it as your active theme

## Configuration

### Site Settings
Configure these in Ghost Settings > General:
- **Site Title** - Your publication name
- **Site Description** - Tagline displayed on homepage
- **Site Logo** - Logo displayed in header
- **Cover Image** - Default cover for posts

### Navigation Menu
Configure in Settings > Navigation:
- Add menu items with custom URLs
- Links display in the header navigation

### Social Links
Set in Settings > General:
- Facebook
- Twitter/X
- Instagram

## Customization

### Colors
Edit `assets/css/style.css` and modify the CSS variables in the `:root` section:

```css
:root {
    --primary-color: #1f2937;
    --secondary-color: #ef4444;
    --accent-color: #3b82f6;
    --text-color: #111827;
    --bg-primary: #ffffff;
    /* ... more variables */
}
```

### Fonts
To change fonts, modify the `font-family` property in the `body` selector in `assets/css/style.css`.

### Layout Adjustments
- **Posts per page**: Modify in `package.json` config section
- **Grid columns**: Adjust `grid-template-columns` in CSS
- **Container width**: Change `max-width` in `.container` class

## File Structure

```
ghost-news-theme/
├── package.json              # Theme metadata
├── default.hbs              # Main template layout
├── index.hbs                # Homepage template
├── post.hbs                 # Article/post template
├── assets/
│   └── css/
│       └── style.css        # Main stylesheet
└── partials/
    ├── header.hbs           # Header component
    ├── footer.hbs           # Footer component
    ├── article-card.hbs     # Featured article card
    ├── article-list-item.hbs # Article list item
    └── newsletter-signup.hbs # Newsletter signup form
```

## Template Tags

The theme uses Ghost's Handlebars templating system. Common tags:

- `{{@site.title}}` - Site title
- `{{@site.description}}` - Site description
- `{{@site.logo}}` - Site logo URL
- `{{posts}}` - List of posts
- `{{title}}` - Article title
- `{{excerpt}}` - Article excerpt
- `{{content}}` - Article content
- `{{feature_image}}` - Featured image URL
- `{{primary_author.name}}` - Author name
- `{{published_at}}` - Publication date
- `{{tags}}` - Article tags

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT License - Feel free to use and modify this theme

## Support

For questions or issues:
1. Check Ghost documentation: https://ghost.org/docs/
2. Review theme code comments
3. Inspect network and console for errors

## Tips for Best Results

1. **Use high-quality feature images** (1200x600px minimum)
2. **Write compelling excerpts** - These display in cards and lists
3. **Use appropriate tags** - Help with content organization and SEO
4. **Keep headlines concise** - They display better on all screen sizes
5. **Format content properly** - Use heading hierarchy (H1, H2, H3)
6. **Add alt text to images** - Important for SEO and accessibility

## Version History

### v1.0.0 (Initial Release)
- Initial theme release
- Homepage with featured and latest articles
- Article post template with author info
- Newsletter signup integration
- Fully responsive design
- Professional typography and spacing
