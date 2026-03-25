# Technical Issue & Resolution Log

The following table documents the systematic fixes applied to the starter codebase to meet Level 4 requirements.

| Original Error (Starter Code) | The "How" (My Fix) | Technical Requirement Met |
| :--- | :--- | :--- |
| **HTML Syntax:** `<sction clss="videos">` | Corrected to valid `<section class="videos">` tags. | 0 HTML Validation Errors |
| **Missing Semantics:** Content was loose in `div` tags. | Wrapped content in `<main>`, `<article>`, and `<aside>`. | 7+ Semantic tags per page |
| **Broken CSS Links:** Styles used `.top` and `.nav`. | Updated CSS to match HTML classes `.header` and `.nav-list`. | Organized Structure |
| **Static Layout:** No flexible movement on resize. | Implemented `display: flex` and `flex-wrap: wrap`. | Flexbox Layouts |
| **Portfolio Layout:** Images were stacked vertically. | Applied `display: grid` with `repeat(auto-fit, minmax(200px, 1fr))`. | CSS Grid Layout |
| **Missing Interactivity:** Buttons had no hover state. | Added `:hover` with `transform: scale(1.05)` and `transition`. | Transforms & Transitions |
| **Form Issues:** All inputs were `type="text"`. | Changed to `email`, `tel`, and `date` with `required` attributes. | 7+ Form types & Validation |
| **Visual Effects:** Plain text headers. | Added `text-shadow` and `linear-gradient` clipping. | Text Effects |
| **Missing Animation:** No dynamic movement. | Defined `@keyframes bounce` and applied it to the Hero title. | Keyframe Animations |
