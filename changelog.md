# Changelog

## [2.1.3] - 2026-01-19

### Finalized

- Version 2 is now complete.
- **Credits Update:** Updated credits to reflect the 2.1.3 milestone and collaborative inspiration.
- **Documentation:** Major updates to PRD and Readme files, including deep technical explanations of curve "slow-down" and the String-Line drafting method.
- **UI Refinement:** Sidebar labels now explicitly describe the Analysis Overlays and their colors.

### Fixed

- Verified SVG export functionality for all diagnostic layers.
- Confirmed coordinate mapping remains robust under extreme panning.

## [2.1.2]

- Initial labels for Speed Points and Envelope guides.

## [2.1.0] - [2.1.1]

- Implementation of Speed Points (Forest Green dots) and Density slider.
- 3px point size refinement.

## [2.0.3]

- Refined Envelope of Tangents logic using constant subtangent properties.

## **[1.5.1] - 2026-01-19**

### **Changed**

- Updated documentation and credits to reference **Yves Leterme**'s anatomical principles instead of Albert Kapr.

## **[1.5.0] - 2026-01-19**

### **Added**

- **Canvas Panning:** Implemented Right-click + Drag (Desktop) and 2-finger touch + Drag (Mobile) to offset the display.
- **Dynamic Coordinate Mapping:** Updated marquee logic to remain accurate during panning.
- **Context Menu Suppression:** Disabled browser context menu on the canvas for smoother navigation.

### **Fixed**

- **Drawing Bug:** Resolved an issue where sidebar offsets prevented accurate marquee clicks.
- **Curve Refinement:** Fine-tuned the exponential formula mapping to perfectly match $(x,y)$ coordinates for a 5-unit transition.

## **[1.4.0] - 2026-01-19**

### **Added**

- **Responsive Drawer:** Collapsible sidebar with a persistent toggle button.
- **Purple Theme:** Updated preview curves and UI highlights to a deep purple.
- **Visual Hierarchy:** Bolder H1 titles and refined typography.

## **[1.3.0] - 2026-01-19**

### **Added**

- **Layered SVG Export:** Support for distinct layers (Grid, Stem, Serifs).
- **Undo Logic:** Step-back functionality for serif creation.
- **Reference Circle:** Proportional $N \times N$ unit guide.
- **Darker Grid-lines:** Visual emphasis on Baseline and Left Sidebearing.
