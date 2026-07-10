# Flight Management

Avio's flight management features allow virtual airlines to plan flights
with ease, straight from Discord and our advanced web dashboard. Easily
keep your passengers alerted with upcoming flights.

## Scheduling a Flight

1. Run `/flight-planner [flightID]` to create a draft flight
2. Head to the [dashboard](https://dashboard.aviobot.app) and log in with Discord
3. Navigate to **Flight Planner** in the sidebar
4. Enter your flight ID and click **Load Draft**
5. Fill in the flight details
6. Click **Save**, then **Publish to Discord**

!!! warning "Unique flight IDs"
    You cannot have multiple flights with the same flight ID. For example, `BA471m`.

### Accessing the Dashboard Flight Planner

!!! note "Permissions required"
    You need to be a **Trusted User** or **Flight Manager** on the dashboard
    to access the Flight Planner. See [Dashboard Settings](../dashboard-settings.md)
    for details on getting these roles.

### Filling in Details for a New Flight

Before you can fill in the flight details, you need to load your draft flight.

![New Flight](../images/avio-flight-new.png){ width="600" }
*The Flight Planner "load draft" screen*

Enter the flight ID you created earlier, then click **Load Draft**. You'll
be taken into the flight editor, where you can fill in the remaining fields.

Once everything looks right, click **Save**, then **Publish to Discord** —
your flight plan will be posted to your flights channel.



### Example:
/flight add BA249 2026-08-14

Avio will automatically pull departure time, gate, and status once available.

## Editing or Removing a Flight

| Command | Description |
|---------|-------------|
| `/flight edit` | Update an existing flight's details |
| `/flight remove` | Remove a flight from tracking |
| `/flight list` | Show all flights currently tracked |

!!! tip
    You can track flights up to 330 days in advance for most airlines.

## Status Notifications

Avio checks flight status periodically and will notify you automatically if:

- Departure gate changes
- Flight is delayed or cancelled
- Boarding has started

!!! note "Notification delivery"
    Notifications are sent to whichever channel or DM you configured in **Chat Settings**.
