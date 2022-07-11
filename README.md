Meet App

The Meet App is built as a serverless, progressive web application (PWA) with React using a test-driven development (TDD) technique. It is designed to display a list of upcoming events for a city and time of the user’s choosing, even while offline. 

Feature 2: Show/Hide an Event’s Details

As a user I should be able to view a list of events that I can select to expand and view details and collapse once I’m done viewing the details so that I can see more or less information depending on my preference.

Scenario 1: An event element is collapsed by default
•	Given a user is on the main page of the app
•	When no event is selected
•	Then the event details will be collapsed 

Scenario 2: User can expand an event to see its details 
•	Given the user wants to learn more about an event
•	When the user selects the event
•	Then the event expands to show the event details

Scenario 3: User can collapse an event to hide its details
•	Given the user wants to view another event
•	When the user selects the expanded event again
•	Then the event will collapse

Feature 3: Specify number of events

As a user, I should be able to view up to 32 events if I haven’t specified a number of events I want to see so that I have the option of improving my viewing experience.  

Scenario 1: When user hasn’t specified a number, 32 is the default number
•	Given the user has not specified the number of events they want to view
•	When the user selects a city to view its upcoming events
•	Then they should be able to view up to 32 events at a time

Scenario 2:  User can change the number of events they want to see
•	Given the user has found a city of interest in the app 
•	When the user selects the city
•	Then the number of events they see should be the same as the number specified by the user

Feature 4: Use the app when offline

As a user I should be able to access event information while offline

Scenario 1: Show cached data when there’s no internet connection
•	Given the app has no internet or data connection
•	When the user opens the app while it’s offline 
•	Then the user should be able to view the cached data in the app so that the user can still use the app offline

Scenario 2: Show error when user changes the settings (city, time range)
•	Given the app is offline 
•	When the user changes the settings of the app 
•	Then they should see an error message 

Feature 5: Data Visualization

As a user I should be able to view a chart with the number of upcoming events in each city so that I have an easy to comprehend visual to give me data quickly on cities with the most and least upcoming events

Scenario 1: Show a chart with the number of upcoming events in each city
•	Given the user is on the main page 
•	When they want to view upcoming events
•	Then they should be able to see a chart displaying the number of upcoming events in each city





