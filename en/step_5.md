<h2 class="c-project-heading--task">Round the Card Corners</h2>

--- task ---
Add rounded corners to both card faces to give the card a softer style.
--- /task ---

--- task ---
Add the `rounded` class to both faces in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 29
line_highlights: 32,35
---
       <section class="wrap">
         <div class="card">
            <div class="card-content">
              <div class="card-face gradient1 rounded">
                <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
              </div>
              <div class="card-face flipme gradient2 rounded">
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
**Test:** Run the project and flip the card to check that both sides have rounded corners.
--- /task ---
