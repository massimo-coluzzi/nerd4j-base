# Welcome to the Nerd4J project

This is a collection of libraries and frameworks developed during the years to avoid the effort to rewrite always the same [boilerplate code](https://en.wikipedia.org/wiki/Boilerplate_code).
How many times did you see something like this?

```java
if( someObject != null && ! someObject.empty() )
  // do something
```

It would be much quicker to write (and easyer to read) something like this:

```java
if( IsNot.empty(someObject) )
   // do something
```

This kind of code can be found spread in multiple libraries but life is too short to waste time searching for the right library (or worst rewriting every time the same code), so I decided to put all the most common checks in one utility class, so that I don't have to think about it anymore.
Based on the same principle I am developing all the libraries and frameworks composing the Nerd4J project.
Every time I need to write the same code multiple times I think how to make my life easier and I add my solution to the Nerd4J project for others to use.
Every time I need to face pretty much the same problem more than once I try to create an abstraction and I develop a framework that solves that kind of problems


### So far I have published the following projects:


Project | Description
--------|-------------
[nerd4j-utils](utils/index.html) | This is a collection of the most frequently used pieces of code along with some useful classes to handle the samey pesky code.


### Code style

I come from C and C++ and actually I don't like the Google code style that much.
I find it very confusing to have the open bracket not aligned with the close bracket and I like having some space inside the code to make it more readable.\
Therefore I have defined my own Eclipse code style formatter document that can be imported into Eclipse, VSCode and other IDEs.
If you don't like the Google code style as well you may find my style  more compliant to your taste.

It is publicly available at http://nerd4j.org/codestyle/nerd4j-eclipse-java-style.xml