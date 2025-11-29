# Ex02 Time Table
## Date: 28-11-2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

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
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="lightgrey">
<caption><b>SLOT TIME TABLE - MADHU SHRUTHI.A.R (25008368)</b></caption>
<tr align="center">
<th bgcolor="#FFBDEA" style="color:black;">Day/Time</th>
<th bgcolor="#FFBDEA" style="color:black;">Monday</th>
<th bgcolor="#FFBDEA" style="color:black;">Tuesday</th>
<th bgcolor="#FFBDEA" style="color:black;">Wednesday</th>
<th bgcolor="#FFBDEA" style="color:black;">Thursday</th>
<th bgcolor="#FFBDEA" style="color:black;">Friday</th>
<th bgcolor="#FFBDEA" style="color:black;">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="#FFBDEA" style="color:black;">8-10</th>
<td bgcolor="#EBC9FD">ENG</td>
<td bgcolor="#EBC9FD">ENG</td>
<td bgcolor="#EBC9FD">FWAD</td>
<td bgcolor="#EBC9FD">C PROGRAM</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">FWAD</td>
</tr>
<tr align="center">
<th bgcolor="#FFBDEA" style="color:black;">10-12</th>
<td bgcolor="#EBC9FD">FWAD</td>
<td bgcolor="#EBC9FD">FWAD</td>
<td bgcolor="#EBC9FD">FWAD</td>
<td bgcolor="#EBC9FD">C PROGRAM</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">ENG</td>
</tr>
<tr>
<th bgcolor="#FFBDEA" style="color:black;">12-1</th>
<td colspan="6" align="center">LUNCH</td>
</tr>
<tr align="center">
<th bgcolor="#FFBDEA" style="color:black;">1-3</th>
<td bgcolor="#EBC9FD">C PROGRAM</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">MENTOR MEET</td>
<td bgcolor="#EBC9FD">ENG</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="#FFBDEA" style="color:black;">3-5</th>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">C PROGRAM</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">FREE SLOT</td>
<td bgcolor="#EBC9FD">C PROGRAM</td>
</tr>
</table>
<br>

<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th bgcolor="#EBC9FD" style="color:black;">S. No.</th>
<th bgcolor="#EBC9FD" style="color:black;">Subject Code</th>
<th bgcolor="#EBC9FD" style="color:black;">Subject Name</th>
</tr>
<tr>
<td align="center" bgcolor="#EBC9FD">1.</td>
<td align="center" bgcolor="#FFBDEA">19A1414</td>
<td bgcolor="#FFBDEA">FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center" bgcolor="#EBC9FD">2.</td>
<td align="center" bgcolor="#FFBDEA">19A1301</td>
<td bgcolor="#FFBDEA">FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
</tr>
<tr>
<td align="center" bgcolor="#EBC9FD">3.</td>
<td align="center" bgcolor="#FFBDEA">19EN101</td>
<td bgcolor="#FFBDEA">COMMUNICATIVE ENGLISH (ENG)</td>
</tr>
</table>
</body>
</html>

```


## OUTPUT
<img width="1897" height="1010" alt="image" src="https://github.com/user-attachments/assets/0dc32e72-916c-4642-9e78-06e809c5bb06" />




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
