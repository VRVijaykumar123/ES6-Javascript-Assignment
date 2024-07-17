# ES6-Javascript-Assignment
# Exercise 1: Let and Const
```html

let age = 30;
const name = "Alice";
console.log(age); 
console.log(name); 
```
# output
![js1](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/82a9d582-e5ad-4bf5-998a-7c9e823ec798)

# Exercise 2: Arrow Functions
```html
const add = (a, b) => a + b;
console.log(add(2, 3)); 
```
# output
![js2](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/739ca3f7-3223-4e73-a2f5-ffb6247acd29)

# Exercise 3: Template Literals
```html
let age = 30;
const name = "Alice";
console.log(`Hello, ${name}! Your age is ${age}.`);
```
# output
![js3](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/49e6dd20-279a-4b7c-a118-f4164f68719d)

# Exercise 4: Destructuring Objects
```html
const person = { firstName: "Alice", lastName: "Johnson" };
const { firstName, lastName } = person;
console.log(firstName); 
console.log(lastName);  
```
# output
![js4](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/6923dcb4-d1b0-4dc4-a23f-dd6587a17634)

# Exercise 5: Destructuring Arrays
```html
const numbers = [1, 2, 3, 4, 5];
const [first, second] = numbers;
console.log(first);  
console.log(second); 
```
# output
![js5](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/2e764ee1-18a4-49c8-827a-13c16c40f491)

# Exercise 6: Spread Operator
```html
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
const combined = [...arr1, ...arr2];
console.log(combined);
```
# output
![j6](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/f03686f0-9bab-4351-94a8-9362607ddef2)

# Exercise 7: Rest Parameters
```html
const sum = (...numbers) => {
    return numbers.reduce((acc, current) => acc + current, 0);
  };
  console.log(sum(1, 2, 3));       
  console.log(sum(10, 20, 30, 40)); 
  console.log(sum(5));              
  console.log(sum());             
  ```
# output
![j7](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/07f61771-0999-4d38-bd4d-9ab04d8b0896)

# Exercise 8: Default Parameters
```html
const greet = (name, greeting = "Hello") => {
    return `${greeting}, ${name}!`;
  };
  console.log(greet("Alice"));          
  console.log(greet("Bob", "Hi"));      
  console.log(greet("Charlie", "Hey")); 
  console.log(greet("David",));         
  ```
# output
![js8](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/3b71299e-2716-4760-b712-0380ab6c9960)

# Exercise 9: Classes and Inheritance
```html
class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  class Dog extends Animal {
    constructor(name) {
      super(name); 
    }
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }
  const myDog = new Dog("Buddy");
  console.log(myDog.bark()); 
  ```
# output
![j9](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/3bee5dfb-7bf1-471a-a875-f6e2dc273e33)

# Exercise 10: Promises and Async/Await
```html
const waitAndReturn = () => new Promise(resolve => {
    setTimeout(() => {
      resolve("Done");
    }, 2000);
  });
  async function run() {
    const result = await waitAndReturn();
    console.log(result); 
  }
  run();
  ```
# output
![js10](https://github.com/PrakashG-2002/ES6-Javascript-Assignment/assets/144507749/4c10c001-f143-46ed-b7eb-768726de0074)
