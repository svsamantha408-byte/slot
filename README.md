# Ex03 Time Table
## Date: 20.09.2025

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
        <title>
        slot time table
        </title>
    </head>
    <body bgcolor="lightblue" text="black">
        <center>
    <img src="/static/logo.png" height="150" width="1000">  
    </center>
    <br>
    <br>
    <br>
        <h2>SLOT TIME TABLE- Samantha Shree SV (25017585)</h2>
        <table border="5" cellspacing="4">
            <tr bgcolor="yellow">
                <td>Day/Time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
            </tr>
            <tr>
                <td bgcolor="yellow">8.00-10.00</td>
                <td bgcolor="skyblue" colspan="2" align="center">C pro</td> 
                <td bgcolor="skyblue">web</td>
                <td bgcolor="skyblue">free</td>
                <td bgcolor="skyblue">web</td>
                
            
            </tr>
            <tr>
                <td bgcolor="yellow">10.00-12.00</td>
                <td bgcolor="skyblue">free</td>
                <td bgcolor="skyblue">D.S</td>
                <td bgcolor="skyblue">C pro</td>
                <td bgcolor="skyblue">free</td>
                <td bgcolor="skyblue">web</td>
            </tr>
            <tr>
                <td bgcolor="yellow">12.00-1.00</td>
                <td bgcolor="skyblue" colspan="5" align="center">lunch</td>
            </tr>
            <tr>
                <td bgcolor="yellow">1.00-3.00</td>
                <td bgcolor="skyblue">D.S</td>
                <td bgcolor="skyblue">C pro</td>
                <td bgcolor="skyblue">mentor</td>
                <td bgcolor="skyblue">free</td>
                <td bgcolor="skyblue">web</td>
                
            </tr>
            <tr>
                <td bgcolor="yellow">3.00-5.00</td>
                <td bgcolor="skyblue">free</td>
                <td bgcolor="skyblue">C pro</td>
                <td bgcolor="skyblue">D.S</td>
                <td bgcolor="skyblue">D.S</td>
                <td bgcolor="skyblue">C pro</td>
            </tr>
        </table>
        <br>
        <br>


        <table border="4" cellspacing="4">
             <tr>
                <td>SI.NO</td>
                <td>subject code</td>
                <td>subject name</td>
             </tr>
             <tr>
                <td>1.</td>
                <td>19AI304</td>
                <td>C programming(C pro)</td>
             </tr>
             <tr>
                <td>2.</td>
                <td>19AI414</td>
                <td>Fundamentals of web application(web)</td>
             </tr>
            <tr>
                <td>3.</td>
                <td>19AI403</td>
                <td>Introduction to data science(D.S)</td>
            </tr>
        </table>
    </body>
</html>
 ```       
## OUTPUT
![alt text](<Screenshot (32)-1.png>)
                
              
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
