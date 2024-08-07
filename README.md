# SchedulingExcel

Possible Solution:
- ~~Make an object for each employee which has attr(
	Availability #Yes and No column.
	Name
	Amount of Availability #Priority based on available hours )~~ 
- ~~Make schedule which has 4x shifts (3N and Library) per timeslot.~~
- Split rooms into 2 rows for inputting names for shifts.
- Create structure to check for least available employee, then input them into the schedule accordingly.
	- ~~Select a timeslot ~~
	- Check which employee is available (Yes)
	- Order by Priority
	- Select based on least priority (whoever has the least availablity). 
	- No duplicates allowed for a single timeslot. 


Current:

I want to make an autoscheduler in VBA. I  have a sheet named "ScheduleTemp",which is an already formatted template for the autoscheduling part of this project. In column C, starting at row 2, are where I need to automate the inputting of names. Column C has no values and extends all the way to the bottom of the table. I want to do this by
	- Selecting a timeslot 
	- Check which employee is available by checking the Priority variable of their availability object
	- Order by the priority variable in the class.
	- Select based on least priority.
	- No duplicates allowed for a single timeslot.
	- There are 4 shifts per timeslot.


