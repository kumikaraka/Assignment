# Budget Tracker

This project is a simple budget tracking webpage built as part of the Week 3 visual design challenge. It includes a form for adding expenses, a structured expense table, multimedia content, and a cohesive CSS visual identity.

## Files in this project

- `index.html` – Contains the page structure and all required HTML elements.
- `style.css` – Adds the visual styling, typography, table formatting, form layout, responsive behavior, and advanced CSS selectors.
- `README.md` – Explains what the project contains and how each section works.

## What is included

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
