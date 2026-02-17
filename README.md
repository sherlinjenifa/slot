# Ex02 Time Table
## Date:13-02-2026

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
        <title>Sample</title>
    </head>
    <body>
        <img src="c:\Users\acer\Pictures\Screenshots\Screenshot 2026-02-17 090900.png" width="600">
        <br>
        <caption align="center">Name : Sherlin Jenifa VS   Reg No : 25017634</caption>
        <table border = "8" cellspacing = "10" cellpadding = "10">
            <tr bgcolor = "Lightblue">
                <th>DAY/TIME</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td>08-10</td>
                <td>Free</td>
                <td>web</td>
                <td colspan="3">Free</td>
                <td>python</td>
            </tr>
            <tr>
                <td>10-12</td>
                <td>web</td>
                <td>Free</td>
                <td>web</td>
                <td colspan="3">Free</td>
             </tr>
             <tr>
                <td>12-01</td>
                <td colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td>01-03</td>
                <td colspan = "3">Free</td>
                <td>python</td>
                <td>web</td>
                <td>web</td>
            </tr>
            <tr>
                <td>03-05</td>
                <td>python</td>
                <td>python</td>
                <td colspan = "2">Free</td>
                <td>python</td>
                <td>Free</td>
            </tr>
        </table>
        <br>
        <br>
        <table border ="4" cellspacing= "10" cellpadding = "10">
            <tr>
                <th>S.NO</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of web application(web)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming(python)</td>
            </tr>
        </table>
    </body>
</html>

```


## OUTPUT
![alt text](<Screenshot (43).png>)





## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
