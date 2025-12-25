# Hope Foundation - Donate Today

A modern, responsive single-page donation landing site for **Hope** Foundation, built using pure HTML, CSS, and vanilla JavaScript.

## 🌐 Live Links

- Live Website: https://hope-foundation-chi.vercel.app  

## ✨ Features

- Responsive single-page layout with hero, mission, and donation sections.
- Sticky navigation bar with smooth section navigation using anchor links.
- Interactive donation form with:
  - Preset amount buttons ($10, $25, $50, $100)
  - Custom amount input with automatic deselection of presets
  - Basic validation to ensure amount > 0
- Clean card-based mission section for Food Security, Education, and Healthcare.
- Modern UI with hover animations, soft shadows, and smooth transitions.
- Font Awesome 6 icons integrated via CDN for visual enhancement.

## 🛠️ Tech Stack

- **HTML5**: Semantic structure for hero, mission, donation, and footer sections.
- **CSS3**: Custom responsive styling, layout, hover effects, and media queries.
- **JavaScript (Vanilla)**: Handles amount selection, custom amount logic, form submission, and success alerts.
- **Font Awesome 6 (CDN)**: Icons for feature cards.
- **Unsplash Background Image**: High-quality hero section image via external URL.

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

## 🚀 Getting Started

1. Clone the repository:
"git clone https://github.com/adityanakedar366/Hope-Foundation.git"
2. Open `index.html` in any modern browser.
3. Test interactions:
- Click preset donation amounts.
- Enter a custom amount.
- Fill in name and email.
- Submit to see the simulated confirmation alert.

## 🔧 Customization

- **Change preset amounts**: Update `data-amount` attributes and button labels in the donation form.
- **Switch currency**: Replace `$` symbols in HTML and alert messages with your desired currency.
- **Update hero image**: Replace the Unsplash URL in the `.hero` background property.
- **Modify mission content**: Edit card titles and descriptions under the Mission section.
