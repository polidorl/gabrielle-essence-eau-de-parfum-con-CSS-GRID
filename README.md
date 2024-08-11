# project :gabrielle-essence-eau-de-parfum$ 

 ![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)
 
## Table of contents

  - [Overview](#overview)
  - [The challenge](#the-challenge)
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


 

 






## Steps to follow to build a project

 1. Initialize the project as a public repository on [GitHub](https://github.com/).  

2. Configure your repository to publish your code to a web address. 

3. Look through the designs to start planning out how you'll tackle the project. This step is crucial to help you think ahead for CSS classes to create reusable styles.

4. Before adding any styles, structure your content with HTML. Writing the HTML first   tocreating well-structured content.

5. Write   the base styles for the project, including general content styles, such as `font-family` and `font-size`.

6. Start adding styles to the top of the page and work down. Only move on to the next section once completed the area that working on.

 
 


