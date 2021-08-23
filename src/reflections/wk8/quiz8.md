# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
This file is used to give information to npm that allows it to identify the project as well as handle the project's dependencies. It can also contain other metadata such as a project description, the version of the project in a particular distribution, license information, even configuration data - all of which can be vital to both npm and to the end users of the package
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
``` 
located at the root directory of a Node.js project. otherwise node won't be able to find the information it needs
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env files
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
MORE -> log items OR you can go to the cli and type  heroku logs
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
make sure it is targeting your production branch and npm run build again on that branch to update the herokuapp
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It allows you to double and triple check code before it reaches production at different levels
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
before you submit your work at the production phase
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging a pull request
```
