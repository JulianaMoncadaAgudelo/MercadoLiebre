# MercadoLiebre

A responsive e-commerce website built with Node.js and Express, showcasing a modern product catalog interface inspired by Latin American marketplace platforms. This project demonstrates proficiency in full-stack web development, responsive design, and clean code practices.

## Overview

MercadoLiebre is a static e-commerce landing page that features a product showcase with promotional offers, responsive navigation, and a professional layout. The project emphasizes semantic HTML, CSS Grid and Flexbox layouts, and serves as a foundation for understanding modern web application architecture.

## Features

- **Responsive Design**: Fully responsive layout that adapts to different screen sizes using CSS Grid and Flexbox
- **Product Catalog**: Dynamic product display with pricing and discount information
- **Navigation System**: User-friendly navigation with multiple sections (Offers, Official Stores, Help)
- **Static Asset Management**: Efficient serving of CSS, images, and fonts through Express middleware
- **Modern UI Components**: Search bar, user authentication links, and promotional sections
- **Icon Integration**: Font Awesome icons for enhanced visual communication
- **Custom Typography**: Google Fonts (Roboto) integration for consistent branding

## Tech Stack

### Backend
- **Node.js** - JavaScript runtime environment
- **Express.js 4.19.2** - Web application framework for routing and middleware

### Frontend
- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling with Grid and Flexbox
- **Font Awesome 6.0** - Icon library
- **Google Fonts** - Roboto font family

### Development Tools
- **npm** - Package management
- **Git** - Version control

## Installation and Setup

### Prerequisites

Before running this project, ensure you have the following installed:
- Node.js (v14.0.0 or higher)
- npm (v6.0.0 or higher)
- Git

### Installation Steps

1. Clone the repository:
```bash
git clone https://github.com/JulianaMoncadaAgudelo/MercadoLiebre.git
```

2. Navigate to the project directory:
```bash
cd MercadoLiebre
```

3. Install dependencies:
```bash
npm install
```

## How to Run the Project

### Development Mode

Start the server by running:

```bash
npm start
```

The application will start on port 3001. You can access it by opening your browser and navigating to:

```
http://localhost:3001
```

You should see a confirmation message in the terminal:
```
Se levantó el servidor en el puerto 3001
```

### Stopping the Server

To stop the server, press `CTRL + C` in the terminal.

## Usage Example

Once the server is running:

1. Open your browser and go to `http://localhost:3001`
2. Browse the product catalog featuring items like:
   - Coffee makers
   - MacBook Pro
   - Samsung Galaxy smartphones
   - Samsung Smart TVs
3. View promotional discounts (ranging from 5% to 40% off)
4. Explore the responsive navigation menu
5. Test the responsive design by resizing your browser window

## Project Structure

```
MercadoLiebre/
├── public/                 # Static assets
│   ├── css/               # Stylesheets
│   │   ├── styles.css     # Main styles with Grid/Flexbox
│   │   └── font.css       # Font configurations
│   └── images/            # Product images and logo
├── src/                   # Source code
│   ├── app.js            # Express server configuration
│   └── views/            # HTML templates
│       └── home.html     # Main landing page
├── package.json          # Project dependencies and scripts
├── package-lock.json     # Dependency lock file
└── README.md            # Project documentation
```

## Key Technical Implementations

### Server Configuration
- Express server setup with static file serving
- Middleware configuration for public asset access
- Route handling for the home page

### Styling Architecture
- CSS Grid for multi-column layouts
- Flexbox for flexible product containers
- Responsive design patterns
- Custom component styling (search bar, product cards, footer)

### Code Organization
- Separation of concerns (views, styles, server logic)
- Clean folder structure following industry standards
- Modular CSS approach

## Future Improvements

- **Backend Enhancements**:
  - Implement RESTful API for product management
  - Add database integration (MongoDB/PostgreSQL)
  - Create user authentication and authorization system
  - Develop shopping cart functionality

- **Frontend Enhancements**:
  - Migrate to a modern frontend framework (React/Vue)
  - Implement client-side routing
  - Add product filtering and sorting features
  - Create responsive mobile menu (hamburger menu)

- **Features**:
  - User registration and login system
  - Product detail pages
  - Shopping cart with checkout process
  - User profile and order history
  - Product search functionality
  - Admin panel for product management

- **Performance & Quality**:
  - Add unit and integration tests
  - Implement image optimization
  - Set up continuous integration/deployment (CI/CD)
  - Add accessibility improvements (WCAG compliance)
  - Implement SEO best practices

- **DevOps**:
  - Docker containerization
  - Environment configuration management
  - Production deployment setup
  - Monitoring and logging implementation

## Skills Demonstrated

- Full-stack web development
- Express.js server configuration
- Responsive web design
- CSS Grid and Flexbox mastery
- Semantic HTML structure
- Static asset management
- Git version control
- npm package management
- Clean code principles

## License

ISC

## Author

Juliana Moncada Agudelo

---

**Note**: This project was created as a learning exercise to demonstrate web development fundamentals and is intended for educational and portfolio purposes.
