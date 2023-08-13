## Goal: Create a reusable abstraction component which can be used for all kinds of data tables.

## Features in terms of priority
- Sorting
- Global search
- Filtering per column
- Pagination
- Mobile responsive: The table should start scrolling horizontally when the device becomes too small

- You should provide an option to set a column fixed such that only that column is not scrolled
- Row selection using checkboxes
- Choosing what column should be displayed

### In a later version
- Column reordering (with DND)
- Column width resizing
- Row DND

Persist table settings: useLocalStorage - https://usehooks.com

## Tech stack
- React 18
- TailwindCSS (we also have access to the paid components)
- ShadCN -> nice looking tables
https://ui.shadcn.com/docs/components/data-table
https://ui.shadcn.com/examples/tasks
- Tanstack Table

## Examples
Directus: https://www.youtube.com/watch?v=ZjcfDToTU5o
