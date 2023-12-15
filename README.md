# 25-Killer-JavaScript-One-Liners
Supercharge Your Code and Impress Your Peers

# 1. Check if a string is empty:
```
!str.trim()
```
2. Reverse a string:

str.split("").reverse().join("")

3. Check if an object is empty:

Object.keys(obj).length === 0

4. Get the last element of an array:

arr[arr.length - 1]

5. Shuffle an array:

arr.sort(() => Math.random() - 0.5)

6. Deep clone an object:

JSON.parse(JSON.stringify(obj))

7. Flatten an array:

arr.flat(Infinity)

8. Get the sum of all elements in an array:

arr.reduce((acc, curr) => acc + curr, 0)
