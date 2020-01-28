# Javascript-notes

Notes about importants topics of Javascript 

* [Clourse and Scope](https://blog.bitsrc.io/a-beginners-guide-to-closures-in-javascript-97d372284dda)

* [Clourse and Scope - exercises](https://github.com/Bloc/mentor-exercises/blob/master/exercises/javascript/closure-scoping-exercises.md)


## Algorithms

* [Sorting Algorithms](https://github.com/yeb9925/sorting-algorithms-javascript)


## Arrow functions
- Are always anonymous functions
- You can use in function and arrow defaults arguments like (a = 0, r = 0,1)
- Don´t use arraw function "when you really need `this`" and "when you need a method to bind to an object"
- In arrow functions the this is not bound for example in an on event..
- When you need to add prototype method
- When you need the keyword 'arguments' objects


## Promises

`const p = new Promises((resolve, reject)=>{
 setTimeOut(()=>{
    reject('err');
 })
})` 

## Prototype
object.prototype.name = function () { }

## Generators
Generators are functions which can be exited and later re-entered. Their context (variable bindings) will be saved across re-entrances

## Proxies
Ovewrite default behavior in objects
