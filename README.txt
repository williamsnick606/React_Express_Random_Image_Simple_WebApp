Project Description:

Random Image Single Page React-Express WebApp

. Front-End
    - React + Bootsrap UI Framework (for a little styling)
    - Uses "fetch" method to grab random images from my Express server
      at the API endpoint "/api/random-image" and display them.

. Backend
    - Express Backend
    - The backend grabs a random image from the "images/" folder on
      the backend and serve them up as an API for the React front-end.

Backend <-> Front-End Dependencies
. NONE!
. *You can swap out either the backend or frontend with a 
   different one if you wanted to. 
    - * The API sending a random image is the only thing connecting these.



Directory Structure:

- Random_Image_WebApp/
    -react-node-app/
        - package.json
        - node_modules/
        - server/
            - images/
            - index.js
    -client
        - package.json
        - node_modules/
        - public/ (ignore this!)
        - src
            - index.js
            - App.js
            - RandomImage.js
            -  (other files that don't matter)


How to run:

1. Run server
Go into react-node-app/
. Run "npm start"

2. Run the React Front-End
Go into client/
. Run "npm start"


If You Wanna Edit the Front-End
1. Edit "RandomImage.js"
