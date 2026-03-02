<h2 class="c-project-heading--task">Add Gradient Backgrounds</h2>

--- task ---
Apply gradient classes to both card faces so the front and back use different colour blends.
--- /task ---

--- task ---
Add gradient classes in `index.html`.

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
              <div class="card-face gradient1">
                <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
              </div>
              <div class="card-face flipme gradient2">
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
**Test:** Run your project and flip the card to verify that both sides now have gradient backgrounds.
--- /task ---
