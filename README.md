# 2.3 - Mathematics

##### ICS3 - Mr. Brash 🐿️

**If you missed the live demonstration in class, read below. Otherwise you can go straight to [your task](./YOUR_TASK.md).**

- Want to [watch a video](https://youtu.be/adReYfUPPoQ) instead?

### Mathematics in Code
The _symbols_ we use to do math are called **operators**.<br>
The list of _operators_ [is available here](https://www.w3schools.com/js/js_operators.asp).
The list of _assignment operators_ [is available here](https://www.w3schools.com/js/js_assignment.asp).

```JS
// Add, subtract, etc...
let x = 1;
x = x + 5;
x = 7 - 2;
x = x * 3;
x = 24 / 8;

// Exponent
let four_squared = 4**2;
let six_cubed = 6**3;

// Math Shortcuts
x = x + 3;
x += 3;   // Add 3 to x's current value

x = x - 2;
x -= 2;   // Reduce x's value by 2

x *= 4;   // Multiply 4 into the value of x
x /= 2;   // Divide x by 2 and store it back in x

// Incrementation (increase or decrease the variable by 1)
x++;
x--;

/* Anything in "quotes" is text (called a String)
 * We can combine (concatenate) strings */
let first = "Mr.";
let last = "Brash";
let myName = first + " " + last;      // The simple way

// It is NOT possible to subtract strings
myName = myName - "B";  // Not possible
```

### The Math Object
JavaScript has a special [Math object](https://www.w3schools.com/js/js_math.asp) for doing complicated stuff.
- `Math.random()`  // Get a random decimal number bettwen 0 and 1
- `Math.round()`   // Round to the nearest whole value
- `Math.sqrt()`    // Take the square root of the number

### Examples:
```JS
// Calculate the area of a circle with radius of 3
let r = 3;
let area_circle = Math.PI * r**2;
```
```JS
// Calculate pythagorean theorem
let a = 8;
let b = 4;
let c = Math.sqrt(a**2 + b**2);
console.log(`The hypotenuse of a triangle with sides ${a} and ${b} is ${c}`)
```

**Now go check out [your task](./YOUR_TASK.md).**

<br>
<br>
🐿️
