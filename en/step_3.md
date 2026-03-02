<h2 class="c-project-heading--task">Make the Card Flip</h2>

--- task ---
Wrap your content with the flip-card classes so the card has a front face and a back face.
--- /task ---

--- task ---
Update the card structure in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 28
line_highlights: 30-32,35
---
    <main>
       <section class="wrap">
         <div class="card">
            <div class="card-content">
              <div class="card-face">
                <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
              </div>
              <div class="card-face flipme">
                <h2>Lapis Sarawak</h2>
                <p>A cake baked in layers to make colourful patterns.</p>
              </div>
            </div>
        </div>
      </section>

--- /code ---

</div>

--- /task ---

--- task ---
**Test:** Click **Run**, then hover over or tap the card to confirm it flips and shows the text on the back.
--- /task ---
