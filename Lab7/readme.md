## Javi Rodriguez / October 11, 2021

## Executive Summary 
Lab 7 explores file compression, object oriented programming in Python, and the concepts behind object orient programming in general. File compression is used to make file sizes smaller. In this lab, we use object oriented programming to create a Python program that defines a shark class that is used to instantiate sharks that have names, can swim, and be awesome. We also discuss object oriented concepts such as instatiated objects, inheritance, abstraction, and encapsulation. Finally, we used Lucidchart to create a diagram to represent the shark class.

## File Compression
### Purpose of File Compression
The purpose of file compression is to make file sizes smaller. Smaller file sizes allow files to be uploaded and downloaded faster than files with larger sizes.
### Compression and File Size
SVG files are generally much large than JPG files. This is because JPG files are already compressed using lossy compression. My SVG graphic went from 599KB to 382KB after being compressed.

## Object Oriented Programming (OOP) and the Shark Class
### Attributes: name, age
The name attribute keeps track of the name of a shark object and is used to describe which shark is doing something. Age would also be an attribute if it was used.
### Methods: swim(self), be_awesome(self)
The swim method prints the name of the shark object followed by the string "is swimming.". The be_awesome method prints the name of the shark object followed by the string " is being awesome."
### Constructor: \_\_init\_\_(self, name)
The purpose of the constructor is to initialize the data of an instantiated object. The constructor of the shark class takes the parameters self and name. The self parameter is a reference to an object that is made based on the shark class. The name parameter is used to give a name to the shark object. The constructor sets the instantiated object's name attribute to the value of the name parameter.
### Class vs. Object
A class is a blueprint for an object created by a programmer. A class defines attributes and methods that can be used by an object of the class. An object is an instance of a class. This means an object is its own seperate entity that follows the rules and definitions set by a class. To "instantiate an object from a class" is to initialize an object based on the definition that is set by the class for that object.
## Object Oriented Concepts
### Instantiated Objects
The instantiated objects of the shark class are sammy, stevie, and javi.
### Inheritance
Inheritance in OOP is the ability for classes to have children. The parent class is known as the base class. The child class is called a derived class. The derived class can inherit all of the attributes and behaviors of the base class while also having its own additional attributes and behaviors. The shark class could have a child class called HammerheadShark that has a name and can swim like the base shark class but also has attributes and behaviors specific to hammerhead sharks.
### Encapsulation and Abstraction
Abstraction is the process of defining a real-life object into the attributes and methods of a class. The shark class as it is defines a shark as something that has a name, can swim, and can be awesome. We could abstract it further as something that has gills and eats. Encapsulation is the mechanism of binding data together and hiding it from the outside world. We can encapsulate the steps of doing something into a method of a class. The shark's behaviors are encapsulated in the shark class's methods. When we call the swim method we don't know exactly what swim is doing unless we look inside the methods definition.
## Unified Modeling Language (UML)

## Conclusion
In this lab, I compressed my SVG graphic which almost halved its file size. I learned the concepts behind object oriented programming. I also learned how to create classes, define methods, and instantiate objects in Python. My experience with this lab will be exteremely useful for my project in which I will create a game using Python. I am excited to apply this knowledge when creating my own classes for my project. Lastly, I used Lucidchart to create a class diagram to represent the shark class. I like being able to visualize a class's attributes and functionality along with its inheritance with Lucidchart.
