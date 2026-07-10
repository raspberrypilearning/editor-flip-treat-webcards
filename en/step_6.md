## Challenge: Create Your Own Palette

Design your own look by choosing new gradient colours for both sides of the card.

In `default.css`, replace the four gradient colour variables with colours you choose.

```css filename="default.css" line_numbers="true" line_number_start="3" line_highlights="5-6,12-13"
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
```

## Now run your code

Run the project and check that your card now flips between the new colour gradients you selected.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-flip-treat-webcards-step-8" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
</iframe>

> [!CHALLENGE]
>
> ## Add a second card
>
> Duplicate your existing `<div class="card">...</div>` block inside `<section class="wrap">`, then change the image file, heading, paragraph, and `alt` text.
