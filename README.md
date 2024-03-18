# Ex03 Time Table
## Date:

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
<html>
<head>
    <title>
        SLOT TIME TABLE
    </title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <img src="logo.png">
    <table border="2" cellspacing="4" cellpadding="6" height="100" width="200">
        <caption>STUDENTS GRADE SHEET</caption>
        <tr>
                    <th bgcolor="yellow">TIMING/DAY</th>
                    <th bgcolor="yellow">MONDAY</th>
                    <th bgcolor="yellow">TUESDAY</th>
                    <th bgcolor="yellow">WEDNESDAY</th>
                    <th bgcolor="yellow">THURSDAY</th>
                    <th bgcolor="yellow">FRIDAY</th>
                    <th bgcolor="yellow">SATURDAY</th>
                </tr>
                <tr>
                    <td bgcolor="red">8-10</td>
                    <td bgcolor="red">free</td>
                    <td bgcolor="red">ml</td>
                    <td bgcolor="red">web</td>
                    <td bgcolor="red">os</td>
                    <td bgcolor="red">statistic</td>
                    <td bgcolor="red">ml</td>
            
                    


        
        
        
                </tr>
        
                <tr>
                    <td bgcolor="cyan">10-12</td>
                    <td bgcolor="cyan">free</td>
                    <td bgcolor="cyan">web</td>
                    <td bgcolor="cyan">phy</td>
                    <td bgcolor="cyan">free</td>
                    <td bgcolor="cyan">c</td>
                    <td bgcolor="cyan">free</td>
        
                </tr>
        
                <tr>
                    <td bgcolor="green">1-3</td>
                    <td bgcolor="green">web</td>
                    <td bgcolor="green">os</td>
                    <td bgcolor="green">creative skill</td>
                    <td bgcolor="green">statistic</td>
                    <td bgcolor="green">free</td>
                    <td bgcolor="green">free</td>
        
                </tr>
                <tr>
                    <td bgcolor="blue">3-5</td>
                    <td bgcolor="blue">c</td>
                    <td bgcolor="blue">phy</td>
                    <td bgcolor="blue">free</td>
                    <td bgcolor="blue">free</td>
                    <td bgcolor="blue">free</td>
                    <td bgcolor="blue">free</td>
        
                </tr>
            </table>
        
    <table border='3' cellspacing="4" cellpadding='3'>
		<tr >
			<th bgcolor=" purple">S.NO</th>
			<th bgcolor=" purple">Subject code</th>
			<th bgcolor=" purple">Subject Name</th>
			
		</tr>
		<tr>
			<td bgcolor="olive">1.</td>
			<td bgcolor="olive">19AI414</td>
            <td bgcolor="olive">Fundamentals of Web Apllication Development(web)</td>
		</tr>

		<tr>
            <td bgcolor="grey">2.</td>
			<td bgcolor="grey">19AI304</td>
            <td bgcolor="grey">Fundamentals of C programmig(c)</td>
		</tr>

		<tr>
            <td bgcolor="coral">3.</td>
			<td bgcolor="coral">19PH214</td>
            <td bgcolor="coral">Physics for Quantum computing(phy)</td>
			
		</tr>
		<tr>
            <td bgcolor="brown">4.</td>
			<td bgcolor="brown">19Cs405</td>
            <td bgcolor="brown">Operating System(os)</td>
		</tr>
		<tr>
            <td bgcolor="pink">5.</td>
			<td bgcolor="pink">19MA211</td>
            <td bgcolor="pink">Statistics and Numerical Method(statistics)</td>
		</tr>
        <tr>
            <td bgcolor="violet">6.</td>
			<td bgcolor="violet">19EY702</td>
            <td bgcolor="violet">Creative Skills for Commmunication(creative skill)</td>
		</tr>
	</table>
	</body>
</body>
```
## OUTPUT

![alt text](<Screenshot 2024-03-18 140542.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
