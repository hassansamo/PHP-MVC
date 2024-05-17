# PHP MVC Framework

This is a lightweight PHP MVC (Model-View-Controller) framework for building web applications. The framework follows the MVC architectural pattern, separating the application logic from the presentation layer, and promoting code reusability and maintainability..

## Features
Routing: The framework handles URL routing and dispatches requests to the appropriate controller and method.
Controllers: Controllers handle the application logic and pass data to the views.
Views: Views are responsible for rendering the user interface using the data provided by the controllers.
Models: Models interact with the database and encapsulate the business logic related to data manipulation.
Database Abstraction: The framework includes a database abstraction layer for executing SQL queries and retrieving results.
Autoloading: Classes are automatically loaded when needed, following the PSR-4 autoloading standard.
Error Handling: The framework includes a dedicated controller for handling 404 errors.
Configuration Management: Easily configure database settings, application URLs, and other constants through a centralized configuration file.
Helper Functions: Utility functions are provided for common tasks like escaping output, redirecting, and debugging.
