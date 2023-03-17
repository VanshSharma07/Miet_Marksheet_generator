# Miet_Marksheet_generator
This code is a C program that takes input from the user, calculates the total marks, percentage, and grade of a student, and outputs the result to a file named "reports.txt". The program uses a structure named "stu" to store the information of the student, including their name, section, department, roll number, marks in five subjects, and attendance percentage.

The program first opens the "reports.txt" file in append mode and uses the "fprintf" function to write the output to the file. It prompts the user to enter the required information using "printf" and "scanf" statements. The program then calculates the total marks and percentage of the student and uses a switch-case statement to provide three options to the user: 1) student result, 2) subject-wise performance, and 3) student attendance.

For the first option, the program uses the "fprintf" function to write the student's information, total marks, percentage, and grade to the "reports.txt" file based on their percentage. For the second option, it outputs the marks obtained in each subject to the file. For the third option, the program checks the student's attendance and writes a message to the file based on their attendance percentage.

The program uses appropriate comments to explain the purpose of each variable, function, and statement.
