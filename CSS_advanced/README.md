# CSS Advanced

This project is part of the Holberton School web front-end curriculum, focusing on advanced CSS concepts including custom properties (CSS variables), typography, layout, and styling techniques.

## Project Description

This project demonstrates progressive CSS styling for the Techium website, starting from basic color definitions and advancing to complex layouts with custom properties and responsive design principles.

## Files Structure

### HTML Files
- `index.html` - Main HTML structure for the Techium homepage

### CSS Files (Progressive Tasks)

#### Task 1: `styles/1-style.css`
- Implements smooth scrolling behavior

#### Task 2: `styles/2-style.css`
- Adds color values for body, anchors, and various elements
- Introduces `.visually-hidden` class
- Sets foreground colors for `.card-category` and `.section-tagline`

#### Task 3: `styles/3-style.css`
- Introduces CSS custom properties (variables)
- Defines color variables in `:root`
- Implements reusable color scheme

#### Task 4: `styles/4-style.css`
- Adds font family variables
- Applies different fonts to body and headings

#### Task 5: `styles/5-style.css`
- Defines font size variables using rem units
- Sets base font size to 62.5% for easier rem calculations

#### Task 6: `styles/6-style.css`
- Adds font weight variables
- Applies appropriate font weights to body and headings

#### Task 7: `styles/7-style.css`
- Integrates Google Fonts (Open Sans and Raleway)
- Updates font family variables with Google Fonts as primary choices

#### Task 8: `styles/8-style.css`
- Defines line height variables
- Applies base line height to body

#### Task 9: `styles/9-style.css`
- Removes default text decoration from anchor elements

#### Task 10: `styles/10-style.css`
- Adds section header alignment
- Centers section titles using custom property

#### Task 11: `styles/11-style.css`
- Adds advanced styling to section taglines
- Implements text transformation (uppercase)
- Applies title font family and bold weight to taglines

## CSS Custom Properties

The project uses the following CSS custom properties defined in `:root`:

### Colors
```css
--color-primary: #D73953
--color-black: #090909
--color-white: #FFFFFF
--color-light-grey: #f3f3f3
--color-dark-grey: #353535
--text-color: var(--color-black)
```

### Typography
```css
--font-family-base: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif
--font-family-title: 'Raleway', 'Helvetica Neue', Helvetica, Arial, sans-serif
```

### Font Sizes
```css
--font-size-small: 1.2rem
--font-size-medium: 1.6rem
--font-size-large: 1.8rem
--font-size-x-large: 2.3rem
--font-size-xx-large: 4.8rem
```

### Font Weights
```css
--font-weight-regular: 400
--font-weight-bold: 700
```

### Line Heights
```css
--line-height-small: 1.2
--line-height-base: 1.5
--line-height-big: 1.8
```

### Layout
```css
--section-header-align: center
--section-tagline-transform: uppercase
```

## Key Concepts Learned

1. **CSS Custom Properties (Variables)**: Using `--variable-name` syntax for reusable values
2. **Progressive Enhancement**: Building styles incrementally from basic to advanced
3. **Typography**: Managing font families, sizes, weights, and line heights
4. **Color Management**: Creating a consistent color scheme using variables
5. **Accessibility**: Using `.visually-hidden` class for screen reader content
6. **Modern CSS**: Leveraging CSS features like `var()`, `:root`, and custom properties
7. **Rem Units**: Using relative units for scalable typography
8. **Text Transformation**: Applying uppercase transformation via CSS

## Usage

To use these stylesheets:

1. Link the desired CSS file in your HTML `<head>`:
```html
<link rel="stylesheet" href="styles/11-style.css">
```

2. Ensure you have the Google Fonts link included:
```html
<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700|Raleway:700&display=swap" rel="stylesheet">
```

## Browser Compatibility

The CSS in this project uses modern features including:
- CSS Custom Properties (variables)
- `rem` units
- Smooth scrolling

These features are supported in all modern browsers (Chrome, Firefox, Safari, Edge).

## Author

Victor - Holberton School Student

## Repository

- **GitHub repository**: `holbertonschool-web_front_end`
- **Directory**: `CSS_advanced`

## Notes

- Files are designed to build upon each other progressively
- Each numbered file represents a specific task in the curriculum
- Not all files need to pass W3C validation (as noted in task requirements)
- The project emphasizes practical CSS skills and modern best practices
