# GameFrame - Custom Sports Graphics Designs

A professional website for GameFrame, offering custom sports graphics designs that turn your child's game day photos into professional-quality sports graphics.

## Features

- **Responsive Design** - Works perfectly on desktop and mobile devices
- **Dynamic Portfolio** - Easy-to-manage image gallery system
- **Professional Styling** - Modern design with brand colors and hover effects
- **Multi-page Architecture** - Dedicated portfolio showcase page

## Pages

- `index.html` - Main landing page with hero, samples, pricing, and FAQ
- `portfolio.html` - Complete portfolio showcase with all designs

## Adding New Samples

To add new sample images:

1. Add your new image file to the `media/` folder (e.g., `sample6.png`)
2. Update the `allSamples` array in both `index.html` and `portfolio.html`:

```javascript
const allSamples = [
  'sample6.png',  // Add new samples at the top
  'sample5.png',
  'sample4.png', 
  'sample3.png',
  'sample2.png',
  'sample1.png'
];
```

The system automatically:
- Shows the 5 newest samples on the main page
- Displays all samples on the portfolio page
- Maintains proper styling and hover effects

## Technology Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Responsive Grid/Flexbox layouts

## Local Development

1. Open `index.html` in VS Code
2. Use Live Server extension for live preview
3. Navigate between pages using the portfolio button and navigation links

## License

© 2024 GameFrame. All rights reserved.