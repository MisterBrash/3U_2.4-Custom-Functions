# 2.4 - Custom Functions

##### ICS3 - Mr. Brash 🐿️

**If you missed the live demonstration in class, read below. Otherwise you can go straight to [your task](./YOUR_TASK.md).**

A `function` is something that is repeatable, with a specific purpose. The human body has countless `functions` from respiratory and coronary, to balance, movement, and sleep. Even just _blinking_ is a `function` of the human body.

**Mathematical `functions`** are similar - area of a circle, pythogorean theorem, the quadratic formula, etc.

**Code `functions`** are the same! They perform an action the same way, every time.

You have been using `functions` to _command_ the code to do something:
```JS
console.log(`You area ${age} years old.`);  // The console's log() function
let x = Math.round(value);                  // The round() function
let rnd = Math.random();                    // The random() function
```

### 💡 More JS _Functions_ - User Input!

While it's not very pretty, JavaScript has a `prompt()` _function_ which asks the user for some input.

```JS
let user_age = prompt("How old are you?");
```

❕**There is a minor issue** - the input always comes in as a _String_.
```JS
console.log(typeof user_age);

'string'
```

**Thankfully**, there is a function to attempt to convert to a number!
```JS
user_age = Number(user_age);

console.log(typeof user_age);

'number'
```

**Now you know two more `functions`!** They can even be combined:
```JS
let length = Number(prompt("Please give a length in centimeters."));
```

---

### 🙌🏻 We can make our _own_ functions!

In programming, these are called "custom functions" and _sometimes_ "user-defined functions".

- What if you wanted a function that outputs the current time?
- How about a function that calculates the distance from your position to an enemy position?
- Perhaps a random number generator for rolling dice?

### The syntax is simple:
```JS
function name() {

    // Code goes here

}
```

### Example 1:
```JS
function say_hello() {

    console.log("Hello!");

}
```

When a JavaScript file is loaded, it stores the functions into memory, ready to by run whenever the programmer wants.

In order to _run_ our custom function, we "call" it:
```JS
say_hello();    // This "calls" our custom function, which prints "Hello!"
```

### Example 2:
Let's make an area of the circle function (this is in your [main.js](./main.js) file)
```JS
function circle_area() {
    let radius = Number(prompt("What is the radius for the circle?"));
    console.log(`The area is: ${Math.PI * radius**2}`);
}
```

We can test or use our function by going to the console and running `circle_area()`. Give it a try!


---

**Now go check out [your task](./YOUR_TASK.md).**

<br>
<br>
🐿️
