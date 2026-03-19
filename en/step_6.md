<h2 class="c-project-heading--task">Apply the Display Font</h2>

--- task ---
Apply the imported font so the page heading and card title use a decorative style.
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
