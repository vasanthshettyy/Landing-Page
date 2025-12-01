# NeoTranslate Pro – AI Universal Translator

This project is a single-page landing site for **NeoTranslate Pro**, a dedicated AI-powered universal translation device. The page is implemented completely in `index.html` with embedded styles and scripts.

## Overview

The landing page is designed to:

- **Explain the problem** of language barriers for travelers, professionals, students, and researchers.
- **Present NeoTranslate Pro as the solution**, highlighting its key benefits and use cases.
- **Showcase key specifications and features** (battery life, accuracy, languages supported, etc.).
- **Collect user interest** via an email wishlist form.
- **Visually demonstrate translations** with a device mockup and animated text.

## File Structure

- `index.html`  
  Main entry point for the NeoTranslate Pro landing page. Contains:
  - HTML structure
  - Embedded CSS for layout, parallax background, cards, and device mockup
  - Embedded JavaScript for animated translation text

- `Bgimage.jpeg`  
  Background image used for the parallax effect (referenced in CSS).

- `Device.png`  
  Device mockup image displayed on the right side of the layout.

> Ensure these image files exist in the same directory as `index.html` or update the paths in the CSS accordingly.

## Key Features

- **Hero Section**
  - Product name and tagline: *“NeoTranslate Pro – Breaking Language Barriers with AI Precision”*.
  - Short description of real-time translation across 150+ languages.

- **Problem & Solution Blocks**
  - Cards explaining common communication issues (travel, business, learning, etc.).
  - Cards describing how NeoTranslate Pro solves these problems.

- **Advantages & Target Users**
  - Lists of advantages (offline use, portability, long battery life, reliability).
  - Audience segments: travelers, business professionals, students, researchers.

- **Technical Specifications**
  - Languages supported: 150+
  - Battery life: 72 hours
  - Response time: 0.3 seconds
  - Accuracy: 99.7%
  - Connectivity: 5G, Wi-Fi 6
  - Weight: 85g

- **Feature Grid**
  - Universal translation, speed, context awareness, battery endurance.

- **Animated Device Preview**
  - Device mockup (`Device.png`) with cycling sample phrases.
  - JavaScript periodically updates the source and translated text while replaying CSS animations.

- **Email Wishlist Form**
  - Simple form for users to enter their Gmail address and click **“Add to Wishlist”**.
  - Front-end only (no backend integration by default).

- **Footer**
  - Credits: *Designed by team Amazon*.

## How to Run Locally

1. Place the following files in the same folder:
   - `index.html`
   - `Bgimage.jpeg`
   - `Device.png`

2. Open `index.html` in any modern browser:
   - Double-click `index.html`, or
   - Right-click → **Open with** → your browser, or
   - Drag and drop `index.html` into a browser window.

3. Scroll and interact with the page:
   - Observe the parallax background and glassmorphism cards.
   - Watch the device mockup cycle through example translations.
   - Test the email input and wishlist button (front-end only).

## Technologies Used

- **HTML5** – Page structure and semantic layout.
- **CSS3** – Custom styling, parallax background, responsive grid, cards, animations.
- **JavaScript (vanilla)** – Text animation logic for cycling translations.

## Notes / Next Steps

- Connect the wishlist form to a real backend (API or service) to collect emails.
- Add validation and success/error messaging for form submissions.
- Optimize images (`Bgimage.jpeg`, `Device.png`) for web performance.
- Extend responsiveness testing across mobile, tablet, and desktop breakpoints.
