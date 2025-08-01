# To-Do App – Emergency Bug Fix Challenge

This is a simple and efficient browser-based To-Do List application, submitted as part of the **Emergency Bug Fix Challenge**. The application allows users to add, complete, and filter tasks — with full data persistence using `localStorage`.

> All three critical bugs have been fixed and tested successfully.

---

## Fixed Bugs

### Bug 1 – Tasks Not Visible on Page Load
- **Root Cause:** The original implementation used `setTimeout()` in `loadTasks()`, causing a delay before loading tasks from `localStorage`.
- **Fix:** Removed `setTimeout()` and made task loading synchronous, ensuring tasks are ready before rendering.

### Bug 2 – Filter Buttons Don’t Filter
- **Root Cause:** Clicking a filter button updated the internal state but did not re-render the task list.
- **Fix:** Added a call to `renderTasks()` inside `setFilter()` so the task list updates immediately when a filter is selected.

### Bug 3 – Tasks Disappear on Refresh
- **Root Cause:** Same as Bug 1 — delayed loading meant the tasks weren’t available in time for rendering after page load.
- **Fix:** With the fix in Bug 1, this issue was also resolved by ensuring synchronous data loading.

---

## File Overview

```bash
todo-bugfix-challenge/
├── index.html       # HTML structure of the To-Do App
├── app.js           # JavaScript logic (including all bug fixes)
├── styles.css       # Styling for tasks, filters, and layout
├── instructions.md  # Original readme.md containing specs of challenge
└── README.md        # This file

