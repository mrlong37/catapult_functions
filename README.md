# Lesson 4.3: Basic Conditional Statements

## Conditional Statements
Conditional statements allow you to execute different actions under different conditions. They are a fundamental part of programming logic and are used to make decisions within your code.

### Syntax of Conditional Statements
```javascript
if (condition) {
  // statement 1
} else {
  // statement 2
}
```
- `if`: The keyword to start the conditional statement.
- `condition`: An expression that evaluates to true or false.
- `else`: The keyword for the alternate path when the condition is false.

### Examples
1. Basic Example:
    ```javascript
    let age = 17;
    if (age > 16) {
      console.log("You can drive!");
    } else {
      console.log("Sorry. Too young!");
    }
    ```

2. Working with Strings:
    ```javascript
    let weather = "raining";
    if (weather === "raining") {
      alert("☔️");
    } else {
      alert("☀️");
    }
    ```

### Operators in Conditions
- `<`: Less than.
- `>`: Greater than.
- `<=`: Less than or equal to.
- `>=`: Greater than or equal to.
- `===`: Equal to.
- `!==`: Not equal to.

### Real-World Analogies
- If it's raining outside, bring an umbrella; otherwise, bring sunglasses.
- If travel time is more than 1 hour, read a book; otherwise, listen to music.
- If it's a weekday, go to sleep at 10 PM; otherwise, stay up and play video games.

---

Happy coding! 😊