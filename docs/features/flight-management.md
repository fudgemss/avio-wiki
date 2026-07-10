# Flight Management

Avio's flight management features allow virtual airlines to plan flights with ease, straight from Discord and our advanced web-dashboard. 
Easily keep your passengers alerted with upcoming flights.

## Scheduling a Flight

To schedule a flight, you first need to use the command `/flight-planner [flightID}`. Your flightID can be anything you'd like, for example BA471m. 
**Important:** You cannot have multiple flights with the same flightID.
Once you have created a draft flight, you will need to head to our dashboard. You can access it via the link https://dashboard.aviobot.app. You will need to login to Discord to access the dashboard.

### Accessing the Dashboard Flight Planner
To do this, you will need to be a **Trusted User** or a **Flight Manager** on the dashboard. Details on how to do this can be found in the **Dashboard Settings** page. 
Once you are on the dashboard, navigate to the **Flight Planner** page found on the sidebar.
In this section, you can fill in the details for a new flight, or edit an existing flight.

### Filling in Details for a new Flight
Before you can fill in the flight details, you need to load the draft flight.
The image below shows the section you will need to initially fill in.
![New Flight](../images/avio-flight-new.png)

The ID you will enter is the one you created in step one, when creating the draft flight.
Once you have entered the correct ID, simply click the **Load Draft** button.
After clicking that button, you will be in the flight editor for your draft flight.
Now all you need to do is fill in the different fields, click save, then publish to Discord!

If you have done everything correctly, your flight plan will be sent to your flights channel.



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
