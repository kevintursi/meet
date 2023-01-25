# Meet App


## Basic Information


- This application is be built using React and the Test Driven Development technique. It fetches upcoming information about events through Google Calendar API.
- Users are able to use this application to see upcoming events in any city of their choosing. 
- Users will never have an excuse to be bored on a weekend (or weekday) night again after downloading the Meet app! From pottery classes to heavy metal rock concerts, Meet will give users every possible option in any given city they choose!


## Key Features


- Filter events by city.
- Show/hide event details.
- Specify number of events. 
- Use the app when offline. 
- Add an app shortcut to the home screen.
- View a chart showing the number of upcoming events by city.


## Feature Scenarios: 


### FEATURE TWO: SHOW/ HIDE AN EVENTS DETAILS


- Scenario One: An event element is collapsed 
- Given: An event and the information is accessible
When: A user initially sees the event
Then: The details of the event will be collapsed 


- Scenario Two: User can expand an event to see its details
- Given: An event and the information is accessible
When: A user clicks a button to open the further event details
Then: The details of the event will be shown to the user 


- Scenario Three: User can collapse an event to hide its details
- Given: An event and the information are expanded
When: A user clicks a button to minimize the event details shown
Then: The details of the event will revert to not being shown 


### FEATURE THREE: SPECIFY NUMBER OF EVENTS


- Scenario One: When user hasn’t specified a number, 32 is the default number
- Given: A user has not specified the number of events they’d like to see shown on the page
When: A user is using the application
Then: There will be at most 32 events shown 


- Scenario Two: User can change the number of events they want to see
- Given: A user has a specific number of events they’d like to see
When: A user is using the application
Then: Exactly that many events should be the maximum amount loaded on the users page. 


### FEATURE FOUR: USE THE APP WHEN OFFLINE


- Scenario One: Show cached data when there’s no internet connection
- Given: A user has used the application before with an internet connection
When: They have no internet connection
Then: The app should load cached data from previous times the user has used the app


- Scenario Two: Show error when user changes the settings (city, time range)
- Given: A user has no internet connection
When: A user tries to change the settings on the app
Then: An error message will show letting the user know it has no internet connection and cannot process these changes



### FEATURE FIVE: DATA VISUALIZATION


- Scenario One: Show a chart with the number of upcoming events in each city.
- Given: There are events found for every city
When: A user searches for a city on the app
Then: A user will see a chart visualizing the number of upcoming events in that city



## USER STORIES

- As a user,
I should be able to both show and hide any events details
So that I can expand and see further details of events I am interested in, and hide details of events I am not interested in.


- As a user,
I should be able to specify the number of events shown to me
So that I can choose the exact amount of events I’d like to see


- As a user,
I should be able to use the app when offline
So that I can use the app even if I do not have WiFi or an internet connection


- As a user,
I should be able to see a chart that visualizes the number of upcoming events in any city
So that I can visualize the amount of events happening in any city in a moment