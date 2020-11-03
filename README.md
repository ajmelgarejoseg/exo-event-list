
![Logo](logo.png) **ExoLever Boilerplate Angular Elements**  

# Installation

1. `git clone https://github.com/ajmelgarejoseg/exo-event-list.git`
2. `npm install`
3. `npm run start` to local or `npm run build:elements` to create the custom elements

# Create custom element

1. In the app module constructor, we are creating the customElement. You can modify the selector and the component.
2. Modify index.html to load your component.
3. npm run build:elements, this step will do the ng build and executo the build-script.js file to create an element folder with your custom-element.

# Sample Usage

1. Create an index.html file
2. ```html
   <script>
     <exo-event-list domain="https://platform.openexo.com" ></exo-event-list>  
   </script>
   
   <script src="https://platform.openexo.com/custom-elements/exo-event-list/exo-event-list.js"></script>
   <link rel="stylesheet" href="https://platform.openexo.com/custom-elements/exo-event-list/styles.css">
   <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
   <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500" rel="stylesheet">
   ```
3. To set the widget inside a wordpress/squarespace project page you need to insert an inject code section in the page you want the widget,
for instance https://www.ostraining.com/blog/wordpress/custom-js/
  

# Running unit test

1. npm run test via karma.js

# Running e2e test

1. npm run e2e

# Running lint 

1. npm run lint

