# 🌟 Meridian News Theme - Premium Professional Publishing

A premium, high-quality professional news publishing theme for Ghost CMS with advanced features, beautiful typography, and modern design patterns.

## 🎯 Features

### 📰 Content Publishing
- Professional article layouts with hero images
- Breaking news ticker with automatic scrolling
- Featured stories section with grid display
- Latest news with thumbnail images
- Related articles recommendation
- Reading time estimates

### 🎨 Design Excellence
- Premium typography using Playfair Display for headlines
- Modern, clean interface
- High-quality gradients and shadows
- Smooth animations and transitions
- Professional color scheme (black, red accents)
- Responsive grid layouts

### 📱 Responsive Design
- Desktop optimized
- Tablet-friendly layout
- Mobile-first responsive approach
- Touch-friendly navigation
- Optimized images

### 🏢 Business Features
- Newsletter subscription widgets
- Trending articles sidebar
- Category filtering
- Search functionality
- Social media integration
- Author profiles with bios

### 💾 Advanced Functionality
- Post pagination
- Category tags
- Author management
- Featured image support
- Excerpt display
- Article metadata

## 📂 File Structure

```
meridian-news-theme/
├── package.json                 # Theme metadata
├── default.hbs                  # Main layout
├── index.hbs                    # Homepage
├── post.hbs                     # Article detail
├── assets/
│   └── css/
│       ├── style.css            # Main styles (1500+ lines)
│       └── typography.css       # Typography rules
└── partials/
    ├── header.hbs               # Navigation header
    ├── footer.hbs               # Footer
    ├── featured-article.hbs     # Featured article card
    ├── article-item.hbs         # Article list item
    ├── article-card.hbs         # Article grid card
    ├── article-sidebar.hbs      # Article page sidebar
    ├── newsletter-widget.hbs    # Newsletter subscription
    ├── trending-widget.hbs      # Trending articles
    ├── categories-widget.hbs    # Category list
    └── newsletter-section.hbs   # Newsletter CTA section
```

## 🚀 Installation

### Step 1: Download Theme
1. Download the `meridian-news-theme.zip` file
2. Keep it as a ZIP file (do not extract)

### Step 2: Upload to Ghost
1. Log in to your Ghost Admin Panel
2. Navigate to **Settings → Design → Themes**
3. Click **Upload theme**
4. Select the `meridian-news-theme.zip` file
5. Wait for upload to complete
6. Click **Activate** to use the theme

### Step 3: Configure Settings
1. Go to **Settings → General**
2. Set your:
   - Site Title
   - Site Description
   - Logo (recommended: 200x50px)
   - Cover Image
3. Add social media links (Facebook, Twitter, Instagram)
4. Save settings

### Step 4: Create Navigation
1. Go to **Settings → Navigation**
2. Add menu items with titles and URLs
3. These appear in the header navigation

## ✨ Key Features Explained

### Homepage
- **Hero Banner**: Prominently displays site title and description
- **Breaking News**: Red banner with latest article
- **Featured Stories**: 3-column grid of featured articles
- **Latest News**: Main news feed with thumbnails
- **Sidebar**: Newsletter, trending, and category widgets

### Article Pages
- **Full-width hero image** with article metadata overlay
- **Professional typography** optimized for reading
- **Author information** with profile image and bio
- **Related articles** recommendation section
- **Article sidebar** with sharing buttons and widgets
- **Call-to-action** newsletter section

### Navigation
- **Sticky header** with smooth animations
- **Search functionality** (ready to implement)
- **Subscribe button** for member management
- **Social icons** in footer

## 🎨 Customization

### Change Colors
Edit the CSS variables in `assets/css/style.css`:

```css
:root {
    --primary-color: #1a1a1a;        /* Black */
    --secondary-color: #dc2626;      /* Red */
    --accent-color: #0066cc;         /* Blue */
    /* ... more colors */
}
```

### Change Fonts
Modify font URLs in `assets/css/typography.css`:

```css
@import url('https://fonts.googleapis.com/css2?...');
```

### Adjust Layout
- Container max-width: 1200px (in `.container`)
- Grid columns: Modify `grid-template-columns` values
- Spacing: Edit margin/padding values

## 📊 Content Management

### Featured Articles
To feature articles:
1. Edit article
2. Check "Featured" or use featured image
3. Add primary tag
4. Save

### Categories
Use Ghost tags to organize content:
1. Create tags (e.g., "Breaking News", "Technology")
2. Assign to articles
3. Tags appear in sidebar and filters

### Authors
1. Go to Staff section
2. Add author bio and profile image
3. Assign to articles
4. Author info displays on article pages

## 🔍 SEO Features

- Semantic HTML structure
- Proper heading hierarchy
- Meta tags for OG/Twitter
- Structured data ready
- Mobile-friendly design
- Fast loading times
- Clean URLs

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+
- **Tablet**: 768px - 1024px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🌐 Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## ⚡ Performance

- Lightweight CSS (~2000 lines)
- No external dependencies
- Optimized images
- Smooth animations using CSS
- Fast page load times
- Mobile optimized

## 📝 Typography System

- **Headlines**: Playfair Display (serif) - elegant and professional
- **Body**: Inter (sans-serif) - clean and readable
- **Code**: Monaco/Courier - monospace
- **Line Heights**: Optimized for readability
- **Font Sizes**: Responsive scaling

## 🎯 Use Cases

Perfect for:
- News websites
- Magazine publishing
- Blog platforms
- Content publishers
- Media outlets
- Tech blogs
- Fashion publications
- Business news
- Financial reporting
- Industry publications

## 💡 Tips for Best Results

1. **High-quality images**: Use professional photos (1200x600px minimum)
2. **Compelling excerpts**: Write engaging summaries
3. **Consistent tagging**: Use meaningful categories
4. **Author bios**: Add professional author information
5. **Regular updates**: Keep content fresh
6. **Social sharing**: Encourage content sharing
7. **Newsletter**: Build subscriber list
8. **SEO optimization**: Use descriptive titles and meta descriptions

## 🔧 Advanced Configuration

### Custom Colors for Sections
Add custom classes in your HTML:

```css
.section-red {
    --secondary-color: #dc2626;
}
```

### Dark Mode (Future)
The theme is ready for dark mode implementation:

```css
body.dark-mode {
    --bg-primary: #1a1a1a;
    --text-color: #ffffff;
}
```

## 📞 Support

For issues or questions:
1. Check Ghost documentation: https://ghost.org/docs/
2. Verify theme files are uploaded correctly
3. Clear browser cache
4. Try a different browser
5. Check browser console for errors

## 📄 License

MIT License - Feel free to use and modify

## 🎉 What's Included

✅ Professional design
✅ Fully responsive
✅ Modern typography
✅ SEO optimized
✅ Easy to customize
✅ Fast loading
✅ Mobile friendly
✅ Social integration
✅ Newsletter ready
✅ Professional layouts

## 🚀 Next Steps

1. Download and upload the theme
2. Configure site settings
3. Add your logo and images
4. Create navigation menu
5. Publish your first article
6. Promote on social media
7. Build subscriber list
8. Monitor performance

---

**Meridian News Theme** - Premium Professional Publishing for Ghost CMS

Version 2.0.0 | MIT License | Ghost 5.0+
