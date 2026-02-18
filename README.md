# SmartStay Hotel Reservation System – Software Design
**Overview**
SmartStay is a hotel reservation system designed to support room availability search, booking, confirmation messaging, and online check-in.<br>
 <br>
This project focuses on full software design, including scope definition, requirements analysis, architecture design, detailed design, pseudocode, unit testing, and traceability.

**Technologies and methods used**<br>
UML style component design<br>
Three tier architecture approach<br>
Pseudocode for core workflows<br>
Unit test case design<br>
Requirements traceability<br>

**Process and how it was built**
1. Defined scope and out of scope features. 
2. Wrote functional and non functional requirements. 
3. Designed architecture components and interfaces. 
4. Created detailed design with functional decomposition and object oriented view. 
5. Wrote pseudocode for key functions like searchRooms, saveBooking, and checkInGuest. 
6. Drafted unit test case and a traceability matrix linking requirements to design and code level functions.

---

**System Requirements**
Guests can search available rooms using check-in and check-out dates.
Guests can book rooms through a structured booking flow.
Booking form includes dropdowns for room type and dates.
System stores guest name, email, dates, and room type.
System displays confirmation page after booking.
Guests can check in online using reservation ID.
System updates and saves check-in status.
System responds within 3 seconds.
Checked-in rooms are no longer shown as available.

# Software Architecture
**Main Components**
Guest Interface<br>
-Handles room search, booking form, and check-in interaction.

Reservation Processor<br>
-Handles business logic including search, validation, booking, and check-in.

Data Manager<br>
-Stores and retrieves booking data and availability.

Notification Service<br>
-Generates and sends booking confirmations. 

---

**Architecture Layers**<br>
Presentation Layer<br>
-Guest Interface and Notification Service<br>

Business Logic Layer<br>
-Reservation Processor<br>

Data Layer<br>
-Data Manager<br>

---

# Detailed Design

****Functional Decomposition****<br>
**Reservation Processor**<br>
- Search Available Rooms
- Validate Booking Info
- Create Reservation
- Process Guest Check-In

**Notification Service**<br>
- Generate Confirmation Message
- Send Confirmation Email 

---

**Object-Oriented Design**
Data Manager
- Get Available Rooms
- Store Booking Data
- Update Check-In Status<br>


**Guest Interface**
- Get Search Input
- Show Available Rooms
- Display Booking Form
- Display Confirmation<br>


**Reservation Processor**
- Search Rooms
- Validate Booking
- Save Booking
- Check In Guest<br>



**Notification Service**
- Generate Confirmation
- Send Email <br>

# Core Pseudocode
**Includes functions:**
searchRooms
validateBooking
saveBooking
checkInGuest
NotificationService.sendEmail 


# Unit Testing
**Example test case validates:**
Valid booking flow
Booking storage
Confirmation message generation
Requirement traceability coverage 

# Traceability Matrix


---

**What I learned**
- How to turn a basic idea into a structured system design.
- How to write clear requirements and connect them to design and tests.
- How to separate UI, business logic, and data management in a simple architecture. 

**How it could be improved**
Add a real database schema and ER diagram.
Build a working prototype using a web framework.
Add authentication and role based access for staff features.
Add payment processing as an optional module.

**Evidence and files**
