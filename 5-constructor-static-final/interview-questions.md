
#### What is a Constructor in Java?
    Constructor is just like a method in Java that is used to initialize the state of an object and will be invoked during the time of object creation.

#### Can we have a class with no Constructor in it ? What will happen during object creation ?
    Yes, we can have a class with no constructor, When the compiler encounters a class with no constructor then it will automatically create a default constructor for you.

#### What is constructor overloading in java?

    Constructor overloading is a technique in which a class can have more than one constructor having the same name but different parameter lists. A parameter list consists of order and types of arguments.

#### What is static in Java?

    A Static variable gets memory allocated only once during the time of class loading.
    All the instance of the class share the same copy of the variable, a static variable can be accessed directly by calling “<<ClassName>>.<<VariableName>>” without need to create an instance for the class.
    value of a static variable will be common for all instances.

#### Can we Overload static methods in Java
  Yes, you can overload a static method in Java.

#### What is a static block?
  A static block is a block of code inside a Java class that will be executed when a class is first loaded into the JVM. Mostly the static block will be used for initializing the variables.
  The static block will be called only one while loading and it cannot have any return type, or any keywords (this or super).

#### Can Interface in Java have static methods in it ?
  Yes, From Java 8 onwards the interface can have static methods in it.

#### What is the use of the final keyword in Java?
  Final keyword can be applied to variable, method, and class. Each of them has its own uses

  The final variable is a variable whose value cannot be changed at any time once assigned, it remains as a constant forever.
  The final method cannot be overridden
  A final class cannot be subclassed (cannot be extended)

#### Can we declare constructor as final?
  No, Constructor cannot be declared as final. Constructors are not inherited and so it cannot be overridden, so there is no use to have a final constructor.

#### Can final method be overloaded in Java?
   Yes, the final method can be overloaded but cannot be overridden. Which means you can have more than one final method with the same name with different parameters.
