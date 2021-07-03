# CH10  
## ORDER OF EXECUTION 
### -To find the source of an error, it helps to know how scripts are processed. 
## EXECUTION CONTEXTS 
### -the JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope. Every statement in a script lives in one of three execution contexts:
1- GLOBAL CONTEXT: Code that is in the script, but not in a function. There is only one global context in any page.
2- FUNCTION CONTEXT: Code that is being run within a function. Each function has its own function context. 
3- EVAL CONTEXT: (NOT SHOWN) Text is executed like code in an internal function called eva l {) 
## ERROR OBJECTS 
### -Error objects can help you find where your mistakes are and browsers have tools to help you read them. 
[table of errors](lab10-1.png)
## HOW TO DEAL WITH ERRORS
### -Now that you know what an error is and how the browser treats them, there are two things you can do with the errors:
1- **DEBUG THE SCRIPT TO FIX ERRORS**:  If you come across an error while writing a script (or when someone reports a bug), you will need to debug the code, track down the source of the error, and fix it.
2- **HANDLE ERRORS GRACEFULLY**: You can handle errors gracefully using try, catch, throw, and f i na 1 ly statements.
## A DEBUGGING WORKFLOW 
### -Debugging is about deduction: eliminating potential causes of an error. 
### WHERE IS THE PROBLEM?
#### -First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important
##### 1. Look at the error message, it tells you:
• The relevant script that caused the problem. 
• The line number where it became a problem for the interpreter. (As you will see, the cause of the error may be earlier in a script; but this is the point at which the script could not continue.) 
• The type of error (although the underlying cause of the error may be different). 
#### Secondly, Check how far the script is running. 
1- Use tools to write messages to the console to tell 
2- how far your script has executed. 
#### Third, Use breakpoints where things are going wrong. 
1- They let you pause execution and inspect the values 
2- that are stored in variables.

