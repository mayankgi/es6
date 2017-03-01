# ES6 Features #

## Table Of Content ##

1. [Varibles](variables)
1. [Arrow Functions](arrow-functions)
1. [Enhanced Object Literals](enhanced-objects-literals)
1. [Arrays](arrays)
1. [String Interpolation](string-interpolation)
1. [Classes](classes)
1. [Destructuring](destructuring)
1. [Module](modules)
1. [Default + Rest + Spread](default-rest-spread)

## Variables ##

let and const variables introduced in ES6 are lexical scope variables.

```

let foo = 'bar';

const PI = 3.14159;

```

## Arrow Functions ##

Shorthand to create functions. Arrow functions don't bind to its own this.

```
() => {...} //shorthand for function

(param1, param2, ...) => {...} //params with block

(param1, param2, ...) => expression //arrow function with single expression

```

## Enhanced Object Literals

Property shorthand

```
let foo = {
  bar //Same as bar:bar  
}

```

Computed methods

```
function greetingTo(){
  return 'World';
}

let greeting = {
  ['Hello' + greetingTo()]: 'Hello World!'
}

```

Methods Shorthand

```

let foo = {
  bar(){...} //same as bar: function(){...}
}

```

## Arrrays

## String Interpolation ##

```



```

## JavaScript Coding Conventions by Airbnb ##

1. [JavaScript](https://github.com/airbnb/javascript)
1. [React](https://github.com/airbnb/javascript/tree/master/react)
