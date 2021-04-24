1. Pulling the input values from the DOM returned strings, not numbers, so they were just being concatenated.
2. To fix this issue, I just casted the strings by calling the Number constructor on the DOM values.
3. citylots.json
4. part2.js
5. 11.7 MB
6. 3.85s
7. Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/90.0.4430.85 Safari/537.36 Edg/90.0.818.46
8. Apache
9. Tue, 26 Jan 2021 22:14:13 GMT
10. application/json
11. fetchData()