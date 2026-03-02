<h2 class="c-project-heading--task">Import a Display Font</h2>

--- task ---
Import a Google Font and apply it so the card heading uses a decorative style.
--- /task ---

--- task ---
Add the font link to `index.html`, then update the font variables in `default.css`.

Code snippet 1: add the Google Fonts stylesheet link in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 13
line_highlights: 16-18
---
  <!-- Import fonts from Google -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Bangers&display=swap" rel="stylesheet">

--- /code ---

</div>

Code snippet 2: switch heading and title fonts in `default.css`.

<div class="c-project-code">

--- code ---
---
language: css
filename: default.css
line_numbers: true
line_number_start: 15
line_highlights: 16-17
---
  --body-font: 1.1rem Verdana, sans-serif;
  --header-font: lighter 3rem Bangers, cursive;
  --title-font: lighter 2rem Bangers, cursive;

--- /code ---

</div>

--- /task ---

--- task ---
**Test:** Run the project and flip the card to check that the `Lapis Sarawak` heading now uses the new display font.
--- /task ---
