# Olivia Website Review

## Completed in CSS

- Shared green navigation with brown hover and visible keyboard focus.
- Navigation changes from wrapping Flexbox to a two-dimensional Grid at `768px` and below.
- Added consistent heading, form-control, submit-button, and table styling.
- Added small-screen table and form adjustments.
- No CSS framework is used.

Flexbox suits the desktop navigation row and wrapping behavior. Grid gives navigation links consistent columns on small screens.

## Still needs HTML changes

The earlier instruction was to leave HTML files untouched, so these remain open:

- `about.html` has a broken stylesheet link (`href="C"`).
- Most pages need a viewport meta tag for reliable mobile sizing.
- Several pages use an absolute `/CSS/style.css` link; use a path appropriate to the site location.
- A shared footer and card component are not present in the page markup.
- Forms use plain text labels and line breaks instead of associated labels and structured layout.

## QA status

Source review only; no browser testing was performed. Check at mobile, tablet, and desktop widths. Pay special attention to tables and navigation wrapping. Images were not found on the reviewed site pages.
