# Ex03 Time Table
## Date:19/03/2024

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
        <title>My Time Table</title>
    </head>
    <body>
        <img src="logo.png" height="150" width="950">
        <table border="4" cellspacing="6" cellpadding="6">
        <caption>My Time Table</caption>
            <tr>
                <th bgcolor="pink">Days</th>
                <th bgcolor="pink">Monday</th>
                <th bgcolor="pink">Tuesday</th>
                <th bgcolor="pink">Wednesday</th>
                <th bgcolor="pink">Thursday</th>
                <th bgcolor="pink">Friday</th>
                <th bgcolor="pink">Saturday</th>
            </tr>
            <tr>
                <th bgcolor="cyan">8-10</th>
                <th>FREE</th>
                <th>Statistics</th>
                <th rowspan="2">FREE</th>
                <th>Japanese</th>
                <th>Web development</th>
                <th>FREE</th>
            </tr>
            <tr>
                <th bgcolor="cyan">10-12</th>
                <th>English</th>
                <th>C programming</th>
                <th>C programming</th>
                <th>Intro to ML</th>
                <th>Statistics</th>
            </tr>
            <tr>
                <th bgcolor="cyan">1-3</th>
                <th rowspan="2">FREE</th>
                <th>Web development</th>
                <th>English</th>
                <th>Web development</th>
                <th>FREE</th>
                <th>Japanese</th>
            </tr>
            <tr>
                <th bgcolor="cyan">3-5</th>
                <th>Intro to ML</th>
                <th>Japanese</th>
                <th>Creative skills</th>
                <th colspan="2">FREE</th>
            </tr>
        </table>
        <table border="2" cellspacing="1">
            <tr>
                <th>S No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Development</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamentals of C Pregramming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EN615C</td>
                <td>Japanese Basic & advanced</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19EY702</td>
                <td>Creative skills for communication</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19MA211</td>
                <td>Statistics and Numerical Methods</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2024-03-19 141912.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
