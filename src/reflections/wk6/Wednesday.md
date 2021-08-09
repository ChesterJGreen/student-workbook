8/4/2021
# Daily Journal

The morning started with a challenge on how to compare 2 arrays and create a new array showing the difference between the 2. That was interesting because it seemed like we would need 2 for loops running to get the answer, but ended up that we needed 1 for loop and then we could use the find method on the other array. The lecture for the day was spent building out greg's list in vue with just the car section rendered. We spent the rest of the afternoon building out the jobs and houses from the front end side of the server. Here is  a link to my github repository - [GregsList](https://github.com/ChesterJGreen/late-summer21-gregslist-vue)

---
Read Frontend Frameworks with Vue3 > Understanding VueJs Lifecycle Hooks and answer the following questions

---
1. What are lifecycle hooks? What are lifecycle hooks used for?
- Lifecycle hooks are a window into how the library you're using works behind-the-scenes. Lifecycle hooks allow you to know when your component is created, added to the DOM, updated, or destroyed.
2. How have you utilized lifecycle hooks in your afternoon projects?
- We have used the setup(), and onMounted() lifecycle hooks. to show changes that are made in the DOM
3. What are mounting hooks? When might you use them?
- They allow you to access your component immediately before and after the first render. You might use them when you need to access or modify the DOM of your component immediately before or after the initial render. 