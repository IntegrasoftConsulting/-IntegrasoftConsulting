---
name: frontend-best-practices
description: Core standards for premium front-end development, glassmorphism design, and robust presentation layouts.
---

# Front-End Best Practices: Integrasoft Standard

This skill codifies the architectural and aesthetic standards used in the Integrasoft Consulting workspace. It ensures consistency, performance, and visual excellence across all projects.

## 1. Core Design Principles

### A. Glassmorphism & Depth
Every UI container should feel like a premium glass surface.
- **Background**: Use `rgba(255, 255, 255, 0.05)` to `0.1` for dark themes.
- **Blur**: Apply `backdrop-filter: blur(12px)`.
- **Borders**: Subtle top borders `border-t-2 border-white/10` simulate light hitting the edge.
- **Shadows**: Use soft, colored glows instead of harsh black shadows (e.g., `box-shadow: 0 0 30px rgba(13, 185, 242, 0.2)`).

### B. Ambient Backgrounds
- Use a dark base `background: #050505`.
- Layer with animated "ambient glows" (large blurred divs with radial gradients).
- Add a subtle grid overlay for a high-tech/engineering feel.

## 2. HTML5 & Semantic Structure

- **Sectioning**: Use `<section>` for logical slides or blocks with unique IDs.
- **Typography Hierarchy**: Use a single `<h1>` per page. Use fluid typography scales (e.g., `text-fluid-title`).
- **Accessibility**: Ensure all interactive elements have ARIA labels or descriptive titles.

## 3. Advanced CSS Patterns

### A. Animations
- **Micro-interactions**: Every button and hover state should have a `transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1)`.
- **Floating Effects**: Use `@keyframes float` to give life to static elements.
- **Neon Accents**: Define core brand colors as CSS variables or utility classes (e.g., `.text-neon-cyan`).

### B. Responsive Grid/Flex
- Prefer **Grid** for main quadrant layouts.
- Use **Flex** for centered card alignment.
- **Fluid Title Rule**: Always use `clamp()` for titles to ensure they fit both mobile and desktop.

## 4. PDF Export Reliability (Hard-won Lessons)

When building capture-ready presentations:
- **Fixed Dimensions**: Capturing for PDF requires a standardized "Export Viewport". Use `1600x900px` (16:9) to prevent clipping.
- **Style Overrides**: Create a `.pdf-no-filters` class.
    - **Crucial**: Disable `backdrop-filter` during export. `html2canvas` often fails or produces noise with heavy blurring.
    - **Crucial**: Set `height: auto` on containers but a fixed `height` on individual sections to prevent "ghost pages".
- **Dynamic Capture**: Always calculate the number of slides programmatically to adjust the final capture area height.

## 5. JavaScript Integration

- **Clean State Management**: Use CSS classes (e.g., `.active`, `.hidden`) instead of inline styles for state transitions.
- **Initialization**: Wait for `DOMContentLoaded` and ensure all SVG charts or interactive elements are rendered before enabling user interactions.

---
*Created for Integrasoft Consulting by Antigravity.*
