# Clean Portfolio Website

A professionally designed, responsive portfolio website built with modern web standards and best practices. Perfect for showcasing your skills, projects, and professional information to potential clients and employers.

![Portfolio Preview](assets/images/portfolio-preview.png)

## Live Demo

[View Live Demo](#)

## Features

- **Clean, Modern Design**: Elegant user interface with attention to typography, spacing, and visual hierarchy
- **Fully Responsive**: Optimized for all screen sizes from mobile to desktop
- **Dark/Light Mode**: User-selectable theme with persistence via localStorage
- **Smooth Animations**: Tasteful animations and transitions for an enhanced user experience
- **Interactive Components**: 
  - Mobile-friendly navigation
  - Project showcase with detailed popup views
  - Contact form with validation and email integration via Formspree
  - Interactive map for location
  - FAQ accordion
  - Back-to-top button
  - Auto-typing animation
  - Background animations and visual elements
- **Accessibility**: Follows WCAG guidelines with proper semantic markup, ARIA attributes, and keyboard navigation
- **SEO Optimized**: Includes proper meta tags, Open Graph protocol, structured data, and semantic HTML
- **Performance Optimized**: Lightweight and fast-loading with optimized assets

## Project Structure

```
clean-portfolio/
├── assets/
│   ├── css/
│   │   ├── styles.css       # Main styles and variables
│   │   ├── components.css   # Component-specific styles
│   │   └── responsive.css   # Media queries for responsive design
│   ├── js/
│   │   └── main.js          # Site functionality
│   └── images/              # Image assets
├── index.html               # Main HTML file
├── robots.txt               # Instructions for search engine crawlers
├── sitemap.xml              # Site structure for search engines
└── README.md                # Project documentation
```

## Technologies Used

- HTML5
- CSS3 (Flexbox, Grid, Custom Properties)
- JavaScript (ES6+)
- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [Typed.js](https://github.com/mattboldt/typed.js/) for typing animation
- [Formspree](https://formspree.io/) for contact form submissions

## Getting Started

### Prerequisites

- A modern web browser
- Basic understanding of HTML, CSS, and JavaScript (for customization)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/jmooreCodes/jamesngariu-website.git
   ```
   
2. Navigate to the project directory:
   ```
   cd jamesngariu-website
   ```

3. Open `index.html` in your browser or use a local development server.

## Deployment

This site is ready to deploy on any static hosting service:

### GitHub Pages

1. Create a new GitHub repository
2. Push your code to the repository
3. Go to Settings > Pages
4. Select the main branch as your source
5. Your site will be published at `https://yourusername.github.io/repositoryname/`

### Netlify, Vercel, or other static hosts

1. Create an account on your preferred hosting service
2. Follow their instructions for deploying a static site
3. Connect your GitHub repository or upload the files directly

## Customization

### Personal Information

Update the content in `index.html` to include:
- Your name and profession
- About section information
- Skills and technologies
- Project details and screenshots
- Contact information

### Theme and Styling

The color scheme and theme variables can be modified in the `:root` section of `styles.css`. The website uses CSS variables for consistent theming:

```css
:root {
  --primary-color: #3563E9;
  --primary-dark: #2D54C8;
  --primary-hover-color: #2D54C8;
  /* other variables */
}
```

### Formspree Integration

1. Create an account at [Formspree](https://formspree.io/)
2. Create a new form and get your form ID
3. Replace `mpwpjnbq` in the form action URL with your own form ID:
   ```html
   <form id="contactForm" action="https://formspree.io/f/your-form-id" method="POST">
   ```

### Images

Replace the placeholder images in the `assets/images/` directory with your own images. Recommended:
- Professional headshot for the profile image
- High-quality screenshots for project images
- Optimized images for faster loading

## Browser Support

The website is compatible with all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is available under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Acknowledgments

- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/) (Poppins & Raleway)
- Typing effect by [Typed.js](https://github.com/mattboldt/typed.js/)
- Form processing by [Formspree](https://formspree.io/)

---

## Author

**James Ngariu**
- Website: [James Ngariu](https://jmoorecodes.github.io/jamesngariu-website/)
- GitHub: [@jmooreCodes](https://github.com/jmooreCodes)
- LinkedIn: [James Ngariu](https://linkedin.com/in/james-ngariu-538108346)

---

*This project was built as a showcase of frontend development skills and best practices. Feel free to use it as a template for your own portfolio.*

### Adding Your Resume

To enable the "Download CV" button:

1. Create an HTML version of your resume/CV (or edit the provided template)
2. Save it as `john-doe-resume.html` (or choose another name)
3. Place it in the `assets/files/` directory
4. If you renamed the file, update the download link in `index.html`:
   ```html
   <a href="assets/files/your-filename.html" class="btn secondary-btn" download>
   ```

The HTML resume format ensures cross-browser compatibility and proper rendering of your resume when downloaded. The template includes responsive styling for both screen viewing and printing. 
