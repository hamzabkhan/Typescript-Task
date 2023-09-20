// Variable declarations with type annotations
let firstName: string = "John";
let age: number = 30;
let isStudent: boolean = false;

// Functions with parameter types and return types
function addNumbers(num1: number, num2: number): number {
  return num1 + num2;
}

function greet(name: string): string {
  return `Hello, ${name}!`;
}

// A class definition with properties and methods
class Person {
  private name: string;
  private age: number;

  constructor(name: string, age: number) {
    this.name = name;
    this.age = age;
  }

  getDetails(): string {
    return `Name: ${this.name}, Age: ${this.age}`;
  }
}

// Usage of the code
console.log(`First Name: ${firstName}`);
console.log(`Age: ${age}`);
console.log(`Is Student: ${isStudent}`);

const sum = addNumbers(5, 7);
console.log(`Sum: ${sum}`);

const greeting = greet("Alice");
console.log(greeting);

const person = new Person("Bob", 25);
console.log(person.getDetails());
