# Jobby App

## About
Jobby App is a basic clone of job portals like Glassdoor. It allows users to login and view a list of available jobs by searching with a job title and filtering them based on salary range and employment type. Authentication is mandatory to access the list of available jobs. Upon successful login, the user is redirected to the home page and can navigate to the jobs page.

## Functionalities
- User authentication is required to access the app.
- Users can search for available jobs by entering a job title.
- Jobs can be filtered based on salary range and employment type.
- Clicking on a job provides more detailed information about that specific job.

## Technical Details
- The app is a single-page, responsive web application deployed on Heroku.
- It is implemented using React components, lists, hooks, and event handlers.
- User login is persisted by storing the JWT token in a client-side storage mechanism, such as cookies.
- Protected routes ensure that only authenticated users can access the app and make authorized HTTP API calls.
- Loaders are added to indicate when network calls are in progress.
- Logging out removes the JWT token from the cookie and navigates the user back to the login page.

## Key Learnings
- Routing in a React app using `react-router-dom`.
- Handling JWT authentication in the frontend.
- Usage of local storage and cookies.
- Implementing media queries for responsiveness.
- Adding spinners to indicate network call progress.
- Sending HTTP requests to fetch backend data using the Fetch API in JavaScript.
- Adding React Icons for an attractive UI.
- Dynamically updating query parameters of the API based on user-selected filters.

## Technologies Used
- React.js
- CSS
- react-router-dom
- js-cookies
- CSS Media Queries

## App Demo
Check out the [Jobby App](https://example.com) to see the app in action.

## Credentials
- Username: rahul
- Password: rahul@2021
