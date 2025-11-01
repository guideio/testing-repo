# Guilabs Website

A modern, responsive landing page for Guilabs - Your Transformation Partner.

## Project Structure

```
guilabs-domain/
├── index.html               # Main HTML file with navigation and footer
├── src/
│   ├── pages/              # Individual page templates
│   │   ├── home.html       # Home page content
│   │   ├── services.html   # Services page content
│   │   ├── about.html      # About us page content
│   │   └── contact.html    # Contact page content
│   ├── js/                 # JavaScript modules
│   │   ├── app.js          # Main application logic
│   │   ├── router.js       # Client-side routing
│   │   └── utils.js        # Utility functions
│   └── styles/             # CSS files
│       └── styles.css      # Main stylesheet
└── assets/                 # Static assets
    ├── images/            # Image files
    └── fonts/             # Font files
```

## Features

- **Single Page Application (SPA)** with client-side routing
- **Responsive Design** that works on all devices
- **Modern UI** with smooth animations and transitions
- **Contact Form** with client-side validation
- **Modular Architecture** with separated concerns

## Getting Started

### Prerequisites

- A modern web browser
- Python 3.x (for local development server) or any other web server

### Running Locally

1. Clone the repository:
```bash
git clone [repository-url]
cd guilabs-domain
```

2. Start a local server:

Using Python:
```bash
python3 -m http.server 8000
```

Using Node.js (if you have http-server installed):
```bash
npx http-server
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Navigation

The website includes the following pages:

- **Home** (`#/`) - Main landing page with hero section, services overview, and insights
- **Services** (`#/services`) - Detailed information about our services
- **About Us** (`#/about`) - Company information, mission, and values
- **Contact** (`#/contact`) - Contact form and office locations

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Styling with custom properties and animations
- **JavaScript ES6** - Modern JavaScript with modules
- **Google Fonts** - Kalam font family

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2025 Guilabs Corporation. All rights reserved.