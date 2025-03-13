# Ex03 Time Table
## Date:13/03/2025

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
        <center>
        <img src="Screenshot 2025-03-13 031641.png">
        <title>SLOT TIME TABLE</title>
        <caption><h3>SLOT TIMETABLE- SWETHA C (24901183)</h3></caption>
        </center>
    </head>
    <body>
        <center>
           <table border="1">
            <tr bgcolor="purple">
                <td><h3>Day/Time</h3></td>
                <td><h3><center>Monday</center></h3></td>
                <td><h3><center>Tuesday</center></h3></td>
                <td><h3><center>Wednesday</center></h3></td>
                <td><h3><center>Thursday</center></h3></td>
                <td><h3><center>Friday</center></h3></td>
                <td><h3><center>Saturday</center></h3></td>
            </tr>
            <tr bgcolor="violet">
                <td bgcolor="violet "><center><h3>8-10</h3></center></td>
                <td></td>
                <td></td>
                <td></td>
                <td>Fundamental of Web Application</td>
                <td></td>
                <td></td>
            </tr>
            <tr bgcolor="violet">
                <td bgcolor="violet"><center><h3>10-12</h3></center></td>
                <td></td>
                <td>Computer Architecture</td>
                <td>Reasoning Ability</td>
                <td>Python Programming</td>
                <td>Python programming</td>
                <td>Fundamental of Web Application</td>
            </tr>
            <tr bgcolor="violet">
                <td bgcolor="violet"><center><h3>12-1</h3></center></td>
                <td colspan="6"><center><h3>L U N C H</h3></center></td>
            </tr>
            <tr bgcolor="violet">
                <td bgcolor="violet"><center><h3>1-3</h3></center></td>
                <td></td>
                <td></td>
                <td>Mentor Meet</td>
                <td>Computer Network</td>
                <td>Computer Network</td>
                <td></td>
            </tr>
                <tr bgcolor="violet">
                    <td bgcolor="violet"><center><h3>3-5</h3></center></td>
                    <td>Chemistry</td>
                    <td></td>
                    <td>Computer Architecture</td>
                    <td>Chemistry</td>
                    <td></td>
                    <td></td>
                </tr>
            

        </table><br>

        <table border="1">
            <tr>
                <td><h3>S.NO</S></h3></td>
                <td><h3>SUBJECT CODE</h3></td>
                <td><h3><center>SUBJECT NAME</center></h3></td>
            </tr>
            <tr>
                <td> 1.</td>
                <td><center>19AI414</center></td>
                <td>Fundamental of  Web Application</td>
            </tr>
            <tr>
                <td> 2.</td>
                <td><center>19AI301C</center></td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td> 3.</td>
                <td><center>19CS406</center></td>
                <td>Computer Network</td>
            </tr>
            <tr>
                <td> 4.</td>
                <td><center>19CS305</center></td>
                <td>Computer Architecture</td>
            </tr>
            <tr>
                <td> 5.</td>
                <td><center>19EY709</center></td>
                <td>Reasoning Ability</td>
            </tr>
            <tr>
                <td> 6.</td>
                <td><center>19CY205</center></td>
                <td>Chemistry</td>
            </tr>
        </table>
        </center>
    </body>
</html>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/25dcb3ae-432a-4705-b911-8238cf590275)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
