# July 15th, 2021
Today's review had a few new items. Things that we needed to learn though. We learned about SASS which its acronym is pretty funny. Syntactically Awesome Style Sheets. It seems like a pretty easy way to edit your bootstrap templates and add in other items without having to use css. We watched Mark construct a pizza ordering website with the options to create and remove the different concoctions. At the end, he showed us how to use local storage to save and load. It seems pretty simple. During partner lab time I was partnered with Tom. I am grateful that I got to work with him. I could see that he really understands HOW this new code works and was able to implement it well. I on the other hand am memorizing  how to use the code and the how seems to come later, usually a few days down the road. Here is a link to our store called [cj's store](https://chesterjgreen.github.io/cjs-store/)



---
Daily Journal
Read Advancing with JS > The Observer Pattern and answer the following questions

---
1. What problems does the Observer Pattern seek to solve?
-  You need a way to update parts of a page in response to certain events, with the data these provide.
2. What are the three mechanisms of the observer pattern?
-  subscribe, unsubscribe, and broadcast
3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
- the template sends the proxy objects through the controller and view. In some areas you are calling for it once like in a subscribe method and some instances you are calling multiple methods like the broadcast method. And if you need to remove a method the unsubscribe method is used. I think its similar to the export and import abilities. 