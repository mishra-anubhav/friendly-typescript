# Friendly-typescript
TypeScript is an open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript, and adds optional static typing to the language. TypeScript is designed for development of large applications and transcompiles to JavaScript.
# Topics:
## Variable Types
As we know, javascript has seven different data types : Null, Undefined, Boolean, Number, String, Symbol (introduced in ES6), and Object;
where as in typescript there are some additional types like enum, any, never, tuples and etc, thus you need not to worry about compatibilty in typescript.

## Flow control statements
1. The single-selection structure (if)

2. The double-selection structure (if…else)

3. The inline ternary operator (?)

4. The multiple-selection structure (switch)

5. (do…while)

6. while

7. Iterate on each object's properties (for…in)

8. Counter controlled repetition (for)


## Functions

Just as in JavaScript, TypeScript functions can be created either as a named function or as an
anonymous function. This allows us to choose the most appropriate approach for an
application, whether we are building a list of functions in an API or a one-off function to hand
over to another function

// named function
function greet(name? : string) : string {
if(name){
return "Hi! " + name;
}
else
{
return "Hi!";
}
}

## Classes

ECMAScript 6, the next version of JavaScript, adds class-based object orientation to
JavaScript and, since TypeScript is based on ES6, developers are allowed to use class-based
object orientation today, and compile them down to JavaScript that works across all major
browsers and platforms, without having to wait for the next version of JavaScript.

## Interfaces
In TypeScript, we can use interfaces to enforce that a class follow the specification in a
particular contract.

## Namespaces
Namespaces, also known as internal modules, are used to encapsulate features and objects that
share a certain relationship. Namespaces will help you to organize your code in a much
clearer way. To declare a namespace in TypeScript, you will use the namespace and export
keywords.
