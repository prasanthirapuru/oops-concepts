# OOP Interview Questions — Complete Study Guide (Python + Java)

This README organizes all three source documents into one file with a clickable Table of Contents. Click any question below to jump straight to its answer. Content is preserved as originally written; only structure/formatting has been organized for navigation.

---

## 📑 Table of Contents

- [Quick Reference: Python vs Java Terminology](#quick-reference-python-vs-java-terminology)
- **[Part 1 — Python + Java OOP Interview Questions: Complete Study Guide](#part-1--python--java-oop-interview-questions-complete-study-guide)**
  - [Part 1.1: Basic OOP Concepts](#part-11-basic-oop-concepts)
    - [1. What is OOP in Python, and what are its advantages?](#1-what-is-oop-in-python-and-what-are-its-advantages)
    - [2. What is a class in Python?](#2-what-is-a-class-in-python)
    - [3. What is an object in Python?](#3-what-is-an-object-in-python)
    - [4. What is the difference between a class and an object?](#4-what-is-the-difference-between-a-class-and-an-object)
    - [5. What is the `__init__()` method in Python, and why is it used?](#5-what-is-the-__init__-method-in-python-and-why-is-it-used)
    - [6. What is the `self` keyword in Python, and why is it used?](#6-what-is-the-self-keyword-in-python-and-why-is-it-used)
    - [7. What are the four pillars of OOP, and how are they implemented in Python?](#7-what-are-the-four-pillars-of-oop-and-how-are-they-implemented-in-python)
    - [8. What is encapsulation in Python? How do you implement it?](#8-what-is-encapsulation-in-python-how-do-you-implement-it)
  - [Part 1.2: The Four Pillars of OOP](#part-12-the-four-pillars-of-oop)
    - [9. What is abstraction in Python, and how do you achieve it?](#9-what-is-abstraction-in-python-and-how-do-you-achieve-it)
    - [10. What is inheritance in Python, and what are its different types?](#10-what-is-inheritance-in-python-and-what-are-its-different-types)
    - [11. What is polymorphism in Python? Explain with an example.](#11-what-is-polymorphism-in-python-explain-with-an-example)
  - [Part 1.3: Methods and Inheritance](#part-13-methods-and-inheritance)
    - [12. What is the difference between instance methods, class methods, and static methods in Python?](#12-what-is-the-difference-between-instance-methods-class-methods-and-static-methods-in-python)
    - [13. What is the difference between method overloading and method overriding in Python?](#13-what-is-the-difference-between-method-overloading-and-method-overriding-in-python)
    - [14. What is the `super()` function in Python, and why is it used?](#14-what-is-the-super-function-in-python-and-why-is-it-used)
    - [15. What is multiple inheritance in Python?](#15-what-is-multiple-inheritance-in-python)
    - [16. What is Method Resolution Order (MRO) in Python, and how does it work?](#16-what-is-method-resolution-order-mro-in-python-and-how-does-it-work)
    - [17. What is the difference between `isinstance()` and `issubclass()`?](#17-what-is-the-difference-between-isinstance-and-issubclass)
  - [Part 1.4: Important Python OOP Features](#part-14-important-python-oop-features)
    - [18. What is the difference between instance variables and class variables?](#18-what-is-the-difference-between-instance-variables-and-class-variables)
    - [19. What are access modifiers in Python? Explain public, protected, and private members.](#19-what-are-access-modifiers-in-python-explain-public-protected-and-private-members)
    - [20. What are magic methods (dunder methods) in Python? Explain `__str__()` and `__repr__()`.](#20-what-are-magic-methods-dunder-methods-in-python-explain-__str__-and-__repr__)
    - [21. What is the difference between `==` and `is` in Python?](#21-what-is-the-difference-between--and-is-in-python)
    - [22. What is the difference between an instance method and a constructor? Does Python support multiple constructors?](#22-what-is-the-difference-between-an-instance-method-and-a-constructor-does-python-support-multiple-constructors)
  - [Part 1.5: Common Follow-Up Questions](#part-15-common-follow-up-questions)
    - [23. What is the difference between inheritance and composition in Python?](#23-what-is-the-difference-between-inheritance-and-composition-in-python)
    - [24. What is the difference between shallow copy and deep copy in Python?](#24-what-is-the-difference-between-shallow-copy-and-deep-copy-in-python)
    - [25. What is an abstract class in Python, and how do you create one using the `abc` module?](#25-what-is-an-abstract-class-in-python-and-how-do-you-create-one-using-the-abc-module)
  - [Bonus: The `self`, `cls`, and `this` Interview Questions](#bonus-the-self-cls-and-this-interview-questions)
    - [26. What is the difference between `self` and `cls` in Python?](#26-what-is-the-difference-between-self-and-cls-in-python)
    - [27. Is `self` a keyword in Python? Is `cls` a keyword?](#27-is-self-a-keyword-in-python-is-cls-a-keyword)
    - [28. Does Java have `self` or `cls`?](#28-does-java-have-self-or-cls)
  - [Final Revision Sheet](#final-revision-sheet)
  - [How to Practise These for Interviews](#how-to-practise-these-for-interviews)
- **[Part 2 — General OOPS Interview Questions & Answers (27 Important Questions)](#part-2--general-oops-interview-questions--answers-27-important-questions)**
  - [1. What is OOP/OOPS?](#1-what-is-oopoops)
  - [2. What is a class?](#2-what-is-a-class)
  - [3. What is an object?](#3-what-is-an-object)
  - [4. What are the four main principles of OOP?](#4-what-are-the-four-main-principles-of-oop)
  - [5. What is encapsulation?](#5-what-is-encapsulation)
  - [6. What is abstraction?](#6-what-is-abstraction)
  - [7. What is inheritance?](#7-what-is-inheritance)
  - [8. What are the types of inheritance?](#8-what-are-the-types-of-inheritance)
  - [9. What is polymorphism?](#9-what-is-polymorphism)
  - [10. What is method overloading?](#10-what-is-method-overloading)
  - [11. What is method overriding?](#11-what-is-method-overriding)
  - [12. What is the difference between overloading and overriding?](#12-what-is-the-difference-between-overloading-and-overriding)
  - [13. What is the difference between a class and an object?](#13-what-is-the-difference-between-a-class-and-an-object)
  - [14. What is an abstract class?](#14-what-is-an-abstract-class)
  - [15. What is an interface?](#15-what-is-an-interface)
  - [16. Abstract class vs interface?](#16-abstract-class-vs-interface)
  - [17. What is a constructor?](#17-what-is-a-constructor)
  - [18. What is a destructor?](#18-what-is-a-destructor)
  - [19. What are access modifiers?](#19-what-are-access-modifiers)
  - [20. What is the difference between public, private, and protected?](#20-what-is-the-difference-between-public-private-and-protected)
  - [21. What is the difference between composition and inheritance?](#21-what-is-the-difference-between-composition-and-inheritance)
  - [22. What is association?](#22-what-is-association)
  - [23. What is aggregation?](#23-what-is-aggregation)
  - [24. What is composition?](#24-what-is-composition)
  - [25. What is dynamic binding?](#25-what-is-dynamic-binding)
  - [26. What is the difference between static binding and dynamic binding?](#26-what-is-the-difference-between-static-binding-and-dynamic-binding)
  - [27. Why is OOP useful? What are its advantages?](#27-why-is-oop-useful-what-are-its-advantages)
  - [⭐ Very Common Follow-Up Questions](#-very-common-follow-up-questions)
- **[Part 3 — Class and Object: Structure Walkthrough (Java & Python)](#part-3--class-and-object-structure-walkthrough-java--python)**
  - [1. First, understand the concepts](#1-first-understand-the-concepts)
  - [2. Python — Class and object](#2-python--class-and-object)
  - [3. Java — Class and object](#3-java--class-and-object)
  - [4. The complete structure — side by side](#4-the-complete-structure--side-by-side)
  - [5. One important thing to remember](#5-one-important-thing-to-remember)

---

## Quick Reference: Python vs Java Terminology

| Concept | Python | Java |
| --- | --- | --- |
| Current object | `self` | `this` |
| Current class | `cls` | No direct `cls` equivalent; use `ClassName` for static members |
| Constructor | `__init__()` initializes an object | Constructor uses the class name |
| Class method | `@classmethod` | No direct equivalent; static methods are different |
| Static method | `@staticmethod` | `static` method |
| Inheritance | `class Child(Parent):` | `class Child extends Parent` |
| Interface-like abstraction | `abc` module | `interface` or `abstract class` |

> Important: Python's `self` and `cls` are conventional parameter names, not keywords. Java's `this` is a keyword. Java does not have a direct equivalent of Python's `@classmethod`.

---
---

# Part 1 — Python + Java OOP Interview Questions: Complete Study Guide

👍 We'll learn Python and Java side by side, so you can understand the concepts and explain them confidently in interviews.

For every question, I'll follow your requested format:

1. **Interview answer** — A short, 2–3 line answer that you can memorize and say in an interview.
2. **Explanation of key terms** — Simple explanations of words like blueprint, instance, abstraction, overriding, and reference.
3. **Python and Java code** — Complete examples or syntax, with comments explaining what each important line does.

### First, understand these Python and Java differences

| Concept | Python | Java |
| --- | --- | --- |
| Current object | `self` | `this` |
| Current class | `cls` | No direct `cls` equivalent; use `ClassName` for static members |
| Constructor | `__init__()` initializes an object | Constructor uses the class name |
| Class method | `@classmethod` | No direct equivalent; static methods are different |
| Static method | `@staticmethod` | `static` method |
| Inheritance | `class Child(Parent):` | `class Child extends Parent` |
| Interface-like abstraction | `abc` module | `interface` or `abstract class` |

> Important: Python's `self` and `cls` are conventional parameter names, not keywords. Java's `this` is a keyword. Java does not have a direct equivalent of Python's `@classmethod`.

## Part 1.1: Basic OOP Concepts

### 1. What is OOP in Python, and what are its advantages?

**Python + Java**

#### Interview answer

Object-Oriented Programming (OOP) is a programming paradigm that organizes code using classes and objects. It combines data and the methods that operate on that data, making programs easier to organize, reuse, maintain, and extend.

#### Explanation of key terms

- Programming paradigm: A style or approach to writing programs.
- Object: A specific entity that contains data and can perform actions.
- Data: Information stored in a program, such as a name or age.
- Methods: Functions defined inside a class that describe an object's behavior.
- Code reusability: Using existing code again instead of rewriting it.
- Maintainability: How easily code can be understood, fixed, and updated.

#### Advantages of OOP

1. Reusability: Inheritance allows a class to reuse another class's code.
2. Encapsulation: Keeps data and related methods together and controls access.
3. Abstraction: Hides implementation details and exposes essential operations.
4. Maintainability: Organizes large programs into manageable classes.
5. Polymorphism: Allows the same method interface to behave differently for different objects.

#### Python code

```python
# A class combines data and behavior.
class Student:
    def __init__(self, name):
        self.name = name  # Data (attribute)

    def introduce(self):
        return f"My name is {self.name}"  # Behavior (method)


student = Student("Ravi")  # Create an object
print(student.introduce())
```

#### Java code

```java
class Student {
    String name;

    Student(String name) {
        this.name = name;
    }

    void introduce() {
        System.out.println("My name is " + name);
    }

    public static void main(String[] args) {
        Student student = new Student("Ravi");
        student.introduce();
    }
}
```

[⬆ Back to top](#-table-of-contents)

---

### 2. What is a class in Python?

#### Interview answer

A class is a blueprint or template used to create objects. It defines the attributes (data) and methods (behavior) that its objects can have.

#### Explanation of key terms

- Blueprint: A design or plan that describes how something should be created. For example, a house blueprint describes the house's structure.
- Template: A predefined structure that can be used repeatedly.
- Attributes: Variables that store information about an object.
- Methods: Functions defined inside a class.
- Define: Create the structure of something in code.

Think of a `Student` class as a form that specifies that every student can have a name and an age. Individual students can have different values.

#### Python syntax

```python
class Student:
    # Class attributes and methods are defined here.
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

#### Java syntax

```java
class Student {
    String name;
    int age;

    Student(String name, int age) {
        this.name = name;
        this.age = age;
    }
}
```

> Remember: A class defines the structure; creating an object gives you a particular instance of that structure.

[⬆ Back to top](#-table-of-contents)

---

### 3. What is an object in Python?

#### Interview answer

An object is an instance of a class. It has its own identity and can hold data in attributes while providing behavior through methods.

#### Explanation of key terms

- Instance: A specific object created from a class.
- Identity: What distinguishes one object from another.
- State: The current data stored in an object's attributes.
- Behavior: The actions an object can perform through its methods.

For example, `Student` is a class, while `student1` and `student2` can refer to two different student objects.

#### Python code

```python
class Student:
    def __init__(self, name):
        self.name = name

    def display(self):
        print(self.name)


student1 = Student("Ravi")  # First object
student2 = Student("Priya")  # Second object

student1.display()  # Ravi
student2.display()  # Priya
```

#### Java code

```java
class Student {
    String name;

    Student(String name) {
        this.name = name;
    }

    void display() {
        System.out.println(name);
    }

    public static void main(String[] args) {
        Student student1 = new Student("Ravi");
        Student student2 = new Student("Priya");

        student1.display();
        student2.display();
    }
}
```

[⬆ Back to top](#-table-of-contents)

---

### 4. What is the difference between a class and an object?

#### Interview answer

A class is a blueprint that defines attributes and methods, whereas an object is an instance created from that class. One class can be used to create multiple objects, each with its own instance data.

#### Explanation

Imagine a `Car` class:

- The class describes what a car has, such as a color and brand.
- An object is one particular car, such as a red Toyota.
- Multiple objects can share the same class but have different attribute values.

#### Python code

```python
class Car:
    def __init__(self, brand, color):
        self.brand = brand
        self.color = color


car1 = Car("Toyota", "Red")
car2 = Car("Honda", "Blue")

print(car1.brand)  # Toyota
print(car2.brand)  # Honda
```

#### Java code

```java
class Car {
    String brand;
    String color;

    Car(String brand, String color) {
        this.brand = brand;
        this.color = color;
    }

    public static void main(String[] args) {
        Car car1 = new Car("Toyota", "Red");
        Car car2 = new Car("Honda", "Blue");

        System.out.println(car1.brand);
        System.out.println(car2.brand);
    }
}
```

| Class | Object |
| --- | --- |
| Defines a structure | Is an instance of that structure |
| Declared using `class` | Created by calling the class in Python or using `new` in Java |
| Example: `Car` | Example: `car1` |

[⬆ Back to top](#-table-of-contents)

---

### 5. What is the `__init__()` method in Python, and why is it used?

#### Interview answer

`__init__()` is a special method that Python calls to initialize a newly created object. It is commonly used to assign initial values to the object's attributes.

#### Explanation of key terms

- Initialization: Setting an object's initial state.
- Special method: A method with a predefined role in Python.
- Attribute: A variable associated with an object.
- Constructor (interview terminology): `__init__()` is often called the constructor, but technically, Python's `__new__()` creates the object and `__init__()` initializes it.

#### Python code

```python
class Student:
    def __init__(self, name, age):
        # Initialize the object's attributes
        self.name = name
        self.age = age


student = Student("Ravi", 21)

print(student.name)  # Ravi
print(student.age)   # 21
```

When you write `Student("Ravi", 21)`, Python creates the object and then calls `__init__()` to initialize it.

#### Java code

```java
class Student {
    String name;
    int age;

    // Java constructor
    Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    public static void main(String[] args) {
        Student student = new Student("Ravi", 21);
        System.out.println(student.name);
    }
}
```

> Key difference: Java constructors have the same name as the class and no return type. Python uses the special `__init__()` method for initialization.

[⬆ Back to top](#-table-of-contents)

---

### 6. What is the `self` keyword in Python, and why is it used?

#### Interview answer

`self` refers to the current instance of a class. It is used to access that object's attributes and methods, and Python passes the instance automatically when an instance method is called through an object.

#### Explanation of key terms

- Current instance: The particular object on which a method is being called.
- Instance method: A method that operates on an object.
- Parameter: A named input received by a function or method.
- Automatically passed: Python supplies the object as the first argument when calling an instance method through that object.

> Important: `self` is not a Python keyword. You could technically use another name, but `self` is the standard convention.

#### Python code

```python
class Student:
    def __init__(self, name):
        self.name = name  # Store name in this object

    def display(self):
        print(self.name)


student1 = Student("Ravi")
student2 = Student("Priya")

student1.display()  # Ravi
student2.display()  # Priya
```

Conceptually, this call:

```python
student1.display()
```

is equivalent to:

```python
Student.display(student1)
```

The object `student1` is passed as `self`.

#### Java comparison: `this`

```java
class Student {
    String name;

    Student(String name) {
        this.name = name; // this refers to the current object
    }

    void display() {
        System.out.println(this.name);
    }
}
```

In Java, `this` plays a similar role to Python's `self`, but `this` is a language keyword.

[⬆ Back to top](#-table-of-contents)

---

### 7. What are the four pillars of OOP, and how are they implemented in Python?

#### Interview answer

The four pillars of OOP are encapsulation, abstraction, inheritance, and polymorphism. They help organize data, hide implementation details, reuse code, and allow a common interface to support different behaviors.

#### Explanation

| Pillar | Meaning | Python implementation |
| --- | --- | --- |
| Encapsulation | Bundling data and methods together, with controlled access | Classes, properties, naming conventions |
| Abstraction | Exposing essential operations while hiding implementation details | Abstract classes and methods using `abc` |
| Inheritance | Creating a class based on another class | `class Child(Parent)` |
| Polymorphism | A common interface with different behaviors | Overriding, duck typing, operator overloading |

#### Python example

```python
from abc import ABC, abstractmethod

# Abstraction
class Animal(ABC):
    def __init__(self, name):
        self.name = name  # Encapsulation: data and behavior in a class

    @abstractmethod
    def sound(self):
        pass


# Inheritance
class Dog(Animal):
    # Polymorphism: this class provides its own sound()
    def sound(self):
        return "Woof!"


class Cat(Animal):
    def sound(self):
        return "Meow!"


animals = [Dog("Buddy"), Cat("Kitty")]

for animal in animals:
    print(animal.name, animal.sound())
```

#### Java example

```java
abstract class Animal {
    String name;

    Animal(String name) {
        this.name = name;
    }

    abstract String sound();
}

class Dog extends Animal {
    Dog(String name) {
        super(name);
    }

    @Override
    String sound() {
        return "Woof!";
    }
}

class Cat extends Animal {
    Cat(String name) {
        super(name);
    }

    @Override
    String sound() {
        return "Meow!";
    }
}

class Main {
    public static void main(String[] args) {
        Animal[] animals = {
            new Dog("Buddy"),
            new Cat("Kitty")
        };

        for (Animal animal : animals) {
            System.out.println(animal.name + " " + animal.sound());
        }
    }
}
```

[⬆ Back to top](#-table-of-contents)

---

### 8. What is encapsulation in Python? How do you implement it?

#### Interview answer

Encapsulation is the bundling of data and the methods that operate on it within a class, while controlling how that data is accessed or modified. In Python, it is implemented using classes, naming conventions, properties, and name-mangled attributes.

#### Explanation of key terms

- Bundling: Keeping related data and functionality together.
- Data hiding: Restricting or discouraging direct access to internal data.
- Getter: A method or property used to retrieve a value.
- Setter: A method or property used to validate or update a value.
- Name mangling: Python changes the name of a double-underscore attribute to reduce accidental access or name conflicts. It is not strict security.

Python does not enforce Java-style access modifiers. A single underscore, such as `_balance`, signals that an attribute is intended for internal use. A double underscore, such as `__balance`, triggers name mangling.

#### Python code using a property

```python
class BankAccount:
    def __init__(self, balance):
        self.__balance = balance  # Name-mangled attribute

    @property
    def balance(self):
        # Getter
        return self.__balance

    @balance.setter
    def balance(self, amount):
        # Setter with validation
        if amount >= 0:
            self.__balance = amount
        else:
            raise ValueError("Balance cannot be negative")


account = BankAccount(1000)

print(account.balance)  # Calls the getter
account.balance = 1500  # Calls the setter
print(account.balance)
```

#### Java code

```java
class BankAccount {
    private double balance; // Private field

    BankAccount(double balance) {
        this.balance = balance;
    }

    public double getBalance() {
        return balance;
    }

    public void setBalance(double amount) {
        if (amount >= 0) {
            balance = amount;
        }
    }

    public static void main(String[] args) {
        BankAccount account = new BankAccount(1000);

        System.out.println(account.getBalance());
        account.setBalance(1500);
    }
}
```

> Interview tip: In Python, `@property` provides controlled attribute access with convenient attribute syntax. In Java, `private` fields and public getters/setters are a common encapsulation pattern.

[⬆ Back to top](#-table-of-contents)

---

## Part 1.2: The Four Pillars of OOP

### 9. What is abstraction in Python, and how do you achieve it?

#### Interview answer

Abstraction means exposing only the essential functionality while hiding unnecessary implementation details. In Python, abstraction can be achieved using abstract classes and abstract methods from the `abc` module.

#### Explanation of key terms

- Essential functionality: The operations a user needs to know about.
- Implementation details: The internal code that makes an operation work.
- Abstract class: A class intended to serve as a base for other classes; it cannot be instantiated when it has unimplemented abstract methods.
- Abstract method: A method declared in the base class that concrete subclasses are required to implement.

For example, a user can call `car.start()` without needing to know the internal details of the engine.

#### Python code

```python
from abc import ABC, abstractmethod

class Vehicle(ABC):
    @abstractmethod
    def start(self):
        pass  # Subclasses must implement this method


class Car(Vehicle):
    def start(self):
        return "Car engine started"


car = Car()
print(car.start())

# Vehicle()  # TypeError: cannot instantiate an abstract class
```

#### Java code

```java
abstract class Vehicle {
    abstract void start(); // Abstract method
}

class Car extends Vehicle {
    @Override
    void start() {
        System.out.println("Car engine started");
    }
}

class Main {
    public static void main(String[] args) {
        Vehicle car = new Car();
        car.start();
    }
}
```

> Remember: Abstraction focuses on what an object does, while hiding the details of how it does it.

[⬆ Back to top](#-table-of-contents)

---

### 10. What is inheritance in Python, and what are its different types?

#### Interview answer

Inheritance allows a child class to acquire attributes and methods from a parent class. It promotes code reusability and allows child classes to extend or override inherited behavior.

#### Explanation of key terms

- Parent/base/superclass: The class whose features are inherited.
- Child/derived/subclass: The class that inherits from another class.
- Extend: Add new features to an existing class.
- Override: Provide a new implementation of an inherited method.

#### Five commonly discussed types

1. **Single inheritance** — One child inherits from one parent.
2. **Multilevel inheritance** — A class inherits from a child class, forming a chain.
3. **Multiple inheritance** — One child inherits from multiple parent classes.
4. **Hierarchical inheritance** — Multiple child classes inherit from one parent.
5. **Hybrid inheritance** — A combination of two or more inheritance patterns.

#### Python code: single inheritance

```python
class Animal:
    def eat(self):
        print("Eating")


class Dog(Animal):  # Dog inherits from Animal
    def bark(self):
        print("Barking")


dog = Dog()
dog.eat()   # Inherited method
dog.bark()  # Dog's own method
```

#### Java code

```java
class Animal {
    void eat() {
        System.out.println("Eating");
    }
}

class Dog extends Animal {
    void bark() {
        System.out.println("Barking");
    }
}

class Main {
    public static void main(String[] args) {
        Dog dog = new Dog();
        dog.eat();
        dog.bark();
    }
}
```

> Java note: Java supports single, multilevel, and hierarchical class inheritance. A class cannot extend multiple classes, so multiple inheritance of implementation is not supported for classes. Java supports multiple inheritance of type through interfaces.

[⬆ Back to top](#-table-of-contents)

---

### 11. What is polymorphism in Python? Explain with an example.

#### Interview answer

Polymorphism means "many forms." It allows different objects to respond to the same method call in different ways, commonly through method overriding and duck typing in Python.

#### Explanation of key terms

- Poly: Many.
- Morph: Forms.
- Method overriding: A child class provides its own implementation of an inherited method.
- Duck typing: Python focuses on whether an object supports the required operation, rather than requiring a specific class or declared interface.

#### Python code

```python
class Dog:
    def sound(self):
        return "Woof"


class Cat:
    def sound(self):
        return "Meow"


def make_sound(animal):
    # Works with any object that provides sound()
    print(animal.sound())


make_sound(Dog())  # Woof
make_sound(Cat())  # Meow
```

Notice that `make_sound()` accepts both objects without requiring them to share a parent class.

#### Java code

```java
class Animal {
    void sound() {
        System.out.println("Animal sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Woof");
    }
}

class Cat extends Animal {
    @Override
    void sound() {
        System.out.println("Meow");
    }
}

class Main {
    public static void main(String[] args) {
        Animal a1 = new Dog();
        Animal a2 = new Cat();

        a1.sound(); // Woof
        a2.sound(); // Meow
    }
}
```

> Key interview term — dynamic dispatch: The method implementation is selected at runtime based on the actual object's type. This is demonstrated by the Java example.

[⬆ Back to top](#-table-of-contents)

---

## Part 1.3: Methods and Inheritance

### 12. What is the difference between instance methods, class methods, and static methods in Python?

#### Interview answer

An instance method receives `self` and works with an object's data. A class method receives `cls` and works with class-level data, while a static method receives neither automatically and is used for a related utility operation.

#### Explanation of `self`, `cls`, and static methods

| Method | First parameter | Used for |
| --- | --- | --- |
| Instance method | `self` | Object-specific data |
| Class method | `cls` | Class-level data and alternative constructors |
| Static method | None automatically | Related utility logic |

- `self`: Refers to the current object.
- `cls`: Refers to the class itself.
- Decorator: A feature written with `@` that modifies or registers a function's behavior.
- Class variable: A variable associated with the class and commonly shared by its instances.

#### Python code

```python
class Student:
    school = "ABC School"  # Class variable

    def __init__(self, name):
        self.name = name

    # Instance method
    def display(self):
        return self.name

    # Class method
    @classmethod
    def change_school(cls, school):
        cls.school = school

    # Static method
    @staticmethod
    def is_adult(age):
        return age >= 18


student = Student("Ravi")

print(student.display())             # Ravi
Student.change_school("XYZ School")
print(Student.school)                # XYZ School
print(Student.is_adult(20))          # True
```

#### Java comparison

```java
class Student {
    static String school = "ABC School";
    String name;

    Student(String name) {
        this.name = name;
    }

    // Instance method: uses this
    void display() {
        System.out.println(this.name);
    }

    // Static method: belongs to the class
    static boolean isAdult(int age) {
        return age >= 18;
    }
}
```

> Java has instance methods and static methods, but no direct equivalent of Python's `@classmethod`. A Java static method cannot use `this` because it is not called on a particular instance.

[⬆ Back to top](#-table-of-contents)

---

### 13. What is the difference between method overloading and method overriding in Python?

#### Interview answer

Method overloading means using the same method name with different parameter lists, while method overriding means redefining an inherited method in a child class. Python does not support traditional signature-based method overloading directly, but it can achieve similar behavior using default arguments or variable-length arguments.

#### Explanation of key terms

- Parameter list/signature: The parameters a method accepts.
- Overloading: Same method name, different parameter combinations.
- Overriding: A subclass replaces an inherited method's implementation.
- Variable-length arguments: `*args` lets a function accept a variable number of positional arguments.

#### Python: overloading-like behavior

```python
class Calculator:
    # One method handles different numbers of arguments
    def add(self, a, b, c=0):
        return a + b + c


calc = Calculator()
print(calc.add(2, 3))     # 5
print(calc.add(2, 3, 4))  # 9
```

Defining two ordinary methods with the same name in a Python class does not create traditional overloads; the later definition replaces the earlier one.

#### Python: overriding

```python
class Animal:
    def sound(self):
        return "Animal sound"


class Dog(Animal):
    def sound(self):  # Overrides the inherited method
        return "Woof"


print(Dog().sound())  # Woof
```

#### Java comparison

```java
class Calculator {
    // Overloading: different parameter lists
    int add(int a, int b) {
        return a + b;
    }

    int add(int a, int b, int c) {
        return a + b + c;
    }
}

class Animal {
    void sound() {
        System.out.println("Animal sound");
    }
}

class Dog extends Animal {
    @Override
    void sound() {
        System.out.println("Woof");
    }
}
```

> Interview distinction: Java supports traditional method overloading. Python generally uses default values, `*args`, or other dispatch techniques to handle varying inputs.

[⬆ Back to top](#-table-of-contents)

---

### 14. What is the `super()` function in Python, and why is it used?

#### Interview answer

`super()` provides a way to call methods from the next class in the Method Resolution Order (MRO). It is commonly used to invoke a parent class's initializer or extend an inherited method without directly naming the parent class.

#### Explanation of key terms

- MRO: The order Python follows when searching for methods in an inheritance hierarchy.
- Parent initializer: The parent's `__init__()` method.
- Cooperative inheritance: Classes work together using `super()` so that methods can be called in the correct MRO order.

#### Python code

```python
class Person:
    def __init__(self, name):
        self.name = name


class Student(Person):
    def __init__(self, name, roll_no):
        super().__init__(name)  # Call Person's initializer
        self.roll_no = roll_no


student = Student("Ravi", 101)
print(student.name)
print(student.roll_no)
```

#### Java code

```java
class Person {
    String name;

    Person(String name) {
        this.name = name;
    }
}

class Student extends Person {
    int rollNo;

    Student(String name, int rollNo) {
        super(name); // Call parent constructor
        this.rollNo = rollNo;
    }
}
```

> Important difference: In Python, `super()` follows the MRO, which matters especially in multiple inheritance. In Java, `super()` invokes a superclass constructor or accesses superclass members.

[⬆ Back to top](#-table-of-contents)

---

### 15. What is multiple inheritance in Python?

#### Interview answer

Multiple inheritance occurs when a class inherits from more than one parent class. Python supports it directly, allowing the child class to access inherited features from multiple parents, with method lookup determined by the MRO.

#### Explanation

Suppose a `SmartPhone` class inherits from `Camera` and `Phone`. It can use the features provided by both parent classes.

#### Python code

```python
class Camera:
    def take_photo(self):
        print("Photo taken")


class Phone:
    def make_call(self):
        print("Calling...")


class SmartPhone(Camera, Phone):
    pass  # Inherits both methods


device = SmartPhone()
device.take_photo()
device.make_call()
```

#### Java comparison

Java does not allow this:

```java
// Not valid Java:
// class SmartPhone extends Camera, Phone { }
```

Instead, Java can use interfaces:

```java
interface Camera {
    void takePhoto();
}

interface Phone {
    void makeCall();
}

class SmartPhone implements Camera, Phone {
    public void takePhoto() {
        System.out.println("Photo taken");
    }

    public void makeCall() {
        System.out.println("Calling...");
    }
}
```

> Java interfaces can declare methods and, in some cases, provide default implementations. This is not the same as inheriting implementation from multiple classes.

[⬆ Back to top](#-table-of-contents)

---

### 16. What is Method Resolution Order (MRO) in Python, and how does it work?

#### Interview answer

Method Resolution Order (MRO) is the order in which Python searches classes to find a method or attribute. Python uses the C3 linearization algorithm to create a consistent order, which can be inspected using `ClassName.mro()` or `ClassName.__mro__`.

#### Explanation of key terms

- Resolution: Finding which implementation should be used.
- Linearization: Turning an inheritance hierarchy into a single ordered list.
- C3 linearization: Python's algorithm for maintaining parent-order constraints and a consistent method lookup order.
- Diamond inheritance: A structure where two parent classes inherit from the same base class, and a child inherits from both.

#### Python code

```python
class A:
    def show(self):
        print("A")


class B(A):
    def show(self):
        print("B")


class C(A):
    def show(self):
        print("C")


class D(B, C):
    pass


obj = D()
obj.show()       # B
print(D.mro())   # D, B, C, A, object
```

Because `B` comes before `C` in `class D(B, C)`, Python finds `show()` in `B` first.

#### Java comparison

Java does not expose a Python-style MRO list for classes. Class method lookup follows Java's inheritance and overriding rules. Java also avoids multiple inheritance of classes, reducing the class-based diamond problem; conflicting interface default methods must be resolved explicitly.

[⬆ Back to top](#-table-of-contents)

---

### 17. What is the difference between `isinstance()` and `issubclass()`?

#### Interview answer

`isinstance()` checks whether an object is an instance of a particular class or its subclasses. `issubclass()` checks whether one class inherits from another class or is the same class.

#### Explanation

- Object check: Ask whether a particular object belongs to a type.
- Class check: Ask whether one class is derived from another.
- Both Python functions support tuples of classes as the second argument.

#### Python code

```python
class Animal:
    pass


class Dog(Animal):
    pass


dog = Dog()

print(isinstance(dog, Dog))       # True
print(isinstance(dog, Animal))    # True
print(issubclass(Dog, Animal))    # True
print(issubclass(Animal, Dog))    # False
```

#### Java comparison

```java
class Animal { }
class Dog extends Animal { }

class Main {
    public static void main(String[] args) {
        Animal animal = new Dog();

        // Object's runtime type check
        System.out.println(animal instanceof Dog); // true

        // Class relationship check
        System.out.println(
            Animal.class.isAssignableFrom(Dog.class)
        ); // true
    }
}
```

> In Java, `instanceof` checks an object, while `Class.isAssignableFrom()` can check class-type compatibility.

[⬆ Back to top](#-table-of-contents)

---

## Part 1.4: Important Python OOP Features

### 18. What is the difference between instance variables and class variables?

#### Interview answer

Instance variables belong to individual objects, so each object can store a different value. Class variables belong to the class and are shared by instances unless an instance overrides the value with its own attribute.

#### Explanation of key terms

- Instance variable: Stores object-specific information.
- Class variable: Stores information associated with the class.
- Shared: Multiple instances can access the same class-level value.
- Shadowing: An instance attribute with the same name takes precedence when accessing that name through the instance.

#### Python code

```python
class Student:
    school = "ABC School"  # Class variable

    def __init__(self, name):
        self.name = name   # Instance variable


s1 = Student("Ravi")
s2 = Student("Priya")

print(s1.name)    # Ravi
print(s2.name)    # Priya
print(s1.school)  # ABC School

Student.school = "XYZ School"
print(s1.school)  # XYZ School
```

#### Java code

```java
class Student {
    static String school = "ABC School"; // Class variable
    String name;                         // Instance variable

    Student(String name) {
        this.name = name;
    }

    public static void main(String[] args) {
        Student s1 = new Student("Ravi");
        Student s2 = new Student("Priya");

        System.out.println(s1.name);
        System.out.println(s2.name);
        System.out.println(Student.school);
    }
}
```

> Java terminology: A class variable is declared `static`. An instance variable is a non-static field.

[⬆ Back to top](#-table-of-contents)

---

### 19. What are access modifiers in Python? Explain public, protected, and private members.

#### Interview answer

Access modifiers control the intended visibility of class members. Python uses naming conventions and name mangling rather than strict access modifiers, whereas Java provides explicit access levels such as `public`, `protected`, package-private, and `private`.

#### Explanation

| Convention / modifier | Python | Java |
| --- | --- | --- |
| Public | `name` | `public` |
| Protected | `_name` (convention) | `protected` |
| Private | `__name` (name mangling) | `private` |

- Public: Intended to be accessible from anywhere.
- Protected: Intended for use within a class and its subclasses. Python's single underscore is a convention; Java enforces its protected access rules.
- Private: Intended for use within a class. Python's double underscore triggers name mangling, while Java's `private` restricts access to the declaring class.

#### Python code

```python
class Example:
    def __init__(self):
        self.public = "Public"
        self._protected = "Internal-use convention"
        self.__private = "Name-mangled"

    def show_private(self):
        return self.__private


obj = Example()

print(obj.public)
print(obj._protected)      # Accessible, but conventionally internal
print(obj.show_private())

# obj.__private  # AttributeError
```

Python name mangling changes `__private` to a name like `_Example__private`. It discourages accidental access; it is not a security boundary.

#### Java code

```java
class Example {
    public String publicField = "Public";
    protected String protectedField = "Protected";
    private String privateField = "Private";

    public String getPrivateField() {
        return privateField;
    }
}
```

> Java also has package-private access: when no access modifier is specified, a member is accessible within its package, subject to Java's access rules.

[⬆ Back to top](#-table-of-contents)

---

### 20. What are magic methods (dunder methods) in Python? Explain `__str__()` and `__repr__()`.

#### Interview answer

Magic methods, also called dunder methods, are special methods with double underscores that let objects work with Python's built-in operations. `__str__()` provides a user-friendly string representation, while `__repr__()` provides a developer-oriented representation.

#### Explanation of key terms

- Dunder: Short for "double underscore."
- Representation: A string describing an object.
- User-friendly: Designed to be readable when displaying an object.
- Developer-oriented: Intended to help inspect or understand an object; ideally, `repr()` is unambiguous.

Other examples include `__init__()` for initialization, `__len__()` for `len()`, and `__add__()` for the `+` operator.

#### Python code

```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def __str__(self):
        # Readable output for users
        return f"{self.name}, age {self.age}"

    def __repr__(self):
        # Informative representation for developers
        return f"Student({self.name!r}, {self.age!r})"


student = Student("Ravi", 21)

print(str(student))   # Ravi, age 21
print(repr(student))  # Student('Ravi', 21)
```

#### Java comparison

Java commonly uses `toString()` for an object's string representation.

```java
class Student {
    String name;
    int age;

    Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    @Override
    public String toString() {
        return "Student{name='" + name + "', age=" + age + "}";
    }
}
```

> Java has no exact built-in equivalent of Python's separate `__repr__()` convention.

[⬆ Back to top](#-table-of-contents)

---

### 21. What is the difference between `==` and `is` in Python?

#### Interview answer

The `==` operator checks whether two objects are equal in value, while `is` checks whether both references point to the exact same object. Use `==` for value comparison and `is` when checking object identity, such as `value is None`.

#### Explanation of key terms

- Equality: Whether two values are considered equal.
- Identity: Whether two references point to the same object.
- Reference: A way to access an object.
- Immutable: An object whose value cannot be changed after creation, such as a string or tuple (though a tuple can contain mutable objects).

#### Python code

```python
a = [1, 2, 3]
b = [1, 2, 3]
c = a

print(a == b)  # True: same contents
print(a is b)  # False: different list objects
print(a is c)  # True: same object

value = None
print(value is None)  # True
```

#### Java comparison

Java uses `==` for primitive value comparison and for reference identity when comparing objects. For object value equality, use `.equals()` when the class implements it appropriately.

```java
String a = new String("hello");
String b = new String("hello");

System.out.println(a == b);      // false: different objects
System.out.println(a.equals(b)); // true: same string value
```

> Common interview trap: In Python, use `is None`, not `== None`, when checking for `None`.

[⬆ Back to top](#-table-of-contents)

---

### 22. What is the difference between an instance method and a constructor? Does Python support multiple constructors?

#### Interview answer

An instance method performs an operation on an existing object, while a constructor is associated with creating and initializing an object. Python commonly uses `__init__()` for initialization and does not support multiple `__init__()` methods distinguished by parameter lists in the same class.

#### Explanation of key terms

- Constructor: A class mechanism involved in creating an object.
- Initializer: Python's `__init__()` method, which initializes the new object's state.
- Instance method: A method called on an object, usually using `self`.
- Overloading: Defining multiple methods with the same name but different parameter lists.

Strictly speaking, Python's `__new__()` creates an instance, and `__init__()` initializes it. In ordinary interview discussions, `__init__()` is often referred to as the constructor.

#### Python code: one initializer with default arguments

```python
class Student:
    def __init__(self, name="Unknown", age=0):
        self.name = name
        self.age = age

    def display(self):
        # Instance method
        print(self.name, self.age)


s1 = Student()
s2 = Student("Ravi", 21)

s1.display()
s2.display()
```

You can also use `@classmethod` to create alternative ways to construct objects.

```python
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    @classmethod
    def from_string(cls, text):
        name, age = text.split(",")
        return cls(name, int(age))


s = Student.from_string("Ravi,21")
print(s.name, s.age)
```

#### Java code

Java supports constructor overloading:

```java
class Student {
    String name;
    int age;

    Student() {
        this("Unknown", 0);
    }

    Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    void display() {
        System.out.println(name + " " + age);
    }
}
```

> Remember: Java can have multiple constructors with different parameter lists. Python generally uses one `__init__()` and handles alternatives through defaults, class methods, or argument processing.

[⬆ Back to top](#-table-of-contents)

---

## Part 1.5: Common Follow-Up Questions

### 23. What is the difference between inheritance and composition in Python?

#### Interview answer

Inheritance represents an "is-a" relationship, where a child class inherits from a parent class. Composition represents a "has-a" relationship, where an object contains or uses another object to provide functionality.

#### Explanation of key terms

- Is-a relationship: A `Dog` is an `Animal`.
- Has-a relationship: A `Car` has an `Engine`.
- Composition: Building a class using objects of other classes.
- Loose coupling: Designing components so they depend less on each other's internal implementation.

#### Python code

```python
# Inheritance: Dog IS an Animal
class Animal:
    def eat(self):
        print("Eating")


class Dog(Animal):
    pass


# Composition: Car HAS an Engine
class Engine:
    def start(self):
        print("Engine started")


class Car:
    def __init__(self):
        self.engine = Engine()  # Car contains an Engine

    def start(self):
        self.engine.start()


dog = Dog()
dog.eat()

car = Car()
car.start()
```

#### Java code

```java
class Animal {
    void eat() {
        System.out.println("Eating");
    }
}

class Dog extends Animal { } // Inheritance

class Engine {
    void start() {
        System.out.println("Engine started");
    }
}

class Car {
    private Engine engine = new Engine(); // Composition

    void start() {
        engine.start();
    }
}
```

> Interview tip: Inheritance is useful when there is a genuine subtype relationship. Composition is useful when a class needs to use another object's functionality without becoming its subtype.

[⬆ Back to top](#-table-of-contents)

---

### 24. What is the difference between shallow copy and deep copy in Python?

#### Interview answer

A shallow copy creates a new outer object but keeps references to the original nested objects. A deep copy recursively copies nested objects, so changes to mutable nested objects in the copy do not affect the original.

#### Explanation of key terms

- Copy: Creating another object based on an existing object.
- Nested object: An object stored inside another object, such as a list inside a list.
- Shallow copy: Copies the outer container, not the nested objects themselves.
- Deep copy: Recursively copies nested objects, subject to the behavior of those objects and any custom copying rules.
- Mutable: An object that can be changed, such as a list or dictionary.

#### Python code

```python
import copy

original = [[1, 2], [3, 4]]

# Shallow copy
shallow = copy.copy(original)

# Deep copy
deep = copy.deepcopy(original)

original[0][0] = 99

print(original)  # [[99, 2], [3, 4]]
print(shallow)   # [[99, 2], [3, 4]]
print(deep)      # [[1, 2], [3, 4]]
```

The shallow copy has its own outer list, but both lists refer to the same inner lists. The deep copy has independent nested lists in this example.

#### Java comparison

Java does not provide a universal built-in deep-copy operation for arbitrary objects. A shallow copy can be created manually or through mechanisms such as `Object.clone()` when appropriately implemented. Deep copying usually requires custom logic, serialization, or another suitable copying strategy.

```java
import java.util.ArrayList;
import java.util.List;

class Main {
    public static void main(String[] args) {
        List<Integer> original = new ArrayList<>();
        original.add(10);
        original.add(20);

        // Shallow copy of the list structure.
        // Integer objects are immutable.
        List<Integer> shallow = new ArrayList<>(original);

        original.set(0, 99);

        System.out.println(original); // [99, 20]
        System.out.println(shallow);  // [10, 20]
    }
}
```

This Java example copies a list containing immutable integers. For nested mutable objects, copying the outer list alone would not independently copy the nested objects.

[⬆ Back to top](#-table-of-contents)

---

### 25. What is an abstract class in Python, and how do you create one using the `abc` module?

#### Interview answer

An abstract class is a base class intended to define a common interface for its subclasses. In Python, it is commonly created using `ABC` and `@abstractmethod` from the `abc` module, and subclasses must implement the required abstract methods before they can be instantiated.

#### Explanation of key terms

- `abc`: Python's module for Abstract Base Classes.
- `ABC`: A helper base class used to define abstract classes.
- `@abstractmethod`: A decorator marking a method as abstract.
- Concrete class: A class that provides implementations for all required abstract methods and can be instantiated.
- Interface: A description of operations that an implementation should provide.

#### Python code

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        # Subclasses must implement area()
        pass


class Rectangle(Shape):
    def __init__(self, width, height):
        self.width = width
        self.height = height

    def area(self):
        return self.width * self.height


rectangle = Rectangle(5, 4)
print(rectangle.area())  # 20

# shape = Shape()  # TypeError: abstract method not implemented
```

#### Java code

```java
abstract class Shape {
    abstract double area();
}

class Rectangle extends Shape {
    private double width;
    private double height;

    Rectangle(double width, double height) {
        this.width = width;
        this.height = height;
    }

    @Override
    double area() {
        return width * height;
    }
}

class Main {
    public static void main(String[] args) {
        Shape shape = new Rectangle(5, 4);
        System.out.println(shape.area()); // 20.0
    }
}
```

> Key difference: Python uses the `abc` module to enforce abstract methods. Java has the `abstract` keyword built into the language.

[⬆ Back to top](#-table-of-contents)

---

## Bonus: The `self`, `cls`, and `this` Interview Questions

Since you specifically mentioned `self` and `cls`, make sure you can answer these three follow-up questions too.

### 26. What is the difference between `self` and `cls` in Python?

#### Interview answer

`self` refers to the current instance and is used in instance methods to access instance attributes and methods. `cls` refers to the class itself and is conventionally used as the first parameter of a method decorated with `@classmethod`.

#### Complete Python example

```python
class Employee:
    company = "ABC"

    def __init__(self, name):
        self.name = name  # Instance attribute

    def show_name(self):
        return self.name  # Uses self

    @classmethod
    def show_company(cls):
        return cls.company  # Uses cls

    @classmethod
    def change_company(cls, name):
        cls.company = name


e1 = Employee("Ravi")

print(e1.show_name())       # Ravi
print(Employee.show_company())  # ABC

Employee.change_company("XYZ")
print(Employee.show_company())  # XYZ
```

#### Java comparison

```java
class Employee {
    static String company = "ABC";
    String name;

    Employee(String name) {
        this.name = name;
    }

    void showName() {
        System.out.println(this.name);
    }

    static void showCompany() {
        System.out.println(Employee.company);
    }
}
```

> Java's `this` refers to the current object. Java uses the class name, such as `Employee`, to access static class-level members.

[⬆ Back to top](#-table-of-contents)

---

### 27. Is `self` a keyword in Python? Is `cls` a keyword?

#### Interview answer

No, neither `self` nor `cls` is a Python keyword. They are conventional parameter names: `self` is used for instance methods, and `cls` is used for class methods.

#### Python example

```python
class Example:
    def instance_method(self):
        return "Instance method"

    @classmethod
    def class_method(cls):
        return "Class method"
```

Although other names are technically possible, use `self` and `cls` to follow standard Python conventions.

[⬆ Back to top](#-table-of-contents)

---

### 28. Does Java have `self` or `cls`?

#### Interview answer

Java uses the keyword `this` to refer to the current object, which is similar to Python's `self`. Java has no direct equivalent of Python's `cls`; static methods access class-level members through the class name and cannot use `this`.

#### Java example

```java
class Example {
    static String message = "Hello";
    String name;

    Example(String name) {
        this.name = name; // Current object
    }

    void showName() {
        System.out.println(this.name);
    }

    static void showMessage() {
        System.out.println(Example.message);
    }
}
```

[⬆ Back to top](#-table-of-contents)

---

## Final Revision Sheet

Use this as your quick revision before an interview.

| Question | One-line memory answer |
| --- | --- |
| Class | A blueprint for creating objects. |
| Object | An instance of a class. |
| `__init__()` | Initializes a newly created object. |
| `self` | Refers to the current instance. |
| `cls` | Conventionally refers to the current class. |
| `this` | Java's reference to the current object. |
| Encapsulation | Bundles data and methods and controls access. |
| Abstraction | Exposes essential functionality and hides implementation details. |
| Inheritance | Allows a class to inherit from another class. |
| Polymorphism | Allows a common interface to have different behaviors. |
| Overloading | Same method name with different parameter lists. |
| Overriding | A subclass redefines an inherited method. |
| `super()` | Accesses the next implementation in Python's MRO or invokes a Java superclass constructor. |
| MRO | The order Python uses to search for methods. |
| `isinstance()` | Checks an object's type relationship. |
| `issubclass()` | Checks a class's inheritance relationship. |
| Class variable | A variable associated with the class. |
| Instance variable | A variable associated with an individual object. |
| `__str__()` | User-friendly string representation. |
| `__repr__()` | Developer-oriented representation. |
| `==` | Checks equality (with language-specific rules). |
| `is` | Checks object identity in Python. |
| Composition | A "has-a" relationship. |
| Shallow copy | Copies the outer object, retaining nested references. |
| Deep copy | Recursively copies nested objects. |
| Abstract class | A base class that can require subclasses to implement methods. |

[⬆ Back to top](#-table-of-contents)

---

## How to Practise These for Interviews

**Your OOP practice checklist** (0 of 5)

- [ ] Explain the concept in your own words.
- [ ] Say the 2–3 line interview answer without looking.
- [ ] Write the Python code from memory.
- [ ] Write the Java equivalent from memory.
- [ ] Explain what each important line does.

*Reset checklist*

**Best learning strategy:** Study one concept in Python, then immediately write the Java equivalent. Focus especially on `self` vs. `this`, `cls` vs. `static`, Python's flexible method arguments vs. Java's method overloading, and Python's multiple inheritance vs. Java's interfaces. These comparisons help you understand both languages instead of memorizing two separate sets of definitions.

[⬆ Back to top](#-table-of-contents)

---
---

# Part 2 — General OOPS Interview Questions & Answers (27 Important Questions)

Absolutely. Below is a **27-question OOP/OOPS interview set** designed to cover the concepts most commonly asked in interviews, with **short, interview-ready answers** you can actually say aloud.

### 1. What is OOP/OOPS?

**Interview answer:**
"OOP stands for Object-Oriented Programming. It is a programming approach where we organize software around **objects and classes**. Objects contain data and methods that operate on that data. The main principles of OOP are **encapsulation, inheritance, polymorphism, and abstraction**."

[⬆ Back to top](#-table-of-contents)

---

### 2. What is a class?

**Interview answer:**
"A class is a **blueprint or template for creating objects**. It defines the properties and behaviors that its objects will have."

**Example:**
A `Car` class can have properties like `color` and `speed`, and methods like `start()` and `stop()`.

[⬆ Back to top](#-table-of-contents)

---

### 3. What is an object?

**Interview answer:**
"An object is an **instance of a class**. It represents a real-world or logical entity and contains its own state and behavior."

**Example:**
If `Car` is a class, then `myCar` can be an object of the `Car` class.

[⬆ Back to top](#-table-of-contents)

---

### 4. What are the four main principles of OOP?

**Interview answer:**
"The four main principles are:

1. **Encapsulation** – wrapping data and methods together.
2. **Abstraction** – hiding unnecessary implementation details.
3. **Inheritance** – acquiring properties and behavior from another class.
4. **Polymorphism** – allowing the same interface or method name to behave differently in different situations."

[⬆ Back to top](#-table-of-contents)

---

### 5. What is encapsulation?

**Interview answer:**
"Encapsulation means **bundling data and the methods that operate on that data together**, while controlling direct access to the data. It helps protect an object's internal state."

**Example:**
We can make a variable private and provide public getter and setter methods to access it.

[⬆ Back to top](#-table-of-contents)

---

### 6. What is abstraction?

**Interview answer:**
"Abstraction means **hiding implementation details and showing only the necessary functionality to the user**."

**Example:**
When I use an ATM, I know how to withdraw money, but I don't need to know the internal implementation of the banking system.

[⬆ Back to top](#-table-of-contents)

---

### 7. What is inheritance?

**Interview answer:**
"Inheritance is a mechanism where one class **acquires properties and methods of another class**. It promotes code reuse and establishes a relationship between classes."

**Example:**
`Dog` can inherit common characteristics from an `Animal` class.

[⬆ Back to top](#-table-of-contents)

---

### 8. What are the types of inheritance?

**Interview answer:**
"The common types are:

- Single inheritance
- Multilevel inheritance
- Hierarchical inheritance
- Multiple inheritance
- Hybrid inheritance

The availability of some types depends on the programming language. For example, Java doesn't support multiple inheritance through classes, but it can achieve similar behavior using interfaces."

[⬆ Back to top](#-table-of-contents)

---

### 9. What is polymorphism?

**Interview answer:**
"Polymorphism means **one interface or method name can have different behaviors depending on the situation**."

"There are two commonly discussed types: **compile-time polymorphism**, such as method overloading, and **runtime polymorphism**, such as method overriding."

[⬆ Back to top](#-table-of-contents)

---

### 10. What is method overloading?

**Interview answer:**
"Method overloading means having **multiple methods with the same name but different parameter lists** in the same class. It is generally considered compile-time polymorphism."

**Example:**

```text
add(int a, int b)
add(int a, int b, int c)
```

[⬆ Back to top](#-table-of-contents)

---

### 11. What is method overriding?

**Interview answer:**
"Method overriding occurs when a child class provides its **own implementation of a method inherited from the parent class**. It is commonly associated with runtime polymorphism."

[⬆ Back to top](#-table-of-contents)

---

### 12. What is the difference between overloading and overriding?

| Overloading | Overriding |
| --- | --- |
| Usually same class | Parent-child relationship |
| Different parameter list | Same method signature, subject to language rules |
| Compile-time polymorphism | Runtime polymorphism |
| Usually doesn't require inheritance | Requires inheritance/subtyping |

**Interview answer:**
"The main difference is that overloading provides multiple versions of a method based on different parameters, while overriding allows a child class to provide a different implementation of an inherited method."

[⬆ Back to top](#-table-of-contents)

---

### 13. What is the difference between a class and an object?

**Interview answer:**
"A class is a **blueprint**, while an object is an **instance created from that blueprint**. For example, `Car` can be a class and `myCar` can be an object."

[⬆ Back to top](#-table-of-contents)

---

### 14. What is an abstract class?

**Interview answer:**
"An abstract class is a class that is intended to be **used as a base class rather than instantiated directly**. It can contain abstract methods as well as concrete methods, depending on the language."

**Java example:**

```java
abstract class Animal {
    abstract void sound();

    void eat() {
        System.out.println("Eating");
    }
}
```

[⬆ Back to top](#-table-of-contents)

---

### 15. What is an interface?

**Interview answer:**
"An interface defines a **contract that implementing classes agree to follow**. It is useful for abstraction and for defining common behavior across potentially unrelated classes."

[⬆ Back to top](#-table-of-contents)

---

### 16. Abstract class vs interface?

**Interview answer:**
"An abstract class is useful when related classes need to share **common state or implementation**, while an interface is useful for defining a **common contract or capability**. The exact features differ between languages."

**For Java specifically:**
An abstract class can have instance variables, constructors, concrete methods, and abstract methods. An interface primarily defines a contract, although modern Java interfaces can also contain default, static, and private methods.

[⬆ Back to top](#-table-of-contents)

---

### 17. What is a constructor?

**Interview answer:**
"A constructor is a special mechanism used to **initialize an object when it is created**. It typically has the same name as the class in languages such as Java and C++ and doesn't have a return type."

[⬆ Back to top](#-table-of-contents)

---

### 18. What is a destructor?

**Interview answer:**
"A destructor is a mechanism used to perform cleanup when an object is being destroyed. Languages handle this differently. For example, C++ has destructors, while Java uses garbage collection and does not have traditional destructors."

[⬆ Back to top](#-table-of-contents)

---

### 19. What are access modifiers?

**Interview answer:**
"Access modifiers control the **visibility and accessibility of classes, methods, and variables**."

"For example, Java commonly has `private`, default/package-private, `protected`, and `public` access levels."

[⬆ Back to top](#-table-of-contents)

---

### 20. What is the difference between public, private, and protected?

**Interview answer:**
"`public` members can generally be accessed from anywhere allowed by the language. `private` members are restricted to the defining class. `protected` provides access to the defining class and, depending on the language, subclasses and/or related package or module contexts."

[⬆ Back to top](#-table-of-contents)

---

### 21. What is the difference between composition and inheritance?

**Interview answer:**
"Inheritance represents an **is-a relationship**, while composition represents a **has-a relationship**."

**Example:**

- `Dog is an Animal` → inheritance
- `Car has an Engine` → composition

"Composition is often preferred when we want to build functionality by combining independent objects."

[⬆ Back to top](#-table-of-contents)

---

### 22. What is association?

**Interview answer:**
"Association is a general relationship between two objects where they are connected or interact with each other."

**Example:**
A `Teacher` can be associated with a `Student`.

[⬆ Back to top](#-table-of-contents)

---

### 23. What is aggregation?

**Interview answer:**
"Aggregation is a **weak has-a relationship** where one object contains or uses another object, but the contained object can exist independently."

**Example:**
A `Department` has `Teachers`, but a teacher can exist independently of that department.

[⬆ Back to top](#-table-of-contents)

---

### 24. What is composition?

**Interview answer:**
"Composition is a **strong has-a relationship** where the contained object's lifecycle is closely tied to the containing object."

**Example:**
If an object represents a `House`, its `Rooms` can be modeled as components of that house. In a composition relationship, the components' lifecycle is managed as part of the whole."

[⬆ Back to top](#-table-of-contents)

---

### 25. What is dynamic binding?

**Interview answer:**
"Dynamic binding means that the method implementation to execute is determined **at runtime rather than compile time**. It is commonly associated with method overriding and runtime polymorphism."

[⬆ Back to top](#-table-of-contents)

---

### 26. What is the difference between static binding and dynamic binding?

**Interview answer:**
"Static binding is resolved at **compile time**, while dynamic binding is resolved at **runtime**. Method overloading is commonly associated with static binding, whereas overridden methods are commonly associated with dynamic binding."

[⬆ Back to top](#-table-of-contents)

---

### 27. Why is OOP useful? What are its advantages?

**Interview answer:**
"OOP helps organize large programs into manageable objects and classes. Its major advantages include **code reuse through inheritance or composition, better encapsulation, abstraction, polymorphism, maintainability, and easier organization of complex systems**."

[⬆ Back to top](#-table-of-contents)

---

## ⭐ Very Common Follow-Up Questions

Interviewers often continue with questions like:

- What is the difference between **encapsulation and abstraction**?
- What is the difference between **inheritance and composition**?
- Can we achieve polymorphism without inheritance?
- Why is **composition often preferred over inheritance**?
- Can we overload a method by changing only its return type?
- Can constructors be overridden?
- Can a static method be overridden?
- What is **upcasting and downcasting**?
- What is an **immutable object**?
- What is the difference between **shallow copy and deep copy**?
- What is the difference between **HAS-A and IS-A**?
- What is the difference between an **abstract class and a concrete class**?

### A good way to answer in an interview

Don't try to give a textbook paragraph. Use this simple structure:

> **Definition → Key point → Small example**

For example, if asked **"What is encapsulation?"**, say:

> "Encapsulation means bundling data and the methods that operate on that data together and controlling access to the internal state. For example, we can make a variable private and provide public methods to access or modify it. This helps protect the object's data."

That style sounds much more natural in an interview than memorizing long definitions.

[⬆ Back to top](#-table-of-contents)

---
---

# Part 3 — Class and Object: Structure Walkthrough (Java & Python)

You're very close! Your understanding of classes, objects, attributes, and methods is mostly correct. Let me clarify a few things and show you the structure in both Java and Python, with comments explaining each block.

## 1. First, understand the concepts

| Concept | Meaning | Example |
| --- | --- | --- |
| Class | A blueprint for creating objects | `Student` |
| Object | An instance of a class | A particular student |
| Attributes | Variables that store an object's data | `name`, `age` |
| Constructor | Initializes an object when it is created | `__init__()` in Python |
| Method | A function that defines an object's behavior | `study()` |

One small correction: attributes are not objects themselves. Attributes are variables that belong to an object and store its data. Methods define what the object can do.

Also, the constructor does not usually create the object itself. The object is created when you instantiate the class, and the constructor initializes it.

[⬆ Back to top](#-table-of-contents)

---

## 2. Python — Class and object

```python
# BLOCK 1: Declare a class
class Student:

    # BLOCK 2: Constructor (initializes the object)
    def __init__(self, name, age):
        # Attributes of the object
        self.name = name
        self.age = age

    # BLOCK 3: Define a method (behavior)
    def study(self):
        print(self.name, "is studying")
        print("Age:", self.age)


# BLOCK 4: Create objects and pass values
student1 = Student("Rahul", 20)
student2 = Student("Priya", 19)


# BLOCK 5: Call methods using the objects
student1.study()
student2.study()
```

### Output

```
Rahul is studying
Age: 20
Priya is studying
Age: 19
```

### How the Python code works

| # | Concept | Code | Explanation |
| --- | --- | --- | --- |
| 1 | Class declaration | `class Student:` | Creates a blueprint for student objects. |
| 2 | Constructor | `__init__(self, name, age)` | Initializes each object with its own name and age. `self` refers to the current object. |
| 3 | Method | `study()` | Defines the behavior of a student object. |
| 4 | Object creation | `student1 = Student("Rahul", 20)` | Creates a `Student` object and initializes its attributes. |
| 5 | Method call | `student1.study()` | Calls the method for that particular object. |

[⬆ Back to top](#-table-of-contents)

---

## 3. Java — Class and object

Java follows a similar structure, but there are a few syntax differences.

```java
// BLOCK 1: Declare a class
class Student {

    // BLOCK 2: Declare attributes
    String name;
    int age;

    // BLOCK 3: Constructor (initializes the object)
    Student(String name, int age) {
        this.name = name;
        this.age = age;
    }

    // BLOCK 4: Define a method (behavior)
    void study() {
        System.out.println(name + " is studying");
        System.out.println("Age: " + age);
    }
}

// BLOCK 5: Main class to run the program
public class Main {

    public static void main(String[] args) {

        // BLOCK 6: Create objects and pass values
        Student student1 = new Student("Rahul", 20);
        Student student2 = new Student("Priya", 19);

        // BLOCK 7: Call methods using the objects
        student1.study();
        student2.study();
    }
}
```

### Output

```
Rahul is studying
Age: 20
Priya is studying
Age: 19
```

### How the Java code works

- Block 1: `class Student` declares the class.
- Block 2: `name` and `age` are attributes (instance variables).
- Block 3: `Student()` is the constructor. It initializes the attributes using `this`.
- Block 4: `study()` defines the behavior.
- Block 5: `main()` is the entry point of the Java program.
- Block 6: `new Student(...)` creates objects and passes values to the constructor.
- Block 7: The dot operator (`.`) is used to call methods on the objects.

[⬆ Back to top](#-table-of-contents)

---

## 4. The complete structure — side by side

This is the general order you should remember:

**Python**

1. Declare the class — `class Student:`
2. Define the constructor — `def __init__(self, ...):`
3. Define attributes and methods
4. Create objects — `student1 = Student(...)`
5. Call methods — `student1.study()`

The Java order is similar, except that you declare the attributes explicitly, use a constructor with the class name, and put the executable statements inside `main()`.

[⬆ Back to top](#-table-of-contents)

---

## 5. One important thing to remember

You said, "In that method we create objects."

The more precise way to say it is:

We define the class and its constructor and methods first. Then, outside the class (or inside another method, such as `main()` in Java), we create objects and call their methods.

You can also create objects inside a method when needed, but it is not a requirement.

**In short:** Class → Constructor and attributes → Methods → Create objects → Call methods.

That's the fundamental structure of object-oriented programming in both Java and Python.

[⬆ Back to top](#-table-of-contents)
