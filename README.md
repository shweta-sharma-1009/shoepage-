git hub repo  link - https://github.com/shweta-sharma-1009/shoepage-

![Screenshot (192)](https://github.com/shweta-sharma-1009/shoepage-/assets/128416925/8a924b47-19bf-4360-95bc-8fcb8dfcefca)
![Screenshot (193)](https://github.com/shweta-sharma-1009/shoepage-/assets/128416925/86aa6216-ba09-4b50-9c26-01ccd0ded32a)
![Screenshot (194)](https://github.com/shweta-sharma-1009/shoepage-/assets/128416925/8b85f7b2-fa41-480c-a16e-9b91b6c5557c)

HTML -
1. Created shoe page by using HTML web page and CSS and Linked both of them. (styleshee)
<body>: This is like the main body of your webpage.
Created <div class="container">: It's like the main section.(shoe details).
<div class="shoe" style=" background: This is a container that represents a shoe. The "style" attribute adds a gradient background color that makes it look cool. It's like putting your shoe on a colorful platform.
<div class="des">: This is another box within the shoe container. described shoe.
<h1>Shoe-1</h1>: This is a big title that says "Shoe-1". name of shoe.
<p>: This is for paragraphs of text. Two paragraphs explaining the features of the shoe.
<img class="shoe-1" src="URL" alt="shoe1">: This is an image of your shoe. The "class" attribute is like a label, used for styling. The "src" attribute put the web address (URL) of the image. The "alt" attribute provides a text description of the image in case it can't be shown.
</div>: This closes the "des" container.
</div>: This closes the "shoe" container.
</div>: This closes the "container" container.
</body>: This closes the main body of your webpage.
</html>: This closes the HTML document.
In simple terms,  code creates a webpage displaying a shoe. Inside the "container," have a "shoe" displayed with a gradient background. Inside the shoe, there's a description box ("des") with a title and two paragraphs of text explaining the shoe's features. There's also an image of the shoe. This creates a nice layout to showcase your shoe on a web page.

CSS -
*: This targets all elements on the webpage.
margin: 0; and padding: 0;: This makes sure there's no extra space around elements, giving a clean look.

box-sizing: border-box;: This helps in calculating the width and height of elements in a better way, including their padding and border.

body: This targets the entire webpage's background.

background-color: lightgrey;: This sets the background color of the whole page to a light gray shade.
.container: This targets an element with the class "container".

width: 100%; and height: 100vh;: This makes the container fill up the entire width of the screen and have a height equal to the viewport height.

position: relative;: This positions the container based on its normal place.

overflow: hidden;: This hides anything that goes beyond the container's boundaries.

.container::after: This targets a pseudo-element after the "container".

This block creates a slanted, gradient background that serves as a visual effect behind the main content.
.shoe: This targets an element with the class "shoe".

width: 85%; and height: 75%;: These rules define the size of the shoe container.

padding: 2%;: This adds some space inside the shoe container.

margin: auto; and margin-top: 7.5%;: These rules center the shoe container horizontally and add some space from the top.

.des: This targets an element with the class "des" (description).

max-width: 40%;: This sets the maximum width of the description container.

color: white;: This makes the text inside white, for contrast with the background.

.des > h1 and .des > p: These target the h1 and p elements within the description container.

font-size: xx-large; and font-size: large;: These rules control the sizes of the heading and paragraphs.

margin-bottom: 30px; and margin-bottom: 50px;: These create space underneath the heading and paragraphs.

line-height: 20px;: This sets the spacing between lines of text.

.shoe-1: This targets an element with the class "shoe-1".

This part positions and defines the size of the shoe image.
.shoe-1:hover: This targets the .shoe-1 element when it's being hovered over.

This part changes the position and size of the shoe image to create an effect when the mouse is over it.
In simpler terms, your CSS code is like a set of instructions for making your webpage look and feel a certain way. It controls colors, sizes, positions, and shadows to create a visually appealing design. It's similar to adjusting the colors and arrangement of objects in a picture to make it look great.
