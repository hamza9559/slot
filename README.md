# Ex03 Time Table
## Date: 31-03-2024

## AIM:
To write a html webpage page to display your slot timetable.

## ALGORITHM:
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

## PROGRAM:
```
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="logo.png" height="100" width="965">
        </center>
        <br>
        <table align="center" cellspacing="2" cellpadding="5" width="540" border="20">
            <caption><b><h1>Timetable HAMZA FAROOQUE (212223040054)</h1></b></caption>
            <tr align="center">
                <th bgcolor="red">Day/Time</th>
                <th bgcolor="red">Monday</th>
                <th bgcolor="red">Tuesday</th>
                <th bgcolor="red">Wednesday</th>
                <th bgcolor="red">Thursday</th>
                <th bgcolor="red">Friday</th>
                <th bgcolor="red">Saturday</th>
            </tr>
            <tr align="center">
                <th bgcolor="blue">8-10</th>
                <td bgcolor="violet">Fundamentals of Web Application Developement</td>
                <td bgcolor="violet">DIGITAL ELECTRONICS</td>
                <td bgcolor="violet">COMPILER DESIGN</td>
                <td bgcolor="violet">DIGITAL ELECTRONICS</td>
                <td bgcolor="violet">COMPUTER NETWORKS</td>
                <td bgcolor="violet">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">10-12</th>
                <td bgcolor="violet">COMPILER DESIGN</td>
                <td bgcolor="violet">PYTHON PROGRAMMING</td>
                <td bgcolor="violet">COMPUTER NETWORKS</td>
                <td bgcolor="violet">CREATIVE SKILLS</td>
                <td bgcolor="violet">FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
                <td bgcolor="violet">ALGEBRA AND NUMBER THEORY</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">12-1</th>
                <td bgcolor="violet">LUNCH</td>
                <td bgcolor="violet">LUNCH</td>
                <td bgcolor="violet">LUNCH</td>
                <td bgcolor="violet">MENTOR MEET</td>
                <td bgcolor="violet">LUNCH</td>
                <td bgcolor="violet">LUNCH</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="violet">ALGEBRA AND NUMBER THEORY</td>
                <td bgcolor="violet">FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</td>
                <td bgcolor="violet">PYTHON PROGRAMMING</td>
                <td bgcolor="violet">FUNDAMENTALS OF WEB APPLICATION</td>
                <td bgcolor="violet">FUNDAMENTALS OF WEB APPLICATION</td>
                <td bgcolor="violet">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="blue">3-5</th>
                <td bgcolor="violet">FREE SLOT</td>
                <td bgcolor="violet">FREE SLOT</td>
                <td bgcolor="violet">FREE SLOT</td>
                <td bgcolor="violet">FREE SLOT</td>
                <td bgcolor="violet">FREE SLOT</td>
                <td bgcolor="violet">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="5" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td><font color="black">Fundamentals of Web Application Development (FWAD)</font></td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19CS4O9</td>
                <td><font color="black">COMPILER DESIGN</font></td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19MA212</td>
                <td><font color="black">ALGEBRA AND NUMBER THEORY</font></td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19AI405</td>
                <td><font color="black">FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</font></td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19EE404</td>
                <td><font color="black">DIGITAL ELECTRONICS</font></td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19AI301</td>
                <td><font color="black">PYTHON PROGRAMMING</font></td>
            </tr>
            <tr>
                <td align="center">7.</td>
                <td align="center">19EY702</td>
                <td><font color="black">CREATIVE SKILLS</font></td>
            </tr>
            <tr>
                <td align="center">8.</td>
                <td align="center">19CS406</td>
                <td><font color="black">COMPUTER NETWORKS</font></td>
            </tr>
            
        </table>
    </body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-04-01 082258.png>)

## RESULT:
The program for creating slot timetable using basic HTML tags is executed successfully.
