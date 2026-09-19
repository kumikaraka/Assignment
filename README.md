# Budget Tracker

This project is a responsive budget tracking dashboard built with semantic HTML, CSS Grid, and Flexbox. It includes a form for adding expenses, a structured expense table, summary cards, navigation, multimedia content, and a cohesive CSS visual identity.

## Files in this project

- `index.html` – Contains the page structure and all required HTML elements.
- `style.css` – Adds the theme variables, Grid page layout, Flexbox navigation and card layouts, typography, table formatting, and responsive behavior.
- `README.md` – Explains what the project contains and how each section works.

## What is included

### Dashboard layout
- The `.app-shell` uses CSS Grid to place the sidebar beside the main dashboard.
- The dashboard uses Grid for the summary cards and lower content area.
- Flexbox arranges the header, sidebar navigation, and content inside each dashboard card.
- Below 768px, the layout collapses to one column and the navigation wraps for smaller screens.

### Theme and interactions
- `:root` custom properties define the brand, accent, surface, background, primary text, and secondary text colors.
- A `prefers-color-scheme: dark` media query overrides only the theme variables for dark mode.
- Dashboard cards animate with a 200ms transform and shadow on hover and keyboard focus.

### Expense table
- The `expenses-section` contains a proper HTML table with `thead`, `tbody`, `tr`, `th`, and `td`.
- It includes five sample expense rows for Name, Amount, Category, and Date.
- The table is styled with borders, colored headers, alternating row colors, and hover effects.

### Add Expense form
- The form is wrapped in a proper `form` element.
- The old category text field was replaced with a `select` dropdown containing the required options: Food, Transport, Rent, Entertainment, and Other.
- Every input has a matching `id` attribute and the button uses `type="button"` as requested.

### Multimedia content
- A small icon image is included near the main heading using the `img` tag.
- A YouTube video is embedded using an `iframe` with the required attributes.

### Interactive elements
- A `details` and `summary` section was added to provide a collapsible explanation of how the tracker works.
- Table rows change color on hover.
- The Add Expense button shows a pointer cursor on hover.

### Visual identity
- A restrained ink, sage, coral, and paper palette is used consistently across the page.
- Space Grotesk is used for headings and DM Sans is used for body text and controls.
- The heading, Add Expense form, and Expense Table are presented as distinct cards with padding, borders, rounded corners, and shadows.
- The table includes a styled header, cell spacing, borders, alternating row colors, and a hover state.
- The form controls and button share consistent sizing, rounded corners, focus styling, and spacing.

### Advanced CSS selectors
- Descendant selector: `.expenses-section td`
- Direct child selector: `.add-expense-section > form`
- Pseudo-class based on position: `tbody tr:nth-child(even)`
- Negation pseudo-class: `input:not([type="button"])`
- Focus state: `.form-group input:focus, .form-group select:focus`

## Purpose
This page acts as a Week 2 step-up from the earlier Budget Tracker, showing how HTML and CSS can be used to build a more complete and polished interface.
