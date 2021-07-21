7/19/2021
# Daily Journal

In lecture today we learned about APIs. Mark went to a website that had all sorts of information on characters of StarWars. It was all about being an API and StarWars. I really enjoyed manipulating that data. So, we learned how to fetch data from an API and then convert it into an object that we would want to use and then displaying that information on the screen. In the afternoon we had a challenge to do the same thing but with a trivia API. Things went well for the most part. I got to a point where I was making the data show up in the view much nicer but it ended up breaking. I'm not even sure how to fix it. I guess I may be starting back over if I have to. Here is a link to [my Trivia Site](https://chesterjgreen.github.io/triviaDB/)

---
Read Asynchronous Code > Callback Hell and answer the following questions
1. What are some of the signs and causes of Callback Hell?
-  a pyramid shape to the code and a lot of }) by themselves at the end of the code. 
2. What does the asynchronous mean and how are callbacks involved?
- aka 'async' just means 'takes some time' or 'happens in the future, not right now'. Usually callbacks are only used when doing I/O, e.g. downloading things, reading files, talking to databases, etc.
3. Summarize the 3 ways to avoid / fix Callback Hell
- keep your code shallow, modularize, and handle every single error