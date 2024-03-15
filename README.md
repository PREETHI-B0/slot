# Ex03 Time Table
## Date:15-03-2024

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
~~~
<html>
    <head>
        <title>SLOT TIMETABLE</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="540">
        </center>
        <br>
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="pink"</table>
        <caption><b>SLOT TIME TABLE-PREETHI B[212221220040]</b></caption>
        <tr align="center">
        <th bgcolor="yellow">Day/Time</th>
        <th bgcolor="cyan">Monday</th>
        <th bgcolor="cyan">Tuesday</th>
        <th bgcolor="cyan">Wednesday</th>
        <th bgcolor="cyan">Thursday</th>
        <th bgcolor="cyan">Friday</th>
        </tr>
        <tr align="center">
        <th bgcolor="lime">8-10</th>
        <th rowspan="2">FREE SLOT</th>
        <td>BSAM</td>
        <td>DAA</td>
         <td>MPMC</td>
         <td>FWAD</td>
        </tr>
        <tr align="center">
            <th bgcolor="olive">10-12</th>
            <td>ADVANCE</td>
            <td>BSAM</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            </tr>
        <tr align="center">
                <th bgcolor="silver">12-1</th>
                <td colspan="5">LUNCH BREAK</td>
                
                </tr>  
                <tr align="center">
                    <th bgcolor="gray">1-3</th>
                    <td>MPMC</td>
                    <td>FWAD</td>
                    <td>AI</td>
                   <td rowspan="2">FREE SLOT</td>
                    <td>DAA</td>
                    </tr>         
                    <tr align="center">
                        <th bgcolor="purple">3-5</th>
                        <td>AI</td>
                        <td>ADC</td>
                        <td>ADC</td>
                        <td>FREE SLOT</td>
                        
                        </tr>             

<table align="center" width="540" cellspacing="2" cellpadding="4" border="5"</table>
<br>
 
<tr align="center"   >
        <th >S.NO</th>
        <th>Subject Code</th>
        <th >Subject Name</th>
  </tr>
<tr>
<td>1</td>
<td>19AI414</td>
<td>Fundamentals of wen application</td>
</tr>
<tr>
<td>2</td>
<td>19CS402</td>
<td>Design and analysis of Algorithm</td>
</tr>
<tr>
<td>3</td>
<td>19CS413</td>
<td>Artifical Intelligence</td>
</tr>
<tr>
<td>4</td>
<td>19EC306</td>
<td>Analog and digital communication</td>
</tr>
<tr>
<td>5</td>
<td>19EC408</td>
<td>Microprocessor and microcontroller</td>
</tr>
<tr>
<td>6</td>
<td>19EY704</td>
<td>Advance Quantitative and Logical Reasoning</td>
</tr>
</body>
<html>
~~~
## OUTPUT
![alt text](<Screenshot 2024-03-15 175850.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
