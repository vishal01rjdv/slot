# Ex03 Time Table
## Date:02.12.2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - VISHAL R (25004464)</b></caption>
<tr align="center">
<th bgcolor="green">Day/Time</th>
<th bgcolor="green">Monday</th>
<th bgcolor="green">Tuesday</th>
<th bgcolor="green">Wednesday</th>
<th bgcolor="green">Thursday</th>
<th bgcolor="green">Friday</th>
<th bgcolor="green">Saturaday</th>
</tr>
<tr align="center">
<th bgcolor="green">8-10</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>FREE SLOT</td>
<td>INTRODUCTION TO MACHINE LEARNING</td>
</tr>
<tr align="center">
<th bgcolor="green">10-12</th>
<td>INTRODUCTION TO MACHINE LEARNING</td>
<td>INTRODUCTION TO MACHINE LEARNING</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
<tr>
<th bgcolor="green">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="green">1-3</th>
<td>INTRODUCTION TO MACHINE LEARNING</td>
<td>COMMUNICATIVE ENGLISH</td>
<td>MENTOR MEET</td>
<td>INTRODUCTION TO MACHINE LEARNING</td>
<td>FREE SLOT</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr align="center">
<th bgcolor="green">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI410</td>
<td>INTRODUCTION TO MACHINE LEARNING</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
```



## OUTPUT

<img width="1329" height="815" alt="Screenshot 2025-12-02 232429" src="https://github.com/user-attachments/assets/6e338744-4b21-4976-a9e3-68ed7e9702ff" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
