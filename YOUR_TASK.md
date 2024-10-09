### 2.4 - Custom Functions

##### ICS3 - Mr. Brash 🐿️

# 📝 Your Task:

Once again we are going to convert temperatures, but this time the _user_ will enter a value to convert!

Reminders:

> Celsius = (Fahrenheit - 32) * 5/9  
Fahrenheit = (Celsius * 9/5) + 32

### Part 1: Convert Celsius `to_fahrenheit()`

Create the function `to_fahrenheit()` that asks the user for a temperature in _Celsius_ and converts the value to a temperature in Fahrenheit. _Round the answer to the nearest whole degree_.

Output the answer as follows substituting `{value}` for the correct numbers:
```TXT
{value}° Celsius is equal to {value}° Fahrenheit
```

---

### Part 2: Convert Fahrenheit `to_celsius()`

Create the function `to_celsius()` that asks the user for a temperature in _Fahrenheit_ and converts the value to a temperature in Celsius.  _Round the answer to the nearest whole degree_.

Output the answer as follows substituting `{value}` for the correct numbers:
```TXT
{value}° Fahrenheit is equal to {value}° Celsius
```

---

### Part 3: `roll_d10()`

**Recall:**  
`Math.random() * 10` gives us values from 0-9 with a bunch of decimals.  
`Math.floor(Math.random() * 10)` gives us _whole_ numbers from 0 to 9 [inclusive].

🤔 How can we modify this to get 1-10 instead of 0-9?  

🔟 A 10-sided die gives the numbers 1-10 with equal chance. We are going to create the function `roll_d10()` that prints to the console a _random_ value from 1-10 [inclusive].

Test your code by running `roll_d10()` on the console.

---

### Part 4: `roll_d6()`

🎲 A typical 6-sided die has... wait for it... 6 sides! 

🤔 Now how can we modify our code from `roll_d10()` to write `roll_d6()` and give us values 1-6 instead of 1-10?

Test your code by running `roll_d6()` on the console.

---

### Part 5: Play

You now have a very powerful set of skills:
- Getting user input (and converting to a number)
- Complex mathematics
- A random number generator
- Creating custom functions

Utilize this playground to continue to play!

<br>
<br>

🐿️
