### Example of the Prototype Design Pattern with Inheritance

This example of the Prototype Design Pattern with Inheritance pattern was develop using C# language.

When we are copying object with a lot of inheritance between them, it starts to get really repetitive to implement one by one a Deep Copy method. To mitigate this, we can change the interface to receive a new member (CopyTo), which has a simpler implementation, but most importantly the method DeepCopy becomes standard in the interface, not making it necessary anymore to implement it in every class. The result it a more decoupled and easy to manage chain of inherited objects.

If you're interested in the [udemy course](https://www.udemy.com/course/design-patterns-csharp-dotnet) by [Dmitri Nesteruk](https://www.udemy.com/user/dmitrinesteruk/).
