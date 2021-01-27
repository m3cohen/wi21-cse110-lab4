## Debugging
The bug is that the values being entered are being taken as strings so the output is just the two numbers being concatonated as strings.
This can be fixed by changing line 9 to 

`let result = parseInt(num1) + parseInt(num2)`

## Network Tab
1. citylots.json
2. part2.js
3. 11.7 MB
4. 1.90 s

5. User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 11_1_0) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/87.0.4280.141 Safari/537.36
6. Server: Apache
7. Last-Modified: Tue, 26 Jan 2021 22:14:13 GMT
8. Content-Type: application/json

9. fetchData
