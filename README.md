# Darren-Watanabe-Portfolio

## Technology Used

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp) | 
| CSS     | [https://www.w3schools.com/css/default.asp](https://www.w3schools.com/css/default.asp)      |   
| Git | [https://www.w3schools.com/git/default.asp?remote=github](https://www.w3schools.com/git/default.asp?remote=github)     |

## Table of Contents

1. [Description](#description)
2. [Code Refactor Example](#code-refactor-example)
3. [Learning Points](#learning-points)
4. [Author Info](#author-info)

## Description 

[Visit the Deployed Site](https://darrenkwatanabe.github.io/Darren-Watanabe-Portfolio/)

In this project, we were assigned to create our professional portfolio to showcase our work, as well providing some background information about us with our contact information. 
While writing out the code for this project, we were to display our knowledge of the material we've learned so far:

1. Utilizing semantic elements in the HTML and CSS to make our code more organized and accesible
2. Incorporating id classes to link keywords to a desired part of the webpage
3. Utilizing the flexbox grid as a way to display content on a page
4. Adding media queries to allow the webpage to adapt as the screen size changes

This project helps us for our future in showcasing our work in hopes of getting hired. We can continue to add any desired projects we would like to display to only help improve the appearance of my portfolio. 

## Code Refactor Example

```html
    <div class="grid-container">
        <section class ="card1"> 
        <section id="gallery"></section>
            <a href="https://darrenkwatanabe.github.io/marketing-refactor/">Marketing Refactor</a>
            <p>In this project, I refactored the HTML and CSS codes while utilizing semantic elements <br>
            to make the file more accessible.
            </p>
            <img src="./assets/images/social-media-marketing.jpg" alt="Marketing Refactor">
        </section>
```

In this example, I making a flexbox grid and declared that this class will be the "grid-container" with each box having their own respective class. In this case, this is "card1". I've also given this section an id, so I can link this part of the page with the id "gallery". I've linked the title of this card "Marketing Refactor" to the deployed webpage and have also added an image preview below. Then we can look at the CSS to see how the page will be displayed.

```css
.grid-container a {
    display: block;
    font-size: 25px;
}

.grid-container .card1  {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    width: 50%;
    border: 3px solid greenyellow;
    padding: 30px;
    font-size: 15px;
    text-align: center;
    flex-grow: 4;
}

.grid-container .card1 img {
    display: block;
    margin: 10px auto;
    max-width: 500px;
}
```

In the CSS, I've set the Marketing Refactor title with a block display and a font-size of 25px. I've given card1 and flex display, flex wrap, and flex-direction set to column. Just like the rest of the cards, I've given this card1 a border of 3px with a solid greenyellow color and a padding of 30px. The font-size within this card is 15px and aligned in the center. Lastly, I edited the image display. I've given the image a block display with a margin of 10px and a max-width of 500px.

## Learning Points

From this project, I've learned how to incorporate the material we've picked up in the course. I've learned how to use semantic elements, incorporate the flexbox grid as a way to display information, and have gotten more comfortable with developing a webpage. In such a short time, I've gained a lot of confidence in my ability and have picked up the material a lot faster than I had anticipated. I'm sure there are ways to simplify my code with numerous techniques that I don't know of yet, but I can't wait to learn these methods. 

## Author Info

Darren Watanabe
UC Berkeley Coding Bootcamp Student
Email: watanabedarren@yahoo.com
[Github](https://github.com/Darrenkwatanabe)
[LinkedIn](https://www.linkedin.com/in/darren-watanabe-982526253/)
