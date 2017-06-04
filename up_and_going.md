# Y.D.K.J.S UP and Going

Javascript has built in types for each of these primitive values
values included directly in the source code are called literals

converting types to each other 
*explicit coercion*

```
	 var a = "42";
	var b = Number(a) //42
```
Trying to compare values that are not of the same type 

*implicit coercion*

```
	"99.99" == 99.99 //use the two == for loosely equals 

	this converts the expression to 99.99 == 99.99 (true)
```

##  Comments

 *Rules of commenting*
1. Code without comments is suboptimal
2. Too many comments is  a sign of poorly written code
3. Comments should explain why and not what. ANd how if the code is a bit confusing

//single-line comments

/*
	This is amultiline comment

*/

## Variables

Variable is a container that is assigned a specific value

#### variable declaration

1. static typing/type enforcement -This is when a variable declared can only
hold a value from a specific type 

2. dynamic typing/ weak typing - allos a variable to hold any type of value
at anytime

primary job of variables is to manage program state

*state* is tracking the changes to values as your program runs.


### Constants
A variable with a value that is not intended to change.

By convention a constant:

1. Declared at the top of the page
2. All letters are capitalized
3. words are separated by underscores

in es6 to declare constants we use const instead of var

ie :
	 var TAX_RATE = 0.08;
	 const TAX_RATE=0.08; //new to es6

### Loops
each time a loop block is executed it is called an iteration

*while loops and do while loops*

A while loop the conditional is tested before the first iteration

while a do-while loop the conditional is tested after the first iteration

for loops have 3 clauses

for(var i = 0; i <=9; i++){}

1. the initialization clause  i = 0;
2. the conditional clause i < = 9;
3. the update clause i++;


### scoping/lexical scope
scope is a collection of variables as well as the rules of how thse 
variables are accessed by name

