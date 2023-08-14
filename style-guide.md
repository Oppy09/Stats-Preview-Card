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

  

  
  figure::after {
    display: block;
    content: '';
    background-color: hsl(277, 64%, 40%);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    opacity: 0.5;
  }
  



* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body {
    display: flex;
    flex-direction: column;
    position: relative;
    /* min-height: 100vh; */
    background-color: hsl(233, 47%, 7%);
    align-items: center;
    justify-content: center;
    font-family: 'Lexend Deca';
}

header {
    color: hsl(0, 0%, 100%);
}

div.container {
    width: 75%;
    background-color: hsl(244, 38%, 16%);
    display: flex;
    margin: 10% auto;
    overflow: hidden;
}
div.illustration {
    min-height: 100%;
}
figure {
    /* /* min-width: max-content; */
    min-height: 100%;
    position: relative; */
}

figure > img {
    max-height: 100%;
}

/* 
} */

div.content {
    /* padding: 3rem; */
    /* text-align: center; */
    max-height: 100%;
    overflow: hidden;
}

div.content > div.text-wrapper {
    width: 80%;
    margin: 2rem auto;
    /* padding: 2rem 0; */
    background-color: aqua;
}

div.details {
    padding: 1rem;
    display: flex;
    flex-direction: column;
    gap: 3rem;
    max-width: 70%;
}

p {
    color: hsla(0, 0%, 100%, 0.75);
    line-height: 2;
}

.stats {
    color: white;
    display: flex;
    gap: 3rem;
}

.stats span {
    display: block;
}

.stats span:nth-child(2) {
    color: gray;
    text-transform: uppercase;
}

.company-stats {
    display: flex;
    flex-direction: column;
    gap: .5rem;
}

.template-stats {
    display: flex;
    flex-direction: column;
    gap: .5rem;
}

.query-stats {
    display: flex;
    flex-direction: column;
    gap: .5rem;    
}







.attribution {
    position: absolute;
    text-align: center;
    bottom: 0;
    width: 100%;
}

/* font-size: 15px; */