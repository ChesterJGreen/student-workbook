# 7/20/2021

We started the day with a coding challenge. It was very interesting to see how long a code block could be for something that seems so simple. The challenge was to take a string and find the most common letter in that word. We started off by creating a dictionary. Then we inserted every letter into that dictionary where each letter was its own index. We then iterated over the object with a for loop. We still had to do another iteration to count all the numbers of each letter appeared in the dictionary. It was super interesting to see done. In our lecture in the morning we learned to add async and await command lines while using the axiom api. Things to note: you have to include the axiom script in the html above the javascript script. You need to create a AxiomServices.js file with a specific code. Then use it in the functions where you are getting information from whatever server you are requesting data from. We ended up updating our GregsList with the cars/houses/and jobs retrieving data from the boiseCodeWorks sandbox. Here is my link to [Greg's List](https://chesterjgreen.github.io/gregslist-mvc/)

---
Read Asynchronous Code > JavaScript Promises and answer the following questions

---
1. What are the three states of a Promise?
- pending, resolved, rejected
2. How do promises seek to resolve the issues of "callback hell"?
- they place a time limit or a limit on the number of processes it will try to process before returning with a failure notification
3. What is the difference between .then() and .catch()?
- then() will execute a line of code after a successful attempt while catch() will execute a line of code after a failed attempt