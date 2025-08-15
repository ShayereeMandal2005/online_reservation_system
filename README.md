# online_reservation_system
I recently developed a simple Java-based train ticket reservation system as part of my learning journey. This program allows users to log in, book tickets, and cancel reservations-all through the console.

Here's how the code works

1. Login Authentication

When the program starts, it first asks the user for a Login ID and Password.

Only if the entered credentials match the predefined ones (user/pass) will the user be allowed to proceed

If the credentials are wrong, the program stops with the message "Invalid login."

2. Main Menu Options

Once logged in, the user sees three choices:

Reservation Book a new train ticket

Cancellation-Cancel an existing ticket

Exit-Close the program

This menu keeps appearing until the user chooses Exit

3. Making a Reservation

When the user selects Reservation:

The program asks for details:

PNR Number (unique booking ID)

Passenger Name

Train Number

Train Name

Class Type (eg. Sleeper, AC)

Date of Jourmey

From Station

To Station

All these details are stored together in memory using a HashMap, where the PNR acts as the key.

A confirmation message "Reservation Successful." is shown

4. Cancelling a Reservation

When the user selects Cancellation:

The program asks for a PNR Number.

If the PNR exists in the stored reservations:

The booking details are shown.

The user is asked to confirm the cancellation by

typing "yes"

If confirmed, the booking is deleted, and "Cancellation Successful." is shown

If not confirmed, the cancellation is aborted.

If the PNR is not found, it shows "PNR Not Found

5. How Data is Stored

Value All booking details combined into a single string

Data exists only while the program is running (no file/database storage).

End Result

This Java code lets you

Log in securely 

Make multiple train ticket reservations

Cancel reservations using PNR number

See booking detalis during cancellation for verification

Exit the system anytime
Oasisinfobyte #Oasisinfobyte
