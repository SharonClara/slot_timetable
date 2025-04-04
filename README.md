# Ex03 Time Table
## Date:30.03.2025

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
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Slot TimeTable</title>
        <style>
            body{
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                margin: 40px;
                background:linear-gradient(to right, #e20582);
            }
            .logo{
                width: 700px;
                margin-bottom: 20px;
                height : 100px;
            }
            table{
                width: 100%;
                border-radius: 20px;
                border-collapse: separate;
                border-spacing: 3;
                border: none;
            }
            th, td {
                
            padding: 10px;
            text-align: center;
            background-color: rgb(250, 215, 236);
            border: 1px solid #060501;
            }
            th {
            background-color: #f7f4f4;
            color: rgb(15, 0, 0);
            }
            #table_head{
                background-color: #f400a3;
                color: white;
                font-size: 20px;
            }
            .Days{
                background-color: #f7f4f4;
                color: black;
                font-weight: bold;
            }
        </style>
    </head>

    <body>
        <img src="/static/logo.png" alt="logo" class="logo">
        <h1>EVEN SEM TIME TABLE</h1>
        <table>
            <tr>
                <th colspan="5" id="table_head">SLOT TIMETABLE - SHARON CLARA A(212224040310)</th>
            </tr>
            <tr class="Days">
                <th></th>
                <th>8-10 </th>
                <th>10-12 </th>
                <th>1-3 </th>
                <th>3-5</th>
            </tr>
            <tr>
                <td class="Days">MONDAY</td>
                <td>Free Slot</td>
                <td>Software Engineering</td>
                <td>Advance C programming</td>
                <td>Computer Networks</td>
            </tr>
            <tr>
                <td class="Days">TUESDAY</td>
                <td>Free Slot</td>
                <td>Digital Electronics</td>
                <td>Physics</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <td class="Days">WEDNESDAY</td>
                <td>Digital Electronics</td>
                <td>Reasoning Ability</td>
                <td>Mentor Meet</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <td class="Days">THURSDAY</td>
                <td>Physics</td>
                <td>Computer Networks</td>
                <td>Maths</td>
                <td>Fundamental of Web Application</td>
            </tr>
            <tr>
                <td class="Days">FRIDAY</td>
                <td>Free Slot</td>
                <td>Fundamental of Web Application</td>
                <td>Human Values</td>
                <td>Free Slot</td>
            </tr>
            <tr>
                <td class="Days" >SATURDAY</td>
                <td>Free Slot</td>
                <td>Software Engineering</td>
                <td>Advance C programming</td>
                <td>Maths</td>
            </tr>
        </table>

    </body>

</html>
```

## OUTPUT
![alt text](<WhatsApp Image 2025-03-30 at 18.00.57_e92b7369.jpg>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
