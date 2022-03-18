# Debugging

## JS

# Ch 10: Error Handling & Debugging

- The key to finding an error is following the process order and tracking statements
- lines of code are processed on at a time
- when data is being called then the statements will start to stack
- When JavaScript runs into an error it will throw an exception and follow up with exception handling code
- You can either fix the script directly or use `try`, `catch`, `throw`, and `finally` statements to catch exceptions
- The JavaScript terminal will tell you what the error is and what line its found at
- console logs are useful in tracking where exactly your code may be breaking
- `console.assert()` will only executes if the condition that your looking for evaluates to true
- You can use breakpoints to stop your script at the designated point
- You can then step through your code to see what exactly is going on as you walk through each statement
- the `debugger` key word will insert a breakpoint

[Return to Code 201 Table of Contents](https://rogermreyes.github.io/Reading-Notes/Code-201-Reading-Notes)
