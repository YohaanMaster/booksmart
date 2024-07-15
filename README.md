# booksmart


User Interface
- The system for choosing rooms should be graphical, where a user clicks on them on a virtual floorplan
- It should be simple for the user to access the status of all their bookings (approval, time, location), and they should be organised in one location
- There should be a pagination system for users to access the different pages in the website

Booking specifications
- There should be two types of bookings: one-time and recurring
- A booking can be in three stages: 
   - Pending (When a student submits it, and they are waiting for the booking to be approved)
   - Approved (When a booking has been recorded by the system)
   - Completed (For one-time bookings, or recurring bookings with a limited time period)
- If a room has already been booked by another user at a given time period, users will not be given the option to select that room in a booking. If they are doing a recurring booking, they will be informed that it will not be booked on the conflicting day

Room specifications
- Users should be able to select individual rooms, as well as an entire floor (in the case of large events)
- The school multi-purpose hall, as well as laboratories, should also be options for booking
- There will be discrete time periods during which any room can be booked, to make organisation easier
   - These time periods will likely be 45 minutes each, to match the timing of school periods

User Accounts
- Users will be divided into 3 categories:
   - Students, who need administrator approval for any bookings they make
   - Teachers, who can directly make bookings without administrator approval
   - Administrators, who can approve or deny requests from students, as well as view and cancel erraneous bookings. They should see all pending bookings in order of when they were sent.
- There should be a login and registration system for all users, with passwords in place for security reasons
