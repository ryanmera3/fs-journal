# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
Holds the metadata for your application.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
Root level. To allow npm to identify your project and handle dependencies
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm i
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env / env.js
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
$ heroku logs
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
set heroku to git:remote , git push herouku master
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
We used branching on the capstone after we had our MVP reached on the backend so the frontend could work with our current backend and we wouldn't break anything.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Before you merge your branches with master / main or when you finish with your code
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merging
```