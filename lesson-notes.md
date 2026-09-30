# Lesson 02 - HTML Page Structure Notes

## Database Column Mapping
- **Artifact Name** (`item_title`) -> Maps to `artifacts.title` (VARCHAR)
- **Category** (`item_category`) -> Maps to `categories.name` or `artifacts.category_id` (INT / FOREIGN KEY)
- **Condition** -> Maps to `artifacts.condition` (VARCHAR)
- **Status** (`item_status`) -> Maps to `artifacts.status` (VARCHAR / ENUM)

## Jinja Execution Note
Jinja will run on the server side inside Flask before rendering and sending the finalized HTML page to the browser.

## Progress Note
- **What works:** `mockup.html` and `form.html` are linked together. Labels properly trigger inputs, and table headers use proper scoping.
- **What is blocked:** None.
- **Next action:** Style the pages using custom CSS for Lesson 03.