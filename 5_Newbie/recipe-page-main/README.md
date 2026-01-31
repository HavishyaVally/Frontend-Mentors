# Frontend Mentor - Recipe Page Solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help improve coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [Implementation Details](#implementation-details)
  - [Responsive Design Approach](#responsive-design-approach)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Project Structure](#project-structure)
- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

The challenge was to create a recipe page that:
- Displays a visually appealing recipe for a simple omelette
- Implements responsive design for various screen sizes
- Follows the provided design specifications for colors, typography, and layout
- Ensures accessibility standards are met

### Screenshots

![Mobile View (iPhone 14 Plus)](./assets/images/iPhone-14-Plus-localhost.png)
![Small Device View (Galaxy Fold 2)](./assets/images/Galaxy-Fold2-localhost.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My Process

### Built With

- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling and properties
- **Bootstrap 5.3.6** - Grid system and responsive utilities
- **Google Fonts** - Young Serif and Outfit fonts
- **Mobile-first workflow** - Design approach starting with mobile layouts

### Implementation Details

#### HTML Structure
The project uses semantic HTML5 elements to structure the recipe page:
- `<main>` as the primary container
- Bootstrap grid system with containers, rows, and columns
- Appropriate heading hierarchy (h1, h2, h5)
- Lists for ingredients and instructions
- Table for nutritional information

#### CSS Implementation
The styling follows the design specifications with:
- Custom color palette using HSL values as specified in the style guide
- Typography using Young Serif for headings and Outfit for body text
- Custom styling for different sections (preparation, ingredients, instructions, nutrition)
- Specific styling for list markers, borders, and other design elements

#### Bootstrap Integration
Bootstrap is used primarily for:
- Responsive grid layout
- Utility classes for spacing, alignment, and display
- Table styling for the nutrition section
- Responsive image handling

### Responsive Design Approach

The project follows a mobile-first approach with:
- Base styling for mobile devices (375px width)
- Media queries and Bootstrap's responsive classes to adapt for larger screens
- Fluid container widths with appropriate max-width constraints
- Responsive typography and spacing
- Proper image scaling across different device sizes

Key breakpoints:
- Mobile: Up to 576px
- Tablet: 576px - 992px
- Desktop: 992px and above

### What I Learned

This project provided valuable experience with:
- Implementing Bootstrap's grid system for responsive layouts
- Creating custom styling that integrates with Bootstrap's utilities
- Applying design specifications from a style guide to a real project
- Using HSL color values for a cohesive color scheme
- Implementing proper typography with Google Fonts

```html
<!-- Example of Bootstrap grid implementation -->
<div class="container">
  <div class="row g-3">
    <div class="col-12">
      <h1>Simple Omelette Recipe</h1>
    </div>
  </div>
</div>
```

```css
/* Example of custom styling with HSL colors */
.prep {
  background-color: hsl(330, 100%, 98%);
  padding: 1em;
  border-radius: 10px;
}
```

### Continued Development

Areas for future improvement:
- Enhance accessibility features
- Add print stylesheet for recipe printing
- Implement dark mode toggle
- Add recipe rating or comment functionality
- Optimize performance further

### Useful Resources

- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) - Comprehensive guide for Bootstrap implementation
- [Google Fonts](https://fonts.google.com/) - Source for the Young Serif and Outfit fonts
- [HSL Color Picker](https://hslpicker.com/) - Helpful tool for working with HSL color values
- [Frontend Mentor](https://www.frontendmentor.io/) - Platform providing the challenge and design files

## Project Structure

```
recipe-page-main/
├── assets/
│   ├── fonts/
│   │   ├── outfit/
│   │   └── young-serif/
│   └── images/
│       ├── favicon-32x32.png
│       ├── image-omelette.jpeg
│       ├── iPhone-14-Plus-localhost.png
│       └── Galaxy-Fold2-localhost.png
├── design/
│   ├── desktop-design.jpg
│   └── mobile-design.jpg
├── index.html
├── styles.css
├── style-guide.md
└── README.md
```

## Features

1. **Responsive Layout**
   - Adapts seamlessly from mobile to desktop
   - Maintains readability across all device sizes

2. **Styled Recipe Sections**
   - Clear heading hierarchy
   - Visually distinct preparation section
   - Numbered instructions with bold labels
   - Custom list styling for ingredients and preparation steps

3. **Nutrition Table**
   - Clean, readable table layout
   - Highlighted nutritional values

4. **Typography**
   - Custom fonts (Young Serif for headings, Outfit for body text)
   - Appropriate font sizes and weights for readability
   - Consistent text colors based on the style guide

5. **Visual Design**
   - Rounded corners on images and containers
   - Custom background colors for different sections
   - Consistent spacing and alignment

## Setup Instructions

1. **Clone the repository**
   ```
   git clone [repository-url]
   ```

2. **Navigate to the project directory**
   ```
   cd recipe-page-main
   ```

3. **Open the project**
   - Open `index.html` in your browser to view the project locally
   - No build process or dependencies to install (Bootstrap is loaded via CDN)

4. **Development**
   - Edit `index.html` for markup changes
   - Modify `styles.css` for styling adjustments
   - Reference `style-guide.md` for design specifications

## Author

- Website - [Havishya Vally](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

- Frontend Mentor for providing the challenge and design files
- Bootstrap team for their excellent documentation
- Google Fonts for the typography resources