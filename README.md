Flight Management System

Project Overview :

The "Flight Management System" is a Java-based desktop application developed using "NetBeans IDE". The application manages flight-related data such as flight schedules, passenger details, and ticket booking. This project integrates "MySQL" as its database for data storage and retrieval. No transactions are implemented in this project, providing a simplified flight management system without multi-step database operations.

Features :

- Boarding Pass
- View flight availability.
- Add and manage passanger details.
- Book tickets for flights.
- Retrieve and display flight and booking information.

Prerequisites :

  Software Requirements :
  
    - NetBeans IDE 
    
    - Java Development Kit (JDK)
    
    - MySQL

Dependencies :

   MySQL JDBC Driver :
  
    - Ensure the following JAR file is added to the project's library :
  
        mysql-connector-java-8.0.28-bin.jar

Project Structure :

  - Login.java : Entry point of the application.
    
  - Home.java : Provides options like Flight Details, Add customer Details, Book Flight, journey Details, Cancel Ticket, Boarding Pass.

  - FlightInfo.java : Manages flight details.
    
  - AddCustomer.java : Stores customer information.
    
  - BookingFlight.java : Booking Flight tickets based on the customer information along with the flight availability.
    
  - Cancel.java : Cancels the ticket.

  - JourneyDetails.java : Gives the detailed information about the booked ticket.

  - BoardingPass.java : Provides Boarding Pass.

  - Conn.java : Manages Database Connectivity.

Limitations : 

- No support for transactional operations like rollback.
- Simplistic implementation without error handling for advanced scenarios.
- Basic UI without modern frameworks.

Future Enhancements :

- Implement transaction management for booking processes.
- Enhance UI using JavaFX or a web-based interface.
- Add user authentication and roles (Admin, User).
- Integrate additional features like flight tracking or email notifications.

Team Members : 
  1. Merla Sri Veda Sai
  2. Mandava Jahnavi Nitheesha
