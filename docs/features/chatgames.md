# Chat Games

Avio Bot has a variety of different chat games users can participate in. With leaderboards to climb, and miles to earn (if enabled by the server), our chat games provide endless fun.

## Enabling Chat Games
By default, all chat games are disabled, but they can be easily enabled. 
There are a few ways to enable chat games.

### In your server
1. Run `/chatgames enable`. 

This will enable **ALL** chat games in your server.

### On the dashboard
The dashboard is the best way to enable chat games, as you can pick which ones are enabled/disabled.

1. Head to the [dashboard](https://dashboard.aviobot.app) and log in with Discord
2. Select the **Chat Games** tab on the sidebar
3. Enable/Disable the chat games to your liking.

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
