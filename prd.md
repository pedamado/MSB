# MSB - Ministry of Silly Brackets

## "And Now for an Interactive Application for Something Completely Roman – Very Naughty Serif Cant Curves! No pixels were harmed in the making of these monumental inscription transitions."

The **Ministry of Silly Brackets (MSB)** is a pedagogical and design tool created to explore the transition from the vertical stem stroke to the horizontal serif outline in formal Roman lettering.

More information about this project is available on the GitHub repository: [https://github.com/pedamado/MSB](https://github.com/pedamado/MSB). For a live demo and live page, check out the main branch webpage: [https://pedamado.github.io/MSB/](https://pedamado.github.io/MSB/).

This project was developed within the context of the Graphic Design bachelor and Editorial Projects graduate degree courses _Lettering and Typographic Drawing_ and _Type Design_, in which students are expected to design and develop fully working digital typefaces. See more at: [https://letterforms.fba.up.pt/2026/01/19/and-now-for-something-completely-roman-the-ministry-of-silly-brackets/](https://letterforms.fba.up.pt/2026/01/19/and-now-for-something-completely-roman-the-ministry-of-silly-brackets/). For the official class application demo, check it out here: [https://typedesign.fba.up.pt/msb/](https://typedesign.fba.up.pt/msb/).

## 1. Executive Summary

The **Ministry of Silly Brackets (MSB)** is a highly specialized interactive environment built using **p5.js** for the mathematical analysis and geometric construction of **Monumental Roman (Trajan) serif transitions**. It serves as a pedagogical bridge between digital code and classical "by-eye" calligraphy, specifically analyzing the "Brackett" or "Cant" curve.

## 2. Core Mathematical Logic

### 2.1 The Exponential Decay Model

The curve transition from the vertical stem to the horizontal terminal baseline follows the equation:

$$y = a \cdot b^{-x}$$

Where:

- **a = 10**: The vertical scaling factor (stem connection point).
- **b = 5**: The exponential base defining curvature speed.
- **c = 0**: The vertical asymptote (baseline).

### 2.2 Curvature Evolution

As $x$ increases (moving away from the stem), the curve's vertical distance from the baseline decreases exponentially. This results in a visual "acceleration" that flattens out almost completely as it reaches the 1pw width terminal.

## 3. Interaction Mechanics

### 3.1 Grid Snapping

A dynamic grid of "Pen Width" (pw) units. User-drawn marquees snap to the nearest unit, ensuring anatomical accuracy according to the principles of **Yves Leterme** and **Albert Kapr**.

### 3.2 Coordinate Mapping

- **Canvas Centering:** The grid is automatically centered in the viewport.
- **Pan Logic:** Right-click (desktop) or two-finger touch (mobile) offsets the grid origin via panX and panY.
- **Relativity:** Mouse events are calculated relative to (ox, oy), allowing for drawing and analysis to remain synced during panning.

## 4. Analytical Layers

### 4.1 Tangent Lines (Orange)

Geometric derivatives at $t=0.25, 0.5, 0.75$ visualized as orange lines. Useful for understanding the instantaneous direction of the curve.

### 4.2 Envelope / String-Lines (Red/Blue)

A manual drafting guide based on the **Envelope of Tangents** method.

- **Dark Blue Guides:** Tangents pinned to the Vertical Stem at 100% and 50% height.
- **Dark Red Guides:** Tangents pinned to the Horizontal Baseline at 100% and 50% width.
- **Extension:** Guide-lines extend 10% past intercepts to simulate ruler-overshoot.

### 4.3 Curve Speed Points (Green)

Renders the curve as discrete points (10–100 density).

- **Visual Feedback:** Closer points indicate "slower" change (steep sections); spreading points indicate "acceleration" (flattening sections).

## 5. Deployment & Export

- **JPG Export:** Raster snapshot of the current viewport.
- **SVG Export:** Layered vector output including Grid, Stem, Serifs, and active Analysis Layers (Tangents, Envelopes, Speed Points).

## 6. Historical Development Prompts (AI Master Reference)

- _Refined Formula:_ "y = 10 \* pow(b, x) + c logic with a=10, b=5, c=0."
- _Manual Logic:_ "By identifying where a straight line intersects the vertical stem (waisting) and horizontal terminal (baseline) at easy-to-measure integer units, a student can frame the curve."
- _Layout:_ "Collapsible drawer sidebar on the left, p5.js canvas on the right, fully responsive for mobile."
