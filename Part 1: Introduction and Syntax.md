## Functions

Functions are the heart and soul of JavaScript developers. Everything that a modern application does is done in a function. An application can have hundreds, possibly thousands, of tasks that it must perform to solve a problem or provide a service to humans. Each one of those tasks is in a function.

**You can think of a function as a container for code that completes a specific task.**

These tasks are referenced with a variable, just like numbers, arrays and objects. Here is the basic syntax of what we call an arrow function. It's a very concise syntax for defining a task.

```js
const descriptiveVariable = () => {
	// Code to perform the task goes here
}
```

Think of functions like minions that work for you. Each minion is designated a specific task that makes up your life.

* Buy groceries
* Pay bills
* Prepare meals
* Do math stuff when you don't want to (_which, if we're being honest, is most of the time_)
* Take the car to the repair shop

## Buying Grocery Task

Functions sometimes need to be given information in order to complete the task. Let's look at how you would write task code for a minion that buys groceries.

```js
const buyGroceries = () => {
	// Code to buy groceries with money
}
```

Since the minions can't read your mind, that means that you must provide it with the list of items you want it to purchase. Otherwise, the minion can't do its job.

In a JavaScript function, you specify that input of information with what's called a **_parameter_**. Parameters go inside the parenthesis before the arrow. In the code below, the **_arrayOfFoodToBuy_** variable is the parameter for the function.

It is important to note that parameters only work inside the function. The variable that you type inside those parenthesis cannot be used anywhere else in your code. You will be reminded of this fact throughout this series of exercises.

```js
const buyGroceries = (arrayOfFoodToBuy) => {
	// Code to buy groceries with money
	for (const food of arrayOfFoodToBuy) {
		console.log(`I bought ${food}`)
	}
}
```

What you have now is a definition of a task. The minion hasn't been told to perform the task yet, though. You need to tell the minion which food to buy, and then direct the minion to start the task. 

This is called **_invoking_** a function. You type in the name of the task, and then put parenthesis after it. Inside the parenthesis, you provide the information that the minion needs. In this case, it needs an array of food items to buy.

```js
// Define the task for a minion
const buyGroceries = (arrayOfFoodToBuy) => {
	// Code to buy groceries with money
	for (const food of arrayOfFoodToBuy) {
		console.log(I bought ${food})
	}
}

// Tell the minion to perform the task with specific information
buyGroceries(.["Milk", "Onions", "Ketchup"] )
 ````

Once you have provided that instruction of invoking the function, the minion dutifully performs its task by following the instructions you provided inside the function.

## Practice: Filling the Tank

You have some starter code provided. It's a blank function that defines the task of filling your car up with gas. You can see that the minion will let you know that it filled up the car with gas, but **you** need to tell it how much gas you want put into the tank.

Since the minion needs information from you to do its job, you need to define the parameter of `gallons` inside the parenthesis. When you do that successfully, run the code and the minion will let you know when it completes the task.

Now change the **_argument_** value. It is currently 15. Change it to any other number and see how the behavior of the function changes when the argument does.






# Starter Code
```js
const fillGasTank = () => {
	console.log(`I filled the tank with ${gallons} of gas`)
}

fillGasTank(15)
```
