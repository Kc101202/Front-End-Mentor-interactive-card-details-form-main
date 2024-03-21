# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Linear gradient (active input border): hsl(249, 99%, 64%) to hsl(278, 94%, 30%)
- Red (input errors): hsl(0, 100%, 66%)

### Neutral

- White: hsl(0, 0%, 100%)
- Light grayish violet: hsl(270, 3%, 87%)
- Dark grayish violet: hsl(279, 6%, 55%)
- Very dark violet: hsl(278, 68%, 11%)

## Typography

### Body Copy

- Font size: 18px

### Font

- Family: [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk)
- Weights: 500



@media screen and (max-width:600px) { 
    /* CSS for mobile devices goes here. */
    .container{
        flex-direction: column;
    }
    .front_card .card_container img,.front_card,.back_card img,.back_card{
        width: 260px;
    }
    .left_section{
        width: 100%;
        min-height: 30vh;
        background-image: url('./images/bg-main-mobile.png');
    }

    .cards{
        flex-direction: column-reverse;
        left: 61%;
        top: 50%;
        gap: 0;
    }
    .back_card{
        transform: translateY(70px);
    }
    .front_card{
        z-index: 100;
        left: 10%;
    }
    .right_section{
        margin-top: 4rem;
        width: 80%;
        height: 20%;
    } 
    .right_section form{
        max-width: 100%;
    }
}