# food-gallery

- Food Gallery Application renders the data consumed from the url http://origin-www.tasteofhome.com/feed/msn-slideshows/
- Food Gallery displays information like title,abstract text,image,author on different cards .
- Every card has a gallery button ,which, on click opens a modal to view all the images related to the card.
- The modal displays  different images as a slide
- To navigate through images we have next and prev button and thumbnail images.

To view the application open index.html in a browser.

Project structure

lib
  ____ jquery,jquery ui
src
  ____  FoodGallery.js : Constructs and dynamically renders the cards

  ____  ImageGallery : Constructs and dynamically renders the images

  ____  stubData :json feed from the given url

style
  ____ images : images used in css file
  ____ style.css :styles for the application

index.html :markup and templates for the application

Note: jQuery version used in the application has the following browser support
Chrome: (Current - 1) and Current
Edge: (Current - 1) and Current
Firefox: (Current - 1) and Current
Internet Explorer: 9+
Safari: (Current - 1) and Current
Opera: Current
