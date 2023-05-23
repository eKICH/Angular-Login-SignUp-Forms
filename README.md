## Login & SingUp Tabs
- This project has 3 custom components
    - header component
    - login component
    - signup component
- The header component contains the Login and SignUp tabs
- The login component contains the login form
- The signup component contains the signup form
![Login   SignUp Tabs - Google Chrome 2023-05-23 at 11 15 53 PM](https://github.com/eKICH/Angular-Login-SignUp-Tabs/assets/73248530/a0041e79-d7ed-41a7-ba13-66fb2d576ad6)
![Login   SignUp Tabs - Google Chrome 2023-05-23 at 11 19 38 PM](https://github.com/eKICH/Angular-Login-SignUp-Tabs/assets/73248530/b75e43f8-dcc9-49d7-bb74-dd62cbd8c8a8)

## Angular Routes
- In this project, the Login & SignUp Tabs are created using Angular Routes.
    - The routes object is setup in the app.module.ts file
    - I have used router-outlet tag in the app.component.html file
    - I have used the routerLink tag in the header.component.html file to display each route in its respective tab

## Angular Template-Driven Form
- The login and signup forms are template-driven forms which are based on HTML template
- Basic Form validations are applied to the both forms (Login and Signup)
- On clicking of the both buttons in each tab, in the console, I am logging the NgForm object

![Login   SignUp Tabs - Google Chrome 2023-05-23 at 11 20 43 PM](https://github.com/eKICH/Angular-Login-SignUp-Tabs/assets/73248530/7f13e7fa-b651-44ed-b07c-9c201ee77434)
![Login   SignUp Tabs - Google Chrome 2023-05-23 at 11 21 12 PM](https://github.com/eKICH/Angular-Login-SignUp-Tabs/assets/73248530/4bc576ba-65ad-4670-b5ad-db6afa5d15e2)
