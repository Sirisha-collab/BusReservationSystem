# BusReservationSystem

Built using Code First (Entity Framework Core) in an ASP.NET Core MVC Web Application with Authentication, here’s a professional 5-line output flow for booking tickets with multiple payments:

1. User registers/logs in via ASP.NET Core Identity and selects route, date, and available seats.

2. System creates a Booking record (Code First EF Core) linked to the authenticated user.

3. User selects multiple payment methods (e.g., card, wallet, UPI) and system creates separate Payment entries mapped to the same booking.

4. Total payment validation ensures sum of all payments equals ticket fare before confirmation.

5. Upon successful transaction, booking status updates to Confirmed, and e-ticket is generated with booking reference ID.
