# Introduction
In Javascript there are **5** primitive datatypes:
* Number --- Floating Point Numbers (5.0)
* String --- Sequence of a character
* Boolean --- True or False
* Undefined --- Does not have a value yet.
* Null --- Non-existent

Javascript has *dynamic typing* (decides on the fly)

**Type Coercion ** --- Javascript automatically converts number to a string (Converts to the same data type.)

**Variable Mutation** --- We can change variables later.

```javascript 
var lastname = prompt("What is your last name?");
```

**Operator Precedence** --- An example, **(=)** --> right to left
#### Quick Notes
Double equal **does** type coercion,triple equal does **Not**.

 Always **Triple Equal** is recommend to avoid bugs.
 
 
 
 #### About switch
 ```javascript
 switch (job) {
  case "a":
  console.log("Hi!!");
  break;
  
  .
  .
  .
default:
console.log("Bye!!");
  
 }
```
## Arrays

```javascript
var names = ['Mark','John','Bob'];
var years = new Array(1990,1969,1948);
```
```javascript
john.push('blue'); ---> Adds to the END of an array.``` 
```javascript
john.unshift('Mr'); ---> Adds to the BEGINNING of an array.``` 
```javascript
john.pop(); ---> Remove from the END of an array.``` 
```javascript
john.shift(); ---> Remove from the BEGINNING of an array.``` 
```javascript
john.indexof('Smith'); ---> Shows the position,if there is no match,shows -1.``` 
