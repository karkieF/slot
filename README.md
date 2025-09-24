# Ex03 Time Table
## Date:24/09/25

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
    </head>
    <body>
        <center><img src="logo.png" height="100" width="600"></center>

         <h1 align="center">SLOT TIME TABLE-KARKIE(25016839)</h1>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  
         <table border="5" cellspacing="5" cellpadding="5" style="margin-bottom: 30px;" align="center" >
            <tr bgcolor="Sky Blue">
            <th>DAY/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
            </tr>
            <tr bgcolor="Gray">
                <td bgcolor="Sky Blue">8-10</td>
                <td  bgcolor="Gray"colspan="3" align="center">FREE  SLOT</td>
                <td bgcolor="Gray">C</td>
                <td bgcolor="Gray">FREE  SLOT</td>
                <td bgcolor="Gray">FWAD</tr>
            <tr>
                <tr>
                <td bgcolor="Sky Blue">1 0-12</td>
                <td  bgcolor="Gray"colspan="2" align="center">FREE  SLOT</td>
                <td bgcolor="Gray">FWAD</td>
                <td bgcolor="Gray">FREE  SLOT</td>
                <td  bgcolor="Gray"colspan="2" align="center">FREE  SLOT</tr>
            <tr>
            
                <td bgcolor="Sky Blue">12-1</td>
                <td bgcolor="Gray" colspan="6"  align="center">LUNCH</td>
        
            </tr>
            <tr>
                <td bgcolor="Sky Blue">1-3</td>
                <td bgcolor="Gray"colspan="3" align="center">FREE  SLOT</td>
                <td bgcolor="Gray">C</td>
                <td bgcolor="Gray">FWAD</td>
                <td bgcolor="Gray">FWAD</td>
            </tr>
            <tr>
                <td bgcolor="Sky Blue">3-5</td>
                <td bgcolor="Gray">C</td>
                <td bgcolor="Gray">C</td>
                <td  bgcolor="Gray"colspan="2" align="center">FREE  SLOT</td>
                <td bgcolor="Gray">C</td>
                <td bgcolor="Gray">FREE  SLOT</td>
            </tr>
                <table border="5" cellspacing="5" cellpadding="5" align="center">
            <tr>
             <th>S.NO.</td>
             <th>Subject Code</th>
             <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AL414</td>
                <td>19AL304</td
            </tr>
            <tr>
                <td>2.</td>
                <td>Fundamentals Of Web Application Development</td>
                <td>C Programming</td>
            </tr>
             

          </table> 
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (7).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
