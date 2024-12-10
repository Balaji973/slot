# Ex03 Time Table
## Date: 8.10.2024

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
...
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 10px;
        }
        th, .time-column, .day-column {
            background-color: grey;
        }
        .slot {
            background-color: lightblue;
        }
        .subject-table th {
            background-color: lightgreen;
        }
        .subject-table td:nth-child(2) {
            background-color: orange;
        }
        td {
            text-align: center;
        }
        .subject-table th, .subject-table td {
            padding: 5px;
        }
    </style>
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>

<h1>Timetable-BALAJI.J</h1>
<table>
    <tr>
        <th class="time-column">Time</th>
        <th class="day-column">Monday</th>
        <th class="day-column">Tuesday</th>
        <th class="day-column">Wednesday</th>
        <th class="day-column">Thursday</th>
        <th class="day-column">Friday</th>
    </tr>
    <tr>
        <td class="time-column">8-10</td>
        <td class="slot">FWAD</td>
        <td class="slot">FWAD</td>
        <td class="slot">MAT</td>
        <td class="slot">PHY</td>
        <td class="slot">FWAD</td>
    </tr>
    <tr>
        <td class="time-column">10-12</td>
        <td class="slot">GER</td>
        <td class="slot">CHE</td>
        <td class="slot">GER</td>
        <td class="slot">CHE</td>
        <td class="slot">MAT</td>
    </tr>
    <tr>
        <td class="time-column">12-1</td>
        <td class="slot" colspan="5">Lunch</td>
    </tr>
    <tr>
        <td class="time-column">1-3</td>
        <td class="slot">PHY</td>
        <td class="slot">FWAD</td>
        <td class="slot">PHY</td>
        <td class="slot">SS</td>
        <td class="slot">GER</td>
    </tr>
    <tr>
        <td class="time-column">3-5</td>
        <td class="slot">CHE</td>
        <td class="slot">SS</td>
        <td class="slot">CHE</td>
        <td class="slot">PHY</td>
        <td class="slot">CHE</td>
    </tr>
</table>

<h2>Subject Codes and Names:</h2>
<table class="subject-table">
    <tr>
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
        <th>Abbreviation</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
        <td>FWAD</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19EN612</td>
        <td>German Basic</td>
        <td>GER</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19PH206</td>
        <td>Physics for Information Technology</td>
        <td>PHY</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19CY205</td>
        <td>Principles of Chemistry in Engineering</td>
        <td>CHE</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra</td>
        <td>MAT</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19EY701</td>
        <td>Soft Skills</td>
        <td>SS</td>
    </tr>
</table>

</body>
</html>

...

## OUTPUT

![alt text](<Screenshot 2024-12-10 134915.png>)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
