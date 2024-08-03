# Project3
Bus Reservation system

# Project Overview
The Online Bus Ticket Reservation System is a user-friendly application designed to manage bus reservations, cancellations, and status checks efficiently. It utilizes a simple command-line interface to facilitate booking, viewing, and canceling bus tickets. The system is implemented using C programming and features a straightforward approach to handle bus reservations with options for different bus classes.

# System Components
1. Data Structures:

struct datastore: Defines a structure to hold ticket information including ticket number, passenger name, age, phone number, and gender.
Arrays of struct datastore are used to manage bookings for three different buses.

# Functions:

bus(): Displays the list of available buses with their details such as source, destination, time duration, and available classes.

booking(): Handles the booking process, including seat selection and data entry for passengers. Updates the booking status and stores passenger details.

viewbus(): Provides details of each bus including departure and arrival times, ticket prices, and seat availability.

cancel(): Manages the cancellation of bookings. Allows users to cancel tickets and updates the seat status accordingly.

status(): Checks the status of a particular seat in a specific bus and displays booking details or cancellation status.

# System Functioning
1.Viewing Buses:
Users can view the available buses, their details, and seat availability by selecting the appropriate option.

2.Booking Tickets:
Users choose a bus, view available seats, and book tickets by entering the seat number and passenger details. The system updates the seat status and confirms the booking.

3.Canceling Bookings:
Users can cancel a booking by selecting the bus and seat number. The system updates the seat status and confirms the cancellation.

4.Checking Ticket Status:
Users can check the status of a particular seat in a selected bus. The system displays booking details or indicates if the seat has been canceled.

# Implementation Details
1.Main Program Loop:
Presents a menu with options to view buses, book tickets, cancel bookings, check ticket status, or exit the program. The user’s choice determines which function is executed.

2.Data Management:
Arrays a, b, and c track seat availability for three different buses. Each seat's status is updated based on user actions.

3.User Interaction:
The command-line interface allows users to interact with the system by entering choices and seat details. The system provides feedback on booking status and errors.

