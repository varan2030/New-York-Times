# NYT React Search

### Overview

In this activity, I created a new React-based rendition of the New York Times Article Search application. This assignment requires to create React components, work with helper/util functions, and utilize the React mounting lifecycle to query and display articles based on user searches. Also use Node, Express and MongoDB so that users can save articles to read later.

### Instructions


1. Create a MongoDB database called `nytreact`.

2. Using mongoose, then create an Article schema and model

3. At a minimum, articles should have each of the following fields:

   * `title` (Title of the stored article from nytimes.com)

   * `date` (publish date and time of the article)

   * `url` (URL of the article on nytimes.com)

   * Creating `documents` in your `articles` collection similar to  
     ```js


5. Create a Node/Express/MongoDB/ReactJS app called `nytreact`. This will be a recreation of the [NYT Articles Search](https://nytarticle-search-fsf.herokuapp.com/). Running this application will:

   * Create a Bootstrap layout. This should be a SPA (Single Page Application) that uses [`react-router-dom`](https://github.com/reactjs/react-router) to navigate, hide and show your React components without changing the route within Express.

     * If you want to try out another CSS framework, feel free to use an alternative to Bootstrap.

   * You'll need several Express routes for your app:

     * `/api/articles` (get) - your components will use this to query MongoDB for all saved articles

     * `/api/articles` (post) - your components will use this to save an article to the database

     * `/api/articles` (delete) - your components will use this to delete a saved article in the database

     * `*` (get) - will load your single HTML page (with ReactJS) in `client/build/index.html`. Make sure you put this after all other GET routes

   * The layout should include at least two React Components for each page `Home` and `Saved`.

     * **Home** - contains all of the JSX to be rendered on the homepage. This component may contain other smaller components or JSX that renders plain HTML elements. This component should be able to query the NYT API for articles. It displays the results from the API search in a rendered list that displays the article title, publication date, and allows the user to visit an article's url or save the article to the MongoDB.

     * **Saved** - Renders articles that are saved in the MongoDB and allows the user to visit the article's url or delete it from the MongoDB. This page may be made up of multiple smaller components or JSX that renders plain HTML elements.

* Link to [Heroku](https://new-york-times-app.herokuapp.com/).

### Home Page

[Image](https://github.com/varan2030/New-York-Times/blob/master/public/images/home.png)


### Search Page


[Image](https://github.com/varan2030/New-York-Times/blob/master/public/images/search.png)
- - -

