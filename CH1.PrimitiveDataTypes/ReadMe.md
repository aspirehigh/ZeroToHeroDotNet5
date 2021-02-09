##
Welcome to the first step in your journey to learn C-sharp.

I'm going to introduce you to 
1. Identifiers
2. Variables 
2. Constans 
3. Scope
4. Data types
5. Type Conversions
6. Overflowing

Lets begin our journey:

1. Identifiers: Identifier as the name implies is a name to identify, for example a human has a nane to identify him uniquely. Similarly a variable, function and class needs name to uniqely identify. 
	
	1.1 We have certain rules for our compiler to identify an identifier:
	
	
		1.1.1 An identifier cannot include whitespace, it has to be one word.
		
			Ex: Student Name is not a valid identifier, to fix it we should use StudentName.
			Get Students is not valid identifier, to fix it we should use GetStudents

		1.1.2 An identifier cannot be a reserve keyword like for, class, int etc.,

	1.2 In addition to rules we also have best practices to define Identifiers.
	
		1. Use meaningful names.
			Ex: StudentName as a varaible name to store the name of the student, though compiler will not complain if you use SN or any other name for the identifier it is better to use human readable names for identifiers.
		2. use naming conventions.
		
	1.3 There are three popular naming conventions camel case Pasko case and Hungarian.
		
		1. Camel Case: The first letter of the first word is lower case and the first letter of every subsequent word after it has to be upper case. 
		2. Pasko Case: The first letter of every word has to be uppercase.
		3. Hungarian: Prefixed the name of a variable with the data type it uses.

These best practices will help you in a long way, and this way your code will be more readable more maintainable and cleaner. Having this convention in your organization will help  and everybody in your team to understand your code.

*Note:* Most of the C# developers across the globe use camel case.

1. Variables: A name given to a basic unit of memory in a program.
	Syntax: 
	A type follwed by an identifier ending with a semicolan, in the below example int is the type, x is the identifier.

	Ex: int x;
2. Constants: A variable for which values doesn't change during the lifecycle of the program. Which is also referred to as immutable value.
	
		Syntax:
			'const' keyword followed by a variable declration, in the below example int is the type, DaysInAWeek is the variable whoes value doesn't change once the value is assigned after compilation.
	
		Ex: 
			const int DaysInAWeek = 7;

