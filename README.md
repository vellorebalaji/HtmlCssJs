# WhiteLabel Blog Website

A responsive blog website built with HTML, CSS, and JavaScript without any external frameworks or libraries.

## Project Structure

```
Project1/
├── index.html          # Home page
├── blog-list.html      # Blog list page
├── blog-detail.html    # Blog detail page
├── contact.html        # Contact us page
├── readme.html         # Documentation page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Features

### Home Page (index.html)
- **Header**: Fixed navigation with WhiteLabel logo (clickable, links to home)
- **Navigation Menu**: Home, Blog List, Blog Detail, README, Contact
- **Responsive Hamburger Menu**: For mobile and tablet devices
- **Hero Section**: 
  - Responsive background images (different for desktop, tablet, mobile)
  - Overlay text with heading and description
  - CTA button that redirects to blog detail page
- **Blog List Section**: Latest blog posts displayed as cards
- **Footer**: Copyright text and navigation links

### Blog List Page (blog-list.html)
- Same header and footer as home page
- Grid layout displaying 6 blog posts as cards
- Each card includes image, title, description, and "Read More" link
- Fully responsive design

### Blog Detail Page (blog-detail.html)
- Same header and footer as home page
- Blog header with title, author, date, and category
- Featured image (large, responsive)
- Full blog content with headings, paragraphs, and lists
### Contact Page (contact.html)
- Same header and footer as other pages
- Contact form with name, email, subject, and message fields
- Form validation and mock submission functionality
- Responsive form design

### Documentation Page (readme.html)
- Static HTML version of project documentation
- Clean, readable formatting
- Complete project overview

## Responsive Design

### Breakpoints
- **Desktop**: 1025px and above
- **Tablet**: 769px - 1024px
- **Mobile**: 768px and below

### Features
- Mobile-first approach
- Hamburger menu for smaller screens
- Responsive images and typography
- Grid layouts that adapt to screen size
- Touch-friendly navigation

## Navigation Structure

### Header Navigation
- **WhiteLabel Logo**: Links to index.html
- **Home**: Links to index.html
- **Blog List**: Links to blog-list.html
- **Blog Detail**: Links to blog-detail.html
- **README**: Links to readme.html
- **Contact**: Links to contact.html

### Footer Navigation
- **Home**: Links to index.html
- **Blog List**: Links to blog-list.html
- **Blog Detail**: Links to blog-detail.html
- **Contact**: Links to contact.html

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: 
  - Flexbox and Grid layouts
  - Media queries for responsiveness
  - CSS transitions and hover effects
- **Vanilla JavaScript**: 
  - Hamburger menu functionality
  - Click event handling
  - DOM manipulation
  - Contact form submission

## Key CSS Features

- Custom responsive hero images for different devices
- Smooth transitions and hover effects
- Mobile-optimized hamburger menu animation
- Card-based layout system
- Typography scaling for different screen sizes

## JavaScript Functionality

- Hamburger menu toggle
- Menu close on link click
- Menu close on outside click
- Hero CTA button navigation
- Contact form mock submission

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Responsive design works on all screen sizes

## Getting Started

1. Open `index.html` in a web browser
2. Navigate through the site using the header menu
3. Test responsive design by resizing the browser window
4. Use browser developer tools to test mobile view

## File Descriptions

- **index.html**: Main landing page with hero section and blog preview
- **blog-list.html**: Complete list of all blog posts
- **blog-detail.html**: Individual blog post page with full content
- **contact.html**: Contact form page for user inquiries
- **readme.html**: Static HTML documentation page
- **styles.css**: All styling including responsive design
- **script.js**: Interactive functionality for navigation and forms
- **README.md**: Project documentation

## Design Principles

- Clean, modern design
- Mobile-first responsive approach
- Consistent navigation across all pages
- Accessible color contrast
- Fast loading with optimized images
- No external dependencies