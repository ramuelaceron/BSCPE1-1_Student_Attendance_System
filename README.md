# BSCPE1-1_Student_Attendance_System
READ THIS!
Final Project for Object Oriented Programming Yr. 2024

A simple attendance system that corresponds to the schedule of BSCPE 1-1 in Second Semester.

Class Description
[Program.cs] - Main method - The entry point of the program that displayed the weekly list of scheduled subjects. The system will ask for the day (Wednesday, Thursday, Friday, Saturday) of the scheduled time. Users will enter their student numbers to check their attendance.
[Account.cs] - Student's number verification - This is where the user's credentials are stored which will be used by the system to check if the input student number is valid to proceed in the next step.
[Menu.cs] - This is where user options displays are being held - The student will input the subjects on the option based on their input day to proceed in the next step. 
[Attendance.cs] - The system will ask for the student’s arrival time following the subject they chose. The system will store the data inputted by the user to display their status. After the process of getting the arrival time is finished, the system will display the collected data and ask the users to display an overall report or attendance report. Additionally, the user’s input time corresponding to the subject will be thrown to a different class [Report.cs] for displaying results. 
[AttendanceFunction.cs] - The process of evaluating or comparing the student's arrival time to the scheduled time - Where the corresponding status (present, absent, and late) returns to [Attendance.cs] to display.
[Report.cs] - This is where the results or the Attendance Report are tabulated (System.data) using the collected data in [Attendance.cs]. 
[ReportFunction.cs] - The process in which the collected time data thrown by [Attendance.cs] will be evaluated into status again to be displayed in the [Report.cs].

