# Library Management System (LMS)

The Library Management System (LMS) is a software application designed to manage the operations of a library, including book management, user management, and more. This project is developed in Java, utilizing the MVC (Model-View-Controller) pattern to separate concerns and maintain a structured architecture.

## MVC Architecture

### Model

The Model component of the LMS stores entities and data logic. It serves as the backbone of the system, holding information about books, users, and other relevant entities. Data manipulation and management are provided through getter and setter methods.

### View

The View component acts as the user interface, allowing users to interact with the system. It presents information to users and collects input from them. Users can perform actions such as searching for books, adding new users, and more through the View.

### Controller

The Controller serves as the middleman between the Model and the View. It processes user input, such as button clicks or form submissions, and determines the appropriate actions to take. This may involve updating the Model, fetching new data, or navigating to different Views.

## Features

1. **Add a book**: Users can add new books to the library inventory.
2. **Remove a book**: Books can be removed from the library.
3. **Update book details**: Users can update the details of existing books.
4. **Get book details**: Retrieve details of books from the library.

## Technologies Used

- Java
- Scanner class for input handling

## Components

### View (`com.jsp.lms.view.View`)

- Entry point of the application.
- Handles user interaction and input.
- Utilizes the Controller to perform operations on the Library model.

### Controller (`com.jsp.lms.controller.Controller`)

- Acts as an intermediary between the View and the Library model.
- Contains methods to add, remove, update, and retrieve books from the Library.

### Model

#### Library (`com.jsp.lms.model.Library`)

- Represents the library entity.
- Contains attributes such as library name, address, and pin code.

#### Book (`com.jsp.lms.model.Book`)

- Represents a book entity.
- Contains attributes such as book name, author name, and price.

## Usage

### View

- Upon running the application, the user is prompted to enter the library details.
- Users can then perform various actions such as adding, removing, updating, or retrieving books.

### Controller

- Handles the business logic of the application.
- Interacts with the Library model to perform CRUD operations on books.

## Installation

1. Clone the repository from https://github.com/Shubhangee-shah/Library-Management-System.
2. Compile the Java files using a Java compiler.
3. Run the compiled Java file (`View.java`) to start the application.

Entities

## Book

The Book class represents a book entity in the Library Management System. It contains attributes such as book name, author, and price.

### Attributes:-
- `bookName`: Represents the name of the book.
- `bookAuthor`: Represents the author of the book.
- `bookPrice`: Represents the price of the book.

### Methods:-
- `getBookName()`: Returns the name of the book.
- `setBookName()`: Sets the name of the book.
- `getBookAuthor()`: Returns the author of the book.
- `setBookAuthor()`: Sets the author of the book.
- `getBookPrice()`: Returns the price of the book.
- `setBookPrice()`: Sets the price of the book.
- `toString()`: Returns a string representation of the book, including its name, author, and price.

### Usage
The Book class is used to represent individual books within the library. 
It encapsulates information such as name, author, and price.

## Library

The Library class represents a library entity in the Library Management System. It contains attributes such as library name, address, pin code, and a list of books available in the library.

### Attributes:-
- `libraryName`: Represents the name of the library.
- `libraryAddress`: Represents the address of the library.
- `pincode`: Represents the pin code of the library.
- `books`: Represents the list of books available in the library.

### Methods:-
- `getLibraryName()`: Returns the name of the library.
- `setLibraryName()`: Sets the name of the library.
- `getLibraryAddress()`: Returns the address of the library.
- `setLibraryAddress()`: Sets the address of the library.
- `getPincode()`: Returns the pin code of the library.
- `setPincode()`: Sets the pin code of the library.
- `getBooks()`: Returns the list of books available in the library.
- `setBooks()`: Sets the list of books available in the library.

### Usage
- The Library class is used to represent the properties of a library within the system.
- It encapsulates information such as name, address, and pin code.
- It also maintains a list of books available in the library.

  ## ER Diagram
  
![Screenshot 2024-03-09 230328](https://github.com/Shubhangee-shah/Library-Management-System/assets/138153081/c7bb07e7-5a02-4fdd-8e26-cbc89f10cbb4)


## Use Cases

![WhatsApp Image 2024-03-09 at 17 20 27](https://github.com/Shubhangee-shah/Library-Management-System/assets/138153081/8b4908fa-ea04-4f1b-b472-40e7223fbc99)
![WhatsApp Image 2024-03-09 at 17 20 59](https://github.com/Shubhangee-shah/Library-Management-System/assets/138153081/067ca9f3-6a23-4473-a14b-8b7e0b7c54b4)
![WhatsApp Image 2024-03-09 at 17 20 59](https://github.com/Shubhangee-shah/Library-Management-System/assets/138153081/b399c9d1-b6d0-44f2-b181-450a9341587e)



