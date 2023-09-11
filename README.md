# Employee-Review-System
[Github Link](https://github.com/abhi20012/FeedbackFlow_coding_ninjas) | [See live](https://feedback-flow.onrender.com/users/sign-in)



## Table of Contents 📕

- [Description](#description)
- [Tools and Technology](#tools-and-technology)
- [Features :](#features)
- [How to Setup the project on local system](#how-to-setup-the-project-on-local-system)
- [Folder Structure](#folder-structure)


### Description
* The Challenge
    * Build an Employee Review System
    * Essential features expected 
       1. User sign-in | sign-up flow
       2. Forgot password feature 
       3. On login user get two options either login as Employee | login as Admin
       4. Admin can review available Employee and other Admins
       5. Employee can be promoted to Admins if performance is good.
    * Detailed view of the problem can be found [here](https://docs.google.com/document/d/1AF2H2TsqfYfGdH5fGhMlhA_r96RW6sDLxUGUCAGOt9s/edit)


### Tools and Technology

* Front-end: **HTML, **EJS, **Bootstrap, **CSS
* Back-end: **MongoDB for the database which provide facality to add, remove and update users. **Node.js, **Express.js.
* Deployement: On progress.  

### Features

  You can review the employees. The admin has the special power to assing, the task to employee, remove the employee, add new admin, and also employee;

### How to setup the project on local system

  1. Clone this project
  2. Start by installing npm if you don't have it already.
  3. Navigate to Project Directory.

After reaching the project directory you have to run the following the command.
   ```` 
        npm install 
        npm start || nodemon index.js
   ````

#### If you want to make an employee as admin then use the secret key : admin.
  
  # HomePage / Admin View

  # Home page / Employee view

  
  # Sign-Up


  # Sign-In

  # Forget Password
  
  # Assign Task

  # Employee List
  

  

### Folder Structure

```
Employee Review System
    |
    |               |--->css
    |--->assets---->|--->images
    |             
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport-local-Stradegy.js
    |
    |                  |-->admin_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->review_controller.js
    |                  |-->user_controller.js
    |
    |               |-->review.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->admin.js
    |--->routes---->|-->index.js
    |               |-->review.js
    |               |-->user.js
    |
    |              |--->_header.ejs
    |              |---> addEmployee.ejs
    |              |---> admin.ejs
    |              |---> employe.ejs
    |--->views---->|--->forget_password.ejs
    |              |--->home.ejs
    |              |--->layout.ejs
    |              |--->sign_in.ejs
    |              |--->sign_up.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    ````
