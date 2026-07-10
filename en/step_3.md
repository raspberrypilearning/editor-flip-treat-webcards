## Style the Card Faces

Add the card styling classes in one go so both faces get gradients, rounded corners, shadows, and centred back text.

Update the card face classes in `index.html`.

```html filename="index.html" line_numbers="true" line_number_start="31" line_highlights="32,35"
            <div class="card-content">
              <div class="card-face gradient1 rounded shadow">
                <img src="LapisSarawak02.png" alt="Lapis Sarawak" />
              </div>
              <div class="card-face flipme gradient2 rounded ycenter shadow">
                <h2>Lapis Sarawak</h2>
                <p>A cake baked in layers to make colourful patterns.</p>
              </div>
            </div>
```

## Now run your code

Run the project and flip the card to check that both sides have gradients and shadows, and that the back text sits in the centre.

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/editor-flip-treat-webcards-step-4" width="600" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen>
</iframe>
