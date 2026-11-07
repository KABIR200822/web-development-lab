# P13 – Choosing Between Flexbox and Grid

## Aim
Understand when Flexbox or CSS Grid is more suitable for a shared page layout.

## Flexbox
Flexbox is primarily a one-dimensional layout system. It arranges items in a row or a column.

Example:
```css
.navigation {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 1rem;
}
```

Use Flexbox for navigation bars, toolbars, button groups and a row of aligned items.

## CSS Grid
Grid is a two-dimensional layout system. It controls columns and rows together.

Example:
```css
.project-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem;
}
```

Use Grid for project galleries, dashboards, newspaper layouts and page sections that need aligned rows and columns.

## Comparison

| Flexbox | CSS Grid |
|---|---|
| One-dimensional | Two-dimensional |
| Works along a row or column | Works with rows and columns |
| Useful for navigation and alignment | Useful for page and card layouts |
| Content often determines item sizing | Tracks define the layout structure |

## Conclusion
Neither system replaces the other. Flexbox is a good choice for arranging items along one axis, while Grid is better when both rows and columns need control. They can also be combined in the same page.
