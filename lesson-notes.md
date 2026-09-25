# M02 · HTML Page Structure - Artifact Collector Project

## 1. Data Mapping (Displayed Fields to Database Columns)
- **Title (e.g., "Starry Night Set")** -> Maps to `artifacts.title` column.
- **Category / Platform (e.g., "LEGO Art", "PlayStation 5")** -> Maps to `categories.name` column.
- **Status (e.g., "COLLECTED ✓")** -> Maps to `user_collections.status` column.
- **Hours Logged (e.g., "82.0 hrs")** -> Maps to `play_sessions.logged_hours` column.

## 2. Jinja Execution Note
Jinja will run on the server side (via Flask) before the page is rendered, dynamically populating database query results into the HTML template before sending final plain HTML to the user's browser.

## 3. Progress Note
- **What works:** Built static mockup.html and form.html matching the Artifact Collector presentation layout, complete with tables, form controls, and accessible labels.
- **What is blocked:** Awaiting Flask/SQL backend integration to replace static sample data with live database queries.
- **Next action:** Apply styling in Lesson 03 CSS.