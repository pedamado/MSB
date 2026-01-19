# **MSB - Ministry of Silly Brackets**

**"And Now for an Interactive Application for Something Completely Roman – Very Naughty Serif Cant Curves\!"**

The **Ministry of Silly Brackets (MSB)** is a pedagogical and design tool created to explore the transition from the vertical stem stroke to the horizontal serif outline in formal Roman lettering.

More information about this project is available on the GitHub repository: <https://github.com/pedamado/MSB>. For a live demo and live page, check out the main branch webpage: <https://pedamado.github.io/MSB/>.

This project was developed within the context of the Graphic Design bachelor and Editorial Projects graduate degree courses *Lettering and Typographic Drawing* and *Type Design*, in which students are expected to design and develop fully working digital typefaces. See more at: <https://letterforms.fba.up.pt/2026/01/19/and-now-for-something-completely-roman-the-ministry-of-silly-brackets/>. For the official class application demo, check it out here: <https://typedesign.fba.up.pt/msb/>.

## **Technical Curvature Explanation**

The serif bracket in this application is modeled using an exponential decay formula: $y = 10 \\cdot 5^{-x}$.

### **How the Curve Evolves:**

1.  **At the Stem (x=0):** The curve starts with its highest vertical velocity. It "falls" away from the vertical stem at a steep angle.
2.  **The Mid-Path:** As the curve travels horizontally, the exponential function $5^{-x}$ causes the vertical distance from the baseline to drop rapidly.
3.  **The Slow-Down (Target Point):** As the curve approaches the target width (the edge of the serif), the "speed" of its vertical drop effectively zeros out. It transitions into a flat horizontal line perpendicular to the stem. This visual "slowing down" creates the characteristic swelled, bracketed look of the Trajan column inscriptions.

## **The "String-Line" Method**

For students of calligraphy and stone carving, the **Envelope / String-Lines** feature (enabled in the sidebar) provides the specific straight-line segments required to frame this curve by hand. By marking specific points on your grid (e.g., 50% height on the stem and 50% width on the baseline), you can draw these straight lines to "force" the curve into its correct exponential path.

## **Key Features**

*   **Responsive Workspace:** A collapsible drawer menu for mobile-friendly use and maximum drawing area visibility.
*   **Proportional Analysis:** A reference circumference allows users to maintain the 1:1 square ratio (e.g., 10pw height) typical of 1st-century monumental inscriptions.
*   **Canvas Panning:** Right-click and drag (or two-finger touch) to move the viewport, allowing for detailed inspection of large-scale constructions.
*   **Vector Export:** Download your results as a layered SVG for further refinement in software like Adobe Illustrator or Figma, including active analysis layers.
*   **Diagnostic Overlays:** Toggle Tangent Lines, String-Line Envelopes, and Curve Speed Points to visualize the mathematical logic of the bracket.

## **Credits**

Developed by Pedro Amado (FBAUP/i2ADS/Ligatures), in Gemini 3 Pro, January 2026. Version 2.1.3. Inspired by the principles of **Yves Leterme**.
