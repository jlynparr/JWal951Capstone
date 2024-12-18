Android Version: Android 13.0 ("Tiramisu")/API 33
Link to git repository: 
https://gitlab.com/wgu-gitlab-environment/student-repos/jwal951/d308-mobile-application-development-android.git

Directions:

Home screen- Titled as "Trip Planner"; Under the greeting, the Home Screen allows you to navigate to the login page if you are a returning user and the create account page if you are a 
new user. It contains a dropdown menu that refreshes the current "Home" screen, a "Login" option to navigate to the "User Login" screen, and a "Create Account" button to navigate to the 
"Create Account" screen.

User Login- The "User Login" screen has two user inputs: "username" and "password"; and a log in button. If credentials are entered and valid, once clicking "Login", the user will be 
redirected to their custom vacation list on the "Vacation List" screen. If user does not have an existing account, they have the option to "Create a new account" which will redirect them 
to the "Create Account" screen. It contains a dropdown menu that navigates to the "Home" screen, a "Login" option to refresh the current page, and a "Create Account" button to navigate 
to the "Create Account" screen.

Create Account- The "Create Account" screen has three user inputs: "username", "password", and "confirm password". If the user enters all information, the username does not already exist, 
and both passwords match, the user can then click create account and login to their vacation list. If the username already exists, the user can navigate to the "User Login" screen from 
the "Go to login page" link. It contains a dropdown menu that navigates to the "Home" screen, a "Login" option to navigate to the "User Login" screen, and a "Create Account"
button to refresh the current "Create Account" screen.

Vacation List- The "Vacation List" screen allows you to add a new vacation by directing you to the "Vacation Details" screen; it also allows you to edit or delete a existing vacation. 
(The editing and existing section will be empty until the user adds their first vacation.) After a vacation has been created, the vacation title will display in a list under the 
"Choose A Vacation To Update Or Delete: " section of the "Vacation List" screen. These vacations are unique to each username. It contains a dropdown menu that refreshes the current 
"Home" screen which is the "Vacation List" when a user is logged in, a "Settings" option to delete the user's account, and a "Logout" button to logout of the user account and navigate 
back to the main activity screen.

Vacation Summary- The "Vacation Summary" screen allows the user to view the vacation title, hotel, start date, and end date; as well as a list of cards that display the associated 
excursions for each vacation, which show the excursion name and date. The user has multiple button options; the "Save Vacation" button saves all the updated info and navigates back to 
the "Vacation List" screen. The "Add Excursion" button as well as clicking on any excursion card, navigates to the "Excursion Details" screen. The "Edit Vacation" button takes the user 
to the "Vacation Details" screen and displays all the current vacations info which can be edited. The "Delete Vacation" button allows the user to delete that specific vacation from the 
database; users are unable to delete a vacation if it has associated excursions and will receive an error message. The "Cancel" button takes the user back to the "Vacation List" screen. 
This page also contains a sharing button, displayed using a download icon, under the cancel button which copies all the vacation details to the users clipboard. This screen also has a 
back arrow in the top left and the dropdown menu in the top right. The dropdown menu has the same "Home", "Settings", and "Logout" options as the vacation list screen.

Detailed vacation view- The "Vacation Details" screen allows the user to add, edit, or delete vacation info. The user has the ability to type input to give a vacation a title, hotel, start 
date and end date. When adding dates the user needs to input correct date format; for assistance in choosing a date, a pop up calendar can be used by double clicking on the input fields. 
Both the start and end dates have a notification switch that the user can toggle on to receive the notifications of the vacation beginning and/or ending; they can also leave it turned off. 
This screen also contains multiple buttons; the "Add Excursion" button navigates you to the "Excursion Details" screen to add a new excursion for this vacation (vacation input needs to be 
filled out before adding any excursions). The "Add/Save Vacation" button saves all current vacation info and takes you back to the "Vacation List" screen. The "Delete Vacation" button 
allows the user to delete the current vacation from the database. "Cancel" takes the user back to previous page. Once a vacation has an added excursion the excursion displays as a card in 
a list within "Vacation Details"; this card has an pencil icon which is an edit button that takes the user to that excursions "Excursion Details" page as well as a trash bin icon which will 
delete the associated excursion from the vacation. This screen also has a back arrow in the top left and the dropdown menu in the top right. The dropdown menu has the same "Home", 
"Settings", and "Logout" options as the vacation list screen.

Detailed excursion view- The "Excursion Details" page allows a user to add an excursion to their vacation. The user has the ability to edit input to name the excursion and choose an 
excursion date. When adding a date, by double clicking the input field, the user has the choice to use a pop up calendar to assist with date picking and inputting the correct date format. 
The user needs to choose a date that is between the vacation start date and end date (the vacation name and dates are provided at the top in case the user forgets the start and end dates). 
The date also has a notification switch that can be toggled on to receive a notification when the excursion is beginning; or can be left toggled off. This screen also contains multiple
buttons; the "Save/Update Excursion" button saves the excursion to the associated vacation where it is displayed under the vacation info of the "Vacation Summary" or "Vacation Details" 
screen. The "Delete Excursion" button deletes the current excursion from the database and navigates back to the vacation info. The "Cancel" button takes the user back to the previous 
screen. This screen also has a back arrow in the top left and the dropdown menu in the top right. The dropdown menu has the same "Home" "Settings", and "Logout" options as the vacation list 
screen. 
  
