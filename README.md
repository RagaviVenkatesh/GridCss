# GridCss

CSS Grid is a two-dimensional layout system, meaning you can control both rows and columns simultaneously. It provides powerful layout capabilities that are not possible with Flexbox alone.

**Basic Terminology**

Grid Container – The parent element where display: grid is applied.

Grid Items – The direct children of the grid container.

Grid Lines – The horizontal and vertical lines separating the grid.

Grid Tracks – The space between grid lines (rows and columns).

Grid Cells – The individual units created by rows and columns.

Grid Areas – A collection of grid cells forming a larger block.

**Explanation**

Grid Container (.grid-container)

display: grid; → Enables Grid Layout.

grid-template-columns: repeat(3, 1fr); → Creates 3 equal columns.

grid-template-rows: 100px 100px; → Creates 2 rows of 100px height.

gap: 10px; → Adds spacing between grid items.

Grid Items (.grid-item)

Styled with flexbox to center text inside.

Given rounded corners and background color.

Responsive Design (@media)

If screen width ≤ 600px, switches to single column.
