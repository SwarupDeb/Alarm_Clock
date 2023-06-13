# Alarm_Clock
Certainly! The "Alarm_Clock" project is a JavaScript-based web application that functions as a digital alarm clock. It allows users to set multiple alarms and provides an interactive interface for managing and displaying the alarms.

Here's an overview of how the project works:

User Interface:

The project has a user interface consisting of a clock display, a date display, an alarm form, and a list of alarms.
The clock display shows the current time, which is continuously updated using JavaScript functions.
The date display shows the current date, also updated in real-time.
The alarm form allows users to input the desired hours and minutes for setting a new alarm.
The list of alarms dynamically updates to display the set alarms, including their respective time and options to remove them.
Setting Alarms:

Users can set new alarms by entering the desired hours and minutes in the alarm form.
The setAlarm() function is called when the form is submitted, which retrieves the input values and validates them.
If the inputs are valid, a new alarm time is created and added to the list of alarms.
The new alarm time is appended to the alarms list using JavaScript DOM manipulation.
Managing Alarms:

The list of alarms is displayed on the webpage, showing the time of each alarm and an option to remove it.
Users can remove an alarm by clicking on the corresponding remove button, triggering a JavaScript function to delete the alarm from the list.
Alarm Functionality:

The application continuously compares the current time with the set alarm times.
When an alarm time matches the current time, the playAlarmSound() function is called.
The function plays an alarm sound using the HTML5 Audio element and gradually increases the volume.
It also displays a notification on the webpage using the Notification API, indicating the alarm time and providing a stop button.
Clicking the stop button stops the alarm sound and removes the notification.
Dark Mode:

The project includes a dark mode feature that can be toggled on or off.
Clicking on the dark mode toggle button triggers the toggleDarkMode() function.
The function adds or removes a CSS class from the body element, which changes the appearance of the webpage to a dark color scheme.
Overall, the "Alarm_Clock" project provides a user-friendly interface for setting, managing, and receiving notifications for multiple alarms, along with the option to switch to a dark mode theme.
