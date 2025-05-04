# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

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
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Lexend+Deca:wght@100..900&display=swap');
</style>
font-family: "Inter", sans-serif;
font-family: "Lexend Deca", sans-serif;

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700
  font-normal, font-bold

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400
  font-normal

@theme {
    --color-dark-blue:   hsl(233, 47%, 7%); /* (main background) */
    --color-faded-blue:  hsl(244, 38%, 16%); /* (card background) */
    --color-soft-violet: hsl(277, 64%, 61%); /* (accent) */
    --color-white-00: hsl(0, 0%, 100%);        /* (main heading, stats) */
    --color-white-75: hsla(0, 0%, 100%, 0.75); /* (main paragraph) */
    --color-white-60: hsla(0, 0%, 100%, 0.6);  /* (stat headings) */

    --font-inter:  "Inter", sans-serif;       /* main heading, main paragraph, stats */
    --font-lexend: "Lexend Deca", sans-serif; /* stat headings */

    --text-main: 15px; /* main paragraph */
}

text-xs /* stat headings */
text-2xl /* stats */
text-4xl /*header */

rounded-2 /* border-radius: 8px */
w-lg /* 512px  (photo)   */
w-xl /* 576px  (content) */
