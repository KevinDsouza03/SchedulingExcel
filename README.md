# SchedulingExcel

Possible Solution:
- ~~Make an object for each employee which has attr(
	Availability #Yes and No column.
	Name
	Amount of Availability #Priority based on available hours )~~ 
- ~~Make schedule which has 4x shifts (3N and Library) per timeslot.~~
- Split rooms into 2 rows for inputting names for shifts.
- Create structure to check for least available employee, then input them into the schedule accordingly.
	- Select a timeslot 
	- Check which employee is available (Yes)
	- Order by Priority
	- Select based on least priority (whoever has the least availablity). 
	- No duplicates allowed for a single timeslot. 
