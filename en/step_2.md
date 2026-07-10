## Make the Card Flip

Wrap your content with the flip-card classes so the card has a front face and a back face.

Update the card structure in `index.html`.

```html filename="index.html" line_numbers="true" line_number_start="28" line_highlights="30-32,35,38-39"
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
```

## Now run your code

Click **Run**, then hover over or tap the card to confirm it flips and shows the text on the back.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-flip-treat-webcards-step-3" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
</iframe>
