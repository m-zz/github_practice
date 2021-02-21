# Conceptual Exercise

Answer the following questions below in Markdown. 
Check out the [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

### What is Big O notation and why does it matter?
> Big O notation is a way to standardize the representation of time and space complexity on code and place a relative metric on its performance as the inputs grow. It is important since the notation allows for a quick way to compare the relative performance of code by avoiding the issue of hardware differences between systems and individual system variability during runtime. 

### What is time complexity?
> Time complexity represents the rate at which the code runtime increases as the complexity of the inputs increases. 

### What are important differences between arrays and objects?
> Arrays are a subset of objects which represent an ordered list of elements whereas objects represent key/value pairs. Arrays indices are ordered whereas objects keys are not.

### What are important differences between `var` and `let`?
> var is function scoped while let is block scoped. var can be redeclared while let cannot. var can also be hoisted within functions whereas let cannot.

### What are important differences between `let` and `const`?
> let can be reassigned while const cannot. Both are block-scoped and cannot be redeclared.

### What are important differences between arrow functions and regular functions?
> Arrow functions cannot be named while regular functions can be. Arrow functions can also have an implied return by removing `{}`. Arrow functions do not generate their own '`this`' and gain `this` from the outer context. Regular functions will generate `this` from their respective call.

### What is the purpose of the rest operator?
> The rest operator is generally used to gather the remaining parameters in a function into an array.

### What is the purpose of the spread operator?
> The spread operator is generally used during function call by spreading the elements in the array into a comma separated list.

### What is Object Oriented Programming?
> OOP is a style of programming where objects represent the main form of data assignment and manipulation through its properties and methods. It differs from functional programming where the focus is to run functions to return certain outcomes. OOP can be more useful where multiple instances of the same object exist.

### What is a class? When would you make one?
> A class is a type of an object where it defines and acts as a blueprint of functionality. Classes are used in OOP to create the same structure of objects.

### What is an instance?
> An instance is an iteration of a defined class/object that contains its own values. Multiple instances can be initialized from the same object but represent separate entities.

### What is the keyword `this`?
> `this` refers to the object in which a function is called within. The value of `this` can change as functions are called within different scopes even with the same function definition.

### What does the `bind` function do?
> `bind` allows for functions to reference a specific object/scope when called. `bind` will force a `this` value as the first argument.