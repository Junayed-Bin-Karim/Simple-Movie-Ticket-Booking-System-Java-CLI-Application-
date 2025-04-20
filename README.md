# Simple Movie Ticket Booking System (Java CLI Application)

This is a basic command-line interface (CLI) application written in Java that allows users to:

* View a list of available movies categorized by genre.
* Book movie tickets by selecting a movie and specifying the number of seats.
* Cancel existing ticket bookings.

## Features

* **View Movie List:** Displays movies organized under different genres (Bangla, Hindi, English). Users can choose a genre to see the movies within it.
* **Book Tickets:** Allows users to enter their name, select a movie (currently a placeholder selection), and specify the number of seats they want to book. It calculates the total cost (assuming a fixed price per ticket) and requires an OTP for confirmation.
* **Cancel Booking:** Enables users to cancel their booking by entering the name used during the booking. If the name matches, it simulates a refund.
* **Simple Menu-Driven Interface:** Provides a straightforward numerical menu for easy navigation.

## How to Run

1.  **Prerequisites:** Ensure you have Java Development Kit (JDK) installed on your system.
2.  **Compilation:**
    Navigate to the directory containing the `.java` files in your terminal and compile the code using the Java compiler:
    ```bash
    javac Main.java Movie_List.java Seat_Book.java Cancel.java Payment.java
    ```
3.  **Execution:**
    After successful compilation, run the main class:
    ```bash
    java Main
    ```
4.  **Interaction:** Follow the on-screen menu to view movies, book tickets, or cancel bookings.

## Code Structure

The project consists of the following Java files:

* `Main.java`: Contains the main entry point of the application and the main menu loop.
* `Movie_List.java`: Handles the display of movie genres and movie names within a selected genre.
* `Seat_Book.java`: Manages the ticket booking process, including taking user details, calculating the total cost, and handling OTP-based confirmation. It also contains a method to initiate the cancellation process.
* `Cancel.java`: Implements the functionality to cancel a ticket booking based on the name provided.
* `Payment.java`: A simple class to manage the payment amount and a hardcoded OTP for demonstration purposes.

## Potential Improvements

This is a basic implementation and can be further enhanced with the following features:

* **More Realistic Movie Selection:** Instead of a placeholder, allow users to select a specific movie from the displayed list in the booking process.
* **Seat Availability Management:** Implement logic to track and manage the availability of seats.
* **Data Persistence:** Store booking information (movie, seats, user details) in a file or database so that it persists between application runs.
* **More Robust Input Validation:** Add more comprehensive error handling for user input.
* **User Authentication:** Implement user login and registration.
* **More Sophisticated Payment Processing:** Integrate with actual payment gateways.
* **Detailed Booking Information:** Provide users with a booking ID or more details upon successful booking.
---

##  Author

**Md. Junayed Bin Karim**  
 CSE Student at Daffodil International University  
 [GitHub](https://github.com/Junayed-Bin-Karim)  
 [LinkedIn](https://www.linkedin.com/in/junayed-bin-karim-47b755270/)  
 karim22205101667@diu.edu.bd  


---


