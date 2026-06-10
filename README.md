In the Badminton Club Attendance and Registration system, the main entities are:
User, Session, Racket, FridayApplication.
Associative entities:
Attendance, RacketAssignment, and GuestRacketReservation.
A User can have many Attendance records, and each Attendance record belongs to exactly one Session (1:M relationship). 
Club members may be assigned one club Racket permanently through RacketAssignment, creating an optional one-to-one relationship where a member can have zero or one assigned racket, and a racket can be assigned to zero or one member.
A Session can receive many FridayApplications from guests, and guests who need equipment may receive a temporary racket through GuestRacketReservation. 
Key attributes include identifiers such as user_id, session_id, and racket_id, while a derived attribute such as attendance_rate can be calculated from attendance records.
