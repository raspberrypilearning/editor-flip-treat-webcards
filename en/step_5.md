<h2 class="c-project-heading--task">Center Text and Add Shadows</h2>

--- task ---
Improve readability and depth by centering the back content and adding shadows to both faces.
--- /task ---

--- task ---
Update your card face classes in `index.html`.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 31
line_highlights: 34,37
---
         <div class="card">
            <div class="card-content">
              <div class="card-face gradient1 rounded shadow">
                <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
              </div>
              <div class="card-face flipme gradient2 rounded ycenter shadow">
                <h2>Lapis Sarawak</h2>
                <p>A cake baked in layers to make colourful patterns.</p>
              </div>
            </div>
        </div>

--- /code ---

</div>

--- /task ---

--- task ---
**Test:** Run the project and flip the card to confirm the text sits centrally on the back and both faces have a shadow.
--- /task ---
