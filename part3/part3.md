1. The bug is that the type of result was originally a string, but in order to get the right output, it is supposed to be a number.
2. I fixed it by using parseInt() to num1 and num2 and casted them to be numbers.
3. citylots.json
4. part2.js
5. 11.7 MB
6. 83.92 ms
7. Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json
11. Inside function fetchData(), the fetch('./citylots.json') method made the request.