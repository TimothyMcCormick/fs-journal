# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
It handles the projects dependencies and it can also contain other data such as a project description, the version of the project in a particular distribution, license information, even configuration data.
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
At the root directory. It has to be at the root or base level so that the packages install fully over the entire project.
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run dev
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
Connection Strings
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
By logging into the heroku dashboard or using the heroku cli
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
Using GitHub you can:

1. Clone the repository from GitHub to your local device
2. Make your changes, and commit them to GitHub
3. Login to your Heroku account:. Follow the directions on the screen to login to your account through the browser
4. Set remote for your project
5. Push to Heroku master to deploy updates
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
To achieve code isolation
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
You should do code review before and after code is committed
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
Merge
```