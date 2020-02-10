# **What I Learned in Week 3**

### Booleans Operators

* **===** - equals
* **!==** - does not equal
* **>** - greater than
* **<** - less than
* **>=** - greater than or equal to
* **<=** - less than or equal to

### Array

A variable used to store multiple elements. 

i.e.
> * const x = [1,2,3,4,5]
> * x[0] = 1
> * x[1] = 2
> * x[2] = 3

### If and Else

if (condition){
    if true execute this code
}
else if (condition){
    if this one is true then execute this code
}
else {
    execute this code if all previous conditions are false
}

### App - Back-End Code

* input code in a function here

* export it with module.exports command

### App - Front-End Code

* code that end user interacts with
* import back-end function into a variable using require command
* process.argv[] expects numbers as parameters and returns the array value of the command line input that the parameter specifies. For example const x = process.argv[2] would make the value of x 5 if the user typed node ./front-end.js 5 + 5
* store the return value for the function into a variable
* print the return value back to the user using the console.log command