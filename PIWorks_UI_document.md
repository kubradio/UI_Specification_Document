User Interface Specification 
Overview
The user interface specification document allows administrators to view and manage users within the system. 
This includes viewing users that already saved, adding new users, hiding disabled users, sorting saved users 
with respect to their ID (according to their registeration order starting from 1 and increasing by 1 each time) , User Name, Email or Enabled informations.

Requirements
New User : Users can add themselves by clicking on the new user button and filling the informations on the pop-up new user form 
form like Username, Display Name, Phone, Email, User Roles(can be selected by user as one of the Guest, Admin or 
SuperAdmin choices), and Enabled (there is an empty box, if enabled button clicked then enabled information is become true.).
View Users: The screen should display a list of all users currently registered in the system like monitoring their ID, 
User Name, Email, and Enabled informations.
Sorting Users: Users should be able to sort for registered users ID, User Name, Email, and Enabled informations.
Hide Disabled User: Hide Disabled User button when it clicked it hides the disabled registered users.

UI Components

New User 
New User Button: Button for adding the new user.
New User Form
User Name: Text input field for the user's username.
Display Name: Text input field for the user's display name.
Phone: Text input field for the user's phone number.
Email: Text input field the user's email.
User Roles: Selecting user role among the Guest, Admin or SuperAdmin options.
Enabled:Button, if it's clicked means enabled.
Save Button: Button to save the user information.

View User
Table: Displaying a list of users with columns for ID, User Name, Email, and Enabled.

Sorting Users
Filters in the table.
by their ID: sorts ID number with either ascending or descending order.
by their User Name: sorts with alphaneumeritical order.
by their Email: sorts with alphaneumeritical order.
by their Enabled information: sorts whether it is true or false.

Hide Disabled User
Hide Disabled User Button: When it clicked it hides the disabled registered users.

Behavior
When the page is loaded, it should display a list of all users.
Users can add a new user by clicking on new user button and filling out the pop-up new user form and clicking the save button.
Users can sort for users by clicking the arrows next to their ID, User Name, Email, and Enabled informations.

Initial View
Upon initial loading of the page, the screen should display a list of all users currently registered in the system, with New User Button, 
and Hide Disabled User button.
