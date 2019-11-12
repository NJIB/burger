## Instructions

Improve the app so that a cat can be deleted.

### Edit the following:
* Add a delete button into the views/partials/cats/cat-block.handlebars file next to each cat.

* The public/assets/js/cats.js file to add a jQuery event handler for the delete button.

* The config/orm.js to include a delete key and function

* The cat model at models/cat.js to include a delete key and function that uses the ORM

* The controllers/catsController.js file to have a /api/cats/:id delete route, to call the delete key of the cat model