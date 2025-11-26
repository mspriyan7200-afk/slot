# Ex02 Time Table
## Date: 25-11-2025

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
        <title>Time table</title>
    </head>
    <body>
        <IMG SRC="logo.png"HEIGHT="150"WIDTH="700"BORDER=5>
        <h2>Saveetha Engineering College</h2>
        <h3>SLOT TIME TABLE - PRIYAN</h3>

        <table border="1"  cellspacing="5" cellpadding="5">
            <caption>TIME TABLE</caption>
            <tr bgcolor="cyan">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td bgcolor="cyan">8-10</td>
                <td bgcolor="pink" colspan="2" align="center">FREE SLOT</td>
                <td align="center">FWAD</td>
                <td>PYTHON</td>
                <td bgcolor="pink" >FREE SLOT</td>
                <td align="center">FWAD</td>
            </tr>
            <tr>
                <td bgcolor="cyan">10-12</td>
                <td align="center">FWAD</td>
                <td align="center">FWAD</td>
                <td align="center">FWAD</td>
                <td bgcolor="pink" colspan="3" align="center">FREE SLOT</td>
            </tr>
            <tr>
                <td bgcolor="cyan">12-1</td>
                <td bgcolor="yellow" colspan="6" align="center">LUNCH</td>
            
            </tr>
            <tr>
                <td bgcolor="cyan">1-3</td>
                <td>PYTHON</td>
                <td align="center">CE</td>
                <td>MENTOR MEET</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td align="center">CE</td>
                <td>PYTHON</td>
            </tr>
            <tr>
                <td bgcolor="cyan">3-5</td>
                <td>PYTHON</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td align="center">CE</td>
                <td align="center">CE</td>
                <td>PYTHON</td>
                <td bgcolor="pink">FREE SLOT</td>
            </tr>

        </table>
        
        <h3>SUBJECTS</h3>
        <table border="1" bgcolor="cyan" cellspacing="5" cellpadding="5">
            <tr bgcolor="orange">
                <th>S.No.</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr bgcolor="violet">
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Applications and Development(FWAD)</td>
            </tr>
            <tr bgcolor="violet">
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr bgcolor="violet">
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
        </table>
    </body>

</html>

```

## OUTPUT
![alt text](<Screenshot (28).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
