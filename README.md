# Ex03 Time Table
## Date:14/11/2024

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
        <img src="logo.png">
        <table border="1">
            <caption>TIME TABLE-ATCHAYA B(24900268)</caption>
            <tr bgcolor="blue">
                <th>TIME/DAY</th>
                <th>MONDAY</th>
                <th>TUESDAY</th>
                <th>WEDNESDAY</th>
                <th>THURSDAY</th>
                <th>FRIDAY</th>
                <th>SATURDAY</th>
            </tr>
            <tr bgcolor="pink">
                <td>8-10</td>
                <td>PROBABILITY</td>
                <td>CAREER</td>
                <td>FREE SLOT</td>
                <td> CE</td>
                <td>WEB</td>
                <td>FREE SLOT</td> 
            </tr>
            <tr bgcolor="pink" >
                <td>10-12</td>
                <td>CE</td>
                <td>EDM</td>
                <td>PROBABILITY</td>
                <td>FUND OF C</td>
                <td>FUND OF C</td>
                <td>FREE SLOT</td>
            </tr>
            <tr bgcolor="pink">
                <td>12-1</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
                <td>LUNCH</td>
            </tr>
            <tr bgcolor="pink">
                <td>1-3</td>
                <td>WEB</td>
                <td>WEB</td>
                <td>MENTOT MEET</td>
                <td>DE</td>
                <td>EDM</td>
                <td>FREE SLOT</td>
            </tr>
            <tr bgcolor="pink">
                <td>3-5</td>
                <td>FREE SLOT</td>
                <td>DE</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table border="1">
            <tr>
                <th>S.NO</th>
                <th>COURSE CODE</th>
                <th>COURSE NAME</th>
            </tr>
            <tr>
                <th>1</th>
                <th>19AI414</th>
                <th>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT(WEB)</th>
            </tr>
            <tr>
                <th>2</th>
                <th>19EE404</th>
                <th>DIGITAL ELECTRONICS(DE)</th>
            </tr>
            <tr>
                <th>3</th>
                <th>19AI302</th>
                <th>ENGINEERING DESIGN AND MODELING(EDM)</th>
            </tr>
            <tr>
                <th>4</th>
                <th>19EY708</th>
                <th>CAREER DEVELOPMENT SKILLS(CAREER)</th>
            </tr>
            <tr>
                <th>5</th>
                <th>19MA222</th>
                <th>PROBABILITY AND QUEUING MODELS(PROBABILITY)</th>
            </tr>
            <tr>
                <th>6</th>
                <th>19EN101</th>
                <th>COMMUNICATIVE ENGLISH(CE)</th>
            </tr>
            <tr>
                <th>7</th>
                <th>19AI304</th>
                <th>FUNDAMENTALS OF C PROGRAMING(FUND OF C)</th>
            </tr>
            <tr>
                <th>8</th>
                <th>ECA-M-SCOFT</th>
                <th>MENTOR MEET</th>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (9).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
