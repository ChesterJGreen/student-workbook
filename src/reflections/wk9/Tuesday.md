Daily Journal
8/24/2021

Today I noticed some eye issues that have began over the weekend and haven't seemed to go away. So, I ended up leaving half an hour early to go to a dr. appointment where he gave me a referral to see the eye doctor the next morning. Other than that, this has been an awesome group to work with. John seems to be the most opinionated, but is still fairly easy to get along with. Working on the front end is going great though. We got our create and get functions squared away. 

---
Questions
---
---
Read Working In a Professional Environment > Github Actions and How to Use Them and answer the following questions
1. What is a Github action and how do they work?
- a shared and demoed solution to help offload some of the toolings of GitHub. It works by creating one or more text files in your repository - a workflow. That can execute certain actions when you load the repository
2. What benefits do Github actions provide?
- you can have templates set up. each yaml file can respond to a specific event and have multiple jobs to perform. 
What types of trigger actions can a workflow use? What do they do?
- workflow, scheduled, webhooks, external
webhook - when someone performs an action on GitHub you can have an event triggered by an external process outside of GitHub - a repository dispatch event. workflow - events manage the triggering of actions. like a push, pull request, or a fork.