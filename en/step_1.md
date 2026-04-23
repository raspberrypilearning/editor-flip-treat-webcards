<h2 class="c-project-heading--task">Build Your First Card</h2>

Create the first treat card content so you can see an image and description on your page.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

Update `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 13,29-37
---
<!DOCTYPE html>
<html lang="en">

<!-- This part is for extra information the browser needs to load the page correctly-->
<head>
  
  <meta charset="utf-8">
    
  <!-- Don't shrink the page on mobile -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  <!-- Appears on the web browser tab and search results -->
  <title>Treat flip cards</title>
  
  <!-- Import fonts from Google -->

  
  <!-- Include CSS style file -->
  <link href="style.css" rel="stylesheet" type="text/css" />
  <link href="default.css" rel="stylesheet" type="text/css" />
  <link href="animation.css" rel="stylesheet" type="text/css" />

</head>

<!-- The content that appears in the browser  -->
<body> 

    <main>
      <section class="wrap">
        <div>
          <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
        </div>
        <div>
          <h2>Lapis Sarawak</h2>
          <p>A cake baked in layers to make colourful patterns.</p>
        </div>
      </section>


    </main>

</body>

</html>

--- /code ---

</div>


<div class="c-project-output">
  <iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-flip-treat-webcards-step-2" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
  </iframe>
</div>

## Now run your code

Click **Run** and check that your page shows the Lapis Sarawak image with its heading and description.
