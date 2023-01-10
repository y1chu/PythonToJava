# OOP

Java is an object-oriented programming (OOP) language, which means it uses the concepts of classes and objects to organize and manipulate data. These concepts do not exist in Python, so understanding them is essential to writing Java code.

**Classes and objects**
In Java, a class is a blueprint for an object. It defines the data and behavior of the object. For example, a class called "Dog" might have data such as the dog's name and breed, and behavior such as the ability to bark or fetch. An object is an instance of a class. So, if you create two "Dog" objects, each object will have its own name and breed, but they will both have the ability to bark and fetch.

```agsl
class Dog {
    String name;
    String breed;
    void bark() {
        System.out.println("Woof woof!");
    }
    void fetch() {
        System.out.println("Fetching...");
    }
}

Dog fido = new Dog();
fido.name = "Fido";
fido.breed = "Golden Retriever";
fido.bark(); // prints "Woof woof!"
fido.fetch(); // prints "Fetching..."

Dog spot = new Dog();
spot.name = "Spot";
spot.breed = "Bulldog";
spot.bark(); // prints "Woof woof!"
spot.fetch(); // prints "Fetching..."

```