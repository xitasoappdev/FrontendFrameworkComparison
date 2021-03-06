# FrontendFrameworkComparison Basic HTML Structure
Very simple HTML base layout with requirements to test different Frontend Frameworks (Angular, React, etc.)
The idea is that you use the static HTML files and make them dynamic with your preferred Frontend Framwork. The requirements let you test create, read, update and delete usecases.

To simulate a REST API you can use JSON-Server (https://github.com/typicode/json-server).

Defined requirements:
__________________________________________________________________________________________________


- All recipes are shown on startpage (with pagination, 10 per page)

- Recipes can be sorted by Date, Alphabetical order and Rating

- Recipes can be searched (Title, Author, Short description, Ingredients, Description) 

- New recipes can be created via the create form

- The form data gets validated before submitting (Title unique & required, Author required, Short description max 150 chars, Ingredients at least one, Description max 500 chars)

- Recipes can be rated via the rating button

- Recipes can be edited

- Recipes can be deleted (with their comments)

- Comments can be added to an existing recipe
