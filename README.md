# IT2040_CSharpQuestions1

**Q1: What is a namespace?**

*A namespace, the way I understand it, is a way of organizing code by
grouping methods, classes, etc. together under one "namespace".*

**Q2: What are value types?**

*Value types are, to me, casts that contain a value without having to do
anything. This includes casts like int and char.*

**Q3: What are reference types?**

*Reference types are casts that contain a reference to the actual value rather
than the value itself. Ex. strings, object, etc.*

**Q4: What is an automatic property and how is it useful?**

*A very short way to initialize a field through get/set, allowing us to
skip writing a little bit of code. The way I understand it, its like
writing USA instead of United States of America.*

**Q5: What is the purpose of using statement?**

*To clean up an action after its used so we dont have to use more code to
clean it up later.*

**Q6: What are dynamic type variables?**

*Variables that have flexible or unknown type casts. Basically we can let the
compiler cast it for us by searching our code and making it an appropriate
cast.*

**Q7: What is the purpose of the is operator?**

*To check whether or not an object is compatible with a given type.*

**Q8: What are generics and how is using them useful?**

*Generics are placeholders that allow us to define things until they are used.
This is useful because it allows us to write classes and methods that can
work with any data type.*

**Q9: What is the scope of a public member of a class?**

*Can be accessed by any code in the assembly or any assembly that references
it.*

**Q10: Can you create a function that can accept a varying number of
arguments?**

*Yes.*

**Q11: How do you sort an array?**

*Array.Sort sorts in ascending order. Array.Reverse sorts in descending order.*

**Q12: What is a nullable type and what purpose does it serve?**

*A nullable type is a function that allows us to add null to a value type.
This is useful because it enables null as an allowable value where it wouldnt
otherwise.*

**Q13: What is an enumeration?**

*A set of name constants that correspond to a value and can be referenced.*

**Q14: What is inheritance?**

*Inheritance, the way I understand it, is using super and sub classes in a way
that would give different sub classes access to functions and methods of a
separate class. Basically like my brothers having access to a sink in my
parents house. Thats the way I would explain it anyway. lol*

**Q15: Is multiple inheritance supported?**

*Multiple inheritance is not supported through c# but using an interface
gives us a work around, i think.*

**Q16: What is the purpose of as operator?**

*Used to perform conversion between compatible reference types of nullables.*

**Q17: What is an object?**

*An instance of a method, class, function, etc.*

**Q18: What is the difference between a struct and a class?**

*Structs are value type whilst classes are reference types.*

**Q19: What is the difference between continue and break statements?**

*Break terminates the loop. Continue allows next part of loop to execute.*

**Q20: What is this and how is it used?**

*This is a reference to the current instance of a class. It is used for
passing objects to other methods, declaring indexers, etc.*

**Q21: What is try and catch and when are they used?**

*Try holds code that may cause an exception. Catch is basically a series of
methods trying to handle different exceptions, should they arise.*

**Q23: How is exception handling done?**

*Try holds the code causing exception. Catch receives any exceptions. Finally
executes statements related to exception. Throw outputs the exceptions.*

**Q24: What is finally and what is its purpose?**

*A set of statements that execute whether code executes normally or executes
with an exception. Its job is to release system resources.*

**Q25: List the differences between Array and ArrayList.**

*Array stores one type, has fixed number of elements, and requires no cast.
ArrayList stores multiple types, has dynamic storage, and requires cast.*

**Q26: What is an object?**

*same as question 17*

**Q27: Define constructor.**

*Constructors are basically a body of initialized values to be used as defaults
for a class or struct.*

**Q28: When can var be used to declare a variable and how is the type for
the variable determined?**

*A var can almost always be used and declares a type implicitly. The compiler
determines the type of the var variables.*

**Q29: What is an abstract class?**

*A class that is declared abstract and cant be instantiated. Usually used for
sub-classing and sharing code between closely related methods.*

**Q30: What is an interface?**

*An interface is the declarations of all method and such of an object. It isnt
the implementation. Specifies behavior, but not who does it.*

**Q31: What is a method?**

*A line of code that executes a task written by the user.*

**Q32: What is a property?**

*Special accessors used to read, write, and compute values.*

**Q33: What is an access specifier?**

*A keyword that specifies the accessibility of a type and its members.*

**Q34: What access specifiers are supported and what do they mean?**

*private: limited to inside class/struct where declared

public: accessed from anywhere its referenced

protected: limited to class and classes inherited from base

internal: limited to same program and assembly

protected internal: protected + internal

Private Protected: private in other assembly- not accessible. protected in
current assembly - accessible*

**Q35: What is a collection?**

*Specialized classes for data storage and retrieval. Creates memory dynamically
and accesses it.*

**Q36: What is a Hash Table?**

*A class that stores a collection of key-value pairs.*
