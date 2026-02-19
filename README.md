# collectorsedition
Version: Android 16 API 36.1 (Medium Phone)
Title: Collector's Edition

Page Details: 
Welcome page:
The first page is the welcome page. This is a simple login screen. If you do not have any login info, click the registration button. 
If and when you do have credentials, enter them into their respective fields then click the login button.
Leads to: 
VacationList
RegistrationPage

RegistrationPage:
There are two interactive EditTexts to set a username and password. The username must be unique and the password must be at least eight characters long. 
Once the register button is selected in this page, these restrictions are checked
and saved in the database if passed. Otherwise, the user is prompted to make any necessary corrections. 
Leads to:
The login screen

VacationList: 
This page is titled "Vacations" at the top of the screen. 
It will start out empty, but as vacations are added the titles of added vacations will be listed vertically along the left of the screen.
There is a three dot menu at the top and right of the screen. This can be used to add sample data with vacations and excursions to the database. 
At the bottom-right of this page there is a plus sign floating action button. Clicking this will take the user to a page where a new vacation can be added. 
If vacations are already added, they will appear listed along the left of the screen and the user can tap on the vacation's title name to be taken to its detail screen.
At the bottom-left of this page there is a button labeled, "Search" that allows the user to search all vacation start dates within a selected range.
Leads to:
VacationDetails
SearchReport

SearchReport:
This page is titled "Search Report" at the top of the screen.
There two fields along the top-right of the screen for selecting a start and end date. 
If either field is empty or the start date is after the end date, the user will be prompted to make the necessary corrections.
Tapping on the Search button on this screen will present a vacation name, start date, and end date for each vacation that starts within the selected date range. 
If there are no vacations within the range, then a message will appear to let the user know.

VacationDetails:
If directed here from the plus button, then the page will only have prompts and empty form fields. 
Along the left will be prompts for the Title, Lodging, Start Date, and End Date. Along the right the corresponding details can be typed in or selected. 
The three dot menu at the top and right of the screen can be used to select "Save Changes" to save the new vacation to the database.
However, if the dates are not correctly formatted or the end date is before the start date, then the changes will not be saved and the user will be prompted to make any necessary changes.
The user will then be redirected to the VacationList Screen.
If a vacation was selected from the previous screen, VacationList, then this screen will autopopulate with details about the selected vacation 
These details can be edited simply by tapping on the detail field for each item along the right of the screen 
Any changes can be saved using the three dot menu at the top and right of the screen by selecting "Save Changes"
As with adding a new vacation, the user will be prompted to fix incorrectly formatted dates and out of order date ranges before any data can be saved. 
Additionally, as long as the dates are entered correctly, the user can select from the same three dot menu, "Notify Start Date" and "Notify End Date" to receive a notification that the vacation is starting or ending on the selected dates. 
If there are no excursions associated with the vacation, then within that same three dot menu, the vacation can be deleted from the database by selecting "Delete Vacation"
The "Delete Vacation" menu option will not delete any vacations that have associated excursions.
If the vacation has excursions already associated with it, then those excursions will be listed by title below the blue form and along the left side of the screen.
New excursions can be added using the plus sign, floating action button at the bottom, right of the screen. 
However, if an existing excursion needs to be edited, then simply tapping on its title name will direct the user to the excursion's detail page. 
Finally, if all details and excursions are satisfactory, then tapping the three dot menu at the top right of the screen and selecting "Share" will allow the user to share their vacation and all of its details on social media.
Leads to:
ExcursionDetails

ExcursionDetails:
The left side of the screen will have prompts for the excursions' title, vacation start and end date, and the excursion's date. 
The vacation start and end dates cannot be altered on this page, they are here to remind the user, so that the excursion date can be set within them. 
Along the right of the form the user can edit or set the excursion's title and date. 
Using the three dot menu at the top and right of the screen, the user can save changes, delete the excursion, set an alert or share the excursion.
"Save Changes" will save any changes made to the excursion.  
If the excursion date is not formatted correctly or if the excursion date is outside the vacation date range, the changes will not save and the user will be prompted to make any necessary changes. 
Upon saving, the user will be redirected to the VacationDetails page.
"Delete Excursion" will delete the excursion from the database and remove it from the vacation it was associated with. 
"Notify" will tell the phone to send a notification on the date selected. 
"Share" allows the user to share the excursion using social media.
Leads to: 
VacationDetails
