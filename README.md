# I&Y JEWLZ - Premium Jewelry Store

A fully functional, multi-page jewelry e-commerce website featuring advanced styling, interactivity, and responsive design.

## Features

### Pages
- **Home**: Hero slider, featured products, categories, testimonials, newsletter
- **Shop**: Filterable product grid (category, price, material, collection), sorting, pagination, list/grid view toggle
- **Product Details**: Image gallery, tabs (description, specs, reviews, shipping), customizable options (size, metal), quantity selector
- **About**: Brand story, values, team, customer service highlights
- **Contact**: Contact cards, form with validation, map integration, FAQ
- **Cart**: Full cart management, coupon codes, shipping options, tax calculation, order summary

### Technical Highlights
- **Responsive Design**: Mobile-first approach with breakpoints for tablets and desktops
- **LocalStorage Cart**: Persistent shopping cart across sessions
- **Dynamic Filtering**: Real-time product filtering and sorting on shop page
- **Interactive UI**: Search overlay, mobile menu, cart sidebar, hero slider
- **Placeholder Images**: Auto-fills missing images with Picsum placeholders for quick development

## Technology Stack
- **HTML5**: Semantic markup
- **CSS3**: Custom properties, grid, flexbox, animations
- **Vanilla JavaScript**: ES6+ features, no dependencies
- **Font Awesome**: Icon library via CDN

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/Madmonk2523/I-YJEWLZ.git
   cd I-YJEWLZ
   ```

2. Open `index.html` in your browser:
   ```bash
   # Windows
   start index.html
   
   # Mac
   open index.html
   
   # Linux
   xdg-open index.html
   ```

3. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve
   ```

## Project Structure

```
I&YJEWLZ/
├── index.html              # Home page
├── shop.html               # Product listing page
├── product-details.html    # Individual product view
├── about.html              # About us page
├── contact.html            # Contact form and info
├── cart.html               # Shopping cart page
├── styles.css              # Main stylesheet
├── script.js               # JavaScript functionality
├── images/                 # Image assets folder
│   └── README.txt         # Image placeholder instructions
└── README.md              # This file
```

## Features Breakdown

### Shopping Cart
- Add/remove items
- Update quantities
- Persistent storage (LocalStorage)
- Coupon codes: `WELCOME10` (10% off), `FREESHIP` (free shipping)
- Multiple shipping options
- Automatic tax calculation (8.75%)

### Product Catalog
- 12 demo products across 5 categories
- Price range: $129 - $2,899
- Categories: Rings, Necklaces, Bracelets, Earrings, Watches
- Materials: Gold, Silver, Platinum, Diamond, Pearl
- Collections: Classic, Modern, Vintage, Luxury

### Responsive Breakpoints
- Desktop: 1024px+
- Tablet: 768px - 1023px
- Mobile: < 768px

## Customization

### Adding Real Images
Replace the placeholder images by adding your own files to the `images/` folder:
- Hero images: `hero1.jpg`, `hero2.jpg`, `hero3.jpg`
- Categories: `category-rings.jpg`, `category-necklaces.jpg`, etc.
- Products: `product1.jpg` through `product12.jpg` + alternates
- Team: `team1.jpg` through `team4.jpg`
- Customers: `customer1.jpg`, `customer2.jpg`, `customer3.jpg`

### Expanding Product Catalog
Edit the `PRODUCTS` array in `script.js` (line ~7) to add more products:
```javascript
{ 
  id: 13, 
  name: 'Product Name', 
  category: 'rings', 
  material: 'gold', 
  collection: 'luxury', 
  price: 1299, 
  originalPrice: 1499, 
  rating: 4.5, 
  reviews: 42, 
  image: 'images/product13.jpg', 
  badge: 'New' 
}
```

### Modifying Colors
Update CSS custom properties in `styles.css` (lines 7-18):
```css
:root {
    --primary-color: #d4af37;      /* Gold accent */
    --secondary-color: #1a1a1a;    /* Dark text/headers */
    --text-color: #333;            /* Body text */
    --light-bg: #f8f8f8;           /* Section backgrounds */
    /* ... */
}
```

## Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Required Marketing Text
The site includes the following required messaging across various sections:
- "WELCOME TO I&Y JEWLZ"
- "WE ARE HAPPY TO ANNOUNCE OUR NEW JEWELRY SHOP"
- "WE GIVE OUR BEST CUSTOMER SERVICE"
- "WE CARRY FULL VARIETY AND BEST PRODUCT"
- "IF YOU HAVE ANY QUESTION FEEL FREE TO REACH US"

## Future Enhancements
- [ ] Backend integration for real product data
- [ ] User authentication and accounts
- [ ] Wishlist persistence and page
- [ ] Search results page
- [ ] Product reviews submission
- [ ] Email service integration for forms
- [ ] Payment gateway integration
- [ ] Admin dashboard

## License
This project is open source and available for educational purposes.

## Contact
For questions or support, visit our contact page or reach out via GitHub issues.

---

Built with ❤️ for jewelry enthusiasts everywhere.
