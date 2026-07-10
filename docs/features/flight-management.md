# Flight Management

Track, update, and manage flights directly through Avio.

## Adding a Flight

Use the `/flight add` command followed by your flight number and date:

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
