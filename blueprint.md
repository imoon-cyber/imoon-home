# Project Blueprint: IMOON Robotics Website

## Overview

This document outlines the design, features, and implementation plan for the IMOON Robotics corporate website. The website will serve as a professional online presence for the company, showcasing its mission, products, and services.

## Style and Design

*   **Aesthetics:** A professional and modern design with a dark theme that is sleek and easy on the eyes.
*   **Color Palette:** A dark-themed palette using shades of dark gray and black as a base, with a vibrant blue as the primary accent color. White and light gray will be used for text and highlights.
*   **Typography:** Clear and legible fonts. A combination of a modern sans-serif font for headings and a highly readable font for body text.
*   **Layout:** A responsive, mobile-first layout that ensures a seamless experience across all devices. The layout will be clean and spacious, with a clear visual hierarchy.
*   **Iconography:** Use of icons to enhance usability and visual appeal.
*   **Imagery & Video:** High-quality images, graphics, and videos of robots and healthcare settings will be used.

## Features

*   **Header:** A sticky header containing the company logo and navigation menu.
*   **Hero Section:** A full-screen hero section with a background video and a compelling headline.
*   **About Us Section:** A section detailing the company's mission and vision.
*   **Robots Section:** A section showcasing the company's robot products.
*   **Services Section:** A section outlining the services offered by the company.
*   **Contact Section:** A section with a contact form and other contact information.
*   **Footer:** A footer with copyright information and social media links.

## Current Plan: Add Dark/Light Mode Toggle

### Overview
Implement a theme-switching feature that allows users to toggle between a dark mode and a light mode.

### Steps
1.  **Add a theme toggle button:** Add a button or switch to the header of the `index.html` file.
2.  **Update CSS for theming:** 
    *   Define two color palettes (dark and light) using CSS variables.
    *   Create a `.light-mode` class on the `body` to apply the light theme.
3.  **Implement theme switching in JavaScript:**
    *   In `main.js`, add an event listener to the toggle button.
    *   When the button is clicked, toggle the `.light-mode` class on the `body` element.
    *   Store the user's theme preference in `localStorage` to persist the chosen theme across sessions.
