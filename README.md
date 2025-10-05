
a. Responsive Design and Viewports

I used Fluid Design with Media Queries and created separate CSS files for each device type.
No Flexbox was used.

Viewports:

Laptop/Desktop: laptop.css → (min-width:960px)
Used for larger screens to keep layout wide and spaced.

Tablet: tablet.css → (min-width:481px) and (max-width:959px)
Used for medium screens like tablets.

Mobile: style.css → (max-width:480px)
Used for smaller screens with a single-column layout.



b. Gradient Usage

I used a linear gradient on the body background of all pages.

background: linear-gradient(
    to right,
    rgba(21, 69, 133, 1),
    rgba(22, 133, 197, 1),
    rgba(26, 158, 235, 1),
    rgba(42, 191, 240, 1)
);

This creates a dark-to-light blue transition from navy to aqua.



c. Color Scheme

I created a monochromatic blue color scheme using Adobe Color.

Here is the colour scheme: 

/* Color Theme Swatches in RGBA */
.My-Color-Theme-1-rgba { color: rgba(26, 158, 235, 1); }
.My-Color-Theme-2-rgba { color: rgba(22, 133, 197, 1); }
.My-Color-Theme-3-rgba { color: rgba(42, 191, 240, 1); }
.My-Color-Theme-4-rgba { color: rgba(85, 138, 163, 1); }
.My-Color-Theme-5-rgba { color: rgba(21, 69, 133, 1); }
.My-Color-Theme-6-rgba { color: rgba(255, 255, 255, 1); }

References:
I used the following website to get help in understanding how to make the gradient better:
https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient
