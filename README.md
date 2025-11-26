# 🎨 CSS Flexbox Mini-Project

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-Learning-yellow?style=for-the-badge)

## 📸 Project Preview

![Project Screenshot](./screenshot.png)

## 💡 About The Project

This is a mini learning project focused on mastering *CSS Flexbox*. The goal was to move away from older layout models and understand how to control alignment, spacing, and element sizing dynamically.

I built a layout that demonstrates both *Container* properties and *Item* properties.

## 🛠 Concepts Applied

I focused on the following specific Flexbox properties:

### 1. Container Properties (Parent)
These control the layout of the whole section:
- **display: flex;**: The magic switch to turn on Flexbox.
- **flex-direction**: Controlling the main axis (row vs column).
- **justify-content**: Aligning items along the main axis (centering, spacing out).
- **align-content**: Managing space between multiple rows of items.
- **gap**: Adding consistent spacing between elements without using margins.

### 2. Item Properties (Children)
These control the individual elements inside the container:
- **flex-grow**: I used this to allow specific items to expand and fill the available empty space.

## 💻 Code Snippet

Here is how I implemented the flexible container structure:

css
.container {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-content: center;
    gap: 20px;
}

.item-special {
    /* This item takes up remaining space */
    flex-grow: 1; 
}
