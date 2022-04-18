Here is a created a web front-end for the RestaurantRater database created in Blue Badge, using the MVC model. We will need models to represent our database tables, views to display data or interact with the app, and controllers to handle the interaction between views and data.

For the objective:
Setting up a new MVC Application; setting up a site called Restaurant Rater that will allow those to enter very basic stuff for rating a Restaurant on a numerical scale.

Specifically, need...

A database connection
Restaurant database model
Rating database model
Restaurant Controller
Rating Controller
Restaurant display models (Index, Detail, Create, Edit and Delete)
Rating display models (Index, Create, and Delete)
Restaurant Views (Index, Detail, Create, Edit and Delete pages)
and Rating Views (Index, Create, and Restaurant pages)

Like the RestaurantRater API, the controllers will have GET and POST endpoints, but each view will require a GET endpoint that will return HTML instead of JSON - this is why MVC controllers are defined separately from API controllers.