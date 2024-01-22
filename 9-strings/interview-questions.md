#### What is String Pool?
     As the name suggests, String Pool is a pool of Strings stored in Java heap memory. We know that String is a special class in Java and we can create String object using new operator as well as providing values in double quotes.

#### What are different ways to create String Object?
    We can create String object using new operator like any normal java class or we can use double quotes to create a String object. There are several constructors available in String class to get String from char array, byte array, StringBuffer and StringBuilder.

#### How do you check the equality of two arrays in java? OR How do you compare the two arrays in java?
    You can use Arrays.equals() method to compare one dimensional arrays and to compare multidimensional arrays, use Arrays.deepEquals() method.

####  What is meant by immutable in Java?
    Immutable means that for a given object once execution of the constructor has finished it cannot be modified. For immutable objects the internal fields cannot be modified.

#### How to make an object immutable?
    Objects can be made immutable as follows -
    - The Class must be declared as final so that it cannot be subclassed and its methods cannot be overridden
    - All the class members must be declared as final so that once the object is created it's value cannot be changed
    - For all the class members define getters.
    - Do not define any setter methods for class members
    