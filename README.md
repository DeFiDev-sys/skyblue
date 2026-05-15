# SkyBlue Landing Page

A modern, responsive landing page built with HTML, CSS, and JavaScript featuring a beautiful sky blue color theme with dark mode support.

## Features

- Fully responsive design (mobile, tablet, desktop)
- Dark mode / Light mode toggle with persistence
- Smooth scroll navigation
- Animated stats counter
- Interactive mobile hamburger menu
- Contact form with theme support
- Beautiful sky blue color scheme
- Image backgrounds for hero and contact sections
- FontAwesome icons for social links
- CSS animations and transitions

## Project Structure

```
TestApp-web/
├── index.html      # Main HTML file
├── styles.css      # CSS styles
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## How to Run

### Option 1: Open Directly in Browser
Simply double-click the `index.html` file to open it in your default web browser.

### Option 2: VS Code Live Server
1. Open the project folder in VS Code
2. Install the "Live Server" extension if not already installed
3. Right-click on `index.html` and select "Open with Live Server"

### Option 3: Python HTTP Server
1. Open a terminal in the project directory
2. Run the following command:
   ```bash
   # Python 3
   python -m http.server 8000
   ```
3. Open your browser and navigate to `http://localhost:8000`

### Option 4: Node.js http-server
1. Install http-server globally:
   ```bash
   npm install -g http-server
   ```
2. Run in the project directory:
   ```bash
   http-server
   ```
3. Open the URL shown in the terminal

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization

### Theme Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --sky-blue: #87CEEB;
    --sky-blue-dark: #5DADE2;
    --sky-blue-darker: #3498DB;
    /* ... other variables */
}

/* Dark mode */
[data-theme="dark"] {
    --bg-color: #1a1a2e;
    --bg-secondary: #16213e;
    /* ... dark mode variables */
}
```

### Changing Background Images
Update the URL in `styles.css` for the hero and contact sections:
```css
.hero {
    background: linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)),
                url('your-image-url');
}

.contact {
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)),
                url('your-image-url');
}
```

### Adding/Removing Sections
Modify the corresponding section in `index.html` and update the navigation links accordingly.

## License

MIT License - Feel free to use this project for any purpose.