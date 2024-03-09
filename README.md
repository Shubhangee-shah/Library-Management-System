# Library Management System (LMS)

The Library Management System (LMS) is a software application designed to manage the operations of a library, including book management, user management, and more. This project is developed in Java, utilizing the MVC (Model-View-Controller) pattern to separate concerns and maintain a structured architecture.

## MVC Architecture

### Model

The Model component of the LMS stores entities and data logic. It serves as the backbone of the system, holding information about books, users, and other relevant entities. Data manipulation and management are provided through getter and setter methods.

### View

The View component acts as the user interface, allowing users to interact with the system. It presents information to users and collects input from them. Users can perform actions such as searching for books, adding new users, and more through the View.

### Controller

The Controller serves as the middleman between the Model and the View. It processes user input, such as button clicks or form submissions, and determines the appropriate actions to take. This may involve updating the Model, fetching new data, or navigating to different Views.









###Features

1.Add a book

2.Remove a book

3.Update book details

4.Get book details

Technologies Used

Java

Scanner class for input handling

Components
View (com.jsp.lms.view.View)

Entry point of the application.
Handles user interaction and input.
Utilizes the Controller to perform operations on the Library model.

Controller (com.jsp.lms.controller.Controller)

Acts as an intermediary between the View and the Library model.
Contains methods to add, remove, update, and retrieve books from the Library.
Model

Library (com.jsp.lms.model.Library)

Represents the library entity.
Contains attributes such as library name, address, and pin code.

Book (com.jsp.lms.model.Book)

Represents a book entity.
Contains attributes such as book name, author name, and price.

Usage

View

Upon running the application, the user is prompted to enter the library details.
The user can then perform various actions such as adding, removing, updating, or retrieving books.

Controller

Handles the business logic of the application.
Interacts with the Library model to perform CRUD operations on books.

Installation
Clone the repository from [GitHub link].
Compile the Java files using a Java compiler.
Run the compiled Java file (View.java) to start the application.
