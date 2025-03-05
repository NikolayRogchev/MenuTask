# MenuTask

The chosen solution displays 2 pages: menu with only root elements, and menu with random levels of nesting.

Since we don't have limitation of the levels of nesting we use recursive strategy to propagate the level and the anchor element to the children.

This way we delegate the positioning logic to the child.

We use absolute positioning with js calculations to solve the restriction that each submenu should be both child of parent submenu and a parent to child item
