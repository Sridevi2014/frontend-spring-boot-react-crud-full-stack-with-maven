* create React app

* To be able to enhance the React Application to consume the REST API, we would need to

* Create an Application Component - to represent the structure of the complete application and include it in App.jsx - InstructorApp.jsx
* Add the frameworks need to call the REST API - axios, display a form - formik and support routing - react-router-dom
* Create a view component for showing a list of course details and include it in the Application Component - ListCoursesComponent.jsx
* Invoking Retrieve Courses REST API from React Component - To enable this we will create a service to call the REST API using the axios framework - CourseDataService.js. ListCoursesComponent.jsx will make use of CourseDataService.js

*Invoking Retrieve Courses REST API from React Component
We had created the REST API for retrieving the list of courses earlier. To call the REST API we would need to use a framework called axios.
Axios is a Promise based HTTP client for the browser and node.js

Axios is a frontend framework that helps you make

REST API calls with different request methods including GET, POST, PUT, DELETE etc
Intercept Front end REST API calls and add headers and request content

*NPM install
*npm add axios
*npm add react-router-dom
*npm add formik
*NPM start
