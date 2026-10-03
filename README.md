Movie Theater Ticket Kiosk

This application is a kiosk system for a local movie theater. Using the kiosk, customers can view the movies that are available and their showtimes. After they select a movie, they can see what seats are available and then choose a seat, and now the customer may purchase their ticket. Afterwards, the system will send a confirmation email about the customer's successful purchase. The system shall also have fail-safes in place to make sure the same seats can't be reserved by more than one person.

Purchase Ticket Use Case:
-Primary Actor: Customer
-Precondition: There are upcoming movies that are going to play in the theater associated with the kiosk, and the customer has already selected a showtime and a seat associated with that showtime using the kiosk.
-Steps
  1. TUCBW the customer has already selected a movie, a showtime, and a seat.
  2. The system displays the total cost for the customer's ticket.
  3. The customer chooses their payment option: cash or credit.
  4. If the customer chooses credit, they will insert their card, and if they choose cash, they will insert cash and receive any change if needed.
  6. TUCEW with a confirmation message that the purchase was successful, and the system will prevent any other customers from reserving the seat associated with that show time in the future.

-Postcondition: The system will send a confirmation email to the customer that their purchase was successful.
The system shall also prevent other customers from reserving the seat that was just reserved for that show time in that ticket.
