<h2 class="c-project-heading--task">Import a Display Font</h2>

--- task ---
Import a Google Font and apply it so the page heading and card title use a decorative style.
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
In the **file menu**, select `default.css` so you can apply the imported font in your CSS.
--- /task ---

--- task ---
Update the font variables in `default.css`.

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

<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-flip-treat-webcards-step-6" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

--- task ---
**Test:** Run the project and flip the card to check that the `Lapis Sarawak` heading now uses the new display font.
--- /task ---
