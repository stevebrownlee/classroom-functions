## Candy Function Flow

Now that you have spent a few exercises writing functions that have parameters, add properties to objects, and have condition logic inside of them, it's time to actually invoke those functions. Since you just got done with the candy functions, you will go right back to it and invoke them.

#### Reminder: JavaScript ignores your variables. They are for humans. All JavaScript cares about is the value that's assigned to them.

## Review

It's time to practice the confusing flow of passing values around to different functions again.

```
Value sent to function as an argument 
   -> Function stores value in a parameter
      -> Function does something with the value
         -> Function returns the updated value
            -> Returned value gets stored in a variable
               -> Go back to first step and repeat
```

A quick review of example syntax is below. In case it hasn't been mentioned yet, you need to remember that when a function returns a value, you must store that value in a variable.

```js
const returnValueFromFunction1 = function1()
const returnValueFromFunction2 = function2(returnValueFromFunction1)
const returnValueFromFunction3 = function3(returnValueFromFunction2)
const returnValueFromFunction4 = function4(returnValueFromFunction3)
```

See the pattern?

It's almost of if the code executes from right to left. In fact, this is exactly what's happening, and that's exactly why most humans struggle to understand it. Most cultures read text from left to right.

If you can start the process of training your brain to read code like this from right to left, it's the first step in remembering the flow.

## Practice

All of the function definitions are provided for you. You don't need to change anything about them.

You will notice that there is one additional function at the end, with nothing in it but a comment. Its assigned to the makeCandy variable. You will be writing all of your code inside that function. Follow the data flow pattern that you practiced in previous exercises, and was reviewed above.

On your last line of code, make sure you return the variable that stores the return value of breakBark().

This is an example of what the last two lines in the function should look like. DO NOT COPY THIS CODE. Use your own variable names for the return values.

```js
const pieces = breakBark(bakeCandyReturnValue)
return pieces
```

Feel free to use `console.log()` every time you invoke a function and capture its return value. 

#### Example

```js
const bug = catchBug()
console.log(bug)

const jar = putBugInJar(bug)
console.log(jar)

const box = putBugJarInBox(jar)
console.log(box)
```



















.
