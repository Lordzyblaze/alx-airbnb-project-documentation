Detailed Requirement Specifications
User Authentication
Overview:
This feature handles user registration, login, and session management to ensure secure and authenticated access to the application.

API Endpoints:

POST /api/auth/register

POST /api/auth/login

GET /api/auth/profile

2. Property Management
Overview:
This feature allows hosts to create, update, and delete property listings.

POST /api/properties

PUT /api/properties/{propertyId}

DELETE /api/properties/{propertyId}

3. Booking System
Overview:
Allows guests to book properties, manage bookings, and prevent double bookings.


POST /api/bookings

PUT /api/bookings/{bookingId}/cancel

GET /api/bookings/{guestId}