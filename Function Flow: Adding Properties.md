## Student Grades

Remember that to add a new property to an object, you use dot notation and an equals sign after the object is created.

```js
// Object creation
const dog = {
	breed: "Shihtzu",
	age: 1,
	name: "Murph"
}

// Adding a property after creation
dog.neutered = true

console.log(dog)

> {
	breed: "Shihtzu",
	age: 1,
	name: "Murph",
	neutered: true
}
```

In this exercise, you have three functions. Each of which adds a grade for a subject to a student object. 

The original studentObject that is created at the beginning must flow through all of the function - passed in as an argument, being returned from the function, captured into a variable, and then being passed to the next function.

1. addMathGrade() should add a new "math" property to the student with a value of "B".
2. addHistoryGrade() should add a new "history" property to the student with a value of "C".
3. addScienceGrade() should add a new "science" property to the student with a value of "A".

Remember to follow the flow that you learned about in the last chapter.

1. Each function should define a parameter to hold the object.
2. Each function should be invoked with an object provided as an argument.
3. Each function should return the object after the property is added.
4. The return value of the function should be stored in a variable.

```js
const example = { }

const returnValueOne = firstFunction(example)
const returnValueTwo = secondFunction(returnValueOne)
const returnValueThree = thirdFunction(returnValueTwo)
```

Notice the pattern? The variable from a line above is always provided as an argument to the next function. This isn't always the case, but for these exercises, you will be following this pattern most of the time because it is a highly common pattern of writing software.

Now it is your turn to invoke all three grading functions, and then use `console.log()` to output the final state of the object. It should have all of the properties on it in the console.

```js
{
	student: "Andri Alexeandrou",
	grade: 6,
	math: "B",
	history: "C",
	science: "A"
}
```




# Sample Code

```js
const student = {
	student: "Andri Alexeandrou",
	grade: 6
}

const addMathGrade = () => {

}

const addScienceGrade = () => {

}

const addMathGrade = () => {

}

```
