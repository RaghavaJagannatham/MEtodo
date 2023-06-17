To-do list app dashboard page

# TO_DO_APP Link <a href="https://64893a2a304b694f5107ea0c--endearing-starburst-77f66d.netlify.app/" target="_blank">Link for the App </a>

# About TO_Do
* Added Guest login for easiest login as for now 
* Login credentials : Mani9@gmail.com, qwert12345
* Dashboard contains 3 parts:
* 1st section contains logo and acts as a sidebar menu
* Can also create subtasks here main tasks to be added here
* main page contains list / cards of tasks in the main task
* Search bar that helps to find a particular task in a pool of tasks
* consists functionalities of 
    * Mark favourite
    * Delete task 
    * mark as complete
    * Date of rememberance
    * Status of the task
    * Sort functionalities according to the requirement
* 3rd section consists of Logout button which moves you to the Login page
* Status bar that shows the level of tasks completed
* A button to delete all the tasks and makes new dashboard

![Screenshot (438)](https://github.com/RaghavaJagannatham/MEtodo/assets/70148332/0d00206a-0fc2-43c5-ae5a-83f2e538f7b8/200x150)
![Screenshot (439)](https://github.com/RaghavaJagannatham/MEtodo/assets/70148332/eaee65e8-1c2d-4bd4-bc88-e0281f3ff23e/200x150)
![Screenshot (440)](https://github.com/RaghavaJagannatham/MEtodo/assets/70148332/73c79ecb-2b56-41ec-a5dd-582efe70eb6f/200x150)

# Code Explanation

Login and Logout
The login functionality is implemented using the useState hook. When users enter their email and password and click the "Login" button, the handleLogin function is called. This function performs validation (replace with your own logic) and sets the isLoggedIn state to true if the credentials are correct. The user's email and password are stored in the browser's local storage using localStorage.setItem.

The logout functionality is implemented in the handleLogout function. It removes the email and password from local storage and sets isLoggedIn to false, logging the user out.

# Dashboard
If the user is logged in (isLoggedIn is true), the dashboard is displayed. You can add your own dashboard content here.

# Styling and Animations
The code includes CSS styles and animations to enhance the user interface. The App.css file contains the styles for the login and dashboard components. Animation styles are added to provide a fade-in effect for the login form elements and a pulse effect for the login button. Additionally, error handling is implemented with a shake animation for the form container when there is a login error.
