# Ex03 Time Table
## Date: 22/04/2025

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
</head>
 
<style>
    table,th,td{border: 2px solid black; text-align: center;border-collapse: collapse;}
    
    th{ background-color: antiquewhite;}
    
</style>    
<body style="background-color: white;">
    <div><a href="http://training.saveetha.in/" title="Saveetha Engineering College"> <img src="C:\Users\MAHALAKSHMI B\OneDrive\Documents\web\logo_1.png"; width=100% height=200px></a></div>
    <h1></h1>
    <table width = 100% height="50px" style="background-color: white; border: 0cap;">
        <tr>
            <th style="background-color:rgb(57, 216, 121);border: 0cap; text-align: center;">SLOT TIME TABLE - MAHALAKSHMI B (24900270)</th>
        </tr>  
    </table> 
    <table style="border: 2px solid black; text-align: center;background-color: aqua; width: 100%; height: 400px;">
        <tr>
            <th width="100"> Day/time </th>
            <th width="100"> Monday </th>
            <th width="100"> Tuesday </th>
            <th width="100"> Wednesday</th>
            <th width="100"> Thursday</th>
            <th width="100"> Friday</th>
            <th width="100"> Saturday</th>
        </tr>
        <tr>
            <th>8:00-10:00</th>
            <td>Free hour</td>
            <td>Chemistry</td>
            <td>Statistics</td>
            <td colspan="3">Free hour</td>
        </tr>
        <tr>
            <th>10:00-12:00</th>
            <td>Career</td>
            <td>Physics</td>
            <td>Python</td>
            <td>Free hour</td>
            <td colspan="2">Web</td>
        </tr>
        <tr>
            <th>12:00-1:00</th>
            <td colspan="7">LUNCH</td>
        </tr>
        <tr>
            <th>1:00-3:00</th>
            <td>Web</td>
            <td>Statistics</td>
            <td>Free hour</td>
            <td>Chemistry</td>
            <td>Python</td>
            <td>Physics</td>
        </tr>
    </table>
<h1>
</h1>
<h2>
    
</h2>
    <table style="border: 2px solid black;background-color: white; width: 100%; height: 400px;">
         <tr>
            <th style="background-color: white;">S.NO</th>
            <th style="background-color: white;">SUBJECT CODE</th>
            <th style="background-color: white;">SUBJECT NAME</th>
         </tr>
         <tr> 
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development(Web)</td>
         </tr>
         <tr>
            <td>2.</td>
            <td>19AI301</td>
            <td>Python Programming(Python)</td>
         </tr>
         <tr>
            <td>3.</td>
            <td>SH3214</td>
            <td>Physics for Quantum Computing(Physics)</td>
         </tr>
         <tr>
            <td>4.</td>
            <td>19EY708</td>
            <td>Career Development Skills(Career)</td>
         </tr>
         <tr>
            <td>5.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering(Chemistry)</td>
         </tr>
         <tr>
            <td>6.</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods(Statistics)</td>
         </tr>
    </table>
```

## OUTPUT
![Screenshot 2025-04-22 225947](https://github.com/user-attachments/assets/885c3695-1368-45e0-b0b0-83ebb8c5292b)
![Screenshot 2025-04-22 230011](https://github.com/user-attachments/assets/fe2f9487-4922-4b50-a150-cf2d089e4404)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
