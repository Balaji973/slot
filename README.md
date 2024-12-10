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
</head>
<body>
    <center>
        <img src="/static/logo.png" height="100" width="540">
    </center>

<h1>Timetable-BALAJI.J</h1>
<table border="1" cellpadding="10" style="border-collapse: collapse;">
    <tr>
        <th style="background-color: grey;">Time</th>
        <th style="background-color: grey;">Monday</th>
        <th style="background-color: grey;">Tuesday</th>
        <th style="background-color: grey;">Wednesday</th>
        <th style="background-color: grey;">Thursday</th>
        <th style="background-color: grey;">Friday</th>
    </tr>
    <tr>
        <td style="background-color: grey;">8-10</td>
        <td style="background-color: lightblue;">FWAD</td>
        <td style="background-color: lightblue;">FWAD</td>
        <td style="background-color: lightblue;">MAT</td>
        <td style="background-color: lightblue;">PHY</td>
        <td style="background-color: lightblue;">FWAD</td>
    </tr>
    <tr>
        <td style="background-color: grey;">10-12</td>
        <td style="background-color: lightblue;">GER</td>
        <td style="background-color: lightblue;">CHE</td>
        <td style="background-color: lightblue;">GER</td>
        <td style="background-color: lightblue;">CHE</td>
        <td style="background-color: lightblue;">MAT</td>
    </tr>
    <tr>
        <td style="background-color: grey;">12-1</td>
        <td style="background-color: lightblue;" colspan="5">Lunch</td>
    </tr>
    <tr>
        <td style="background-color: grey;">1-3</td>
        <td style="background-color: lightblue;">PHY</td>
        <td style="background-color: lightblue;">FWAD</td>
        <td style="background-color: lightblue;">PHY</td>
        <td style="background-color: lightblue;">SS</td>
        <td style="background-color: lightblue;">GER</td>
    </tr>
    <tr>
        <td style="background-color: grey;">3-5</td>
        <td style="background-color: lightblue;">CHE</td>
        <td style="background-color: lightblue;">SS</td>
        <td style="background-color: lightblue;">CHE</td>
        <td style="background-color: lightblue;">PHY</td>
        <td style="background-color: lightblue;">CHE</td>
    </tr>
</table>

<h2>Subject Codes and Names:</h2>
<table border="1" cellpadding="5" style="border-collapse: collapse;">
    <tr>
        <th style="background-color: lightgreen;">S.No</th>
        <th>Subject Code</th>
        <th style="background-color: orange;">Subject Name</th>
        <th>Abbreviation</th>
    </tr>
    <tr>
        <td style="background-color: lightgreen;">1</td>
        <td>19AI414</td>
        <td style="background-color: orange;">Fundamentals of Web Application Development</td>
        <td>FWAD</td>
    </tr>
    <tr>
        <td style="background-color: lightgreen;">2</td>
        <td>19EN612</td>
        <td style="background-color: orange;">German Basic</td>
        <td>GER</td>
    </tr>
    <tr>
        <td style="background-color: lightgreen;">3</td>
        <td>19PH206</td>
        <td style="background-color: orange;">Physics for Information Technology</td>
        <td>PHY</td>
    </tr>
    <tr>
        <td style="background-color: lightgreen;">4</td>
        <td>19CY205</td>
        <td style="background-color: orange;">Principles of Chemistry in Engineering</td>
        <td>CHE</td>
    </tr>
    <tr>
        <td style="background-color: lightgreen;">5</td>
        <td>19MA201</td>
        <td style="background-color: orange;">Calculus and Matrix Algebra</td>
        <td>MAT</td>
    </tr>
    <tr>
        <td style="background-color: lightgreen;">6</td>
        <td>19EY701</td>
        <td style="background-color: orange;">Soft Skills</td>
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
