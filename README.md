# Ex03 Time Table
## Date:20/11/2024

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
<body>
    <center><img src="logo.png" height="400" width="600" align="center"></center>
    <table border="3" cellspacing="15" cellpadding="2" align="center">
        <caption>SLOT TIME TABLE-S.STAR ASHIL (24009003)</caption>
        <tr bgcolor="Purple">
            <th align="center">Day/Time</th>
            <th align="center">Monday</th>
            <th align="center">Tuesday</th>
            <th align="center">Wednessday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">8-10</td>
            <td bgcolor="Yellow" colspan="2" align="center">FREE SLOT</td>
            <td bgcolor="Yellow" align="center">MATHS</td>
            <td bgcolor="Yellow" align="center">ENG</td>
            <td bgcolor="Yellow" align="center">WEB</td>
            <td bgcolor="Yellow" align="center">FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">10-12</td>
            <td bgcolor="Yellow" align="center">ENG</td>
            <td bgcolor="Yellow" align="center">EDM</td>
            <td bgcolor="Yellow" align="center">MM</td>
            <td bgcolor="Yellow" align="center">MATHS</td>
            <td bgcolor="Yellow" colspan="2" align="center">FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">12-1</td>
            <td bgcolor="Yellow" colspan="6" align="center">LUNCH</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">1-3</td>
            <td bgcolor="Yellow" colspan="2" align="center">FREE SLOT</td>
            <td bgcolor="Yellow" align="center">MATHS</td>
            <td bgcolor="Yellow" align="center">PYTHON</td>
            <td bgcolor="Yellow" align="center">WEB</td>
            <td bgcolor="Yellow" align="center">FREE SLOT</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">3-5</td>
            <td bgcolor="Yellow" align="center">FREE SLOT</td>
            <td bgcolor="Yellow" align="center">PYTHON</td>
            <td bgcolor="Yellow" colspan="2" align="center">FREE SLOT</td>
            <td bgcolor="Yellow" align="center">CG</td>
            <td bgcolor="Yellow" align="center">FREE SLOT</td>
        </tr>
    </table>
    <table border="3" cellspacing="15" cellpadding="2" align="center">
        <caption>TIME TABLE</caption>
        <tr bgcolor="Purple">
            <th align="center">S.No</th>
            <th align="center">COURSE CODE</th>
            <th align="center">COURSE NAME</th>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">1.</td>
            <td bgcolor="Yellow" align="center">19AI414</td>
            <td bgcolor="Yellow" align="center">Fundamentals Of Web Application Development</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">2.</td>
            <td bgcolor="Yellow" align="center">19AI301</td>
            <td bgcolor="Yellow" align="center">Python Programming</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">3.</td>
            <td bgcolor="Yellow" align="center">19AI302</td>
            <td bgcolor="Yellow" align="center">Engineering Design And Modelling</td>
        </tr>
        <tr>
            <td bgcolor="Green" align="center">4.</td>
            <td bgcolor="Yellow" align="center">19EN101</td>
            <td bgcolor="Yellow" align="center">Communicative</td>
        </tr>
    </table>
</body>
</html>
```


## OUTPUT!

![alt text](image.png)




## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
