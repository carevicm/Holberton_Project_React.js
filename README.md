# Holberton_Project_React.js
Holberton School React.js Website Project


School Dashboard
A React-based web application that provides a dashboard for school-related functionalities.

Overview
The School Dashboard application provides a user interface for users to interact with various functionalities related to a school system. The application is built using React and Redux, and it leverages the Immutable.js library for state management. The application's styling is achieved using Aphrodite.

Features
User Authentication: Users can log in to access the full dashboard. The application provides a login form where users can enter their email and password.

Notifications: Users receive notifications. The notifications can be filtered based on their type (e.g., URGENT or DEFAULT).

Course List: Once logged in, users can view a list of available courses.

Footer and Header: The application has a consistent footer and header. The footer displays copyright information, while the header displays the school's logo and a welcome message for logged-in users.

Directory Structure
actions: Contains Redux action creators.

reducers: Contains Redux reducers to handle state changes.

selectors: Contains selectors to compute derived data from the Redux store.

components: Contains React components for the application's UI.

schema: Contains normalizers to transform API response data.

utils: Contains utility functions.

Testing
The application uses Enzyme for unit testing React components. Tests are focused on ensuring components render correctly, Redux state is mapped to props correctly, and other functionalities work as expected.

Running Tests
Before running tests, ensure all dependencies are installed:

bash
Copy code
npm install
To run the tests:

bash
Copy code
npm test
Test Details
Styling Tests: Before all tests run, Aphrodite's style injection is suppressed to prevent any issues with inline styles during tests. After all tests have run, the style buffer is cleared and style injection is resumed.

Component Rendering Tests: Tests to ensure components render without crashing and render the expected UI based on given props.

Redux Tests: Tests related to Redux's mapStateToProps function and other Redux functionalities.

Getting Started
Clone the repository:
bash
Copy code
git clone [repository-url]
Navigate to the project directory:
bash
Copy code
cd school-dashboard
Install dependencies:
bash
Copy code
npm install
Start the development server:
bash
Copy code
npm start
The application should now be running on http://localhost:3000.
