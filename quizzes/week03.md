# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction
Encapsulation
Inheritance
Polymorphism
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
Using JSON.parse() method.
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Encapsulation is putting data and methods of acting on that data together in a way that restricts access to that data from the outside. Only the objects methods can access it. Also, heard it defined in class as the grouping of like-minded things.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single Responsibility principle
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class describes a data type. An instance of a class is an object of the data type that exists in memory.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
It's a fake stand in object to serve as the go between the user and the app state so the user can't directly access the app state itself.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
To give your web application scalability and keep it more organized and readable.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
The controller takes in the user input. It then talks to the service and which talks to the app state.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
It performs the business logic. Like in a restaurant, this would be like the kitchen performing the work to get your order ready for you.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
It is the model for the data stored in the app state.
```
