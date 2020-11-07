# attendanceMarker

## What this does? ##

![Image](https://img.techpowerup.org/201014/images634.jpg)

Once a session/ lecture is held using google meet you must first download the CSV file generated by @al-caughey 's browser extension.

link to browser extension - https://github.com/al-caughey/Google-Meet-Attendance

This attendance marker helps you to mark attendance as present/absent as 1 or 0 into an excel file that has a list of names of students in the class.

The key advantage is that you can mark the attendance of a class across all the days in which the classes were held for the same class so that it becomes easier for you to calculate the attendance of each student at the end of the term for checking how regular your students are.

## What must you do? ##


Note;

Downloaded CSV file is referred to as "Source file"

The excel file that has a column with the header "Name"(case sensitive) is referred to as destination file


In the destination folder, under the column "Name", the names of students in the class must be there.

Attendance will be appended as successive columns for each date for which the attendance is being marked.

The presence of any other columns (eg.Roll number of students) will not affect the functioning of the Attendance Marker.

Just run the .py file, first select file/folder .

### What is file option(feature 1)? ###

After you click on the "file" button, you will be prompted to select the downloaded file.

After you select the source file, you will be prompted to select the destination file.

Job Done!

Open the "destination file" to check the attendance.


### What is folder option(feature 2)? ###

To make the process easier it would be great to have all the source files that belong to the same class in one folder and only selecting this folder and the destination file.

This is done by selecting this option.

Select the source folder, then the destination file, and Done!

## Features ##

### Minimum time for attendance(feature3) ##

If a student attends the session for less than 20 minutes then, that student will be marked absent. (As most universities conduct at least 1 hour long sessions).

Note - If a student connects and disconnects multiple times the total duration of attendance(sum of each time the student was connected) would be considered.

### Wierd names in google account(feature4) ###

I have noticed some students have wrong names with Google account.

By wrong, I mean;

Real Name - Sushant

Name with Google Account - Sushant Sushant

***Name Repeated, separated by whitespace***


The attendance Marker considers the right name of the student if this is the case.



## How to Run ##

Install python, install pandas and then run Attendance Master trough cmd or by simply double-clicking on it.


Hope you like it.

Suggestions are welcome.

Thank you for your time.
