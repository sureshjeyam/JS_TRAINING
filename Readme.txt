09 Jan 2019
============
Primitive Data Types - 
	Number, string, boolean, null, undefined
	Undefined - Declared variables and not initialized values, that will come undefined.
	Anything followed as string, it's consider as string. Ex :  "Rajjev"+23+23 = Rajjev2323


Non primitive Data types - It's a reference data types
	Object is a collection of your primitive data types
	object can created 2 different way
		- Litteral
		- () - Method
	Object is an unordered list of primitive data types
	Object can access using . notation and bracket [] notation.

Two ways of creating objects

	Literal
		- Anything comes inside {}, those are literal objects
		Reference Data types and Primitive Data Types
			- Ex : var a = 10; 
			console.log(a);
					var b = a;
					var a= 20;
					console.log(a);

			- IMP : Object value cant be overwriiten
			- var values can be overwritten.


		Named function
			function add() {}
			add();

		Anonymous function
			var add1 = function() {}
			add1();

	Constructor: Ex: new key values should be used
		let newPerson = new Object();
		newPerson.name = 'suresh';

		Constructor Pattern for Creating Objects
			function fruit(color, sweetness){
				this.color = color;
				this.sweetness = sweetness;
			}

08 Jan 2019
============
Local Scope - Function Scope
Global Scope - Any 

Global Block,
Local Block

Any "let" declaration cant be over written
Any "var" declaration can be over written
"Let" will not work as a variable

If, elseif, else and all curly braces are block level scope

function curly braces are  closures