RADISSON SHUTTLE BUS — additional timetable update (2026-11-18)

Based on shuttle_bus-main (2).zip. No old trips or destinations have been removed.

Boat Avenue / Le Phang Beach (shared seat pool, unchanged):
  Outbound: 10:00, 12:00, 14:00, 15:00, 16:00, 17:00, 18:00
  Return (Boat Avenue pickup): 10:30, 12:30, 14:30, 15:30, 16:30, 17:30, 18:30
  Le Phang return pickups continue to be 15 minutes after the route's base return time.

Banana Beach:
  Outbound: 11:00, 13:00, 14:00, 15:00, 17:00, 18:00
  Return: 13:30, 14:30, 15:30, 17:30, 18:30
  Note: no 11:30 return was added for outbound 11:00.

Layan Beach: unchanged.
Legacy bookings, Firebase configuration, collections, document ID formula and capacity: unchanged.

DEPLOYMENT: Back up the current GitHub Pages index.html; upload the new index.html
in the repository root. The archive is packaged with shuttle_bus-main/index.html.
This package has NOT been deployed to GitHub or Firebase.

CHECK BEFORE PRODUCTION: Test live Firebase connectivity, booking/cancellation,
seat counters and vehicle availability; local/static checks alone cannot verify
remote Firebase rules or actual van availability.
