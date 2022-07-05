-- Project: Design a store database
/*This is how you write a comment in SQL*/
/*Create TABLE - creates the database*/
/*entry afterwqard - name of database*/
/*(colum_name, column_type, primary_key true or false))*/

-- Set up table
CREATE TABLE ikea (
  ikea_id INTEGER PRIMARY KEY,
  category TEXT,
  product TEXT,
  cost INTEGER,
  stock INTEGER,
  rating FLOAT
);

-- Manipulation/edirs of table
INSERT INTO ikea VALUES(1, 'chair', 'Furniture', 100, 2, 4.5);
INSERT INTO ikea VALUES(2, 'bed', 'Furniture', 1000, 10, 3);
INSERT INTO ikea VALUES(3, 'table', 'Furniture', 35, 2, 5);
INSERT INTO ikea VALUES(4, 'chair', 'Furniture', 100, 2, 2.7);
INSERT INTO ikea VALUES(5, 'bedsheet', 'decor', 100, 56, 4.8);

-- showing results
SELECT * FROM ikea ORDER BY rating DESC;
SELECT AVG(rating) FROM ikea
