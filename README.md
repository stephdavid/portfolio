# Module 2 - Working with CSS Challenge: Portfolio

## A webpage to showcase my skills and talents to prospective employers.

### Interesting features of this responsive HTML/CSS page:

* "Work" section images embedded in the HTML page rather than as a CSS background property. This enables the use of an alt tag and figure/figcaption tags - better for accessibility. The 02-hero-bg.jpg image was left as css property - it's decorative only. As well, it only appears with a larger screen. See @media queries below.
  
* Use of css grid and flex techniques. These are specific to the screen size.  See @media queries below.

* Use of @media queries - mobile first approach.

* Use of variable colors e.g. --altbkd: #adb3f0; Rather than using the color as the name of the property, its function is its name. This is useful if a different look and feel is wanted.
  
### Issues:

These issues will be revisted:

* The grid and flex properties at the top of the page - even when the declarations are used with specificity (e.g. class or id or other approaches) - interfere with later use of grid and flex causing some "funky" misbehaviour. Embedding the "Work" section images in the html started as a work-around, but actually, I think, is a better accessible approach allowing for the use of the alt and figure/figcaption tags.
  
* Perhaps because of the above an attempt to use a responsive image - https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images - failed. I've left a commented-out placeholder in the html file.


