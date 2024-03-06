# Notes: 
# 1. Use the following username and password to access the admin rights 
# username: admin
# password: password
# 2. Ensure you open the whole folder for this task in VS Code otherwise the 
# program will look in your root directory for the text files.
#Functionality extended to allow tasks to be editted, reports to be generated (generate reports to file), and statistics to be displayed (generate reports to screen.)
#Separated many bulky functions to separate tasks with attempts to decouple functions as much as possible without refactoring for OOP
#priority_fixes.txt and RequirementsParkingLot.txt added to give further details to the design of the application as well as the direction of future development.

#Statistics and Reports:
#Completed tasks are tasks that were marked completed regardless of whether they were overdue or not.
#Incomplete tasks are tasks that are marked as incomplete
#Overdue tasks are tasks that are marked incomplete and the due date has passed. Completed overdue tasks
#are not grouped with overdue tasks as they are completed tasks. 

#Task Note: The tasks do not define what "overdue" means, so my interpretation is past due and incomplete.

#Task Note: I tried to code the project as closely to the use cases of the tasks as possible to prevent
#scope creep. Example: va printing ovrdue tasks was not defined in the tasks so I would not have included that feature.

#Task Note: I did eliminated the the task_id unused variable, but I was unable to find the variables that were noted as being unused on lines 477 to 484.
#I added code before looking for them, so I'm not sure where they would be located now or what the variable names are.

#Task Note: I didn't put the log-in portion of the code in a function because the task didn't request that of me. I tried to follow the task
#requirements as closely as I could. TBH, I would have preferred to do all of this using OOP, but the task requested proceduaral programming instead.

#Task Note: Also, plese bear in mind that I turned this assignment in quite early on in the bootcamp. If the assignment details have been changed since, then
#I would not have been privvy to them as the changes would have likely been made after my submission in late December/ early January.
