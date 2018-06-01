# modal-pop-up
Demonstrates how to create a modal pop-up with just html and css.

### The HTML
The page starts with a wrapper to center and shape the content area.
The important bit for this demo is the link and the infopanel div.
- The link targets the infopanel, so we can use that state for css purposes.
- The content div is the actual pop-up which will appear when the link is clicked.
- The close button links back to the top of the page which removes the target state from the pop-up.

The HTML file is commented to make identifying the different elements more easily.

### The CSS
I will leave the standard rules be; these are not relevant for this demo.

modal_box starts out invisble, no dimensions and full transparency.
When modal_box becomes targeted (when the link is clicked) we make it cover everything and transit the background color to black with 80% alpha.

At the same time content becomes visible as a white shadowed box. Please note that by calculating the left position, we can make sure the pop-up always appears in the center of the screen.

Further styling mainly is the close button, which we need to position, make a circle and contain an X.

The CSS file is heavily commented to explain the different rules.

## [Take a look at the live working version of this demo](https://VincentKlijn.github.io/modal-pop-up/)
