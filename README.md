Somethings to keep in mind :-
Make sure MongoDB is installed locally or you have a connection string from MongoDB Atlas.
make sure to use app.use(express.json());   // for parsing JSON request bodies
make sure that Your request body must be valid JSON (no extra commas, no hidden spaces, no smart quotes).
So the main things are:
Mongo running:-
.env correct
express.json() middleware used
Valid JSON bodies
Routes wired properly
