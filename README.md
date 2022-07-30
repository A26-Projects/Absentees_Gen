# Absentees_Gen
This is an absentees generator for online meetings/classes using G-Meet.
Replace the array in the code with a list of the people who are supposed to attend the Meet, paste the code snippet into the correct file and run.

Please read the following instructions

This is a manual for the program "Fabsentees"
It explains how the code works and what the program does

Instructions to generate a list of absentees:

1) In the google meet tab, use the 'Inspect' option to see the code behind the People List.
2) Navigate to the element that contains the People List.
3) This element wil contain the names of all the students who are present.
4) Copy this HTML code and paste it in the "Absentees_inspect.html" file in the same folder as this file.
5) Save the file and run the python code.
6) The code will prompt you to enter the name of the current period.
7) After entering the name, it will print the absentees list along with the date, class and number of absentees.

Note: This is stil a prototype and can be further improved in many ways.

How the code works:

1) There is a Class List of my class in the program.
2) The code reads the file with the G Meet code.
3) It then loops through each element (or name) in the class list and checks if that particular name is 
in the G Meet code.
4) If the name is not present, it adds that particular name to an array of absentees.
5) After this it prints out the list with some other details.

I have attached the Python code, the file for the G Meet code and a PDF on how the program works along 
with this text file in the same folder.

I hope you liked this project and found it interesting.

Thank you,

Necrolin.
