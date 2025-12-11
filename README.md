#EduLearn - Education Landing Page

A modern, responsive landing page for an educational platform built with pure HTML and CSS. This project features a beautiful gradient design, smooth animations, and a fully responsive layout that works seamlessly across all devices.

## 🎯 Features

- **Modern Design**: Clean and professional UI with gradient backgrounds and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Hero Section**: Eye-catching banner with call-to-action buttons
- **Features Showcase**: Highlight key platform benefits with icon cards
- **Course Catalog**: Display popular courses with ratings and pricing
- **Testimonials**: Social proof section with student reviews
- **Smooth Scrolling**: Navigation links with smooth scroll behavior
- **No Dependencies**: Pure HTML/CSS - no frameworks or libraries required

## 🚀 Technologies Used

- HTML5
- CSS3 (with modern features like gradients, animations, and backdrop-filter)
- Responsive Design (CSS Grid and Flexbox)

## 📋 Project Structure

```
html/
├── index.html          # Main landing page
└── README.md          # Project documentation
```

## 🛠️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Utkantha/edulearn.git
   cd edulearn
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (with http-server)
     npx http-server
     ```

3. **View the page**
   - Navigate to `http://localhost:8000` (or the port your server uses)
   - Or double-click `index.html` to open it directly in your browser

## 📱 Sections

The landing page includes the following sections:

1. **Navigation Bar** - Fixed header with logo and navigation links
2. **Hero Section** - Main banner with headline and CTA buttons
3. **Features Section** - Six feature cards highlighting platform benefits
4. **Courses Section** - Grid of popular courses with details
5. **Testimonials** - Student reviews and testimonials
6. **Call-to-Action** - Sign-up prompt section
7. **Footer** - Links and copyright information

## 🎨 Customization

### Changing Colors
The main gradient color scheme can be modified in the CSS:
```css
/* Primary gradient: purple to violet */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Adding Courses
Add more course cards in the `.courses-grid` section by duplicating the `.course-card` structure.

### Modifying Content
All text content can be easily edited directly in the HTML file.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

Created with ❤️ for educational purposes

## 🔗 Live Demo

https://edulearn-indol.vercel.app/
---

**Note**: This is a static HTML page. For a full-featured educational platform, you would need to integrate it with a backend framework and database.
