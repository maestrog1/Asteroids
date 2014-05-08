Asteroids
==============

The classic Asteroids game written in JavaScript as a learning exercise.


See it Live: http://www.maestrographics.net/Asteroids

![Asteroids Screenshot](http://www.maestrographics.net/Asteroids/screenshot.jpg "Asteroids Screenshot")

Intro
-----

What's there to say? It's Asteroids in JavaScript! Create the game, give it a div to draw to, tell it when the keyboard is mashed and that's all you need to 
add Asteroids to a website.

Adding Asteroids to a Web Page
-----------------------------------

First, drop the game.js file into the website.

Now add a canvas to the page.

````HTML
<canvas id="gameCanvas"></canvas>
````

Finally, add the Space Invaders game code. You create the game, 
intialize it with the canvas, start it and make sure you tell
it when a key is pressed or released. That's it!

````HTML
<script>
//	Setup the canvas.
var canvas = document.getElementById("gameCanvas");
canvas.width = 600;
canvas.height = 500;

</script>
````


