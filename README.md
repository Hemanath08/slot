# Ex03 Time Table
## Date:
03.04.2024
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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Semester Timetable</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Slot Timetable K.Hemanath 212223100012</h1>
  <table>
    <thead>
      <tr>
        <th rowspan="2">Time</th>
        <th colspan="6">Days</th>
      </tr>
      <tr>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
        <th>Saturday</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>8:00 AM - 10:00 AM</td>
        <td>Fundamentals OF web Application And Development</td>
        <td>-</td>
        <td>Cyber Law And Compliance</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
     </tr>
      <tr>
        <td>10:00 AM - 12:00 PM</td>
        <td>-</td>
        <td>Computer Networks</td>
        <td>-</td> 
        <td>Computer Networks</td>
        <td>-</td>
        <td>Python With Linear Algebra</td>
      </tr>
      <tr>
        <td>1:00 PM - 3:00 PM</td>
        <td>Engineering Mechanics And Product Development</td>
        <td>Python With Linear Algebra</td>
        <td>Creative Skills For Communication</td>
        <td>Python With Linear Algebra</td>
        <td>Python With Linear Algebra</td>
        <td>Engineering Mechanics And Product Development</td>
      </tr>
      <tr>
        <td>3:00 PM - 5:00PM</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>Fundamentals OF web Application And Development</td>
        <td>Cyber Law And Compliance</td>
        <td>Fundamentals OF web Application And Development</td>
      </tr>
      </tbody>
  </table>
</body>
</html>

## OUTPUT
![alt text](<Output 1.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.


[def]: <Output 1.png>