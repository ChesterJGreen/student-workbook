9/7/2021

Daily Journal

Today we went over the project from the weekend - Bloggr. Since it was a no point checkpoint we ended up reviewing or recreating the original material for the project. Meaning we didn't really touch the comments in class since they are very similar to the blogs. However, after setting up the blogs, accounts, profiles... Mark ended up going over many to many relationships by adding favorites to the project. He showed us how to setup the many to many in the sql tables, and created its own controller, service, repo. He also showed the slight difference in syntax when using the repo to make changes or add to the sql tables. It was good to see that many to many isn't horribly complicated, but it probably helps that he has some good drawings to show the how the tables access each other and display themselves. This afternoon we worked on the Contractors project. Here is a link to the github for it, [Contractors](https://github.com/ChesterJGreen/contracted)

---

Questions:
---

Read Dotnet WebAPI's > Relationships, and answer the following questions
1. What is the difference between a primary key and a foreign key
- Primary keys are pieces of unique information that are used to identify records on a table. Primary key values must be unique, and they may not contain Null values.
- Foreign keys are used to reference data on another table. It's how we tell other tables where to look if they want to pull up a specific record. 
2. What is an Alias?
- when you save an alternate name for a column in sql so that it doesn't conflict with columns in another table. naming convention.

3. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE appointments (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

- ``
SELECT
a.*,
d.*,
p.*,
d.id AS dId,
p.id as pId
FROM 
apointments a
INNER JOIN doctors d ON d.id = a.dId
INNER JOIN patients p ON p.id = a.pid;``
