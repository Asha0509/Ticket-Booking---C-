# Ticket Booking System (C)

## Description
This project is a simple **Movie Ticket Booking System** implemented in C. It allows users to:

1. **Book a ticket** - Choose a movie, timing, and seat.
2. **Cancel a ticket** - Remove a booking using the Ticket ID.
3. **View bookings** - See all current bookings.
4. **View available seats** - Check which seats are free.
5. **Exit the system**.

The system efficiently manages ticket reservations using **Queue Data Structure**, ensuring proper sequential handling of bookings and cancellations.

## Features
- **Queue Management**: Ensures tickets are processed in order.
- **Seat Availability Tracking**: Allows users to check and select available seats.
- **Receipt Generation**: Provides a formatted receipt after booking.
- **Cancellation**: Users can cancel a booked ticket by entering their Ticket ID.
- **User-friendly Interface**: Simple menu-based interaction.

## How to Run
1. Compile the program using GCC:
   ```sh
   gcc ticket_booking.c -o ticket_booking
   ```
2. Run the compiled program:
   ```sh
   ./ticket_booking
   ```
3. Follow the on-screen menu to book, cancel, or view tickets.

## Example Output
```
======================================
        WELCOME TO MOVIE BOOKING
======================================

Ticket Booking System
1. Book Ticket
2. Cancel Ticket
3. View Bookings
4. View Available Seats
5. Exit
Enter choice: 1

Available Movies:
1. Avengers: Endgame
2. Inception
3. The Dark Knight
4. Interstellar
Select Movie (1-4): 2

Available Timings:
1. 10:00 AM
2. 1:00 PM
3. 4:00 PM
4. 7:00 PM
Select Timing (1-4): 3

Available Seats: 1 2 3 4 5 6 7 8 9 10
Select Seat Number: 5

===================================
         BOOKING RECEIPT
===================================
Ticket ID   : 1
Movie       : Inception
Timing      : 4:00 PM
Seat Number : 5
===================================
Please check your receipt before leaving!
```

## Future Enhancements
- Implement user authentication.
- Add multiple seat selection.
- Integrate with a database for persistent storage.

Feel free to fork, modify, and enhance this project! 🚀

