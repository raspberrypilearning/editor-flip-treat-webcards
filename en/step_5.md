<h2 class="c-project-heading--task">Import a Display Font</h2>

--- task ---
Import a Google Font so it is ready to use in your card styles.
--- /task ---

--- task ---
Add the Google Fonts stylesheet link in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 16
line_highlights: 17-19
---
  <!-- Import fonts from Google -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">

--- /code ---

</div>

--- /task ---

--- task ---
**Test:** Run the project. You will not see a visible change yet, but the font is now available for your CSS to use.
--- /task ---
