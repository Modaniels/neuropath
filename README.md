# NeuraPath

> Stop Guessing. Start Learning.

NeuraPath is a modern landing page for a Firefox extension that helps students track their study habits and discover personalized insights for more effective learning.

## 🌟 Features

- **Modern Glassmorphism Design** - Beautiful frosted glass UI elements with backdrop blur effects
- **Fully Responsive** - Optimized for all devices from mobile (320px) to desktop (1920px+)
- **Background Image Integration** - Stunning high-quality images used as fixed backgrounds
- **Smooth Animations** - Intersection Observer API for elegant scroll-triggered animations
- **Clean Typography** - Inter font family for excellent readability
- **Performance Optimized** - Lightweight with minimal dependencies

## 🎨 Design Highlights

- **Hero Section** - Full-screen introduction with glassmorphism text overlay
- **Problem Section** - Relatable student struggles with animated statistics
- **Solution Section** - Clear value proposition with insight card
- **How It Works** - Simple 3-step process (Track → Rate → Improve)
- **CTA Section** - Compelling call-to-action with privacy assurance

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/Modaniels/neuropath.git
   ```

2. Open `index.html` in your browser:
   ```bash
   cd neuropath
   open index.html
   ```

That's it! No build process or dependencies required.

## 📱 Mobile Optimization

The site is fully responsive with breakpoints at:
- **968px** - Tablet layout
- **640px** - Mobile layout
- **480px** - Small mobile devices

Features:
- Full-width buttons on mobile
- Stacked layouts for better readability
- Optimized font sizes and spacing
- Touch-friendly interactive elements

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties, Grid, and Flexbox
- **Vanilla JavaScript** - Intersection Observer API for scroll animations
- **Google Fonts** - Inter font family
- **Unsplash** - High-quality royalty-free images

## 📁 Project Structure

```
neuropath/
├── index.html          # Main HTML file with embedded CSS and JS
└── README.md          # Project documentation
```

## 🎯 Key Sections

### Hero
- Introduces the product with a powerful tagline
- Clear call-to-action button
- Workspace background image

### Problem
- Addresses student pain points
- Real quote from frustrated learners
- Animated statistics (67% overwhelmed, 5+ hours wasted, 12 min refocus time)

### Solution
- Explains the value proposition
- Example insight card showing actionable data
- Team collaboration imagery

### How It Works
- 3 simple steps: Track, Rate, Improve
- Glassmorphism cards with gradient accent bars
- Technology/space background

### CTA
- Final conversion opportunity
- Privacy assurance message
- Team success background

## 🎨 Color Palette

```css
--dark-blue: #0a192f       /* Background */
--light-slate: #ccd6f6     /* Headings */
--slate: #8892b0           /* Body text */
--accent-color: #64ffda    /* CTAs and accents */
--accent-purple: #c792ea   /* Secondary accent */
--card-bg: #112240         /* Card backgrounds */
```

## 🔧 Customization

### Change Images
Replace the Unsplash URLs in the CSS background properties:

```css
background: url('YOUR_IMAGE_URL') center/cover no-repeat;
```

### Update Colors
Modify the CSS custom properties in the `:root` selector:

```css
:root {
    --accent-color: #your-color;
    /* ... other variables */
}
```

### Modify Content
All text content is in the HTML body. Simply edit the text within the section tags.

## 📄 License

This project is licensed under the MIT License - feel free to use it for your own projects.

## 👨‍💻 Author

**Modaniels**
- GitHub: [@Modaniels](https://github.com/Modaniels)

## 🙏 Credits

- Images from [Unsplash](https://unsplash.com)
- Fonts from [Google Fonts](https://fonts.google.com)
- Powered by [Modexia](https://modexia.com)

---

**Note:** This is a landing page template. The actual Firefox extension is not included in this repository.
