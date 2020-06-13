# LAB 22 - Class 22

## Project Name - Counter React App - Testing and Development

Code 401 Class 22 ReactTesting and Development

Write unit tests for a counter application, and then deploy the counter application to a variety of places.Your main implementation task for this lab will be to add unit tests for the main components within the starter code. 

**Code Implementation**

`Counter.test.js`: Write robust tests for the Counter component that must test:

* On clicking the - button, the state count variable should be decreased by 1
* On clicking the + button, the state count variable should be increased by 1
* When the state count variable changes, the HTML should update and match that change

`App.test.js`: 
 
* Implement a snapshot test that asserts that the page looks as expected. 

**Design Implementation**

`styles.scss`

* Attempt to style this counter application differently from your Lab 21 counter application
* Utilize at least one variable (for example $backgroundColor)
* Utilize SASS nesting capabilities
* Utilize partials so that your style code can be broken up across multiple files. `@use` these partials in your main `styles.scss/styles.sass` file

**Deployment**

Deploy this counter application to three different services. 
1. Netlify
2. AWS S3
3. AWS Amplify


### Author: Sue Duclos

### Links and Resources

- [Submission Pull Request](https://github.com/sueduclos-401-advanced-javascript/lab-22/pull/1)
- [Netlify Deployment](www.abc.com)
- [AWS S3 Deployment](www.abc.com)
- [AWS Amplify Deployment](www.abc.com)

### Setup

* npm install
* npm install enzyme
* npm install enzyme-adapter-react-16
* npm start

#### How to initialize/run your application

#### Tests

- npm run test

#### UML

- ![UML22](https://github.com/sueduclos-401-advanced-javascript/lab-22/blob/master/assets/lab-22-uml.png)
