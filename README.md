Build a small application that will allow the following:

It will be a directory containing users with the following info:
First name
Last Name
Address
Mail
Phone 

(There should be at least 10 users pre loaded on the application)
The app should have a search functionality that allows the user search by any of the parameters or combination of them.
It should display a table with the results of the search and should be sortable if there is more than one result.

Also, there should be a section that allow the registration of new users having the following validations:
All fields should be required, the first and last name can only contain alphabetic values, mail must have a valid email format, phone will only allow numeric characters and should be formatted as (###) ###-####.
In case of any validation being broken the user must get an error on the input and disable the submit button until corrections are made.

Make use of CSS or pre-compilers for design and user experience.
If possible apply material design.
After capturing a new user I should be able to search for him on the search functionality.
Mock http calls for the services of capture and search. (a loader between “calls” would help to indicate the process is in place)

This little project must be on git to be able to review it.
Notes or nice to have:
Unit testing with jasmine.
The project being done in angular 5 +.
