# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>JAVASCRIPT PROGRAM TO DISPLAY RESULT OF A STUDENT</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=95)&&(percentage<=100))
{
    alert("O Grade");
}
else if((percentage>=85)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=75)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=65)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=55)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```



## OUTPUT
![PG 01](https://github.com/JeevithaParthiban/Ex06_Web-Design/assets/127817091/8bc7dead-b6d8-47b6-9388-89ae359271ec)
![PG 02](https://github.com/JeevithaParthiban/Ex06_Web-Design/assets/127817091/78a1ef38-55d3-414e-b3fe-f44a634206d6)
![PG 03](https://github.com/JeevithaParthiban/Ex06_Web-Design/assets/127817091/65e6500b-5e13-4973-9ad1-8b82c7e6e31d)
![PG 04](https://github.com/JeevithaParthiban/Ex06_Web-Design/assets/127817091/8cf24268-b802-4e99-bb9b-50bede5679f2)
![PG 05](https://github.com/JeevithaParthiban/Ex06_Web-Design/assets/127817091/2ebfc08d-ac37-4adb-aa96-02de51d60783)
![PG 06](https://github.com/JeevithaParthiban/Ex06_Web-Design/assets/127817091/8e58b6da-2013-42af-af55-7ef9368a4078)



## RESULT
  Student result using JavaScript is created successfully.
