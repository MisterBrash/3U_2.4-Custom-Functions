### 2.3 - Mathematics

##### ICS3 - Mr. Brash 🐿️

# 📝 Your Task:

We are going to ask the computer to convert temperatures.

The equation to convert Fahrenheit to Celsius is:
> C = (F - 32) * 5/9

In the above equation, we _know_ the Fahrenheit value `F` and use it to create and store the new Celsius value into `C`.

The equation to convert in the _opposite_ direction is:
> F = (C * 9/5) + 32

#### We will use the code file [main.js](./main.js) and printing to the console to see our answers

**Part 1: Convert Celsius to Farenheit**
  1. Declare a variable and call it `celsius`, setting `celsius` to 100.
  2. Declare _another_ variable and call it `fahrenheit` - setting this variable to 0.
  3. Let's add 2 to `celsius`, just to practice that skill.
  4. Using the correct equation (above) and the value of the variable `celsius`, convert that temperature to degrees Fahrenheit and store the answer in your `fahrenheit` variable. This will overwrite the value of 0 you set in step 2.
  5. Output the value of `fahrenheit` to the console. Just the number.

**Part 2: Convert Farenheit to Celsius**
  This task will reuse the variables from Part 1 - *no* new `let` statements required.
  1. Now set `fahrenheit` to 77 
  2. Using the correct equation, convert from this Fahrenheit value to Celsius, and store the answer in the `celsius` variable.
  3. Output the current value of `celsius` to the console. Just the number.
  
**Part 3: Now for some text:**
  Printing just the numbers is boring. Let's try that output again (on a new line) but with some pizzazz!
  - Using the variables `farenheit` and `celsius` create an output that looks like this:  `{value} degrees Fahrenheit is {value} degrees celsius.` where {value} gets replaced by the appropriate numbers from your variables.

**Part 4: Slope**
  1. Slope of a line is defined as `m = (y2 - y1)/(x2 - x1)`. Define a variable `m` and compute the slope from point A(-4, 5) to point B(6, 0), and store it into `m`.
  2. Print the value of `m` to the console.

**Part 5: The Math object**
  Lets use the [Math object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math) a little to create a random volume of a cylinder. Reminder:  V = π r² h
  1. Create a random radius between 0 and 10
  2. Create a random height between 0 and 10
  3. Use `Math.PI` and `Math.round()` to calculate the volume of this cylinder.
  4. Output the volume of the cylinder as: `The volume of my random cylinder is {value}`

<br>

---

<br>

🕒 If you finish with class time left, you can do independent learning.
