
🔹 Key Features

1. Guest Registration & Room Booking
Users can enter guest details such as Name, Phone Number, Room Type, and Number of Nights.
The system validates:
Name must not be empty.
Phone number must be exactly 10 digits.
Nights must be a positive integer.
Available room types:
Single (₹800 per night)
Double (₹1200 per night)
Suite (₹2000 per night)
The application checks room availability before booking.

2. Automatic Check-In and Check-Out Dates
When booking is confirmed, the system automatically records:
Check-in date (current date)
Check-out date (current date + nights)

3. Room Availability Management
The system keeps track of how many rooms of each type are available.
When a room is booked, availability decreases.
When a guest checks out, the room is released back into availability.

4. Guest List Display
All current guests are displayed in a Treeview table with columns:
Name
Phone
Room Type
Nights
Check-In Date
Check-Out Date
The table updates dynamically whenever guests are added or removed.

5. Billing System
Selecting a guest in the table shows their generated bill.
Billing formula:

Total Bill = Room Rate × Number of Nights
Bill preview is displayed in the GUI.


6. Guest Check-Out
Users can select a guest and check them out.
This removes them from the guest list and frees the room.

🔹 Technologies Used

Python 3
Tkinter (GUI library)
ttk.Treeview (for displaying tabular data)
datetime module (for date calculations)

🔹 Workflow Summary
1. User enters guest details and books a room.
2. System validates inputs and updates room availability.
3. Guest details are added to the table.
4. Selecting a guest shows their bill.
5. On check-out, the guest is removed and the room becomes available again.

🔹 Project Advantages
Simple and user-friendly GUI.
Useful for small hotels, lodges, and guest houses.
Automates manual tasks such as:
maintaining guest logs
calculating bills
tracking room availability
Reduces chances of manual errors.

🔹 Possible Enhancements
Persistent database storage (SQLite/MySQL).
Room history and reporting.
Admin login system.
Printing receipts or saving bills as PDF.
Enhanced UI theme (Ttk Themes).


