# MEtodo
To-do list app dashboard page

<a href="https://64893a2a304b694f5107ea0c--endearing-starburst-77f66d.netlify.app/" target="_blank">Marquee Equity To-Do App Assessment</a>

# To the Team of ME 
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
<div>
</div>
![image](https://github.com/RaghavaJagannatham/MEtodo/assets/70148332/90fc7b6b-2f4a-415b-bdd3-6be38a0eea0e/200x150)
![image](https://github.com/RaghavaJagannatham/MEtodo/assets/70148332/87323c0f-b1ed-45be-aa2c-6aca4f63d886/200x150)
![image](https://github.com/RaghavaJagannatham/MEtodo/assets/70148332/6d6c5300-076c-4aa4-9ccf-e6c7be4a0032/200x150)



# Code Explanation

Login and Logout
The login functionality is implemented using the useState hook. When users enter their email and password and click the "Login" button, the handleLogin function is called. This function performs validation (replace with your own logic) and sets the isLoggedIn state to true if the credentials are correct. The user's email and password are stored in the browser's local storage using localStorage.setItem.

The logout functionality is implemented in the handleLogout function. It removes the email and password from local storage and sets isLoggedIn to false, logging the user out.

# Dashboard
If the user is logged in (isLoggedIn is true), the dashboard is displayed. You can add your own dashboard content here.

# Styling and Animations
The code includes CSS styles and animations to enhance the user interface. The App.css file contains the styles for the login and dashboard components. Animation styles are added to provide a fade-in effect for the login form elements and a pulse effect for the login button. Additionally, error handling is implemented with a shake animation for the form container when there is a login error.
