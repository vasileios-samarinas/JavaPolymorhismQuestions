# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

The word polymorphism means having many forms. In simple words, we can define polymorphism as the ability of a message to be displayed in more than one form.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

We can treat an instance of a class as if it is also another class/type at the same time.
Polymorphism can be implemented using both abstract classes and interfaces.
An example of polymorphism is a Network class with printers and desktops with an
IConnect interface. With polymorphism, we can than create an ArrayList of IConnect which means that it can contain both Desktop and Printer objects.

3. What can we use to implement polymorphism in Java?

Polymorphism can be implemented using both abstract classes, superclasses and interfaces.

4. How many 'forms' can an object take when using polymorphism?

When we talk of something being 'polymorphic' we mean that it can have 'many forms'.

5. Give an example of when you could use polymorphism.

Wilma is an example of polymorphism.
We can look at Wilma in many ways: * Wilma the wife(of Fred) * Wilma the parent(of Pebbles) * Wilma the brain surgeon * Wilma the baseball fan

When Wilma is at home she is Wilma the wife and/or Wilma the parent, but not Wilma the brain surgeon or baseball fan. When at work she is Wilma the brain surgeon etc.

Also,an example of polymorphism is a Network class with printers and desktops with an
IConnect interface. With polymorphism, we can than create an ArrayList of IConnect which means that it can contain both Desktop and Printer objects.


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Composition allows us to model objects that are made up of other objects, thus defining a “has-a” relationship between them.

Furthermore, the composition is the strongest form of association, which means that the object(s) that compose or are contained by one object are destroyed too when that object is destroyed.

7. When would you use composition? Provide a simple example in Java.

It describes a class that references one or more objects of other classes in instance variables. This allows you to model a has-a association between objects.

A computer is composed of different parts, including the microprocessor, the memory, a sound card and so forth, so we can model both the computer and each of its parts as individual classes.Computer meets the “has-a” condition with the classes that model its parts.



8. What is/are the advantage(s) of using composition?

If you are looking for code reuse and the relationship between two classes is has-a then you should use composition rather than inheritance.

Benefit of using composition in java is that we can control the visibility of other object to client classes and reuse only what we need.Composition allows creation of back-end class when it’s needed.

9. When an object is destroyed, what happens to all the objects it is composed of?
