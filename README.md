# Movie Database 
This is a Movie Database which stores my interesting movie names with the names of lead actor, actress, year of release and the director name

# Contents of the Code

## 1. Connected to the SQLite Databse
The private function called connect() which will connect to the database if it exists or will create a databse named movies.

## 2. Creating a new table (Movies)
The function called createTable() which will create a table named Movies to the databse movies.db.

## 3. Inserting data into Movies table
The function called insert() which will accept the Movie_Id, Movie_Name , Lead Actor ,Actress ,Year and Director Name.

## 4 Querying data from Movies table
The function called selectAll() will query all rows from the Movies table, selectparam() will query the movie name of the given actor in which he has acted.
