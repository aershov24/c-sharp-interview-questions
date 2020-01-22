# C# Interview Questions and Answers

Having a Senior Developer C# Interview? Don't panic, we got you covered! Check that list of top most advanced C# interview questions for experienced developer and got your next six-figure job offer in style!

> You could also find all the answers here 👉 https://www.fullstack.cafe/C%23.


### Q1: What is C#? ⭐

**Answer:**

C# is the programming language for writing Microsoft .NET applications. C# provides the rapid application development found in Visual Basic with the power of C++. Its syntax is similar to C++ syntax and meets 100% of the requirements of OOPs like the following: 
* Abstraction
* Encapsulation
* Polymorphism
* Inheritance

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q2: What is an Object? ⭐

**Answer:**

According to MSDN, "_a class or struct definition is like a blueprint that specifies what the type can do. An object is basically a block of memory that has been allocated and configured according to the blueprint. A program may create many objects of the same class. Objects are also called instances, and they can be stored in either a named variable or in an array or collection. Client code is the code that uses these variables to call the methods and access the public properties of the object. In an object-oriented language such as C#, a typical program consists of multiple objects interacting dynamically"._

Objects helps us to access the member of a class or struct either they can be fields, methods or properties, by using the dot. 

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q3: What is the difference between "continue" and "break" statements in C#? ⭐

**Answer:**

* using **break** statement, you can jump out of a loop
* using **continue** statement, you can jump over one iteration and then resume your loop execution

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q4: What are property Accessors? ⭐

**Answer:**

The _get_ and _set_ portions or blocks of a property are called accessors. These are useful to restrict the accessibility of a property, the set accessor specifies that we can assign a value to a private field in a property and without the set accessor property it is like a read-only field. By the get accessor we can access the value of the private field, in other words it returns a single value. A Get accessor specifies that we can access the value of a field publically.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q5: What is Managed or Unmanaged Code? ⭐⭐

**Answer:**

* **Managed Code**  - The code, which is developed in .NET framework is known as managed code. This code is directly executed by CLR with the help of managed code execution. Any language that is written in .NET Framework is managed code.
* **Unmanaged Code** - The code, which is developed outside .NET framework is known as unmanaged code. Applications that do not run under the control of the CLR are said to be unmanaged, and certain languages such as C++ can be used to write such applications, which, for example, access low - level functions of the operating system. Background compatibility with the code of VB, ASP and COM are examples of unmanaged code.


🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q6: What is Boxing and Unboxing? ⭐⭐

**Answer:**

Boxing and Unboxing both are used for type conversion but have some difference:

* **Boxing** - Boxing is the process of converting a value type data type to the object or to any interface data type which is implemented by this value type. When the CLR boxes a value means when CLR is converting a value type to Object Type, it wraps the value inside a System.Object and stores it on the heap area in application domain.

* **Unboxing** - Unboxing is also a process which is used to extract the value type from the object or any implemented interface type. Boxing may be done implicitly, but unboxing have to be explicit by code. 

The concept of boxing and unboxing underlines the C# unified view of the type system in which a value of any type can be treated as an object.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q7: What is the difference between a struct and a class in C#? ⭐⭐

**Answer:**

Class and struct both are the user defined data type but have some major difference:  
**  
Struct**

* The struct is value type in C# and it inherits from System.Value Type.
* Struct is usually used for smaller amounts of data.
* Struct can't be inherited to other type.
* A structure can't be abstract.
* No need to create object by new keyword.
* Do not have permission to create any default constructor.

**Class**

* The class is reference type in C# and it inherits from the System.Object Type.
* Classes are usually used for large amounts of data.
* Classes can be inherited to other class.
* A class can be abstract type.
* We can't use an object of a class with using new keyword.
* We can create a default constructor.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q8: What is enum in C#? ⭐⭐

**Answer:**

An **enum** is a value type with a set of related named constants often referred to as an enumerator list. The enum keyword is used to declare an enumeration. It is a primitive data type, which is user defined. An enum is used to create numeric constants in .NET framework. All the members of enum are of enum type. Their must be a numeric value for each enum type.

**Some points about enum**

* Enums are enumerated data type in C#.  
* Enums are strongly typed constant. They are strongly typed, i.e. an enum of one type may not be implicitly assigned to an enum of another type even though the underlying value of their members are the same.  
* Enumerations (enums) make your code much more readable and understandable.  
* Enum values are fixed. Enum can be displayed as a string and processed as an integer.  
* The default type is int, and the approved types are byte, sbyte, short, ushort, uint, long, and ulong.  
* Every enum type automatically derives from System.Enum and thus we can use System.Enum methods on enums.  
* Enums are value types and are created on the stack and not on the heap.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q9: Can "this" be used within a static method? ⭐⭐

**Answer:**

We can't use _this_ in static method because keyword _this_ returns a reference to the current instance of the class containing it. Static methods (or any static member) do not belong to a particular instance. They exist without creating an instance of the class and call with the name of a class not by instance so we can't use this keyword in the body of static Methods, but in case of Extension Methods we can use it as the functions parameters.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q10: Define Property in C#? ⭐⭐

**Answer:**

**Properties** are members that provide a flexible mechanism to read, write or compute the values of private fields, in other words by the property we can access private fields. In other words we can say that a property is a return type function/method with one parameter or without a parameter. These are always public data members. It uses methods to access and assign values to private fields called accessors.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q11: What is the difference between string and StringBuilder in c#? ⭐⭐

**Answer:**

**String**
* It's an immutable object that hold string value.
* Performance wise string is slow because its' create a new instance to override or change the previous value.
* String belongs to System namespace.

**StringBuilder**
* StringBuilder is a mutable object.  
* Performance wise StringBuilder is very fast because it will use same instance of StringBuilder object to perform any operation like insert value in existing string.  
* StringBuilder belongs to System.Text.Stringbuilder namespace.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q12: What are partial classes? ⭐⭐

**Answer:**

A **partial** class is only use to splits the definition of a class in two or more classes in a same source code file or more than one source files. You can create a class definition in multiple files but it will be compiled as one class at run time and also when you'll create an instance of this class so you can access all the methods from all source file with a same object. Partial classes can be create in the same namespace it's doesn't allowed to create a partial class in different namespace. 

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q13: What are generics in C#? ⭐⭐

**Answer:**

**Generics** allow you to delay the specification of the data type of programming elements in a class or a method, until it is actually used in the program. In other words, generics allow you to write a class or method that can work with any data type.

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q14: What you understand by Value types and Reference types in C#.Net? ⭐⭐

**Answer:**

In C# data types can be of two types: **Value Types** and **Reference Types**. Value type variables contain their object (or data) directly. If we copy one value type variable to another then we are actually making a copy of the object for the second variable. Value Type member will located into Stack and reference member will located in Heap always.  

🔗 **Source:** [stackoverflow.com](https://stackoverflow.com/questions/412813/when-to-use-arraylist-over-array-in-c)


### Q15: What is Serialization? ⭐⭐

**Answer:**

**Serialization** means saving the state of your object to secondary memory, such as a file.

1.  Binary serialization (Save your object data into binary format).  
2.  Soap Serialization (Save your object data into binary format; mainly used in network related communication).  
3.  XmlSerialization (Save your object data into an XML file).

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q16: What is LINQ in C#? ⭐⭐

**Answer:**

**LINQ** stands for Language Integrated Query. LINQ has a great power of querying on any source of data. The data source could be collections of objects, database or XML files. We can easily retrieve data from any object that implements the `IEnumerable<T>` interface. 

🔗 **Source:** [c-sharpcorner.com](https://www.c-sharpcorner.com/UploadFile/8ef97c/C-Sharp-net-interview-questions-and-answers/)


### Q17: Can multiple catch blocks be executed? ⭐⭐

**Answer:**

No, Multiple catch blocks can't be executed. Once the proper catch code executed, the control is transferred to the finally block and then the code that follows the finally block gets executed.

🔗 **Source:** [guru99.com](https://www.guru99.com/c-sharp-interview-questions.html)


### Q18: What are Custom Exceptions? ⭐⭐

**Answer:**

Sometimes there are some errors that need to be handeled as per user requirements. Custom exceptions are used for them and are used defined exceptions.

🔗 **Source:** [guru99.com](https://www.guru99.com/c-sharp-interview-questions.html)


### Q19: Why can't you specify the accessibility modifier for methods inside the interface? ⭐⭐

**Answer:**

In an interface, we have virtual methods that do not have method definition. All the methods are there to be overridden in the derived class. That's why they all are public.

🔗 **Source:** [guru99.com](https://www.guru99.com/c-sharp-interview-questions.html)


### Q20: What are the different types of classes in C#? ⭐⭐

**Answer:**

The different types of class in C# are:

*   **Partial class** – Allows its members to be divided or shared with multiple .cs files. It is denoted by the keyword _Partial._
*   **Sealed class** – It is a class which cannot be inherited. To access the members of a sealed class, we need to create the object of the class.  It is denoted by the keyword _Sealed_.
*   **Abstract class** – It is a class whose object cannot be instantiated. The class can only be inherited. It should contain at least one method.  It is denoted by the keyword _abstract._
*   **Static class** – It is a class which does not allow inheritance. The members of the class are also static.  It is denoted by the keyword _static_. This keyword tells the compiler to check for any accidental instances of the static class.

🔗 **Source:** [softwaretestinghelp.com](https://www.softwaretestinghelp.com/c-sharp-interview-questions/)


### Q21: How is Exception Handling implemented in C#? ⭐⭐

**Answer:**

Exception handling is done using four keywords in C#:

*   **try** – Contains a block of code for which an exception will be checked.
*   **catch** – It is a program that catches an exception with the help of exception handler.
*   **finally** – It is a block of code written to execute regardless whether an exception is caught or not.
*   **Throw** – Throws an exception when a problem occurs.

🔗 **Source:** [softwaretestinghelp.com](https://www.softwaretestinghelp.com/c-sharp-interview-questions/)


### Q22: What is an Abstract Class? ⭐⭐

**Answer:**

An **Abstract class** is a class which is denoted by abstract keyword and can be used only as a Base class. An Abstract class should always be inherited. An instance of the class itself cannot be created. If we do not want any program to create an object of a class, then such classes can be made abstract.

Any method in the abstract class does not have implementations in the same class. But they must be implemented in the child class.

🔗 **Source:** [softwaretestinghelp.com](https://www.softwaretestinghelp.com/c-sharp-interview-questions/)


### Q23: Can you return multiple values from a function in C#? ⭐⭐

**Answer:**

Yes! Using output parameters. A return statement can be used for returning only one value from a function. However, using output parameters, you can return two values from a function.

🔗 **Source:** [tutorialspoint.com](https://www.tutorialspoint.com/csharp/csharp_interview_questions.htm)


### Q24: In how many ways you can pass parameters to a method? ⭐⭐

**Answer:**

There are three ways that parameters can be passed to a method:

*   **Value parameters** − This method copies the actual value of an argument into the formal parameter of the function. In this case, changes made to the parameter inside the function have no effect on the argument.
*   **Reference parameters** − This method copies the reference to the memory location of an argument into the formal parameter. This means that changes made to the parameter affect the argument.
*   **Output parameters** − This method helps in returning more than one value.

🔗 **Source:** [tutorialspoint.com](https://www.tutorialspoint.com/csharp/csharp_interview_questions.htm)


### Q25: What is namespace in C#? ⭐⭐

**Answer:**

A **namespace** is designed for providing a way to keep one set of names separate from another. The class names declared in one namespace does not conflict with the same class names declared in another.

🔗 **Source:** [tutorialspoint.com](https://www.tutorialspoint.com/csharp/csharp_interview_questions.htm)


### Q26: What are reference types in C#? ⭐⭐

**Answer:**

The **reference types** do not contain the actual data stored in a variable, but they contain a reference to the variables.

In other words, they refer to a memory location. Using multiple variables, the reference types can refer to a memory location. If the data in the memory location is changed by one of the variables, the other variable automatically reflects this change in value. Example of built-in reference types are: object, dynamic, and string.

🔗 **Source:** [tutorialspoint.com](https://www.tutorialspoint.com/csharp/csharp_interview_questions.htm)


### Q27: What are dynamic type variables in C#? ⭐⭐

**Answer:**

You can store any type of value in the dynamic data type variable. Type checking for these types of variables takes place at run-time.

🔗 **Source:** [tutorialspoint.com](https://www.tutorialspoint.com/csharp/csharp_interview_questions.htm)


### Q28: What are nullable types in C#? ⭐⭐

**Answer:**

C# provides a special data types, the **nullable types**, to which you can assign normal range of values as well as null values.

For example, you can store any value from -2,147,483,648 to 2,147,483,647 or null in a `Nullable<Int32>` variable. Similarly, you can assign true, false, or null in a `Nullable<bool>` variable.

🔗 **Source:** [tutorialspoint.com](https://www.tutorialspoint.com/csharp/csharp_interview_questions.htm)


### Q29: Why to use “finally” block in C#? ⭐⭐

**Answer:**

**Finally** block will be executed irrespective of exception. So while executing the code in try block when exception is occurred, control is returned to catch block and at last `finally` block will be executed. So closing connection to database / releasing the file handlers can be kept in `finally` block.

🔗 **Source:** [a4academics.com](http://a4academics.com/interview-questions/52-dot-net-interview-questions/417-c-oops-interview-questions-and-answers?showall=&start=1)


### Q30: Filter out the first 3 even numbers from the list using LINQ ⭐⭐

**Answer:**

```csharp
var evenNumbers = List
   .Where(x => x % 2 ==0)
   .Take(3)
```

🔗 **Source:** [medium.com/](https://medium.com/sears-israel/my-number-one-c-interview-question-39cdaac16c)


### Q31: What is the difference between Interface and Abstract Class? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q32: What is the difference between constant and readonly in c#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q33: What is the difference between ref and out keywords? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q34:  What is extension method in C# and how to use them? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q35: What is delegates in C# and uses of delegates? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q36: What is sealed class in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q37: What is the difference between overloading and overriding? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q38: What is difference between Throw Exception and Throw Clause? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q39: What is the difference between Equality Operator (==) and Equals() Method in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q40: What is Virtual Method in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q41: What are the uses of “using” in C# ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q42: Explain Anonymous type in C# ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q43: What is Reflection in C#.Net? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q44: What is difference between constants and readonly? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q45: Explain Code compilation in C# ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q46: What is the difference between Virtual method and Abstract method? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q47: What is a Destructor in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q48: What is the difference between dynamic type variables and object type variables? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q49: How encapsulation is implemented in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q50: What is scope of a Internal member variable of a C# class? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q51: What is the use of Null Coalescing Operator (??) in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q52: Given an array of ints, write a C# method to total all the values that are even numbers. ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q53: What is the output of the program below? Explain your answer. ⭐⭐⭐

**Questions Details:**

Consider:
```csharp
delegate void Printer();

static void Main()
{
        List<Printer> printers = new List<Printer>();
        int i=0;
        for(; i < 10; i++)
        {
            printers.Add(delegate { Console.WriteLine(i); });
        }

        foreach (var printer in printers)
        {
            printer();
        }
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q54: Refactor the code ⭐⭐⭐

**Questions Details:**

```csharp
class ClassA
{
  public ClassA() { }

  public ClassA(int pValue) {  }
}

// client program
class Program
{
  static void Main(string[] args)
  {
    ClassA refA = new ClassA();
  }
}
```
Is there a way to modify `ClassA` so that you can you call the constructor with parameters, when the Main method is called, without creating any other new instances of the `ClassA`?




 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q55: What is lambda expressions in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q56: What is an anonymous function in C#? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q57: What is marshalling and why do we need it? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q58: What is the difference between dispose and finalize methods in c#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q59: What is difference between late binding and early binding in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q60: What is the Constructor Chaining in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q61: What is Indexer in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q62: Name difference between "is" and "as" operator in C# ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q63: What is an Object Pool in .Net? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q64: When to use ArrayList over array[] in c#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q65: What are the differences between a multidimensional array and an array of arrays in C#? ⭐⭐⭐⭐

**Questions Details:**

What are the differences between multidimensional arrays `double[,]` and array-of-arrays `double[][]` in C#?


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q66: Describe the accessibility modifier "protected internal". ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q67: What are the different ways a method can be overloaded? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q68: What are pointer types in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q69: What is scope of a Protected Internal member variable of a C# class? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q70: Can you create a function in C# which can accept varying number of arguments? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q71: Is operator overloading supported in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q72: What is the use of conditional preprocessor directive in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q73: What is the difference between System.ApplicationException class and System.SystemException class? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q74: Can we have only “try” block without “catch” block in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q75: In try block if we add return statement whether finally block is executed in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q76: What's the difference between StackOverflowError and OutOfMemoryError? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q77: What are the uses of delegates in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q78: Why to use lock statement in C#? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q79: Can Multiple Inheritance implemented in C# ? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q80: What is the output of the short program below? Explain your answer. ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
class Program {
  static String location;
  static DateTime time;
 
  static void Main() {
    Console.WriteLine(location == null ? "location is null" : location);
    Console.WriteLine(time == null ? "time is null" : time.ToString());
  }
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q81: Is the comparison of time and null in the if statement below valid or not? Why or why not? ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
static DateTime time;
/* ... */
if (time == null)
{
	/* do something */
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q82: What is the output of the program below? Explain your answer. ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
class Program {
  private static string result;
 
  static void Main() {
    SaySomething();
    Console.WriteLine(result);
  }
 
  static async Task<string> SaySomething() {
    await Task.Delay(5);
    result = "Hello world!";
    return “Something”;
  }
}
```
Also, would the answer change if we were to replace `await Task.Delay(5);` with `Thread.Sleep(5)`? Why or why not?


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q83: What is the output of the program below? ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
public class TestStatic {
 public static int TestValue;

 public TestStatic() {
  if (TestValue == 0) {
   TestValue = 5;
  }
 }
 static TestStatic() {
  if (TestValue == 0) {
   TestValue = 10;
  }

 }

 public void Print() {
  if (TestValue == 5) {
   TestValue = 6;
  }
  Console.WriteLine("TestValue : " + TestValue);

 }
}

public void Main(string[] args) {

 TestStatic t = new TestStatic();
 t.Print();
}
```


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q84: What is the "yield" keyword used for in C#? ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
IEnumerable<object> FilteredList()
{
    foreach( object item in FullList )
    {
        if( IsItemInPartialList( item )
            yield return item;
    }
}
```
Could you explain what does the `yield` keyword do there?


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q85: What interface should your data structure implement to make the "Where" method work? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q86: IEnumerable vs List - What to Use? How do they work? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q87: What is the difference between Func<string,string> and delegate? ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
Func<string, string> convertMethod = lambda; // A
public delegate string convertMethod(string value); // B
```
Are they both delegates? What's the difference?


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q88: Explain the difference between Select and Where ⭐⭐⭐⭐

**Questions Details:**

Consider:
```csharp
ContextSet().Select(x=> x.FirstName == "John") // A
ContextSet().Where(x=> x.FirstName == "John") // B
```
When should I use .Select vs .Where?


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q89: Explain what is short-circuit evaluation in C# ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q90: What is the best practice to have best performance using Lazy<T> objects?  ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q91: What are the differences between IEnumerable and IQueryable? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q92: What is deep or shallow copy concept in C#? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q93: What's the difference between the System.Array.CopyTo() and System.Array.Clone()? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q94: What is multicast delegate in C#? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q95: What is the method MemberwiseClone() doing? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q96: List some different ways for equality check in .Net ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q97: What are circular references? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q98: What is jagged array in C#.Net and when to prefer jagged arrays over multi-dimensional arrays? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q99: Could you explain the difference between destructor, dispose and finalize method? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q100: Can you create sealed abstract class in C#? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q101: What is a preprocessor directives in C#? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q102: What is the use of static constructors? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q103: Calculate the circumference of the circle ⭐⭐⭐⭐⭐

**Questions Details:**

Given an instance circle of the following class:

```csharp
public sealed class Circle {
  private double radius;
  
  public double Calculate(Func<double, double> op) {
    return op(radius);
  }
}

write code to calculate the circumference of the circle, without modifying the `Circle` class itself.
```


 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q104: What are the benefits of a Deferred Execution in LINQ? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q105: What is the difference between lambdas and delegates? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q106: Could you explain the difference between Func vs. Action vs. Predicate? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q107: Explain the difference between IQueryable, ICollection, IList & IDictionary interfaces? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q108:  in C#, when should we use abstract classes instead of interfaces with extension methods? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q109: Can you add extension methods to an existing static class? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q110: Implement the "Where" method in C# ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q111: What is the “volatile” keyword used for? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**


### Q112: Explain what is weak reference in C#? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/C%23)**



