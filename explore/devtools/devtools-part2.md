## Debugging

### What was the bug?
The bug was that values from the input fields were treates as string instead of numbers. Because of this, JavaScript concatenates them instead of adding them. For example, "2" + "3" resulted in "23" instead of 5. 

### How would you fix it?
Convert th input values to numbers before adding them. This can be done using Numbers().

Example fix:
let num1 = Number(document.getElementById("num1").value);
let num2 = Number(document.getElementById("num2").value);