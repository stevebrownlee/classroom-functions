## Deconstructing Goals into Functions

We want to make sure the stage is set before you dive into functions. Learning how to define, write, and use functions has humbled some of the smartest people we've ever known. 

We don't want to scare you away. Functions aren't scary. In fact, after you are done with the exercises in this classroom, you will likely say to yourself, "Well, that wasn't as bad as I was expecting!" This caution is to make sure you are mentally prepared to feel dumb for a bit while you learn how to define, write, and use functions in software.

Stick with us. We will do our best to get you there. Crying is ok.

## Deconstruction

One of the reasons it is difficult to achieve proficiency with functions is because they are the end result of deconstruction - a two part job. 

* Part one is breaking down a large task into very small units of work.
* Part two is naming and coding those individual units of work in JavaScript.

The more experience you have had with deconstruction in your life up to this point absolutely determines how long it takes to gain proficiency in doing it with code. Some people become proficient in 2-3 weeks. For others, it takes 2-3 months.

It has nothing to do with innate ability, and everything to do with practice and your brain's neural structure. 

## Goal: Baking a Cake

Baking a cake involves many steps. An expert, professional baker has internalized the steps and can perform the task without too much thought. For a beginner, the process needs to be deconstructed into the various sub-processes in order to do it correctly. You can consider your computer to be a beginner at absolutely everything. If you want to write code that bakes a virtual cake, you need to deconstruct it into the steps, and then tell it to follow the steps in the right order.

### Individual Tasks for Baking a Cake

1. Make sure you have all the ingredients
2. Measure ingredients
3. Prepare the batter
4. Prepare the baking pan
5. Heat the oven to the correct temperature
6. Start baking
7. Rotate the cake
8. Test the cake 
9. Put frosting on cake 

### One Function For Each Task

An experienced software developer will then define one function for each of those tasks. All of those steps should never be written inside of a single function. It makes the code harder to read, and it makes it harder to change.

Here's some sample functions, each assigned to an appropriately named variable.

```js
const rotateCake = () => {
	// Code to rotate the cake
}

const gatherIngredients = () => {
	// Code to gather the ingredients from storage
}

const measureIngredients = () => {
	// Code to measure the ingredients
}

const addFrosting = () => {
	// Code to add frosting to a baked cake
}

const startOven = () => {
	// Code to turn on the oven to a specific temperature
}

const createBatter = () => {
	// Code to create some cake batter
}

const checkIfDone = () => {
	// Code to check if the cake is done
}

const startBaking = () => {
	// Code to put the cake batter into the oven
}
```

The above code **defines** the tasks. The order in which they are defined does not matter. Then, each task can be executed by a software developer in the correct order.

```js
startOven()
gatherIngredients()
measureIngredients()
createBatter()
startBaking()
rotateCake()
checkIfDone()
addFrosting()
```

## Next Steps

Just click the Submit button for this exercise to move on to the next one where can can start writing some functions that define the tasks involved in a larger process.










