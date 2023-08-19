# compose-multiscreen-flowapi
Crud operations using room and observing data with Flow API in single activity multi-screen android application

This is the third assignment from Rajesh Hadiya's Master Android Development Course. 

REQUIREMENTS : 

1. There are total 3 screens, Screen A, B, and C.
2. Add a top bar with title "UserDirectory" on all screens (and appropriate navigation
icons wherever required)
3. Add a top bar with title "UserDirectory" on all screens (and appropriate navigation
icons wherever required)
4. Create a randomly generated list of 5 users (Refer assignment 2 for more info)
5. When app is open, show screen A with a button "Add all users". Upon clicking on this
button, add generated users to local room database.
6. If the users are added, show screen B, otherwise show screen A on app opening.
(Hint: use DataStore)
7. On screen B, show a list of all users from database. Also, add one button "Click here
to add user". Upon clicking on that button, randomly generate one user and add it to
the database.
8. When the database is updated (i.e., new user is added) your list should automatically
update in the UI (Hint: use Observable read)
9. Upon clicking on any user item on Screen B, it should navigate to Screen C. (Hint:
Pass userId as a navigation argument to Screen C and retrieve data there. You may
use `withArgs` function provided in our sample repo or use your own solution.
10. Screen C should show the user details of which we clicked in Screen B. Handle back
button in the TopBar as well.
11. You must use Jetpack Compose to build the UI.
