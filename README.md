# google-apps-for-education
Collection of different Google Apps Scripts focused on educational application. Code is far from perfect, but it works for me. Sorry for the complete lack of help or useful documentation - I'm an English teacher who has had to learn JS/GAS by necessity.

"Student Failure Reporter"
Takes a CSV output of student failure data and combines rows of the same student (e.g. if Johnny is failing 3 classes).

Output from PowerSchool (or other gradebook system) is a report of all students with grades below passing. It includes all the data on Sheet1, with two other blank sheets. The data has unwanted columns.

The script deletes all this - be sure to modify to match your report.

Example Input: https://docs.google.com/spreadsheets/d/1TqdVmB507eBNLuPynk2oAiDeT7L8hbBgiThDfZ-KUuY





"Calendar Color Changer"
Will search through your Google Calendar and change the color of events based on keywords you define. Edit the top section of the code block (between the comments) in order to customize.
