# Maryam Web 2024 - Artist Portfolio Website

> A responsive portfolio website built with HTML, CSS, JavaScript, and PHP, showcasing artwork and projects with a clean, professional design.

This website serves as a digital portfolio and gallery space, presenting artwork and projects with an intuitive interface. The site combines frontend technologies with server-side processing for a complete web experience.

---

## Table of Contents

- [Technologies](#technologies)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage](#usage)

---

## Technologies

| Category | Technology |
|----------|-----------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | PHP |
| **Styling** | Custom CSS |
| **Icons** | Ionicons |
| **Version Control** | Git (GitHub) |

---

## Features

### Responsive Design
- Mobile-friendly layout
- Tablet and desktop optimization
- Adaptive navigation
- Touch-friendly interface

### Content Presentation
- Image gallery and portfolio sections
- Project showcases
- Biography and artist information
- Contact forms and information

### Interactive Elements
- Smooth page transitions
- Interactive navigation
- Form processing
- Dynamic content loading

### Visual Design
- Clean, minimalist aesthetic
- Professional typography
- Custom fonts integration
- Consistent color scheme

---

## Project Structure

```
maryamweb-2024/
├── index.html              # Main homepage
├── welcome.html            # Welcome/landing page
├── welcome.css             # Welcome page styles
├── welcome.js              # Welcome page JavaScript
├── process.php              # PHP form processing
├── css/                    # Stylesheet directory
│   └── [CSS files]
├── js/                     # JavaScript directory
│   └── [JavaScript files]
├── img/                    # Image assets
│   └── [image files]
├── fonts/                  # Custom fonts
│   └── [font files]
├── ionicons/               # Icon library
│   └── [icon files]
└── README.md              # This file
```

**Key Files**:
- `index.html`: Main website structure
- `welcome.html`: Landing/welcome page
- `process.php`: Server-side form processing
- CSS files: Styling and layout
- JavaScript files: Interactive functionality

---

## Getting Started

### Prerequisites

- Web server with PHP support:
  - **XAMPP** (Windows/Mac/Linux)
  - **WAMP** (Windows)
  - **MAMP** (Mac)
  - **LAMP** (Linux)
  - Or any PHP-enabled web server
- Modern web browser
- Text editor or IDE

### Installation

1. Clone the repository:
```bash
git clone https://github.com/mokashmiri/maryamweb-2024.git
cd maryamweb-2024
```

2. Set up local web server:

**Using XAMPP**:
- Copy project folder to `htdocs` directory
- Start Apache server from XAMPP Control Panel
- Access via `http://localhost/maryamweb-2024`

**Using PHP Built-in Server**:
```bash
php -S localhost:8000
```
- Access via `http://localhost:8000`

3. Configure PHP (if needed):
- Ensure PHP is enabled in server configuration
- Check PHP version compatibility

---

## Configuration

### PHP Settings

Ensure PHP is configured for:
- File uploads (if contact form includes file upload)
- Email functionality (for form processing)
- Error reporting (for development)

### File Paths

Update file paths if moving files:
- Check image paths in HTML/CSS
- Verify JavaScript file references
- Update PHP include paths if needed

### Contact Form

Configure `process.php` for email sending:
- Set recipient email address
- Configure SMTP settings if needed
- Add form validation
- Implement security measures (CSRF protection, input sanitization)

---

## Usage

### Adding Content

**Images**:
- Place images in the `img/` directory
- Update image references in HTML files
- Optimize images for web use

**Projects**:
- Add project information to HTML
- Update gallery sections
- Link to project detail pages if applicable

**Biography**:
- Edit biography text in HTML
- Update artist statement
- Add or modify personal information

### Customization

**Styling**:
- Modify CSS files for color schemes
- Adjust layout and spacing
- Update typography and fonts
- Customize responsive breakpoints

**Functionality**:
- Add JavaScript features as needed
- Implement additional interactive elements
- Enhance form processing
- Add new pages or sections

### Form Processing

The `process.php` file handles form submissions:
- Validate form input
- Process and sanitize data
- Send email notifications
- Provide user feedback

---

## Development

### Local Development

1. Set up local server environment
2. Make changes to HTML, CSS, or JavaScript files
3. Refresh browser to see changes
4. Test PHP functionality with server running

### Testing

- Test on multiple browsers
- Check responsive design on different devices
- Verify form submission and processing
- Test all navigation links
- Validate HTML and CSS

### Deployment

For production deployment:
1. Upload files to web server
2. Ensure PHP is enabled on server
3. Configure server settings
4. Set proper file permissions
5. Test all functionality on live server

---

## Browser Support

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

---

## Notes

- Ensure web server has PHP support for form processing
- Keep image file sizes optimized for web performance
- Regularly update content and check for broken links
- Test forms thoroughly before deployment
- Consider security best practices for PHP forms
- Backup files regularly

---

## License

This project is private and proprietary. All rights reserved.

---

## Author

Developed for Maryam Keshmiri's artist portfolio.

---

**Repository Status**: Active maintenance
