# Flexbox and Grid Layouts: A Simple Guide

When building websites, you need ways to arrange items (like buttons, text, images) on the page. Flexbox and Grid are two powerful CSS tools that help you do that easily.

## Flexbox
Flexbox is like a box of flexible items that can stretch or shrink to fit the space. It’s great for aligning items in a row (horizontal) or column (vertical) and making sure they look good on different screen sizes.

### Key Concepts:
- **Container**: The parent element where Flexbox is applied.
- **Items**: The child elements inside the container.
- **Main Axis**: The direction in which the items are arranged (can be horizontal or vertical).
- **Cross Axis**: The direction perpendicular to the main axis.

### Common Flexbox Properties:
- **display: flex;** → Activates Flexbox on the container.
- **justify-content:** → Aligns items along the main axis (e.g., `center`, `space-between`).
- **align-items:** → Aligns items along the cross axis (e.g., `center`, `stretch`).
- **flex-direction:** → Defines the direction of the items (e.g., `row`, `column`).
- **flex-wrap:** → Allows items to wrap onto multiple lines if needed.

### Example:
```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```
This centers the items both horizontally and vertically.


# CSS Grid

Grid is like a spreadsheet or a table. It divides the page into rows and columns, and you place items into those spaces. It’s perfect for creating more complex layouts.

## Key Concepts:
- **Grid Container**: The parent element where Grid is applied.
- **Grid Items**: The child elements inside the grid container.
- **Grid Tracks**: Rows and columns in the grid.
- **Grid Cells**: The individual boxes created by the intersection of rows and columns.

## Common Grid Properties:
- **display: grid;** → Activates Grid on the container.
- **grid-template-columns:** → Defines the number and size of columns.
- **grid-template-rows:** → Defines the number and size of rows.
- **gap:** → Adds space between the rows and columns.
- **grid-column/row:** → Lets you control where an item spans in terms of rows or columns.

### Example:
```css
.container {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 10px;
}
```
This creates a grid with two columns: the first takes 1 part, the second takes 2 parts, and there’s a 10px gap between the grid items.

## When to Use Flexbox vs Grid?
Flexbox: Best for one-dimensional layouts (rows or columns). Use when you want to align items in one direction.

Grid: Best for two-dimensional layouts (rows AND columns). Use when you want a structured layout, like a grid of cards or a dashboard.

Both are amazing for making your website responsive and looking great on all devices!
