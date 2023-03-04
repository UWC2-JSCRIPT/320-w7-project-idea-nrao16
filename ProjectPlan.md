
## Project Plan

**_My Favorite Books and Movies_**

My family likes to read and watch movies. I always have trouble remembering a best seller that I wanted to read or watching a well reviewed movie. 
The goal of this web app is to provide a way for someone to save a favorite list of movies and books. 

This initial version of the project will get best seller books and movie reviews from the New York Times for the user to save to a firebase db. 

*Additional nice to have options if I have time - 
It will have user authentication and also alllow a user to add their own books and movies to their favorites.* 

Eventually my hope to expand this project to allow groups of people to create shared lists of books, movies and shows, so that families and friends can share their favorites.

* Attached a concept diagram created in Miro. The icons, images, card designs are concepts, the actual look and feel may be a slightly different.

* List of dependencies 
    * Setup `create-react-app` scaffold
    * react-router-dom 
      > `npm i react-router-dom`
    * MUI styled components
      > `npm install @mui/icons-material @mui/material @emotion/styled @emotion/react.`
    * Google Firebase for db
      > `npm install firebase`
    * Deploy on GitHub Pages or create account on Heroku for deployment
    * Set up API key for calling the New York Times Books API for bestseller books and Movie Reviews API
    * 
* List of tasks
    * References -
      * Refer to Vacation Rentals assignment for components and shopping cart design and state management.
      * Refer to assignment for Star Wars router for compoents and browser router/loader concepts.
      * Refer to the firebase class exercices to set up firebase functionality.
    * Setup `create-react-app` scaffold
    * Setup .env file with API keys and any other common URL variables
    * Create Pages file skeletons for the home page, Books page, Movies page, Error page. 
    * Connect App.js to home page.
    * Create initial routes in index.js with loaders skeletons.
    * Create App header component
    * Build the Books functionality
      * Create model classe for Book
      * Create component cards to render book - title, image, summary data, icon for adding to favorite and accordian to show book details.
      * Create component card for favorite books list with header, 
      * Create loader to fetch data from Books API in Books page and hook it in the index.js route.
      * Add book and favorite books list components into page.
      * Start adding state callbacks to onclick handlers - 
        * Clicking on favorite icon within book component should trigger disabling the button icon and adding it to favorite list component.
        * Clicking on remove icon within the favorite list component should trigger removing it from the favorite list and enabling the button icon on book display list.
      * Start adding CRUD operations - 
        * Set up favorite books collection on firebase.
        * Create functions to connect, insert and delete books
        * Hook the calls to the onclick handlers.
      * Setup and deploy on Git Hub Pages or Heroku
    * Build the Movies functionality - Follow same steps as building the Books functionality.
    * Cleanup, add README, test full project

* A plan for the next 3 weeks and what you plan to accomplish each week
  
  * Week 1 - 
   
    * Figure out project idea and create project plan. 
    * Create skeleton project with dependencies, check access to New York Times API.

  * Week 2 -
    * Implement Books functionality.
    * Deploy 
    * Build Movie model and database collection.

  * Week 3 - 
    * Implement Movies functionality.
    * Test and deploy.


