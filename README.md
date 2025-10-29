# BARKATZ Judica - Luxury Judaica Website

A sophisticated, responsive website showcasing handcrafted Judaica art pieces with an elegant, luxurious design.

## 🎨 Design Features

- **Elegant Typography**: Premium font combinations (Playfair Display, Lato, Crimson Text)
- **Luxury Color Palette**: Gold accents (#d4af37) with professional grays and whites
- **Smooth Animations**: CSS transitions and scroll-reveal effects
- **Responsive Design**: Mobile-first approach with fluid layouts
- **Professional SASS Structure**: Organized, maintainable stylesheets

## 📁 Project Structure

```
BARKATZ judica/
├── index.html                 # Main HTML file
├── package.json              # Node.js dependencies
├── public/                   # Static assets
│   ├── css/
│   │   └── main.css         # Compiled CSS
│   ├── BJ.png               # Logo
│   └── README-Images.md     # Image requirements
├── sass/                     # SASS source files
│   ├── main.scss           # Main SASS file
│   ├── _variables.scss     # Design tokens
│   ├── _base.scss          # Base styles
│   ├── _hero.scss          # Hero section styles
│   ├── _products.scss      # Products section styles
│   ├── _highlights.scss    # Highlights section styles
│   ├── _artist.scss        # Artist section styles
│   └── _footer.scss        # Footer styles
```

## 🚀 Getting Started

### Prerequisites

- Modern web browser
- Text editor (VS Code recommended)
- Node.js (for SASS compilation, optional)

### Installation

1. **Clone or download the project files**
2. **Add required images** (see `public/README-Images.md` for specifications)
3. **Open `index.html`** in a web browser

### Development Setup (Optional)

If you want to modify SASS files:

```bash
# Install dependencies
npm install

# Compile SASS (one-time)
npm run build-css

# Watch for SASS changes (development)
npm run sass
```

## 📱 Sections Overview

### 1. Hero Section

- Full-screen background with overlay
- Logo placement with animation
- Call-to-action button
- Parallax background effect (desktop)

### 2. Products Section

- 3 featured products with hover effects
- Product cards with images, descriptions, and pricing
- Badge system for featured/new items
- Responsive grid layout

### 3. Highlights Section

- 3 key selling points with icons
- Circular icon containers with hover animations
- Clean, centered layout

### 4. Artist Section

- Split layout with image and content
- Decorative border around artist image
- Two-column text sections with different styling
- Gradient background with subtle overlay

### 5. Footer

- 4-column responsive layout
- Contact information with icons
- Legal policy links
- Social media links
- Brand consistency maintained

## 🎯 Key Features

### Responsive Design

- **Mobile**: Single column layout, touch-friendly buttons
- **Tablet**: Optimized grid layouts, readable typography
- **Desktop**: Full multi-column layouts, hover effects

### Performance Optimizations

- Optimized CSS delivery
- Efficient animations using CSS transforms
- Progressive image loading
- Minimal JavaScript footprint

### Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Focus states for interactive elements
- High contrast color ratios

## 🛠 Customization

### Colors

Edit `sass/_variables.scss` to modify the color scheme:

```scss
$primary-gold: #d4af37; // Main brand gold
$primary-black: #1a1a1a; // Dark backgrounds
$text-dark: #2c2c2c; // Body text
```

### Typography

Update font variables in `sass/_variables.scss`:

```scss
$font-primary: "Playfair Display", serif; // Headings
$font-secondary: "Lato", sans-serif; // Body text
$font-accent: "Crimson Text", serif; // Accents
```

### Layout

Modify breakpoints and spacing in `sass/_variables.scss`:

```scss
$mobile: 480px;
$tablet: 768px;
$desktop: 1024px;
$large-desktop: 1200px;
```

## 📸 Image Requirements

See `public/README-Images.md` for detailed image specifications.

**Required Images:**

- `hero-bg.jpg` (1920x1080px) - Hero background
- `product1.jpg` (400x300px) - Silver Kiddush Cup
- `product2.jpg` (400x300px) - Olive Wood Challah Board
- `product3.jpg` (400x300px) - Brass Menorah
- `icon-handcraft.jpg` (100x100px) - Craftsmanship icon
- `icon-materials.jpg` (100x100px) - Materials icon
- `icon-tradition.jpg` (100x100px) - Tradition icon
- `artist.jpg` (400x500px) - Artist photo

## 🌐 Browser Support

- **Chrome** 90+
- **Firefox** 88+
- **Safari** 14+
- **Edge** 90+
- **Mobile browsers** (iOS Safari 14+, Chrome Mobile 90+)

## 📋 Content Guidelines

### Product Descriptions

- Keep descriptions concise (3-4 lines max)
- Highlight unique features and materials
- Include cultural/religious significance
- Use sensory language (texture, craftsmanship)

### Artist Bio

- Personal story and background
- Craftsmanship philosophy
- Traditional techniques and innovation
- Connection to Jewish heritage

## 🚀 Deployment

### Static Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Pages**: Free hosting for public repos
- **Traditional Web Hosting**: Upload via FTP

### Pre-deployment Checklist

- [ ] All images optimized and added
- [ ] Contact information updated
- [ ] Legal pages linked
- [ ] Cross-browser testing completed
- [ ] Mobile responsiveness verified
- [ ] Performance testing done

## 📄 Legal Considerations

Ensure you have the following pages (referenced in footer):

- Privacy Policy
- Terms of Service
- Shipping Policy
- Return Policy
- Warranty Information
- Accessibility Statement

## 🤝 Support

For technical support or customization requests, contact:
**Gindi Web Solutions**

---

**Built with ❤️ for BARKATZ Judica**
