# Booking Flights

Included in Avio's flight management is the ability for server members to book a seat on one
of your scheduled flights.

## Booking a Flight
There are multiple ways to book a flight.

### Server Member
1. Run `/book-flight [flightID]` and select a seat if you wish to
2. Seat successfully booked

If the flight has no more seats left, you will be given an error message.

### Server Admin
If a user is having issues booking a flight, server admins can manually book them a place.

1. Run `/bookings-admin force-book [user] [flightId] [seat_[pref]` and fill in the required details
2. Run `/bookings-admin list [user]` to see what flights they are currently booked on
3. User successfully forced booked on a flight

### Flights Site (NOT YET RELEASED)
Avio also has a web-based booking system which allows users to have a more realistic booking experience.
This feature is currently being developed and is not yet released.

!!! warning "Multiple Bookings"
    Server members can only have **one** booking per flight, per account.
    To change a booking, you will need to remove any existing bookings.

## Removing a Booking
If you are no longer able to attend a flight, or wish to edit your booking, 
you can remove any existing booking made.

1. Run `/remove-booking [flightID]` and fill in the flight ID
2. Confirm the cancellation
3. Booking successfully removed

Once a booking has been removed, it can no longer be recovered and
will have to be remade.

!!! note "View Bookins"
    You can view all bookings you have currently made using `/bookings`.

    Server admins can view all bookings for each scheduled flight on the
    [dashboard](https://dashboard.aviobot.app) under the **Bookings** tab.


## Status Notifications

15 minutes before a flight you are booked on, Avio will ping you in a message 
stating that boarding will beging soon.

!!! note "Notification delivery"
    Notifications are sent to whichever channel configured in your **Server Setup**.

--- 
