Activity 27: CSS_GRID

CSS Grid 

Here's a breakdown of the grid properties used, along with their meanings:

1. display: grid;
Turns the container into a grid, enabling the arrangement of items (the cards) in a flexible layout.
2. grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
Creates a flexible column layout where each column is at least 200px wide, but can expand to fill extra space. The grid automatically adjusts the number of columns based on the available width.
3. gap: 20px;
Sets a 20px gap between each card in the grid, both vertically and horizontally.
4. padding: 20px;
Adds space inside the grid container, ensuring the cards are not right against the edges of the container.
5. max-width: 1200px;
Limits the width of the grid container to 1200px, preventing it from becoming too wide on large screens.
6. width: 100%;
Makes the grid container take up the full width of its parent (the body of the webpage), adjusting to different screen sizes.
