# movie_theater_seating

Movie Theater Seating Challenge 

Implement an algorithm for assigning seats within a movie theater to fulfill reservation requests. Assume the movie theater has the seating arrangement of 10 rows x
20 seats.

Design and write a seat assignment program to maximize both customer satisfaction and customer safety. For the purpose of public safety, assume that a buffer of
three seats and/or one row is required.

Input: 
File that contains 1 line of input for each reservation request. 
The order of the lines in the file reflects the order in which the reservation requests were received.

Format: R####

Example:
R001 2
R002 4
R003 4
R004 3


Output:
File containing seating assignments for each request.
Each row should include reservation number followed by a space, then comma-delimited list of assigned seats.


Example: 
R001 I1,I2
R002 F16,F17,F18,F19 
R003 A1,A2,A3,A4 
R004 J4,J5,J6
