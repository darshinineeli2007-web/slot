# Ex03 Time Table
## Date:09.12.2025

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
<<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="sample.jpg" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
I<caption><b>SLOT TIME TABLE NEELI DARSHINI (25004961)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">wednesday</th>
<th bgcolor="yellow">thrusday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td >FREE SLOT</td>
<td>FWEB</td>
<td>FWEB</td>
<td>C LANG</td> 
<td>C LANG</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>ENGLISH</td>
<td>FREE SLOT</td>
<td>C LANG</td>
<td>FREE SLOT</td>
<td>ENGLISH</td>
<td>ENGLISH</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="6" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>FWEB</td>
<td>FREE SLOT</td>
<td>MENTOR</td>
<td>FWEB</td>
<td>C LANG</td>
<td>ENGLISH <d>
</tr>
<tr align="/tcenter">
<th bgcolor="yellow">3-5</th>
<td >C LANG</td>
<td>FWEB</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2"> 
<tr align="center">
<th>S.No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td>COMMUNICATIVE ENGLISH</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">ECA-M</td>
<td>MENTOR MEET</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
<img width="1110" height="812" alt="Screenshot 2025-12-09 172245" src="https://github.com/user-attachments/assets/ca7470ef-ab0b-4953-87e6-460bf0212e47" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
