<h2 class="c-project-heading--task">Challenge: Create Your Own Palette</h2>

--- task ---
Design your own look by choosing new gradient colours for both sides of the card.
--- /task ---

--- task ---
In `default.css`, replace the four gradient colour variables with colours you choose.

<div class="c-project-code">

--- code ---
---
language: css
filename: default.css
line_numbers: true
line_number_start: 3
line_highlights: 5-6,12-13
---
:root {
  --primary: #ffffff;
  --secondary: #7b4397;
  --tertiary: #56ab2f;
  --page: #ffffff;
  --onprimary: #664300;
  --onsecondary: #664300;
  --ontertiary: #ffffff;
  --onpage: #000000;
  --detail: #dc2430;
  --detail2: #a8e063;

--- /code ---

</div>

--- /task ---

--- task ---
**Test:** Run the project and check that your card now flips between the new colour gradients you selected.
--- /task ---
