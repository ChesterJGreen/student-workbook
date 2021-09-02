9/1/2021
Daily Journal

Today we learned about mysql. We went to scalegrid.io and created a mysql database. We reinforced our knowledge of the api calls in the controller, and services. However, we also learned to place another step of establishing those api calls into a repository file that would give the specific language that mysql speaks. We setup an database of artists. In the afternoon, we setup a database of knights and castles. Here is the link to my [Kingdom](https://github.com/ChesterJGreen/kingdom).

---
Questions:
---
Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

1. In a SQL table, what is the difference between information in a row and information in a column?
- Information on a row contains an entire object, information on a column contains a specific property
2. Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
- 
CREATE TABLE characters(
  id int NOT NULL,
  name VARCHAR(255), NOT NULL,
  age VARCHAR(255),
  description VARCHAR(255)
);
3. What is the difference between the following statements:

DELETE FROM table_name;

DROP TABLE table_name;

- the 1st will delete all data stored inside the table, the 2nd will delete the entire table including all the data. 