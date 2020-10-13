## JavaScript Interview Questions

**Question**: What is the difference between Java and JavaScript?<br/>
**Answer**: Java is an object-oriented programming (OOPS) or structured programming language like C++ or C whereas JavaScript is a client-side scripting language & used to make web pages interactive.<br/>
**Company**: Avibird <br/>
**Topics**: `JavaScript` <br/>

<hr/>

**Question**: What is the difference between var and let?<br/>
**Answer**: var has a global scope which means when you define it, it is loaded at the starting of the `execution context` with the value `undefined` and can be accessed from anywhere in the program where as let always has a local scope which stays inside the function/module in which it is defined.<br/>
**Company**: Whitepanda <br/>
**Topics**: `JavaScript` <br/>

<hr/>

**Question**: What is the difference between `==` and `===`?<br/>
**Answer**: The `==` operator will compare for equality after doing any necessary type conversions. The `===` operator will not do the conversion, so if two values are not the same type `===` will simply return false. Both are equally quick.<br/>
**Company**: BD <br/>
**Topics**: `JavaScript` <br/>

<hr/>

**Question**: What is NaN property in JavaScript?<br/>
**Answer**: `NaN` property represents “Not-a-Number” value. It indicates a value which is not a legal number.

typeof of a `NaN` will return a Number .

To check if a value is `NaN`, we use the `isNaN()` function,<br/>

```js
isNaN("Hello"); // Returns true
isNaN(345); // Returns false
isNaN("1"); // Returns false, since '1' is converted to Number type which results in 0 ( a number)
isNaN(true); // Returns false, since true converted to Number type results in 1 ( a number)
isNaN(false); // Returns false
isNaN(undefined); // Returns true
```

**Company**: BD <br/>
**Topics**: `JavaScript` <br/>

<hr/>
