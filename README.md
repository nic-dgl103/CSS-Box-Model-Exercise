# CSS Box Model Exercise
This exercise was designed to help you understand this week's content. It is not graded.

1. Clone this repository onto your local computer.

2. In VS Code, add the following styles to the article element with the class name card-one:
   * Make the image round by using the border-radius property.
   * Give the card a background colour of `hsl(0, 0%, 100%)`.
   * Make the width of the card 20% of its parent element's width.
   * Give the card a 50px margin on all four sides so that it isn't so close to the browser window's edges.
   * Give the card 30px of padding on all four sides so that the content doesn't touch the edges of the card.
   * Round the corners of the card by a 5px radius.
   * Give the card a top border that is 3px thick, solid in style and of the color `hsl(180, 62%, 55%)`.
   * Give the card a shadow. Go to https://getcssscan.com/css-box-shadow-examples to find a pleasing shadow.

3. Add the following styles to the article element with the class name card-two:
   * Give the card a background colour of `hsl(234, 12%, 34%);`.
   * Give the card the same width, margin and padding as card one.
   * Round the corners of the card by a 30px radius.
   * Make the card's h2 and p elements white;
   * Play with background properties:
      * Using the background CSS property, add a gradient to the card's background. Go to https://cssgradient.io/ to create a gradient that you like.
      * Give the card a background image that uses the elephant image available in the images folder.
      * Try out different background-size values until you find one that you like: https://developer.mozilla.org/en-US/docs/Web/CSS/background-size.
      * Add your gradient to the background image by copying and pasting it in front of the image url. <br/>
      Ex: `background-image: linear-gradient(356deg, rgba(34,193,195,1) 0%, rgba(253,187,45,0.022846638655462215) 100%), url('images/elephants.jpeg');`
   * Just for fun, see what happens when you apply `filter: grayscale(100%);` to the card so that the whole card becomes grayscale.

