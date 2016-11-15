# Port-Schedule
This is a simple Python application that reads a csv and moves it to google calender

The csv contains the Action, Length of time it will take, Start time, and End time from each action

It is edited as follows in a spreadsheet editor and is exported as a csv
```
Action	 Length: hours      Start	 End
Start	   01:00	       07:00 AM	 08:00 AM
Break	   00:07	       08:00 AM	 08:07 AM
Eat/Go 	   01:00	       08:07 AM	 08:30 AM
Break	   00:25	       08:30 AM  08:55 AM
```


From these lines it appends the action to the user's google calendar
