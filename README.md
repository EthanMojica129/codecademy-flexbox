
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This is the last flexbox test requested by the codecademy page. They requested the creation of a page for a business using only HTML and CSS, as well as flexbox and grid to make it fully responsive.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Links

- Live Site URL: [Add live site URL here](https://product-preview-card-frontendmentors.vercel.app/)

## My process

I started with  the delimitation of the HTML. Then I started to work the main css component. Then I noticed that I would need some media queries for the smaller screen size. Mostly in relation to the width of the elements. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
-Grid



### What I learned

I feel that I learned a lot regarding to the use of grids and media queries. For example: 

```css
@media only screen and (max-width: 400px){
    #header{
        justify-content: space-around;
    }
    .img-logo{
        max-width: 10rem;
        margin: 2.5rem auto 2.5rem 0.5rem;
    }
    .nav-bar{
        display: flex;
        flex-flow: column;
        justify-content: space-between;
    }
}
@media only screen and (max-width: 600px){
    #header{
        justify-content: space-around;
    }
    .img-logo{
        max-width: 10rem;
        margin: 2.5rem auto 2.5rem 0.5rem;
    }
    .nav-bar{
        justify-content: space-between;
    }
    .Director-wrappers{
        display: flex;
        flex-flow: column;
    }
    #Poster-container{
        display: flex;
        flex-flow: column;
    }
    footer{
        display: flex;
        flex-flow: column;
        align-items: center;
    }
    form{
        display: flex;
        flex-flow: column;
        align-items: center;
    }

}
```   
and on
 ```css
 #Poster-container{
    margin: 4rem auto 8rem;
    display: grid;
    grid-template-columns: 50% 50%;
    grid-template-rows: 1fr 1fr;
    grid-auto-flow: row;
}

.Director-wrappers{
    display: grid;
    grid-template-columns: repeat(3, 33%);
    margin: 2rem auto;
    padding: 2rem 0 2rem;
}

 ```   

I am still learning so I hope I get better. This is currently my first month learning how to code. 
### Continued development

I will continue to learn how to do better media queries and also to better use flexbox and grid layout.

### Useful resources

- [CSS-tricks flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-flexbox-properties) - This helped me to understand a little bit better the organization of my flexbox. 




## Author

- Website - [Ethan Mojica](https://github.com/EthanMojica129)
- Frontend Mentor - [@EthanMojica129](https://www.frontendmentor.io/profile/EthanMojica129)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


## Acknowledgments

To Belen c: she is the reason I'm learning how to code. 
