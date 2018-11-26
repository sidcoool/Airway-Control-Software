Airway Control System


Overview: We have added following several functionalities to our project


1} To know the Shortest Path between the two stops:
    We have made a database of a large no. of airports and inserted distance between them using both adjancey list and matrix.
    Then,we have used Floyd Warshal Algorithm(Data structure Graph) to find the minimum distance between all the routes.
    
    
2} Minimum ticket price for the booking:
    We have given price as the weight between all the airports and then by using improvised version of warshal's theorem 
    we have find the minimum ticket price for the booking.
    
    
3} Displaying path between two stops:
    Using the Floyd Warshal Algorithm we have found the shortest path between the stops and then we have displayed the same.
    
4} Reserve your seat:
    We have asked for the input of the no. of seats the user wants to reserve and then checked for the availbility of it 
    by checking the no. of seats already booked and the no. of seats the user wants to book now. And assigned each passanger 
    unique seatID.
    If the seats aren't available then we add their names to the waiting list (developed by using Data Structure queue).
    
    
5} Cancel your booking:
    One can cancel their seat by giving his/her seatID and therefore the first waitlisted person gets the booking perference.
    
    
6} Booking info:
  User can see their booking details by giving his/her seatID.
  
  
7} Information about departed flight
