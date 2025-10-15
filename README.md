# Datawiz Website

A modern, responsive landing page for Datawiz - a community that empowers students through data science, data analytics, and AI.

## 🌟 Features

- Clean and modern UI design
- Responsive navigation bar
- Eye-catching hero section
- Smooth hover effects
- Custom styling with background image

## 📁 Project Structure

```
datawiz-website/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── README.md           # Project documentation
│
└── assets/
    ├── background.png  # Background image
    ├── image.png       # Logo (header)
    └── logo.png        # Logo (main content)
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone or download this repository
2. Ensure all assets are in the `assets/` folder:
   - `background.png` - Main background image
   - `image.png` - Header logo (80px height recommended)
   - `logo.png` - Main content logo (500px width recommended)

3. Open `index.html` in your web browser

## 🎨 Design Elements

### Color Palette

- **Primary Background**: Dark blue/purple (from background.png)
- **Accent Color**: `rgb(50, 234, 157)` - Turquoise/mint green
- **Text Color**: White
- **Button Hover**: `rgb(9, 127, 82)` - Dark green

### Typography

- **Headings**: Serif fonts (italic and bold variants)
- **Body Text**: Monospace font
- **Button Text**: Bold, 20px

### Layout

- **Header**: Flexbox layout with logo on left, navigation on right
- **Main Content**: Two-column layout (50% text, logo on right)
- **Navigation**: 6 links with 20px spacing

## 📄 Pages & Navigation

Current navigation structure:
- HOME
- ABOUT US
- EVENTS
- TEAM
- ACHIEVEMENTS
- CONTACT-US

*Note: All links currently point to `#` (placeholder)*

## 🛠️ Customization

### Changing Colors

Edit the CSS file to modify colors:

```css
/* Accent color (text and button) */
color: rgb(50, 234, 157);

/* Button hover color */
background-color: rgb(9, 127, 82);
```

### Changing Fonts

Modify font families in the CSS:

```css
font-family: serif;      /* For headings */
font-family: monospace;  /* For body text */
```

### Adjusting Layout

Modify spacing and sizing in CSS:

```css
.main-content {
    width: 50%;           /* Content width */
    padding-left: 100px;  /* Left spacing */
}

#logo {
    width: 500px;         /* Logo size */
}
```

## 🔧 Technical Details

### HTML Structure

- Semantic HTML5 elements (`<header>`, `<main>`)
- Flexbox-based layout system
- Organized class naming convention

### CSS Features

- Universal selector for consistent text color
- Flexbox for responsive layouts
- Hover effects on buttons
- Custom spacing and typography
- Background image implementation

## 📱 Responsive Design

*Note: This version is optimized for desktop. Mobile responsiveness can be added using media queries.*

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements!

## 📝 To-Do

- [ ] Add mobile responsiveness
- [ ] Create additional pages (About, Events, Team, etc.)
- [ ] Add smooth scroll navigation
- [ ] Implement form for "Contact Us"
- [ ] Add animations and transitions
- [ ] Optimize images for web

## 📧 Contact

For more information about Datawiz, visit our website or contact us through the navigation menu.

## 📄 License

This project is open source and available for educational purposes.

---

**Built with ❤️ by the Datawiz Team**