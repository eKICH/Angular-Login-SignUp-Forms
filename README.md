## Login & SingUp Tabs
- This project has 3 custom components
    -- header component
    -- login component
    -- signup component
- The header component contains the Login and SignUp tabs
- The login component contains the login form
- The signup component contains the signup form

## Angular Routes
- In this project, the Login & SignUp Tabs are created using Angular Routes.
    -- The routes object is setup in the app.module.ts file
    -- I have used router-outlet tag in the app.component.html file
    -- I have used the routerLink tag in the header.component.html file to display each route in its respective tab

## Angular Template-Driven Form
- The login and signup forms are template-driven forms which are based on HTML template
- Basic Form validations are applied to the both forms (Login and Signup)
- On clicking of the both buttons in each tab, in the console, I am logging the NgForm object