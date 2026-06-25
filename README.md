# Pricing Card Refactor Project

## Overview

This project demonstrates the process of using AI-assisted development to fix, refactor, and improve a broken pricing card web component.

The original component contained multiple HTML and CSS issues that affected layout, styling, responsiveness, and maintainability. Using Cursor AI, the component was analyzed, corrected, and transformed into a reusable card component.

---

## Objectives

* Identify and fix layout bugs
* Correct HTML and CSS errors
* Improve responsiveness
* Enhance accessibility and usability
* Refactor the code into a reusable component
* Test the updated implementation

---

## Original Issues Found

### HTML Issues

* Missing closing `</h2>` tag
* Missing viewport meta tag for responsive layouts

### CSS Issues

* Typo in `box-shadow` property (`box-shdow`)
* No responsive width handling
* No button cursor styling
* No visual transitions
* Limited visual hierarchy

### Reusability Issues

* Hardcoded content
* Component could not be reused with different pricing plans
* No separation between data and presentation

---

## AI Prompt Used

```text
Analyze the following HTML/CSS pricing card component.

Tasks:
1. Identify all HTML and CSS bugs.
2. Fix layout and styling issues.
3. Ensure the button is fully clickable and responsive.
4. Improve accessibility and semantic HTML.
5. Refactor the code into a reusable component pattern named Card(title, price, features).
6. Use modern CSS practices and make the card mobile-friendly.
7. Return clean, production-ready code with comments explaining the changes.
```

---

## Improvements Implemented

### Bug Fixes

* Fixed `box-shadow` typo
* Corrected heading closing tag
* Improved overall layout consistency

### UI Enhancements

* Added rounded corners
* Added modern shadow effects
* Added hover transitions
* Improved spacing and typography

### Responsiveness

* Added viewport configuration
* Replaced fixed width with responsive sizing
* Added mobile-friendly layout behavior

### Accessibility

* Improved semantic structure
* Better button interaction feedback
* Improved readability

### Refactoring

Created a reusable component:

```javascript
Card(title, price, features)
```

Example:

```javascript
Card(
  "Basic Plan",
  "$9.99/month",
  [
    "1 GB Storage",
    "Basic Support",
    "All Core Features"
  ]
);
```

---

## Project Structure

```text
project/
│
├── before.html
├── after.html
└── README.md
```

---

## Testing

The updated component was tested for:

* Correct rendering
* Responsive behavior
* Button functionality
* Hover effects
* HTML validity
* Reusability

### Results

✅ Layout displays correctly

✅ Card remains responsive on smaller screens

✅ Button is fully clickable

✅ Hover states work properly

✅ Reusable component functions as expected

---

## Technologies Used

* HTML5
* CSS3
* JavaScript
* Cursor AI

---

## Outcome

The broken pricing card was successfully repaired, modernized, and converted into a reusable component that can be easily adapted for different pricing plans and future projects.
