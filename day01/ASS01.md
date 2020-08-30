# javascript-essentials
# various methods in the java script console function.

In javascript, the console is an object which provides access to the browser debugging console. We can open a console in web browser by using: Ctrl + Shift + K for windows and Command + Option + K for Mac. The console object provides us with several different methods, like :

log()

error()

warn()

clear()

time() and timeEnd()

table()

count()

group() and groupEnd()

custom console logs

Let’s look at all these methods one by one.

# console.log()

Mainly used to log(print) the output to the console. We can put any type inside the log(), be it a string, array, object, boolean etc.

# console.error()

Used to log error message to the console. Useful in testing of code. By default the error message will be highlighted with red color.

# console.warn()

Used to log warning message to the console. By default the warning message will be highlighted with yellow color.

# console.clear()

Used to clear the console. The console will be cleared, in case of Chrome a simple overlayed text will be printed like : ‘Console was cleared’ while in firefox no message is returned.

# console.time() and console.timeEnd()

Whenever we want to know the amount of time spend by a block or a function, we can make use of the time() and timeEnd() methods provided by the javascript console object. They take a label which must be same, and the code inside can be anything( function, object, simple console).

# console.count()

This method is used to count the number that the function hit by this counting method.

# console.group() and console.groupEnd()

group() and groupEnd() methods of the console object allows us to group contents in a separate block, which will be indented. Just like the time() and the timeEnd() they also accepts label, again of same value.

# Custom Console Logs

User can add Styling to the console logs in order to make logs Custom . The Syntax for it is to add the css styling as a parameter to the logs which will replace %c in the logs as shown in the example below .

# Difference between var,let and const in JavaScript

var and let are both used for variable declaration in javascript but the difference between them is that var is function scoped and let is block scoped.
It can be said that a variable declared with var is defined throughout the program as compared to let.where as const refers to the variable which are constant through out the script and it can't be affected by other variables if we intend to do that we tend raise an error.

An example will clarify the difference even better
//var

var name="lakshman"

var age="24"

var canFly = True

var languages = ["hindi","english","telugu"]

var friends={

    name:"mike",
    
    hobby:"analytics"
    
}

var a =10;

console.log(a);

var a =null;

console.log(a)

console.log("name logged without using let", name)


//let

{
    //let name="lekah";
    
    name="srilu"
    
    console.log("name is printed using Let",name)
    
}

//const

const country="USA";

console.log(country)

// country="UK"

const genre=["horror","romance","comedy"]

console.table(genre)

genre.push('scifi')

console.log(genre)

genre=["horror","romance"]

# JavaScript Data Types
There are eight basic data types in JavaScript. They are:

# String
represents textual data	'hello', 

"hello world!" etc

# Number	
an integer or a floating-point number	

3, 3.234, 3e-2 etc.

# BigInt	
an integer with arbitrary precision	

900719925124740999n , 1n etc.

# Boolean	
Any of two values: true or false	

true and false

# undefined	
a data type whose variable is not initialized	

let a;

# null	
special keyword denoting a null value	

let a = null;

# Symbol	
data type whose instances are unique and immutable	

let value = Symbol('hello');

# Object	
key-value pairs of collection of data	

let student = { };










