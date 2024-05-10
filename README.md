# Ex03 Time Table
## Date:

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
            <img src="/static/logo.png" height="100"width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5">
            <caption><b>SLOT TIMETABLE SREEVARSHA.D(212221040159)</b></caption>
            <tr align="center">
                <th bgcolor="blue">Day/Time</th>
                <th bgcolor="blue">Monday</th>
                <th bgcolor="blue">Tuesday</th>
                <th bgcolor="blue">Wednesday</th>
                <th bgcolor="blue">Thursday</th>
                <th bgcolor="blue">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">8-10</th>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">CALCULUS AND MATRIX ALGEBRA</td>
                <td bgcolor="yellow">PHYSICS FOR INFORMATION TECHNOLOGY</td>
                <td bgcolor="yellow">GERMAN BASIC</td>
                <td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">10-12</th>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
                <td bgcolor="yellow">PHYSICS FOR INFORMATION TECHNOLOGY</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">12-1</th>
                <td colspan="6" align="center">LUNCH BREAK</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="yellow">SOFT SKILLS</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">CALCULUS AND MATRIX ALGEBRA</td>
                <td bgcolor="yellow">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">3-5</th>
                <td bgcolor="yellow">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
                <td bgcolor="yellow">FREE SLOT</td>
                <td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="yellow">GERMAN BASIC</td>
                <td bgcolor="yellow">FREE SLOT</td>
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
                <td>FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EN612</td>
                <td>GERMAN BASIC (GER)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19PH206</td>
                <td>PHYSICS FOR INFORMATION TECHNOLOGY (PHY)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CY205</td>
                <td>PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19MA201</td>
                <td>CALCULUS AND MATRIX ALGEBRA (MAT)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT

<img width="960" alt="Screenshot 2024-04-02 103557" src="https://github.com/sreevarshad/slot/assets/128129573/89524bfa-6af0-4fb1-b2c4-f4bdcdda0de6">

<img width="960" alt="Screenshot 2024-04-02 103928" src="https://github.com/sreevarshad/slot/assets/128129573/2a189570-c486-4ce4-9fc7-a46e733ce105">


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
