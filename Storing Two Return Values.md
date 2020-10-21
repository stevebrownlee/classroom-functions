## Double Your Fun

In the code editor, you have two functions. Each returns a string. You don't need to change anything about the functions. However, you do need to store their returned values into variables on the lines where the functions are invoked.

Then, using interpolation, put both of those strings into a larger one that looks like the one below. Also store this new string in a variable. Name that variable whatever you wish.

"Double your pleasure, double your fun!"

Then log the value of that variable to the console.

```js
const pleasure = () => {
	return "Double your pleasure"
}

const fun = () => {
	return "double your fun"
}

// The return values of these functions are not being captured into variables
pleasure()
fun()

// Use ${} to combine the strings into a larger one


// console.log() the variable whose value is the larger string
```
