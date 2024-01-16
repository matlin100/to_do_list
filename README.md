create a postgresSQL DB name permalist in postgres
and config the password int password 

const db = new pg.Client({
  user: "postgres",
  host: "localhost",
  database: "permalist",
  password: "********************************",
  port: 5432,
});
db.connect();



  title VARCHAR(100) NOT NULL
then create items table with id PRIMARY KEY and  
CREATE TABLE items (
  id SERIAL PRIMARY KEY,
  title VARCHAR(100) NOT NULL
);


run npm i 

and mode index.js 


enjoy
