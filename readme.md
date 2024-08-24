# project :gabrielle-essence-eau-de-parfum$ 

 ![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)
 
## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#Links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
 
## Overview
The task is to build out the project to the designs inside the `/design` folder. There are both a mobile and a desktop version of the design. 

 All the required assets in the `/images` folder. The assets are already optimized.

There is also a `style-guide.md` file containing the information  need, such as color palette and fonts.

### The challenge
The challenge is to build out this product preview card component and get it looking as close to the design as possible.
 
- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Solution URL: [https://github.com/polidorl/gabrielle-essence-eau-de-parfum-con-CSS-GRID] 

- Live Site URL: [https://polidorl.github.io/gabrielle-essence-eau-de-parfum-con-CSS-GRID/] 
 
 
### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned
 
To see how you can add code snippets, see below:

```html
<p class="main__price">$149.99 
  <span class="main__sold">$169.99</span>
</p>
```

```css
.main{
     
    display: grid;
    align-content: center;
    grid-template-columns: repeat(auto-fit, minmax(300px,1fr));

    animation: fade .8s .6s both ease-in;
}

.main__cta{
    background-color: var(--dark-cyan);
    padding: 1em 0;
    display: grid;
    margin-top: 1.5em;
    text-decoration: none;
    color:#fff;
    border-radius: 8px;
    background-color: var(--dark-cyan);

    grid-auto-flow: column;
    grid-auto-columns: max-content;
    justify-content: center;
    gap: 1em;
    
}
.main__price{
    font-size:1.8rem;
    color:var(--dark-cyan);
    font-family: var(--font-headings);

    display: flex;
    align-items: center;
    gap: 1em;
}
.main__sold{
    font-size: initial;
    font-family: "Montserrat", sans-serif;
    text-decoration: line-through;
    color:var(--dark-grayish-blue);
}
``` 



 ## Author

- Website - [in/lisbeth-emperatriz-polidor-solano-139b70117] 
- email - [polidor.lisbeth4@gmail.com] 
 


