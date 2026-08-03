user
-------
id(long)
name
email(username)
password
createdAt
updatedAt
status

movie
------
id(long)
title
description
language
genre
certificate
releaseDate
posterUrl
durationMinutes
createdAt
updatedAt

theatre
---------
id(long)
name
city
address
latitude
longitude
createdAt

screen
-------
id(long)
theatre
screenName
screenType
capacity

seat
--------
id(long)
seatNo
screen
row
column
seatType

Show
------
id(long)
movieId
screenId
startTime
endTime
price
status

showSeat
--------
id(long)
seatId
showId
status
price

Booking
---------
id(long)
user
show
time
status
amount
paymentStatus

bookingSeat
--------
id(long)
bookingId
showSeatId
price

payment
-------
id(long)
bookingSeatId
amount
paymentMethod
status
transationId
createdAt


