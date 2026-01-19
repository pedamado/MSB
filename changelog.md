# **Changelog**

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
