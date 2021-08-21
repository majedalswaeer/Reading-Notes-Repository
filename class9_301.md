# Functional Programming Concepts



## What is functional programming?
* Ans: Functional programming is a programming paradigm , a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data
## What is a pure function and how do we know if something is a pure function?
1- It returns the same result if given the same arguments (it is also referred as deterministic)
2- It does not cause any observable side effects
## What are the benefits of a pure function?
* Ans: asier to test. We don’t need to mock anything
## What is immutability?
* Ans:means that the data unchanging over time or unable to be changed.
## What is Referential transparency?
* Ans:  if function consistently yields the same result for the same input, it is referentially transparent.

********************************************************

# Modules and require()

## What is a module?
* Ans: Within a module, we can use the export keyword to export just about anything.
## What does the word ‘require’ do?
* Ans: it allows us to use functions that are existed in other js file
## How do we bring another module into the file the we are working in?
* Ans: by using export keyword, we can export anything we want
## What do we have to do to make a module available?
* Ans: by typing require on the page that we want to use the functions