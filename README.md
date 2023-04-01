# TamatemTask

This project is a login page designed for tamatem plus as web frontend task.

I created **LoginComponent** to separate login functionality from root component and added the login path in **AppRoutingModule** as empty string to be loaded as the main page.

I used angular material package for styling, and created a custom theme in **src/my-theme.scss** to change the default material theme colors to the colors provided in adobe XD (primary palette, accent palette and warn palette), this way I can also use them as variables multiple times in my scss files.

I used **bootstrap** to create responsive web design in easy and fast way.

I used **typeface-roboto** font package and imported it in style.scss file,then I implemented it on the login page scss file;

I used **ReactiveFormsModule** to validate and create my login fields due to it's robust and flexible validation system.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.
