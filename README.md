# Nostra - E-Commerce Fashion Store

A modern, responsive e-commerce web application for a fashion clothing store built with HTML, CSS, and JavaScript.

## 📋 Project Overview

Nostra is a full-stack frontend e-commerce platform designed to showcase and manage a collection of fashion products. The application features a clean, user-friendly interface with smooth navigation and interactive elements.

## ✨ Features

- **Home Page** - Hero section with promotional offers and featured products
- **Product Showcase** - Dynamic product display with filtering capabilities
- **Collections** - Organized product categories
- **Shopping Cart** - Add/remove products functionality
- **Contact Us** - Customer contact form for inquiries
- **Responsive Design** - Mobile-friendly interface optimized for all devices
- **Promotional Offers** - Special discount banner for new customers
- **Image Carousel** - Interactive product image slider
- **Side Navigation** - Mobile-optimized navigation menu

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Responsive styling and animations
- **JavaScript (Vanilla)** - Interactive functionality
- **Font Awesome Icons** - Icon library for UI elements
- **Google Fonts** - Poppins font family for typography

## 📁 Project Structure

```
Nostra/
├── index.html           # Home page
├── collections.html     # Collections page
├── contactus.html       # Contact us page
├── try.html            # Additional page
├── script.js           # Main JavaScript functionality
├── products.js         # Product data and catalog
├── collections.js      # Collections page logic
├── contact.js          # Contact form logic
├── style.css           # Global styling
├── img/
│   ├── icons/         # Icon assets
│   ├── others/        # Miscellaneous images
│   └── products/      # Product images
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required for basic functionality

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Nostra
```

2. Open the project in your browser:
   - Simply open `index.html` in your preferred web browser
   - Or use a local development server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## 📦 Main Components

### JavaScript Files

- **script.js** - Core functionality including:
  - Offer bar close functionality
  - Mobile menu toggle
  - Product image carousel/slider
  
- **products.js** - Product database containing:
  - Product information (id, name, price, tags)
  - Product images
  - Product descriptions

- **collections.js** - Collections page functionality
- **contact.js** - Contact form submission and validation

### Styling

- **style.css** - Comprehensive styling for:
  - Navigation bar
  - Product cards and grid layouts
  - Responsive breakpoints for mobile/tablet/desktop
  - Animations and transitions

## 🎨 Key UI Elements

- **Navigation Bar** - Main menu with links to Home, New Arrival, Most Wanted, Collections, and Contact Us
- **Offer Banner** - Promotional 20% discount announcement
- **Product Grid** - Dynamic product display with images and pricing
- **Slider** - Image carousel with navigation controls
- **Side Navigation** - Mobile hamburger menu

## 📱 Responsive Design

The application is fully responsive and optimized for:
- **Desktop** - Full navigation and multi-column layouts
- **Tablet** - Adjusted spacing and column layouts
- **Mobile** - Single-column layout with hamburger navigation

## 🔧 Customization

### Adding Products
Edit `products.js` and add new product objects to the array:
```javascript
{
    id: 5,
    name: "Product Name",
    src: "products/image.jpg",
    desc: "Product description",
    price: 299,
    tags: ["tag1", "tag2", "tag3"]
}
```

### Modifying Styles
Edit `style.css` to customize:
- Colors and typography
- Layout and spacing
- Animations and transitions
- Responsive breakpoints

## 🌐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is open source and available under the MIT License.

## 👨‍💻 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📞 Support

For support or questions, please use the Contact Us page or open an issue in the repository.

---

**Nostra** - Where Fashion Meets Elegance
