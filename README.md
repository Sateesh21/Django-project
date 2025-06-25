                                                              MyTravels App

MyTravels is a full-stack bus ticket booking web application built using Django for the backend and React.js for the frontend. It offers users a seamless experience in browsing available buses, viewing full bus details, booking seats, and managing their bookings

## Application Flow:
User Registration → User Login → Bus Details → Seat Details → Login Confirmation → Booking Confirmed (If Already Logged In) → OR Redirect to Login (If Not Logged In) → DONE



## Tech Stack
**React.js** | **Tailwind CSS** | **Axios** | **React Router** | **Django** | **REST Framework** | **Django Admin** **Auth** | **JWT** | **django-rest-framework-simplejwt** | **Media Storage	Azure Blob Storage** | **Cloud Storage** | **Crypto-js**

## Clear Application-Flow With Output Details🌐

## Home Page (Registration):
The Home Page of MyTravels displays Registration form for booking. Each bus is listed with key details like source, destination, departure time, and arrival time. Users can browse through the list to find a suitable journey.. <br> <br>
  ![registration](https://github.com/user-attachments/assets/a3d552f9-7654-47e5-bcea-9ef6f9f15762)


## Login:
If not logged in → they will be redirected to the Login Page for authentication.

  ![Login](https://github.com/user-attachments/assets/1672b711-3dce-4cac-9237-840a15e67b01)

## Bus Details Page:
This page provides complete details of a selected bus. It shows information such as source, destination, departure time, arrival time, and the number of available seats. Users can confirm their seat booking from here. <br> <br>0
  ![fe_busdetails](https://github.com/user-attachments/assets/643c120a-9c40-4a6c-9393-038e69b0dcdd)



## Booking Action (With Authentication Check):
After the user successfully logs in, the application will display all available bus details. If the user wants to book a seat, they need to tap on the "View Seats" button, which will redirect them to the seat details page, where all the available seat information will be shown.

  ![availableSeats](https://github.com/user-attachments/assets/01388d51-75fe-48f3-9eb2-1c036974fcf8)

  ## Login Check:
   Here, a login check will be performed. If the user is already logged in, they can book any seat. and will get  booking success alert !!
   <br> <br>
   ![Success](https://github.com/user-attachments/assets/39131189-b4ad-4ef3-9615-f47605d4ed0a)

   If the user is not logged in, they will be redirected to the login page.
   ![fe_loginFirst](https://github.com/user-attachments/assets/f39fa37d-ba56-47a1-85a0-a30e67e535d3) <br> <br>

  Again to Login Page <br> <br>

  ![Login](https://github.com/user-attachments/assets/1672b711-3dce-4cac-9237-840a15e67b01)

 ### Up to this point, the login and booking processes are completed. If the user wants to check their booking details, they need to tap on the "MyTravels" name, where all their booking details will be displayed.


## MyTravels (Booking History / Dashboard):
  The MyTravels section acts as a personal dashboard for users. It displays all past bookings, with complete details of each journey. This allows users to review their previous bookings and plan future journeys easily.

  ![myBookings](https://github.com/user-attachments/assets/c5f5c734-ff5a-4a8f-8646-46f2314800a3)
