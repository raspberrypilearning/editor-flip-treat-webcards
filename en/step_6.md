<h2 class="c-project-heading--task">Challenge: Create Your Own Palette</h2>

### Step 1
Design your own look by choosing new gradient colours for both sides of the card.

### Step 2
In `default.css`, replace the four gradient colour variables with colours you choose.

<div class="c-project-code">

--- code ---
---
language: css
filename: default.css
line_numbers: true
line_number_start: 3
line_highlights: 5-6, 12-13
---
:root {
  --primary: #ffffff;
  --secondary: #7b4397; /* Front gradient start colour */
  --tertiary: #56ab2f; /* Back gradient start colour */
  --page: #ffffff;
  --onprimary: #664300;
  --onsecondary: #664300;
  --ontertiary: #ffffff;
  --onpage: #000000;
  --detail: #dc2430; /* Front gradient end colour */
  --detail2: #a8e063; /* Back gradient end colour */

--- /code ---

</div>


<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-flip-treat-webcards-step-8" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

### Step 3
**Test:** Run the project and check that your card now flips between the new colour gradients you selected.

### Step 4
**Extra challenge:** Add a second card.

<div class="c-project-callout c-project-callout--tip" style="font-size: 1.1em">
  <strong>Tip:</strong> Duplicate your existing `<div class="card">...</div>` block inside `<section class="wrap">`, then change the image file, heading, paragraph, and `alt` text.
</div>
