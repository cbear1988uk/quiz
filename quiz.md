
<!-- Polymorphism -->
1. What does the word 'polymorphism' mean?
    Polymorphism is taking a single object and manipulating it to
    take on many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
    An example would be multiple classes that inherit from a parent class, then
    bringing in another class that has no reason to inherit from that parent class but
    will have the same behaviour as the other classes.

    A hybrid and electric car would inherit from a parent class called 'Car' -
    they would pull colour, engine, and other characteristics from 'Car'. But then
    you have Tank which has no need for colour, but would still need a drive function
    like the other two classes.

3. What can we use to implement polymorphism in Java?
    Using Interfaces and Abstract classes.

4. How many 'forms' can an object take when using polymorphism?
    As many as you give it.

5. Give an example of when you could use polymorphism.
    See the answer for question 2.


<!-- Composition -->
1. What do we mean by 'composition' in reference to object-oriented programming?
    Using interfaces to perform all the polymorphic behaviour.

2. When would you use composition? Provide a simple example in Java.
    When two classes have similar relationships and behaviours.

    A person and a job both have a salary.

3. What is/are the advantage(s) of using composition?
    DRY code, organisation providing a simpler way to re-use only what we need
    out of our code.

5. When an object is destroyed, what happens to all the objects it is composed of?
    They will need heavy re-factoring to recover them.
