<p align="center">
  <img alt="HackUPC 2018" src="src/images/hackupc-ogimage@2x.png" width="100%"/>
</p>

# Campus Nord (UPC) paths and signs generator
Using a self-created map of the Campus Nord (UPC) where HackUPC is held, it computes the shortest path from a given place to another. Furthermore, it automatically creates a JSON with the signs content to be put on each point so hackers don't get lost. Just tell the system which points do you want to put a sign on and where should they give indications to and it will generate them for you.

##Requirements
It's just a C++ program, so you'll need just any compiler, GCC is okay. Be aware that it uses some C++11 functions and so you'll need at least this version of C++.

##Usage
Change the `placesSigns` function and add any points where you would like to put signs on, you can also follow this ID with all the codes of the places you want them to be on the sign. Compile, run and there you go, a ready to be converted JSON!

###Codes reference
| Code          | Text displayed      |
| ------------- | ------------------- |
| CA            | Cafeteria           |
| ID            | Info-Desk           |
| BC            | Baggage Check-in    |
| HL            | Hardware Lab        |
| T1            | Talk Room 1         |
| T2            | Talk Room 2         |
| TR            | Talk Rooms          |
| ME            | Meals               |
| SH            | Showers             |
| AU            | Auditorium          |
| MB            | Men Bathroom        |
| WB            | Women Bathroom      |
| SR            | Sleeping Rooms      |
| HR            | Hacker Rooms        |