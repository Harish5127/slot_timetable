# Ex03 Time Table
## Date: 29/9/2025

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
```html
<html>
<head>
  <title>Slot Timetable</title>    
</head>
<body>
<center>
  <img src="slot_timetable/logo.png" height="100" width="540">
</center>
<br>

<table align="center" width="540" cellspacing="2" cellpadding="10" border="7" bgcolor="white">
<caption><b>SLOT TIME TABLE - HARISH R (212224230085)</b></caption>

<tr bgcolor="yellow" align="center">
  <th>Day/Time</th>
  <th>Monday</th>
  <th>Tuesday</th>
  <th>Wednesday</th>
  <th>Thursday</th>
  <th>Friday</th>
  <th>Saturday</th>
</tr>

<tr align="center">
  <th bgcolor="yellow">8-10</th>
  <td>FWAD</td>
  <td>BEEE</td>
  <td>FREE>
  <td>FREE</td>
  <td>FWAD</td>
  <td>FREE</td>
</tr>

<tr align="center">
  <th bgcolor="yellow">10-12</th>
  <td>INTRO TO DS</td>
  <td>DS</td>
  <td>ADVANCE C</td>
  <td>DBMS</td>
  <td>FREE SLOT</td>
  <td>FREE</td>
</tr>

<tr>
  <th bgcolor="yellow">12-1</th>
  <td colspan="6" align="center">LUNCH</td>
</tr>

<tr align="center">
  <th bgcolor="yellow">1-3</th>
  <td>BEEE</td>
  <td>FREE SLOT</td>
  <td>MENTOR</td>
  <td>FUND OF AI</td>
  <td>ADVANCE C</td>
  <td>FREE</td>
</tr>

<tr align="center">
  <th bgcolor="yellow">3-5</th>
  <td>FUND OF AI</td>
  <td>INTRO TO DS</td>
  <td>DBMS</td>
  <td>DS</td>
  <td>FREE</td>
  <td>FREE</td>
</tr>
</table>
<br>

<table align="center" cellspacing="2" cellpadding="5" border="2">
<tr align="center">
  <th>S.No.</th>
  <th>Subject Code</th>
  <th>Subject Name</th>
</tr>

<tr><td align="center">1.</td><td align="center">19AI414</td><td>Fundamentals of Web Application Development (FWAD)</td></tr>
<tr><td align="center">2.</td><td align="center">19AI403</td><td>Introduction to Data Science(IDS)</td></tr>
<tr><td align="center">3.</td><td align="center">19AI305</td><td>Advanced C Programming (C)</td></tr>
<tr><td align="center">4.</td><td align="center">19AI405</td><td>Fundamentals of Artificial Intelligence(FAI)</td></tr>
<tr><td align="center">5.</td><td align="center">19AI408</td><td>Data Structure(DS)</td></tr>
<tr><td align="center">7.</td><td align="center">19EE305</td><td>Basic Electrical, Electronics and Measurement Engineering (BEEE)</td></tr>
<tr><td align="center">9.</td><td align="center">19CS404</td><td>Database Management System and Its Application (DBMS)</td></tr>
</table>
</body>
</html>

```

## OUTPUT
C:\Users\admin\OneDrive\图片\Screenshots\Screenshot 2025-10-31 082443.png

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
