# Ex03 Time Table
## Date: 13|3|25
Name: Abhishek kannan M
Reg no: 24901047
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
<img src="C:\Users\admin\OneDrive\Pictures\Screenshots\logo.png"height="160" width="900">
</center>
<br>
<table align="center" width="700" cellspacing="3" cellpadding="2" border="3" bgcolor="green">
<caption><b>SLOT TIME TABLE - Abhishek kannan M (21222404007)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="green">8-10</th>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
<td>Python progrmming</td>
<td>FREE SLOT</td>
<td>operating system</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="green">10-12</th>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
<td>operating system</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="green">12-1</th>
<td colspan="7" align="center"> B R E A K   T I M E</td>
</tr>
<tr align="center">
<th bgcolor="green">1-3</th>
<td>Python programming</td>
<td>Physics for quantum computing</td>
<td>Physics for qauntum computing</td>
<td>Fundamentals of Web Application Development</td>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="green">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>Mathematics for Artificial Intelligence</td>
</tr>
</table>
<br>
<table align="center" cellspacing="3" cellpadding="1" border="3">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center"><b><font color = lightblue>19AI414</font></b></td>
<td><b><font color = blue>Fundamentals of Web Application Development(FWAD)</font></b></td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center"><b><font color = lightblue>19AI301</font></b></td>
<td><b><font color = blue>Python Programming(Python)</font></b></td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center"><b><font color = lightblue>19CS406</font></b></td>
<td><b><font color = blue>operating system(os)</font></b></td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center"><b><font color = lightblue>19MA220</font></b></td>
<td><b><font color = blue>Mathematics for Artificial Intelligence(MATHS)</font></b></td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center"><b><font color = lightblue>19PH214</font></b></td>
<td><b><font color = blue>Physics for quantum computing(PQC)</font></b></td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![Screenshot (278)](https://github.com/user-attachments/assets/9ff6185a-d297-4a80-b4e9-ab348b800511)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
