# Ex03 Time Table
## Date: 25/03.2024

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
```<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\admin\OneDrive\Dokumen\WhatsApp Image 2024-03-25 at 08.10.39_6aa2864b.jpg" height="100" width="500">
</center>
<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="lightblue">
<caption><b>SLOT TIME TABLE - DILIP SANJAY M (23014243)</b></caption>
<tr align="center">
<th bgcolor="cyan">Day/Time</th>
<th bgcolor="cyan">Monday</th>
<th bgcolor="cyan">Tuesday</th>
<th bgcolor="cyan">Wednesday</th>
<th bgcolor="cyan">Thursday</th>
<th bgcolor="cyan">Friday</th>
<th bgcolor="cyan">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="aqua">8-10</th>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
<td>Python progrmming</td>
<td>FREE SLOT</td>
<td>Computer Networks</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="aqua">10-12</th>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
<td>Computer Networks</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="aqua">12-1</th>
<td colspan="6" align="center">L U N C H  B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="aqua">1-3</th>
<td>Python programming</td>
<td>Physics for quantum computing</td>
<td>Physics for qauntum computing</td>
<td>Fundamentals of Web Application Development</td>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="aqua">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>Python Programming(Python)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer Networks(CN)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19MA220</td>
<td>Mathematics for Artificial Intelligence(MATHS)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19PH214</td>
<td>Physics for quantum computing(PQC)</td>
</tr>
</table>
</body>
</html>

```

## OUTPUT
![image](https://github.com/dilipsanjay/slot/assets/155506948/6cbfac02-51ef-49a8-8295-c1220eb2398c)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
