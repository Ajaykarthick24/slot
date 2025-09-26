# Ex03 Time Table
## Date:25/09/2025

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
        <h3>SLOT TIME TABLE- AJAY KARTHICK M (25010418)</h3>
        <table border ="5" cellpadding="5" cellspacing="5">
            <tr bgcolor="cyablue">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="gold">
                <th bgcolor="silver">8-10 </th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>ENG</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>FREE</td>
            </tr>
            <tr bgcolor="gold">
                <th bgcolor="silver">10-12</th>
                <td>PYTHON</td>
                <td>ENG</td>
                <td>ENG</td>
                <td>FREE</td>
                <td>ENG</td>
                <td>ENG</td>
            </tr>
            <tr bgcolor="gold">
                <th bgcolor="silver">12-1</th>
                <th cOlspan="7">LUNCH</th>
            </tr>
            <tr bgcolor="gold">
                <th bgcolor="silver">1-3</th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>ENG</td>
                <td>FREE</td>
            </tr>
            <tr bgcolor="gold">
                <th bgcolor="silver">3-5</th>
                <td>FREE</td>
                <td>FREE</td>
                <td>PYTHON</td>
                <td>PYTHON</td>
                <td>FREE</td>
                <td>FREE</td>
            </tr>
        </table>
        <table border="2" cellpadding="5">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>PYTHON Programming(C PROG)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EN101</td>
                <td>Communicative English(ENG)</td>
            </tr>
        </table>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2025-09-26 092904.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.


