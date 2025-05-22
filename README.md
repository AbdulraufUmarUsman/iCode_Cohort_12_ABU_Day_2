# Campus Connect Learning Platform

![Campus Connect Logo](https://placeholder.svg?height=100&width=300&text=Campus+Connect)

## Overview

Campus Connect is a responsive, single-page learning platform designed to connect students with quality educational content. This project provides a clean, modern interface for an educational website using only HTML and CSS.

## Features

- **Responsive Design**: Fully responsive layout that works on mobile, tablet, and desktop devices
- **Modern UI**: Clean and professional design with gradient accents and subtle animations
- **Comprehensive Sections**:
  - Navigation header with logo
  - Hero section with call-to-action
  - Features highlighting platform benefits
  - Course catalog with categories
  - Student testimonials
  - Call-to-action for registration
  - Detailed footer with links and contact information

## Live Demo

[View Live Demo](#) (file:///C:/Users/CODER/Downloads/compus_connect.html)

## Screenshots

![Desktop View](https://placeholder.svg?height=300&width=600&text=Desktop+View)


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdulraufUmarUsman/campus_connect.git
```

2. Navigate to the project directory:
   ```bash
   cd campus-connect
```

3. Open `campus_connect.html` in your browser:
   - Double-click the file in your file explorer
   - Or use a local development server like Live Server in VS Code

## Project Structure

```
campus-connect/
│
├── index.html          # Main HTML file containing all content and embedded CSS
├── README.md           # Project documentation
└── LICENSE             # License information
```

## Technologies Used

- HTML5
- CSS3
  - Flexbox
  - CSS Grid
  - CSS Variables
  - Media Queries for responsiveness

## Customization

### Changing Colors

The project uses CSS variables for consistent colors. To change the color scheme, modify the `:root` variables in the CSS section of `index.html`:

```css
:root {
    --primary: #4f46e5;      /* Main brand color */
    --primary-dark: #4338ca; /* Darker shade for hover states */
    --secondary: #10b981;    /* Secondary accent color */
    --dark: #1f2937;         /* Text color */
    --light: #f9fafb;        /* Background color */
    --gray: #6b7280;         /* Subdued text color */
    --light-gray: #e5e7eb;   /* Light background accents */
}
