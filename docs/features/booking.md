# Booking

Search and book flights without leaving chat.

## Searching for Flights
/book search LHR JFK 2026-09-01

This searches for flights from London Heathrow to JFK on the given date.
Results are shown with airline, price, and duration.

## Completing a Booking

1. Run a search using `/book search`
2. Select a result using its listed reference number
3. Confirm passenger details
4. Complete payment via the secure link Avio provides

!!! warning
    Booking confirmations are time-limited. If payment isn't completed within
    15 minutes, you'll need to search again as prices may have changed.

## Managing Existing Bookings

| Command | Description |
|---------|-------------|
| `/book list` | View your active bookings |
| `/book cancel` | Cancel a booking (subject to airline policy) |
| `/book receipt` | Resend a booking confirmation |

---

Need help with a booking issue? See [Chat Settings](chat-settings.md) to set up a support channel.
