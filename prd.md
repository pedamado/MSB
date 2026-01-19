## **1. Project Overview**

An interactive typographic laboratory for the analysis and visualization of Monumental Roman "Trajan" serif transitions. The application focuses on the geometric construction of the bracket (cant) curve using an exponential decay model.

## **2. Technical Requirements**

- **Framework:** HTML5, CSS3 (Tailwind), p5.js.
- **Proportional Logic:** Based on "Pen Width" (pw) units, inspired by the anatomical principles of **Yves Leterme**.
- **Mathematical Curve:** $y = 10 \cdot 5^{-x}$ (where $x$ is normalized distance from stem to terminal).
- **Navigation:**
  - **Drawing:** Left-click/single-touch for grid-snapping marquee.
  - **Panning:** Right-click or two-finger touch to offset the workspace.
- **Export:**
  - JPG (Raster snapshot).
  - SVG (Vector export with distinct layers: Grid, Stem, Serifs).

## **3. Visual & Interaction Design**

- **Branding:** "Ministry of Silly Brackets" (Monty Python-inspired).
- **Interface:** Responsive sidebar drawer (open by default, collapsible for mobile/wide viewing).
- **Colors:**
  - Stem/Serifs: Light-Medium Gray fill, Black outline.
  - Preview: Vibrant Purple (`#7e22ce`).
  - Reference Circle: Dotted lavender, representing the $N \times N$ unit square.
- **Grid:** Enhanced visibility for the Baseline and Left Sidebearing.

## **4. User Interaction**

- **Snap-to-Grid:** All marquee selections align to the pw unit grid.
- **Undo System:** Reverse-chronological removal of drawn elements.
- **Dynamic Rescaling:** Adjusting pw or grid height re-renders the canvas live.
