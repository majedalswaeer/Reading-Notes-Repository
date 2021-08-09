# Passing Functions as Props

## What does .map() return?
* it returns a modifed array by a certian function
## If I want to loop through an array and display each value in JSX, how do I do that in React?
* Ans: create a component then a constructor that has a render function then i go to the parent component to call the child component using a for loop that existed in a container in the return
## Each list item needs a unique __key__

## What is the purpose of a key?
Ans: make a unique key for each componen to not have problems when i upload to netlify

# Spread operator

## What is the spread operator?
* Ans:the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments, Spread operator to the rescue! It looks similar to rest parameters, also using ..., but does quite the opposite.

## List 4 things that the spread operator can do.
1- Copying an array
2- Using Math functions
3- Using an array as arguments
4- Adding to state in React

## Give an example of using the spread operator to combine two arrays.

```
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

```

## Give an example of using the spread operator to add a new item to an array.

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

```

## Give an example of using the spread operator to combine two objects into one

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

```

# How to Pass Functions Between Components

## In the video, what is the first step that the developer does to pass functions between components?
* Ans: creating a state to pass the function to other components

## In your own words, what does the increment function do?
*Ans: simply when i click on a button the counter will update

## How can you pass a method from a parent component into a child component?
* Ans: with props i can pass all i need to child components

## How does the child component invoke a method that was passed to it from a parent component?

* Ans: using props also and execute the method you want by having an if condition or other statments.

