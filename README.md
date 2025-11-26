# Ex03 Time Table
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```<html>
    <body>
        <img src="logo.png" width="500">
        <table border="1" cellspacing="2" cellpadding="2">
            <caption>SLOT TIME TABLE-HARISELVAN S(212224040103)</caption>
            <tr bgcolor="red">
                <th>Day/time</th>
                <th>monday</th>
                <th>tuesday</th>
                <th>wednesday</th>
                <th>thursday</th>
                <th>friday</th>
                <th>saturday</th>
            </tr>
            <tr>
                <td bgcolor="yellow">8-10</td>
                <td bgcolor="cyan" colspan="6">FREE SLOT</td>
                
            </tr>
            <tr>
                <td bgcolor="yellow">10-12</td>
                <td bgcolor="cyan">ML</td>
                <td bgcolor="cyan">WEB</td>
                <td bgcolor="cyan">MAT</td>
                <td bgcolor="cyan" colspan="2">C</td>
                <td bgcolor="cyan">ml</td>
            </tr>
            <tr>
                <td bgcolor="yellow">12-1</td>
                <td bgcolor="cyan" colspan="6" align="center">LUNCH</td>
            </tr>
            <tr>
                <td bgcolor="yellow">1-3</td>
                <td bgcolor="cyan">MAT</td>
                <td bgcolor="cyan">OS</td>
                <td bgcolor="cyan">MENTOR</td>
                <td bgcolor="cyan">PQM</td>
                <td bgcolor="cyan">MAT</td>
                <td bgcolor="cyan">WEB</td>
            </tr>
            <tr>
                <td bgcolor="yellow">3-5</td> 
                <td bgcolor="cyan" colspan="2">FREE SLOT</td>
                <td bgcolor="cyan">OS</td>
                <td bgcolor="cyan" colspan="2">FREE SLOT</td>
                <td bgcolor="cyan">PQM</td>
            </tr>
        </table>
        <br>
        <table  border="1" cellpadding="2">
            <tr>
                <td>s.no</td>
                <td>course code</td>
                <td align="center">Course Name</td>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamental of web application development </td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI304</td>
                <td>Fundamental of C programming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19MA220</td>
                <td>Mathematics for Artificial intelligence</td>
            </tr>
           
            <tr>
                <td>4</td>
                <td>19MA222</td>
                <td>Probability and Quining Models</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19CS405</td>
                <td>Operating System</td>
            </tr>
            <tr>
            <td>6</td>
            <td>ECA-M SCOFT</td>
            <td>Mentor Meet</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19AI410</td>
                <td>Introduction to machine learning</td>
            </tr>
        </table>
    </body>
 </html>
```
# OUTPUT
![Screenshot 2025-04-08 131239](https://github.com/user-attachments/assets/835b8720-c626-4bd1-82b6-f8852ea74efc)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
