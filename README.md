<hr>
<div align="center"><h1>1. JavaScript Basic Problems Solvings </h1></div>

### 01.

**Answer:** Declaring a variable and assigning the value 'Volvo'<br>

```Javascript Code```
```javascript
let carName = "Volvo";
```

<br>

### 02.

1. **Answer:** Declaring three variables on a single line<br>

```Javascript Code```
```javascript
let firstName = "John", lastName = "Doe", age = 35;
```

<br>

2. **Answer:** 
<br>1st Variable Name: firstName,
<br>2nd Variable Values: "Doe"
<br>3rd Variable Name: age & Values: 35

```Javascript Code```
```javascript
let firstName = "John";
let lastName = "Doe";
let age = 35;
```

<br>

### 03.

**Answer:** The value of 'x' after using the assignment operator<br>

```Javascript Code```
```javascript
let x = 10;
let y = 5;
x *= y; 
console.log(x); // output: 50
```

<br>

### 04.

**Answer:** Writting data types by using comments<br>

```Javascript Code```
```javascript
let length = 16; // data type: Number
let lastName = "Johnson"; // data type: String

const x = {
  firstName: "John",
  lastName: "Doe",
}; // data type: Object
```

<br>

### 05.

**Answer:** : Executing the function named myFunction<br>

```Javascript Code```
```javascript
function myFunction() {
  alert("Hello World!");
}
myFunction(); // calling the function
```

<br>

### 06.

**Answer:** Creating the Object<br>

```Javascript Code```
```javascript
let person = {
  name: "John",
  age: 50,
};
alert(`${person.name} is ${person.age}`); // output: John is 50
```

<br>

### 07.

**Answer:** fixing the button click <br>

```html code```
```html
<button onclick="clickFunction()">Click me</button>
```

```Javascript Code```
```javascript
function clickFunction() {
    alert("you clicked me");
}
```

<br>

### 08.

1. **Answer:** Alerting the number of items in an array<br>

```Javascript Code```
```javascript
const cars = ["Volvo", "Jeep", "Mercedes"];
alert(cars.length); // output: 3
```

<br>

2. **Answer:** Changing the first item of Brand to "Ford".<br>

```Javascript Code```
```javascript
const Brand = ["Volvo", "Jeep", "Mercedes"];
Brand[0] = "Ford";
console.log(Brand); //output: ["Ford", "Jeep", "Mercedes"];
```

<br>

### 09.

1. **Answer:** Random number between 0 & 1<br>

```Javascript Code```
```javascript
const randomNumber = Math.random();
console.log(randomNumber); //output: random number
```

<br>

2. **Answer:** The largest number of 10 and 20<br>

```Javascript Code```
```javascript
const largestNumber = Math.max(10, 20);
console.log(largestNumber); // output: 20
```

<br>

3. **Answer:** Square root of 9<br> 

```Javascript Code```
```javascript
const squareNumber = Math.sqrt(9);
console.log(squareNumber); // output: 3
```

<br>

### 10.

1. **Answer:** comparison operator to alert true, when x is greater than y.<br>

```Javascript Code```
```javascript
x = 10;
y = 5;
alert(x>y) //output: true
```

<br>

2. **Answer:** Conditional (ternary) operator to alert "Too young" if age is less than 18, otherwise alert "Old enough"<br>

```Javascript Code```
```javascript
let age = 15;
alert(age < 18 ? "Too young" : "Old enough"); //output: Too young
```

<br>
<hr>

<div align="center"><h1>2. JavaScript Basic Problems Solving </h1></div>

### 01.

**Answer:** A function to convert Celsius to Fahrenheit<br>

```Javascript Code```
```javascript
function celsiusToFahrenheit(celsius) {
  return (celsius*9)/5+32;
}
let celsius = 20;
let fahrenheit = celsiusToFahrenheit(celsius);

console.log(fahrenheit); // output: 68
```

<br>

### 02.

**Answer:** A function to check if a number is even<br>

```Javascript Code```
```javascript
function isEven(num) {
  return num % 2 === 0;
}

console.log(isEven(4)); // output: true
console.log(isEven(7)); // output: false
```

<br>

### 03.

**Answer:** A function to sum two numbers<br>

```Javascript Code```
```javascript
function sum(a, b) {
  return a+b;
}

console.log(sum(3, 4)); // output: 7
console.log(sum(10, 20)); // output: 30
```

<br>

### 04.

**Answer:** A function to find the smallest number in an array<br>

```Javascript Code```
```javascript
function findSmallestNum(arr) {
  return Math.min(...arr);
}

console.log(findSmallestNum([3, 5, 1, 9])); // output: 1
console.log(findSmallestNum([-1, -5, 0, 10])); // output: -5
```

<br>

### 05.

**Answer:** A function to count the number of vowels in a string<br>

```Javascript Code```
```javascript
function countVowels(str) {
  let vowels = 'aeiouAEIOU';
  return str.split('').filter(char => vowels.includes(char)).length;
}

console.log(countVowels("hello world")); // output: 3
console.log(countVowels("Javascript")); // output: 3
```

<br>

### 06.

**Answer:** A function to get the first element of an array<br>

```Javascript Code```
```javascript
function getFirstElement(arr) {
  return arr[0];
}

console.log(getFirstElement([1, 2, 3])); // output: 1
console.log(getFirstElement(["a", "b", "c"])); // output: a
```

### 07.

**Answer:** A function to check if an array is empty<br>

```Javascript Code```
```javascript
function isArrayEmpty(arr){
  return arr.length === 0;
}

console.log(isArrayEmpty([])); // output: true
console.log(isArrayEmpty([1, 2, 3])); // output: false
```

### 08.

**Answer:** A function to return the factorial of a number<br>

```Javascript Code```
```javascript
function factorialize(num){
  if (num === 1 || num === 0) return 1;
  return num * factorialize(num - 1);
}

console.log(factorialize(5)); // output: 120
console.log(factorialize(7)); // output: 5040
```

<br>

### 09.

**Answer:** A function to reverse a string<br>

```Javascript Code```
```javascript
function reverseString(str) {
  return str.split("").reverse().join("");
}

console.log(reverseString("hello")); // output: "olleh"
console.log(reverseString("world")); // output: "dlrow"
```
<br>

### 10.

**Answer:** A function to convert a string to lowercase<br>

```Javascript Code```
```javascript
function toLowerCase(str) {
  return str.toLowerCase();
}

console.log(toLowerCase("HELLO WORLD")); // output: "hello world"
console.log(toLowerCase("JavaScript")); // output: "javascript"
```


<br>

### 11.

**Answer:** A function to find the length of a string<br>

```Javascript Code```
```javascript
function stringLength(str) {
  return str.length;
}

console.log(stringLength("hello")); // output: 5
console.log(stringLength("world")); // output: 5
```

<br>

### 12.

**Answer:** A function to merge two arrays<br>

```Javascript Code```
```javascript
function mergeArrays(arr1, arr2) {
  return [...arr1, ...arr2];
}

console.log(mergeArrays([1, 2, 3], [4, 5, 6])); // output: [1, 2, 3, 4, 5, 6]
console.log(mergeArrays(["a", "b"], ["c", "d"])); // output: ["a", "b", "c", "d"]
```

<br>

### 13.

**Answer:** A function to get the last element of an array<br>

```Javascript Code```
```javascript
function getLastElement(arr) {
  return arr[arr.length - 1];
}

console.log(getLastElement([1, 2, 3])); // output: 3
console.log(getLastElement(["a", "b", "c"])); // output: c
```

<br>

### 14.

**Answer:** A function to get the first character of a string<br>

```Javascript Code```
```javascript
function getFirstCharacter(str) {
  return str[0];
}

console.log(getFirstCharacter("hello")); // output: h
console.log(getFirstCharacter("world")); // output: w
```

<br>

### 15.

**Answer:** <br>

```Javascript Code```
```javascript
function sumArray(arr) {
  return arr.reduce((total, num) => total + num, 0);
}

console.log(sumArray([1, 2, 3, 4])); // output: 10
console.log(sumArray([-1, -2, -3, -4])); // output: -10
console.log(sumArray([1.5, 2.5, 3.5])); // output: 7.5
```

<br>

<div align="center"><h1>Thank you &copy; Eyachir</h1></div>
