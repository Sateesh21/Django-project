MyTravels App

MyTravels is a full-stack bus ticket booking web application built using Django for the backend and React.js for the frontend. It offers users a seamless experience in browsing available buses, viewing full bus details, booking seats, and managing their bookings



![BusList](https://github.com/user-attachments/assets/8f52d203-90fc-4626-a002-52a695e97948)



***Table of Contents***
- Features
- Tech Stack
- Application-Flow


## Tech Stack
**React.js** | **Tailwind CSS** | **Axios** | **React Router** | **Django** | **REST Framework** | **Django Admin** **Auth** | **JWT** | **django-rest-framework-simplejwt** | **Media Storage	Azure Blob Storage** | **Cloud Storage** | **Crypto-js**

## Application-Flow 🌐

Home Page (Registration):
The Home Page of MyTravels displays Registration form for booking. Each bus is listed with key details like source, destination, departure time, and arrival time. Users can browse through the list to find a suitable journey..
  ![registration](https://github.com/user-attachments/assets/a3d552f9-7654-47e5-bcea-9ef6f9f15762)




Bus Details Page:
    This page provides complete details of a selected bus. It shows information such as source, destination, departure time, arrival time, and the number of available seats. Users can confirm their seat booking from here.

  ![BusList](https://github.com/user-attachments/assets/58a57bda-4581-4c71-8fd3-6d2705bd8315)


Booking Action (With Authentication Check):
When a user taps on the Book Seat button: If logged in → they will see a “Booking Successful” message.
  ![Success](https://github.com/user-attachments/assets/92f539f1-981e-45ee-98b8-c6c9b1017a93)

|| If not logged in → they will be redirected to the Login Page for authentication.

  ![Login](https://github.com/user-attachments/assets/1672b711-3dce-4cac-9237-840a15e67b01)


MyTravels (Booking History / Dashboard):
  The MyTravels section acts as a personal dashboard for users. It displays all past bookings, with complete details of each journey. This allows users to review their previous bookings and plan future journeys easily.

  ![myBookings](https://github.com/user-attachments/assets/c5f5c734-ff5a-4a8f-8646-46f2314800a3)

Features: List of all previous bookings made by the logged-in user || Details include Bus Name, Route, Seat Count, Booking Date/Time || Personalized experience based on logged-in user.

