userservice
------------
POST /api/v1/users/register

POST /api/v1/users/login

GET /api/v1/users/{id}

PUT /api/v1/users/{id}

DELETE /api/v1/users/{id}

movieservice
-------------
POST /api/v1/movies

GET /api/v1/movies

GET /api/v1/movies/{id}

PUT /api/v1/movies/{id}

DELETE /api/v1/movies/{id}

GET /api/v1/movies/search

Theatreservice
-----------------
POST /api/v1/theatres

GET /api/v1/theatres

GET /api/v1/theatres/{id}

POST /api/v1/screens

POST /api/v1/seats

showservice
------------
POST /api/v1/shows

GET /api/v1/shows

GET /api/v1/shows/{id}

GET /api/v1/shows/{id}/seats

PATCH /api/v1/shows/{id}/lock-seats

PATCH /api/v1/shows/{id}/release-seats

bookingservice
---------------
POST /api/v1/bookings

GET /api/v1/bookings/{id}

GET /api/v1/bookings/user/{userId}

DELETE /api/v1/bookings/{id}

paymentservice
--------------
POST /api/v1/payments

GET /api/v1/payments/{id}

POST /api/v1/payments/refund
