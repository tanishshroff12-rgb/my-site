# Financial Tools Hub

A professional-grade financial calculator website featuring interactive tools for options pricing, portfolio analysis, and financial education.

## 🌟 Features

- **Black-Scholes Option Pricing Calculator** with real-time graphs
- Interactive option Greeks analysis (Delta, Gamma, Theta, Vega)
- Responsive design that works on all devices
- Professional-grade mathematical accuracy
- Educational focus with detailed explanations

## 🚀 Quick Start

### Option 1: Local Development
1. Clone or download this repository
2. Open `home.html` in your web browser
3. Navigate through the different pages using the navigation menu

### Option 2: Live Server (Recommended for Development)
If you have VS Code:
1. Install the "Live Server" extension
2. Right-click on `home.html` and select "Open with Live Server"
3. Your website will open in your browser with auto-refresh

## 📁 Project Structure

```
my-site/
├── index.html          # Redirects to home.html
├── home.html           # Main homepage
├── black-scholes.html  # Black-Scholes calculator
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Shared stylesheet
├── README.md           # This file
└── testing/            # Test files (if any)
```

## 🎯 Pages Overview

### Home Page (`home.html`)
- Landing page with overview of all tools
- Featured calculators and upcoming features
- Professional introduction to the platform

### Black-Scholes Calculator (`black-scholes.html`)
- Interactive option pricing calculator
- Real-time graphs showing price vs strike price
- Option Greeks analysis
- Support for both call and put options

### About Page (`about.html`)
- Information about the platform
- Educational focus and mission
- Technical details and technology stack

### Contact Page (`contact.html`)
- Contact form for feedback and questions
- FAQ section
- Educational resources

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js for interactive visualizations
- **Mathematics**: Custom implementations of financial formulas
- **Design**: Responsive design with CSS Grid and Flexbox
- **Styling**: Modern gradients and professional color scheme

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main` or `master`)
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Vercel (Free)
1. Sign up at [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Deploy automatically with every push
4. Get a custom domain option

### Option 3: Netlify (Free)
1. Sign up at [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Get instant deployment
4. Custom domain and SSL included

### Option 4: Traditional Web Hosting
Upload all files to any web hosting service that supports static websites.

## 📊 Black-Scholes Model

The Black-Scholes model is a mathematical model for pricing options contracts. Our implementation includes:

- **Option Price Calculation**: Using the standard Black-Scholes formula
- **Greeks Analysis**: Delta, Gamma, Theta, and Vega calculations
- **Interactive Graphs**: Real-time visualization of price sensitivity
- **Educational Focus**: Clear explanations and professional presentation

### Input Parameters
- **S₀**: Current stock price
- **K**: Strike price
- **T**: Time to expiry (in years)
- **r**: Risk-free interest rate
- **σ**: Volatility

### Output Results
- **Option Price**: Theoretical fair value
- **Delta**: Price sensitivity to underlying asset
- **Gamma**: Delta sensitivity to underlying asset
- **Theta**: Time decay
- **Vega**: Volatility sensitivity

## 🎨 Customization

### Adding New Calculators
1. Create a new HTML file (e.g., `portfolio-calculator.html`)
2. Include the shared CSS: `<link rel="stylesheet" href="styles.css">`
3. Add navigation links to all pages
4. Follow the existing design patterns

### Styling Changes
- Modify `styles.css` for global style changes
- Use the existing CSS classes for consistency
- Follow the established color scheme and design patterns

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones
- All modern browsers

## 🔧 Development

### Local Development Setup
1. Clone the repository
2. Use a local server (Live Server, Python's `http.server`, etc.)
3. Make changes and refresh to see updates

### Adding Features
- Follow the existing code structure
- Maintain consistent styling
- Test on multiple devices
- Ensure mathematical accuracy

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues for:
- Bug fixes
- New features
- Documentation improvements
- Design enhancements

## 📞 Support

For questions or support:
- Use the contact form on the website
- Open an issue on GitHub
- Check the FAQ section

---

**Note**: This is an educational tool. While calculations are accurate, always consult with financial professionals for actual trading decisions.
