# 📺 Project: YouTube Clone Demonstration

This folder contains the final, responsive YouTube clone built using only pure HTML and CSS. This project demonstrates the practical application of advanced CSS layout techniques learned in the course.

## ✨ Project Status

The clone currently replicates the core homepage structure and successfully displays a static grid of **12 video previews**.

## 🛠️ Implementation Highlights

| Component | Layout Technique Used | Key CSS Properties Demonstrated |
| :--- | :--- | :--- |
| **Header** | **Flexbox** | `display: flex`, `justify-content`, `align-items` |
| **Sidebar** | **Positioning** | `position: fixed`, `left: 0`, `top: 0`, `z-index` |
| **Video Grid** | **CSS Grid** | `display: grid`, `grid-template-columns`, `column-gap`, `row-gap` |
| **Video Cards** | **Nested Flexbox** | Used within each card to align the profile picture and video text details horizontally. |

## 🖼️ Screenshots 

## 🖼️ Screenshots Demonstrating Responsiveness

These images are proof of the successful implementation of CSS media queries and modern layout techniques, ensuring the YouTube clone works well across different screen sizes (viewports).

---

### 1. Full Desktop View (Wide Viewport)

**Heading Focus:** **Wide Layout & Fixed Sidebar**

This screenshot displays the complete layout on a large screen:

* **Fixed Elements:** Highlights the use of `position: fixed` for both the **Header** (Flexbox) and the **full, expanded Sidebar** with text and icons.
* **Video Grid:** Utilizes the available width with a **4-column CSS Grid** structure, demonstrating maximum content density for large viewports.

<img width="1885" height="920" alt="Screenshot 2025-10-17 122400" src="https://github.com/user-attachments/assets/7910d38f-a9ab-4374-b2f0-e844fdcf2a5f" />

---

### 2. Grid Fluidity & Mid-Screen Adaption

**Heading Focus:** **Fluid Grid Columns Adjustment**

This view demonstrates the initial responsive behavior as the screen size narrows:

* **Grid Adjustment:** Shows how the **CSS Grid** layout maintains its integrity, ensuring columns and gutters fluidly adjust without breaking content (e.g., still displaying 4 columns, but narrower).
* **Video Card Detail:** Proves that the internal **Nested Flexbox** of each video card remains perfectly aligned and legible, even as the elements shrink.

<img width="1253" height="866" alt="Screenshot 2025-10-17 122430" src="https://github.com/user-attachments/assets/6ddb0f2e-1816-47c0-b4a3-62bf3fdec7e6" />

---

### 3. Sidebar Collapse & Content Reflow

**Heading Focus:** **Critical Sidebar Breakpoint**

This image captures a major breakpoint, showcasing the most important responsive feature:

* **Sidebar Transition:** Demonstrates the use of a CSS Media Query to collapse the sidebar into a **minified/icon-only state** (or possibly a hidden hamburger menu behind the scenes).
* **Content Reflow:** The main video content area successfully reflows to utilize the space gained from the collapsed sidebar, maximizing content display for tablet or narrower desktop views.

<img width="840" height="871" alt="Screenshot 2025-10-17 122448" src="https://github.com/user-attachments/assets/fabfcbe8-8c8e-4ab9-9a05-b5d2fa3b385e" />



