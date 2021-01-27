## Debugging
The bug is that the values being entered are being taken as strings so the output is just the two numbers being concatonated as strings.
This can be fixed by changing line 9 to 

let result = parseInt(num1) + parseInt(num2);

## Network Tab
