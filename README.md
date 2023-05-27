# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
~~~
## OUTPUT
![calc](https://github.com/SrimathiJeyalakshmi/Ex07_Web-Design/assets/127816530/a38c2d89-81a7-4e4a-bb0d-8790283937a3)
![1 st value](https://github.com/SrimathiJeyalakshmi/Ex07_Web-Design/assets/127816530/50ecfb2a-e74a-4377-b93b-fb45b4a8e636)
![2nd value](https://github.com/SrimathiJeyalakshmi/Ex07_Web-Design/assets/127816530/6be04789-ddc9-44f9-9aac-8f051a44adb0)
![operation](https://github.com/SrimathiJeyalakshmi/Ex07_Web-Design/assets/127816530/4bc65ecb-638c-4138-8af9-c99770caf221)
![result no 01](https://github.com/SrimathiJeyalakshmi/Ex07_Web-Design/assets/127816530/4399a63b-cc11-45a7-9746-3ed330cd11ef)




## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
