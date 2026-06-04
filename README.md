[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/uFImwIHI)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=23179958&assignment_repo_type=AssignmentRepo)
# Advanced Media Production Website

## Overview
A comprehensive restoration of a 4-page media production company website. The project involved a complete codebase audit, refactoring 58+ identified structural and stylistic errors, and implementing advanced modern CSS layouts to ensure full compliance with the Capstone 1 technical requirements.

## Audit & Remediation Summary
The original starter code was non-semantic and lacked responsive design. All issues were mapped and resolved:
* **HTML:** Replaced all generic `<div>` containers with semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
* **Media:** Integrated functional video and audio assets with appropriate fallbacks and `<iframe>` support.
* **Forms:** Reconstructed the contact form using 7+ unique input types, fieldset groupings, and full HTML5 validation constraints.
* **CSS:** Implemented two distinct Flexbox layouts and a responsive CSS Grid gallery.
* **Validation:** Passed W3C Markup and CSS validation (0 errors).

## Technical Requirements Fulfillment
* **Flexbox:** 2 layouts (Header Navigation + Services Section). Used `justify-content`, `align-items`, and `flex-wrap`.
* **CSS Grid:** 1 gallery layout using `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`.
* **Selectors:** 6+ types (including Attribute and Combinator selectors).
* **Pseudo-classes:** 6+ implemented (e.g., `:hover`, `:focus-visible`, `:not()`, `:nth-child`).
* **Animations/Effects:** Implemented `text-shadow`, 3D `transforms`, `transitions` for hover states, and an entrance `@keyframes` animation.

## Project Structure
* `index.html`, `about.html`, `media.html`, `contact.html`: Semantic structural templates.
* `CSS/`: Contains `styles.css` (Modular architecture).
* `media/`: Contains localized audio/video assets for accessibility.
* `documentation/`: Contains PDF reports, wireframes, and `screenshots/` for validation proof.

## Validation & Testing
* **Browser Testing:** Verified across Chrome and Firefox.
* **W3C Validation:** Markup and CSS passed standard validation protocols.
* **Responsiveness:** Fluid layouts confirmed at 320px, 768px, and 1200px breakpoints.

## Screenshot Inventory
| Description | File Path |
| :--- | :--- |
| Desktop Chrome View | `screenshots/desktop-chrome.png` |
| Desktop Edge View | `screenshots/desktop-edge.png` |
| Mobile Layout | `screenshots/mobile-viewport.png` |
| Tablet Grid Layout | `screenshots/tablet-viewport.png` |
| Media Gallery Grid | `screenshots/media-grid-responsive.png` |
| W3C HTML Validation (0 Errors) | `screenshots/w3c-html-validation.png` |
| W3C CSS Validation (0 Errors) | `screenshots/w3c-css-validation.png` |
| Form Validation Proof | `screenshots/interactive-form-validation.png` |

## Reflection
The primary technical challenge was re-engineering the contact form to include all mandatory input types while maintaining a clean, usable interface without JavaScript. By utilizing fieldsets and native HTML5 validation, I achieved a secure, accessible form that meets all project constraints. The transition from a non-semantic legacy codebase to a responsive, grid-based modern architecture significantly improved both the site's accessibility scores and visual performance.