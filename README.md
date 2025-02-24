# Concert Ticket Management 

The Ticket Management System is a Java-based console application designed to manage concert ticket bookings efficiently. 
It supports both admin and customer roles, allowing customers to book tickets and admins to manage concerts and view booking 
details. The system handles file operations, exception handling, and seat allocations dynamically.

## Features

### Admin Mode
* View concert details (timing, venue, seating availability)
* Update ticket prices for different seating zones
* View all booking details for a concert
* View total payment received for a concert

### Customer Mode
* Sign up or sign in using customer ID and password
* View concert schedules
* Check ticket prices and seating layout
* Book seats dynamically based on availability
* View personal booking details

### File Handling & Exception Management
* Reads and writes data from CSV and TXT files
* Handles invalid file paths, incorrect formatting, and missing data
* Detects invalid concert/customer/booking entries and skips them gracefully
