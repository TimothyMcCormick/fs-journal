# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let, const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A block of code designed to perform a particular task
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility principle
Open closed principle
Liskov substitution principle
Interface segregation principle
Dependency Inversion principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
2 - arrays start at position 0 and continue on by 1's. [0,1,2,3,4,5] and so on..
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them);
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
if (you.friends > them.friends){
  console.log('This is a conditional')
  }  else {
      console.log('Still a conditional')
    }

```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
This is called the iteration. It increases or decreases the counter. i++ would increase the counter by one on every iteration
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document Object Model. The html file is what is used to access the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Undefined, Null, Boolean, String, 
Number, Object, Reference, List, and Completion
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are used when defining a function, they are the names created in the function definition. 

Arguments are the values the function receives from each parameter when the function is executed.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive types are stored as simple data types while reference types are stored as objects, which means it holds a reference to a memory’s location.
```