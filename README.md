# Flight-Booking-system-Apsche-
✈️ Fly High – Flight Booking System
📌 Project Overview

Fly High is a full-stack flight booking web application that allows users to search, filter, and book flights seamlessly. The system provides secure authentication, flight search functionality, class-based filtering, online payment integration, and QR-based e-ticket generation.

🔄 Project Flow (Step-by-Step)
1️⃣ User Authentication (Sign In / Sign Up)
➤ Step 1: Registration

New users create an account using:

Full Name

Email ID

Password

Passwords are securely encrypted before storing in the database.

User data is stored in MongoDB.

➤ Step 2: Login

Registered users sign in using:

Email

Password

The system validates credentials.

Upon successful login:

A session or JWT token is generated.

User is redirected to the Flight Search Page.

2️⃣ Flight Search Module
➤ Step 3: Enter Travel Details

Users provide:

Source Airport

Destination Airport

Departure Date

Number of Passengers

➤ Step 4: Fetch Available Flights

Backend queries the database for matching flights.

Flights are displayed dynamically with:

Airline Name

Departure & Arrival Time

Duration

Price

Class Type

3️⃣ Flight Filtering System

Users can refine search results using filters:

➤ Price Filter

Sort flights:

Low to High

High to Low

➤ Class-Based Filter

Economy Class

Business Class

First Class

The frontend dynamically updates results without reloading the page.

4️⃣ Booking Process
➤ Step 5: Select Flight

User selects preferred flight.

System redirects to Passenger Details Page.

➤ Step 6: Enter Passenger Details

Full Name

Age

Gender

Passport Details

➤ Step 7: Fare Summary

Base Fare

Taxes

Total Amount

Booking confirmation preview

5️⃣ Online Payment Integration
➤ Step 8: Choose Payment Method

Supported payment modes:

UPI:Phone pay,Paytm

Credit Card

➤ Step 9: Payment Processing

Payment details are validated.

Transaction is processed securely.

Upon success:

Booking is confirmed.

Payment status is updated in the database.

6️⃣ QR-Based E-Ticket Generation
➤ Step 10: Ticket Generation

System generates:

Unique Booking ID

Flight Details

Passenger Details

Payment Confirmation

➤ Step 11: QR Code Creation

A unique QR code is generated for the ticket.

QR contains:

Booking ID

Flight ID

Passenger Info

➤ Step 12: Ticket Delivery

E-ticket displayed on screen.

Option to:

Download as PDF

Save as Image

Show QR during airport check-in

🛠️ Technical Workflow
Frontend

Built using React / Vite

Dynamic filtering and state management

Responsive UI design

Backend

Node.js & Express

REST API architecture

Authentication middleware

Database

MongoDB

Stores:

Users

Flights

Bookings

Payments

📊 System Architecture Flow

User → Authentication → Flight Search → Filter → Select Flight → Passenger Details → Payment → Ticket Generation → QR Code → Confirmation

🎯 Key Features

✔ Secure User Authentication
✔ Real-Time Flight Search
✔ Advanced Filtering
✔ Secure Online Payments
✔ QR-Based Digital Ticket
✔ Fully Responsive Design
