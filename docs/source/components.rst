Main Components
==================

These are the pages that make up the event app.

1. Start Page
----------------

The start page displays a button that allows the user to access the app. 

2. Login Page
----------------

The login page allows the user to login to the app. It consists of 2 text fields, in which the user can enter their email and password to login. The user can click on the `Sign Up` link to register for the app.

3. Register Page
----------------

The register page allows the user to register for the app. It consists of 3 text fields, in which the user can enter their name, email and password to register. Press the register button to complete registration. The user can click on the `Sign In` link to the login page after making an account.

4. User Mode Page
----------------

In this page the user can select whether to access the app as an event host or an attendee. Depending on which option is picked, the app will have different functionality. For example, hosts can create events but attendees can't.

5.Home Page
----------------

The home page is a central page that the user can navigate to all other pages from. It displays a list of events that are currently stored in the database in the 'Popular Events' section. There is a profile button which takes the user to the profile page, and a side navigation bar which has more pages.

Navigation Bar 
^^^^^^^^^^^^^^^

The navigation bar has the following options in host mode:
* `Switch User Mode <https://setap-documentation.readthedocs.io/en/latest/components.html#user-mode-page>`_
* `Create Events <https://setap-documentation.readthedocs.io/en/latest/components.html#id3>`_
* `Search Events <https://setap-documentation.readthedocs.io/en/latest/components.html#id4>`_
* Logout

The navigation bar has the following options in attendee mode:
* `Switch User Mode <https://setap-documentation.readthedocs.io/en/latest/components.html#user-mode-page>`_
* `Search Events <https://setap-documentation.readthedocs.io/en/latest/components.html#id4>`_
* `Book Events <https://setap-documentation.readthedocs.io/en/latest/components.html#id5>`_
* Logout

6. Profile Page
----------------

On the profile page, the user can view the events they have booked in the past, and a button which leads to a settings page is also available.


7. Create Events Page
----------------

The create events page allows the host to create an event. The host can enter their User ID, event name, date, time, location, description and the ticket price. The host can click the create event button to create the event. When adding the date, time and location, dialogs will appear to help the user input the correct information.

8. Search Events Page
----------------

The search events page allows the user to search for events. The user can enter a query in the search bar and the events matching the query in the search bar will dynamically appear on the screen. The user can search for events by name and by location.

9. Book Events Page
----------------

The book events page allows the user to book an event. The user can click the book event button to book the event after they have inputted the number of tickets they would like to purchase.

10. Your Events Page
----------------

The your events page allows the user to view the events they have booked in the past. They display in a list and display the total price if the user has booked multiple tickets.

11. Settings Page
----------------

The settings page allows the user to change their name, email and password. The user can enter their new name, email and password in the text fields and click the update button to update their information.

12. Payment Page
----------------

The payment page allows the user to pay for the tickets they have booked. The user can enter their card number, expiry date, CVV and name on card in the text fields and click the pay button to pay for the tickets. When the `Pay Now` button is clicked, a dialogue appears to confirm the payment, and then the user is redirected to the `Your Events page<>_.
