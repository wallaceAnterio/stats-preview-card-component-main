# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very dark blue (main background): hsl(233, 47%, 7%)
- Dark desaturated blue (card background): hsl(244, 38%, 16%)
- Soft violet (accent): hsl(277, 64%, 61%)

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%)
- Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)
- Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400


===========================================

:root {
   --Very-dark-blue-background-main: hsl(233, 47%, 7%);
   --Dark-desaturated-blue-card-background: hsl(244, 38%, 16%);
   --Soft-violet: hsl(277, 64%, 61%);
   --White: hsl(0, 0%, 100%);
   --Slightly-transparent-white-main-paragraph: hsla(0, 0%, 100%, 0.75);
   --Slightly-transparent-white: hsla(0, 0%, 100%, 0.6);
}

body {
   font-family: "Lexend Deca", sans-serif;
   background-color: var(--Very-dark-blue-background-main);
}

p {
   font-size: 15px;
   line-height: 1.6;
}

.container {
   background-color: var(--Dark-desaturated-blue-card-background);
   margin: 50px 20px;
   padding: 0 0 20px;
   border-radius: 10px;
}
.container .card-content .picture{
   background: url("/images/image-header-desktop.jpg");
}

/* .container .card-content picture img {
   border-radius: 10px 10px 0 0;
} */
img {
   max-width: 100%;
}
