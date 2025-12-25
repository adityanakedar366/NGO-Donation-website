# Hope Foundation - Donate Today

A modern, responsive single-page donation landing site for **Hope** Foundation, built using pure HTML, CSS, and vanilla JavaScript. The page showcases the mission (Food, Education, Healthcare) and includes an interactive donation form with preset and custom amounts. [web:2][web:5]

## ✨ Features

- Responsive single-page layout with hero, mission, and donation sections. [web:2]
- Sticky navigation bar with smooth section navigation using anchor links.
- Interactive donation form with:
  - Preset amount buttons ($10, $25, $50, $100)
  - Custom amount input with automatic deselection of presets
  - Basic validation to ensure amount > 0
- Clean card-based mission section for Food Security, Education, and Healthcare.
- Modern UI with hover animations, soft shadows, and smooth transitions.
- Font Awesome 6 icons integrated via CDN for visual enhancement. [web:7]

## 🛠️ Tech Stack

- **HTML5**: Semantic structure for hero, mission, donation, and footer sections. [web:5]
- **CSS3**: Custom responsive styling, layout, hover effects, and media queries.
- **JavaScript (Vanilla)**: Handles amount selection, custom amount logic, form submission, and success alerts.
- **Font Awesome 6 (CDN)**: Icons for feature cards. [web:7]
- **Unsplash Background Image**: High-quality hero section image via external URL. [web:2]

## 📁 File Overview

This project is implemented as a single `index.html` file containing:

- `<head>`:
  - Meta tags for charset and viewport.
  - Page title: `Hope Foundation | Donate Today`.
  - Font Awesome stylesheet CDN link.
  - Embedded `<style>` block with all CSS.
- `<body>`:
  - Sticky `<nav>` with logo and navigation links.
  - Hero `<section id="home">` with background image and call-to-action.
  - Mission `<section id="mission">` with three impact cards.
  - Donation `<section id="donate">` with interactive form.
  - `<footer>` with copyright text.
  - Embedded `<script>` block for all JavaScript logic.

No external build tools or bundlers are required; it is a fully static single-file implementation suitable for quick deployment.

## 🚀 Getting Started

1. Create a new file named `index.html` in your project folder.
2. Paste the complete code from your project (the HTML, CSS inside `<style>`, and JS inside `<script>`).
3. Open `index.html` in any modern browser (Chrome, Firefox, Edge, etc.).
4. Test interactions:
   - Click preset donation amounts.
   - Enter a custom amount.
   - Fill in name and email.
   - Submit to see the simulated confirmation alert.

This setup works out-of-the-box on any static hosting provider (GitHub Pages, Netlify, Vercel, etc.). [web:4][web:6]

## 🎯 Key Behaviors

- Selecting a preset amount:
  - Adds a `selected` class to the clicked button.
  - Removes `selected` from other buttons.
  - Clears the custom amount input field.
  - Updates `selectedAmount` in JavaScript.

- Typing in the custom amount input:
  - Removes `selected` class from all preset buttons.
  - Updates `selectedAmount` to the input value.

- Submitting the form:
  - Prevents default page refresh using `e.preventDefault()`.
  - Validates that `selectedAmount` exists and is greater than 0.
  - Shows an alert with donor name, amount, and email.
  - Resets the form, clears button selection, and resets `selectedAmount` to 0.

## 📱 Responsiveness

- On screens `≤ 768px`:
  - Navigation links are hidden for simplicity.
  - Hero heading font size is reduced.
  - Donation container padding is reduced for better fit.
- On larger screens:
  - Full navigation and multi-column card layout are shown.

## 🔧 Customization Tips

- **Change preset amounts**: Update `data-amount` attributes and button labels in the donation form.
- **Switch currency**: Replace `$` symbols in HTML and alert messages with your desired currency.
- **Update hero image**: Replace the Unsplash URL in the `.hero` background property.
- **Modify mission content**: Edit card titles and descriptions under the Mission section.

## 📄 License & Usage

You can reuse and modify this single-file implementation for:

- Non-profit organizations
- Charity campaigns
- Educational projects
- Portfolio examples

For production-ready donation processing, connect the form to a backend or payment provider (Stripe, PayPal, Razorpay, etc.) as demonstrated in many donation templates and tutorials. [web:3][web:8]
