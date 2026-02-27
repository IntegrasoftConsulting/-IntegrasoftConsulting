---
name: "Implement Presentation Prototypes"
description: "Guides the AI agent on how to implement the presentation slide prototypes from Stitch into functional code using User Stories."
---

# Skill: Implement Presentation Prototypes

This skill defines the strategy and User Stories (HUs) required to implement the "Integrasoft AI Strategy - Innovative Slides" prototypes generated in Stitch into a functional, interactive web presentation.

## Core Directives

1.  **Reference the Prototypes:** Always refer to the Stitch project ID `6210089743119414627` (Integrasoft AI Strategy - Innovative Slides) as the visual baseline.
2.  **Design System:** Maintain the dark mode, tech-forward aesthetic. Use space-black/purple backgrounds, glowing neon borders (cyan, magenta, green), glassmorphism effects, and the `Space Grotesk` font.
3.  **Technology Stack:** Implement the slides using HTML, CSS (Tailwind CSS for utility classes, custom CSS for animations/glows), and minimal vanilla JavaScript for slide transitions if necessary.
4.  **Responsive Design:** Ensure the slides look perfect on a 16:9 desktop screen, but are reasonably legible on smaller screens.

## User Stories (Historias de Usuario - HUs)

The implementation is broken down into the following User Stories. When executing this skill, address these sequentially.

### HU1: Implement the "Title / Intro" Slide
*   **As a** presenter,
*   **I want** a visually striking opening slide titled "Estrategia de Adopción de IA: SDLC Agéntico",
*   **So that** I can capture the attention of the client (**Integrasoft**) immediately with a premium consulting look tailored to them.
*   **Acceptance Criteria:**
    *   Must match the Stitch prototype design.
    *   Must include the title, subtitle, and clearly mention "Integrasoft" as the company receiving the consulting.
    *   Must feature the space-blue/black background with subtle glowing accents.

### HU2: Implement the "Impacto Proyectado" Slide
*   **As a** presenter,
*   **I want** to display the projected KPIs (Productivity +25-40%, Tech Debt -60%, ROI > $200k),
*   **So that** stakeholders can quickly understand the value proposition.
*   **Acceptance Criteria:**
    *   Must match the Stitch prototype design.
    *   Must use glassmorphism cards for the metrics.
    *   Must include the minimalist glowing bar chart or progress gauge representation.

### HU3: Implement the "Roadmap de Implementación" Slide
*   **As a** presenter,
*   **I want** to show the 12-month timeline across 4 phases,
*   **So that** the audience understands the strategic execution plan.
*   **Acceptance Criteria:**
    *   Must match the visionary 3D perspective path design from the Stitch prototype.
    *   Must include the 4 floating glassmorphism panels with their respective glowing accents (magenta/cyan).

### HU4: Implement the "Stack Tecnológico" Slide
*   **As a** presenter,
*   **I want** to display the recommended AI tools categorized by function,
*   **So that** technical stakeholders know the suggested architecture.
*   **Acceptance Criteria:**
    *   Must match the Stitch prototype design (floating matrix-like cards).
    *   Must include the 4 categories (IDE, Reasoning, Modernization, Docs & Local) with their specific neon glow colors.

### HU5: Implement the "Plan de Formación por Roles" Slide
*   **As a** presenter,
*   **I want** to compare the training focus for Junior vs. Senior developers,
*   **So that** the team understands how to avoid skill atrophy.
*   **Acceptance Criteria:**
    *   Must match the split-screen/dual-card design from the Stitch prototype.
    *   Must differentiate the roles using specific neon borders (e.g., green vs. magenta) and icons.

### HU6: Implement the "Budget & Governance" Slide
*   **As a** presenter,
*   **I want** to present the budget breakdown alongside critical governance rules,
*   **So that** stakeholders approve the investment with confidence in the safety measures.
*   **Acceptance Criteria:**
    *   Must match the split-view dashboard layout from the Stitch prototype.
    *   Must include the budget list/gauge on one side and the 4 governance glassmorphism cards on the other.

### HU7: Implement the "Consultant Profile" Slide
*   **As a** presenter,
*   **I want** to showcase the consultant's credentials and experience,
*   **So that** I establish authority and trust with the audience.
*   **Acceptance Criteria:**
    *   Must match the final Stitch prototype design.
    *   Must include the large photo placeholder on the left (ready for a transparent PNG) and the "DevSecOps Coach" name card.
    *   Must include the credentials and experience panels on the right under the main title.

## Execution Flow

When instructed to "execute the Implement Presentation Prototypes skill":
1.  Read this `SKILL.md` file comprehensively.
2.  Begin with HU1. Ask the user if they want to proceed HU by HU or build the entire structure at once.
3.  For each HU, generate the necessary HTML/CSS/JS code, ensuring strict adherence to the defined design system and Stitch prototypes.
4.  After completing an HU, show the code or render it, and ask for verification before moving to the next.
