# Ex04 Time Table
## Date: 19/10/2024

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/logo.png" height="100" width="540">
<table border="2" cellspacing="5" cellpading="5">
<caption>SLOT TIMETABLE - Dhivya Bharathi K (212221220010)</caption>
<tr>
<th bgcolor="pink">Day/Time</th>
<th bgcolor="pink">Monday</th>
<th bgcolor="pink">Tuesday</th>
<th bgcolor="pink">Wednesday</th>
<th bgcolor="pink">Thursday</th>
<th bgcolor="pink">Friday</th>
</tr>
<tr>
<td bgcolor="pink">8-10</td>
<td bgcolor="lightblue">Mern</td>
<td bgcolor="lightblue">Mern</td>
<td bgcolor="lightblue">FWD</td>
<td bgcolor="lightblue">Company</td>
<td bgcolor="lightblue">free</td>
</tr>
<tr>
<td bgcolor="pink">10-12</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">free</td>
<td bgcolor="lightblue">Prompt</td>
</tr>
<tr>
<td bgcolor="pink">12-1</td>
<td colspan="5" bgcolor="lightblue">----------------LUNCH TIME----------------</td>
</tr>
<tr>
<td bgcolor="pink">1-3</td>
<td bgcolor="lightblue">DAA/td>
<td bgcolor="lightblue">OS</td>
<td bgcolor="lightblue">Mentor</td>
<td bgcolor="lightblue">OS</td>
<td bgcolor="lightblue">free</td>
</tr>
<tr>
<td bgcolor="pink">3-5</td>
<td colspan="3" bgcolor="lightblue">free</td>
<td bgcolor="lightblue">OS</td>
<td bgcolor="lightblue">maths</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19CS402</td>
<td>Design Analysis of Algorithms</td>
</tr>
<tr>
<td>2.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement(FWAD)</td>
</tr>
<tr>
<td>3.</td>
<td>19CS545</td>
<td>Open Source Operating System</td>
</tr>
<tr>
<td>4.</td>
<td>19EY706</td>
<td>Company Specific</td>
<tr>
<td>5.</td>
<td>19TD608</td>
<td>Prompt Engineering</td>
</tr>
<tr>
<td>6.</td>
<td>19EE305</td>
<td>Basic Electrical Electronics and Measurement Engineering(BEEE)</td>
</tr>
<tr>
<td>7.</td>
<td>19EY702</td>
<td>Creative Skills for Communication(creative skills)</td>
</tr>
<tr>
<td>8.</td>
<td>19MA206</td>
<td>Logics and Cmobinatorics(maths)</td>
</tr>
</table>
</center>
</body>
</html>
```


## OUTPUT

![Screenshot (500)](https://github.com/user-attachments/assets/d772293f-a0ea-4bb9-812c-d9d1a097b856)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
