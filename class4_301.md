# React and Forms

## What is a ‘Controlled Component’?
* Ans: An input form element whose value is controlled by React

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
* Ans: the displayed value will update as the user types, because handleChange runs on every keystroke to update the React state

## How do we target what the user is entering if we have an event handler on an input field?
* Ans: Since the value attribute is set on our form element, the displayed value will always be this.state.value

# The Conditional Operator 
## Why would we use a ternary operator?
* Ans: 1- The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.
2- A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.
3- Finally a : colon. If your condition evaluates to false, any code after the colon is executed.
example: 
```
let person = {
  name: 'tony',
  age: 20,
  driver: null
};
person.driver = person.age >=16 ? 'Yes' : 'No';

```

## Rewrite the following statement using a ternary statement:
```
 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

```
*Ans:

```
x=y? 'true':'false'

```
