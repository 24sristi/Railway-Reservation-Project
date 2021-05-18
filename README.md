# Railway-Reservation-Project
Railways reservation system showcasing Object oriented programming in C++

This is an efficient model for users to access the facilities made available by the Railways.
Users can check the availability of a train and book tickets by entering the boarding point and destination. A ticket will be printed out containing the PNR number which can be used for cancellation of the ticket. 
Whereas the administration can enter a new train record, display all the records, modify or delete current train records with the help of a password.

# For Users
* Enquire(): This function is used to get details of  available Train by entering boarding points and destinations.
* Book(): Using this function, a person can book train tickets for themselves after checking and ensuring the availability of the trains.
* Cancel(): Function to cancel the tickets by using the PNR number provided at the time of booking.

# For Administrator
* Create(): In case of change of train schedules, such as an additional train running on a particular day, this function can be used to add a new record to the data.
* Add(): To add a new detail to the existing record in the database.
* Modify(): To modify details of existing train records in case of some change, such as if the train is ahead or behind schedule.
* Display(): To display the details of passengers that have booked their tickets for a given train record.
* Management(): To create user id and password that has to be used by the user reserve or cancel tickets.
* SECURITY of administration is ensured by protecting the Admin functionalities with a Password.


 
The purpose of this project is to make access to the railway bookings and availability checking easier for the users/travelers. By incorporating this project in real life, a lot of to-and-fro would be cut down upon, which leads to many advantages such as no time being wasted and even lesser traffic. Apart from the obvious advantages, this presents a way as to accumulate data from all over in one place, while also being accessible to everyone at the same time.
The project also results in building a stronger understanding of concepts of Object Oriented programming in C++.
