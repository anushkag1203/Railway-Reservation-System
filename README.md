# Railway-Reservation-System

Tech Stack:
Java Programming Language

Data Structures used:
LinkedList, Array, Queue, Hashmap, HashSet

Project Intro:
The project aims to ease the railway reservation process for passengers by making it a simple and user-friendly process. The passenger can book the ticket for the respective train based on his/her requirements and can easily delete the booked seat. The project is to simplify the reservation process.

Working of the project:
In the project, we have used various data structures to store the data efficiently. We have used LinkedList to store passenger data as he/she books a ticket. We have stored the information of each available train in an array. We have also used an array to store the seat matrix of each train and a HashSet to store the booked seat no. Again we have used a queue to store waiting list passengers and we have used Hashmap to store the index and the seat number at that index of the seat matrix.

The passengers have 3 options:

To book a ticket
To check the passenger's details
To delete a booking
As soon as a passenger selects the book ticket option he will be displayed with all the trains available, their source and destination, their start and end time and the train no. The user will then select a train no to book his ticket and will have to enter his details such as name, age, gender, date of journey, and seat no. Once he has entered the details he will get a ticket with all the details.

In the passenger’s details option, we have to enter the train number to view all the passengers on the train. If the passenger wants to delete the reservation he will have to enter the train no and then this seat no to delete the booking. Once the passenger from the confirmed seat deletes his booking the first person from the waiting list will be allocated the seat and so on. This system works similarly to the actual railway reservation system with some of the functionalities.

Scope or future development:
The future scope of this project includes a UI for the same and various other functionalities like RAC tickets and seat preference based on upper, lower and middle birth. Also, a ladies quota can be included with only female passengers.




