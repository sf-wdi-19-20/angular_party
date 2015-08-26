# Angular Party

Your goal is to implement an AngularJS dance party! The inspiration for this app is <a href="http://gifdanceparty.giphy.com/" target="_blank">GIF Dance Party!</a>. But basically, we'll use the giphy "stickers" api to let users stick moving images onto the page, and we'll add sound and a background image. 

This app focuses on:

* using external APIs
* creating a custom Angular Directive (or using an outside directive)
* caching app data 

## Set Up

* This will be a single page app with one view (no routing necessary).
* You'll need an `index.html` and an `app.js` to get started. Remember to define your app in `app.js` and include your app and controllers in your `index.html` (using `ng-app` and `ng-controller`).  You may use a separate `controllers.js` file if you prefer, or keep your controller(s) in `app.js`.  

## App User Stories

* A user should be able to click a button to add a sticker (from giphy) to the page. 
  * The user should be able to enter a search term or tag into an input field on the page and submit the search. 
  * When the user submits the search, the app should show the user giphy stickers related to their search. Those stickers might be from a new API call, or from a cached (saved) API call. (Start with a new API call every time; it's easier!)
  * The user should be able to see at least three of the dancing stickers, and choose which one they'd like to add.

* A user should be able to drag stickers around over the background.  

* A user should be able to enter the URL for a background image. 

## Bonus

* To help indicate the number of remaining guesses, draw the hangman (or the representation of your choosing) on an <a href="http://www.html5canvastutorials.com/tutorials/html5-canvas-line-color">HTML5 Canvas element</a>.
* Allow the user to enter hints when they create the word, and let the user playing the game see these hints if they choose.
* Find a dictionary API and use it to determine if the word entered at the start of the game is valid.
