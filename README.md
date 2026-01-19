# **MSB - Ministry of Silly Brackets**

**"And Now for an Interactive Application for Something Completely Roman – Very Naughty Serif Cant Curves! No pixels were harmed in the making of these monumental inscription transitions."**

The **Ministry of Silly Brackets (MSB)** is a pedagogical and design tool created to explore the transition from the vertical stem stroke to the horizontal serif outline in formal Roman lettering.

More information about this project is available on the GitHub repository: [https://github.com/pedamado/MSB](https://github.com/pedamado/MSB). For a live demo and live page, check out the main branch webpage: [https://pedamado.github.io/MSB/](https://pedamado.github.io/MSB/).

This project was developed within the context of the Graphic Design bachelor and Editorial Projects graduate degree courses _Lettering and Typographic Drawing_ and _Type Design_, in which students are expected to design and develop fully working digital typefaces. See more at: [https://letterforms.fba.up.pt/2026/01/19/and-now-for-something-completely-roman-the-ministry-of-silly-brackets/](https://letterforms.fba.up.pt/2026/01/19/and-now-for-something-completely-roman-the-ministry-of-silly-brackets/). For the official class application demo, check it out here: [https://typedesign.fba.up.pt/msb/](https://typedesign.fba.up.pt/msb/).

## **Mathematical Foundation**

The "Brackett" or "Cant" curve is a transitional element that gives Trajan letters their characteristic "swelled" elegance. This app utilizes an exponential decay formula to model this acceleration:

$$y = 10 \\cdot 5^{-x}$$

This ensures that the tangent of the transition starts 2pw from the end of the stem stroke and widens smoothly until it flattens completely at the terminal.

## **Key Features**

- **Responsive Workspace:** A collapsible drawer menu for mobile-friendly use.
- **Proportional Analysis:** A reference circumference allows users to maintain the 1:1 square ratio (e.g., 10pw height) typical of 1st-century monumental inscriptions.
- **Canvas Panning:** Right-click and drag to move the viewport, allowing for detailed inspection of large-scale constructions.
- **Vector Export:** Download your results as a layered SVG for further refinement in software like Adobe Illustrator or Figma.

## **Credits**

Developed by Pedro Amado (FBAUP/i2ADS/Ligatures), in Gemini 3 Pro, January 2026. Version 1.5.1. Inspired by the anatomical principles and analysis of **Yves Leterme**.
