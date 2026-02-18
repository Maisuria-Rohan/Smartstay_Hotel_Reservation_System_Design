# SmartStay Hotel Reservation System – Software Design
## Overview
SmartStay is a hotel reservation system designed to support room availability search, booking, confirmation messaging, and online check-in. This project focuses on full software design, including scope definition, requirements analysis, architecture design, detailed design, pseudocode, unit testing, and traceability. <br>

## Technologies and methods used
- UML style component design<br>
- Three tier architecture approach<br>
- Pseudocode for core workflows<br>
- Unit test case design<br>
- Requirements traceability<br>

## Process and how it was built
1. Defined scope and out of scope features. 
2. Wrote functional and non functional requirements. 
3. Designed architecture components and interfaces. 
4. Created detailed design with functional decomposition and object oriented view. 
5. Wrote pseudocode for key functions like searchRooms, saveBooking, and checkInGuest. 
6. Drafted unit test case and a traceability matrix linking requirements to design and code level functions.


## System Requirements
- Guests can search available rooms using check-in and check-out dates.<br>
- Guests can book rooms through a structured booking flow.<br>
- Booking form includes dropdowns for room type and dates.<br>
- System stores guest name, email, dates, and room type.<br>
- System displays confirmation page after booking.<br>
- Guests can check in online using reservation ID.<br>
- System updates and saves check-in status.<br>
- System responds within 3 seconds.<br>
- Checked-in rooms are no longer shown as available.<br>

## Software Architecture
### Main Components
<img width="600" height="400" alt="Screenshot 2026-02-18 at 3 29 39 PM" src="https://github.com/user-attachments/assets/f2c1fb54-9894-4771-95b1-71234c85c139" /><br>
#### Guest Interface<br>
-Handles room search, booking form, and check-in interaction.<br>

#### Reservation Processor<br>
-Handles business logic including search, validation, booking, and check-in.<br>

#### Data Manager<br>
-Stores and retrieves booking data and availability.<br>

#### Notification Service<br>
-Generates and sends booking confirmations.<br>
                                             



## Architecture Layers
### Presentation Layer<br>
-Guest Interface and Notification Service<br>

### Business Logic Layer<br>
-Reservation Processor<br>

### Data Layer<br>
-Data Manager<br>


## Detailed Design
### Functional Decomposition
#### Reservation Processor
<img width="600" height="350" alt="Screenshot 2026-02-18 at 3 30 45 PM" src="https://github.com/user-attachments/assets/db7f00ce-5f05-4c73-86ac-f7d2bcffb5ee" /><br>
- Search Available Rooms
- Validate Booking Info
- Create Reservation
- Process Guest Check-In<br>


#### Notification Service
<img width="600" height="400" alt="Screenshot 2026-02-18 at 3 31 36 PM" src="https://github.com/user-attachments/assets/c41d14c9-8162-458e-81a9-4c5954d153ec" /><br>
- Generate Confirmation Message
- Send Confirmation Email<br>



  


## Object-Oriented Design
<img width="600" height="300" alt="Screenshot 2026-02-18 at 3 32 55 PM" src="https://github.com/user-attachments/assets/026f67c5-83bc-48c7-8807-60e98c7f5471" /><br>
### Data Manager
- Get Available Rooms
- Store Booking Data
- Update Check-In Status<br>

### Guest Interface
- Get Search Input
- Show Available Rooms
- Display Booking Form
- Display Confirmation<br>

### Reservation Processor
- Search Rooms
- Validate Booking
- Save Booking
- Check In Guest<br>

### Notification Service
- Generate Confirmation
- Send Email <br>




## Core Pseudocode
### Includes functions:
- searchRooms
- validateBooking
- saveBooking
- checkInGuest
- NotificationService.sendEmail 



## Unit Testing
### Example test case validates:
- Valid booking flow
- Booking storage
- Confirmation message generation
- Requirement traceability coverage 



## Traceability Matrix
<img width="600" height="200" alt="Screenshot 2026-02-18 at 3 27 43 PM" src="https://github.com/user-attachments/assets/6ebc2a90-2eb4-4fb9-b407-e42b1ef6c7f1" /><br>


## What I learned
- How to turn a basic idea into a structured system design.
- How to write clear requirements and connect them to design and tests.
- How to separate UI, business logic, and data management in a simple architecture. 

## How it could be improved
- Add a real database schema and ER diagram.
- Build a working prototype using a web framework.
- Add authentication and role based access for staff features.
- Add payment processing as an optional module.

## Documents
[SmartStay Hotel Reservation System.pdf](https://github.com/user-attachments/files/25401232/SmartStay.Hotel.Reservation.System.pdf)<br>
[Requirements Document.pdf](https://github.com/user-attachments/files/25401244/Requirements.Document.pdf)<br>
[Software Pseudo Code.txt](https://github.com/user-attachments/files/25401261/Software.Pseudo.Code.txt)<br>
