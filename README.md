# Angular Party

Your goal is to implement an AngularJS dance party! The inspiration for this app is <a href="http://gifdanceparty.giphy.com/" target="_blank">GIF Dance Party!</a>. But basically, we'll use the giphy "stickers" api to let users stick moving images onto the page, and we'll add sound and a background image. 

This app focuses on:

* using external APIs
* creating a custom Angular Directive (or using an outside directive)
* stretch: caching app data 

## Suggested User Stories


1. A user should be able to add a sticker (from giphy) to the page.   
1. The user should be able to enter a search term or tag to determine what kind of sticker they get. 
1. Stretch: The user should be able to see at least three stickers from giphy and choose which one they'd like to add.  

1. A user should be able to drag stickers around over the background. 

1. A user should be able select one of a list of 2-3 background images. 
1. Stretch: The user should be able to enter the URL for whatever background image they want!

1. The user should be able to toggle fun audio on or off!  
1. Stretch: The user should be able to select from a few preloaded audio tracks.
1. Super stretch: The user should be able to enter a search term to hear different audio!


## Suggested Approach

Here are some tips you may find useful as you take on this project!

### Decide user stories and draw wireframes

If you're following the user stories above, you probably only need one page. Draw out what that page will look like, including all of the controls that will be available to the user.   You could even  make a simple paper prototype to experiment with how the user can interact with stickers, but don't spend too long on this step!

<img src="http://www.sabazaidi.com/img/ethny-prototype.png" width="50%">  
_image from Saba Zaidi at http://www.sabazaidi.com/ethny.php_


### Explore the <a href="https://github.com/Giphy/GiphyAPI#giphy-sticker-api" target="_blank">giphy sticker api</a>

1. Use your browser or Postman to make some test calls to the sticker api. You should figure out the structure of the url to send and explore the structure of the data you get back. 
1. Decide what parts of the data you'll want to use to fill out your wireframe. Hint: You'll definitely want something from the `images` section of each gif! :D

<!--### Basic Project Setup-->

<!--1. Create a project directory and tie it to a github repo before you start to code!-->
<!--1. You'll need an `index.html` and an `app.js` to get started. -->
<!--1. Use `script` tags to include AngularJS and your `app.js` in `index.html`. -->
<!--1. Define your app in `app.js` and include it in your `index.html` using `ng-app="yourAppName"`.-->
<!--1. Start up `http-server` and go to the page in your browser. Check back frequently to see if there are errors and/or confirm that the page is still working!-->

<!--### First Controller-->

<!--1. You may use a separate `controllers.js` file if you prefer, or keep your controller(s) in `app.js`. -->
<!--1. -->

### Dragging

1. Include an external `ngDraggable` in your project.  The <a href="https://docs.angularjs.org/guide/directive" target="_blank">Angular Directives guide</a> has a simple draggable implementation (CMD+F draggable), or you could search for a more full-featured one.  Check out a demo of any draggable you consider to make sure it behaves the way you want! 
1. If the draggable you find suggests installing with bower, you can either install bower, or copy the source code directly into your project. If you copy the source code, add a comment that gives attribution to the creator and a link to their site!
1. Remember to add a dependency to your `ngDraggable` module in your application with `angular.module('yourAppName', ['ngDraggable']);`.  
1. Read the module's docs (or check out the demo code) to see how to incorporate it into your html.


