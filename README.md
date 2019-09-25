https://dinhdothuy.github.io/LostandFoundPets/

## Notes:

-User can go to the login page and either sign in or create a new account (index.html -> route localhost:8080/).

-From the they go to their profile (profile.html -> route localhost:8080/profile)

-From the profile page they can search by pet type or add a new pet.

It is all functioning through the routes useing the files in the layout branch.

working on the post and getting an error startitng the server - var Pet = sequelize.define("pet", is not a function - will talk with a ta in the morning.


registerPet.html => takes the user input

registerPet.js => captures user input and stores it for the api

apiRoutes.js => uses the pets.js in models to convert data types and send to the DB

 







### App Details:

Requirements: 

Use a Node and Express Web Server;

Be backed by a MySQL Database an ORM (not necessarily Sequelize);

Have both GET and POST routes for retrieving and adding new data;

Be deployed using Heroku (with Data);

Utilize at least one new library, package, or technology that we haven’t discussed;

Have a polished frontend / UI;

Have folder structure that meets MVC Paradigm;

Meet good quality coding standards (indentation, scoping, naming).

Must not expose sensitive API key information on the server, see Protecting-API-Keys-In-Node.md
