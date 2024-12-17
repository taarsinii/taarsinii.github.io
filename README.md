# **Restaurant Table Reservation Application**

## **Project Overview**  
The **Restaurant Table Reservation Application** is a Java-based Android application that provides users with the following functionalities:  

- Create an account.  
- Make a reservation.  
- Edit a booking.  
- View booking history.  
- Cancel or delete a booking.  
- Receive notifications about bookings.  
- Manage user account information.  

---

## **API Integration**  
This application interacts with a RESTful API to manage booking operations, including creating, viewing, updating, and removing reservations. The app is built using **Android Studio** and uses the **Volley** library for handling network communication.  

### **API Endpoint**  
`https://web.socem.plymouth.ac.uk/COMP2000/ReservationApi/api/Reservations`  

---

### **How the Application Interacts with the API**  

1. **Get the Reservations**:
   - To retrieve all reservation data, send a `GET` request to the API and show it in the application's interface.  

3. **Create a Reservation**:
   - Sends a `POST` request to add a new reservation using the user's provided data, including the name, phone number, meal type, date, number of guests, and table size. These data will be display in JSON format.
   - ![Alt text](ss.png)

5. **Update a Reservation**:
   - To change an existing reservation, send a `PUT` request with the changed information which change new table size.

7. **Delete a Reservation**:
   - Using the reservation's unique ID, send a `DELETE` request to remove a particular reservation.  
---

## **Technologies Used**  
- **Android Studio**: For app development.  
- **Volley Library**: For handling API calls.  
- **Java**: As the primary programming language.  

