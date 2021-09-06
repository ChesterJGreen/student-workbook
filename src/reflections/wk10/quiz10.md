# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespaces are used to organize code into logical groups and to prevent name collisions that can occur especially when your code base includes multiple libraries.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
A structure is a value type so it is stored on the stack, but a class is a reference type and is stored on the heap. A structure doesn't support inheritance, and polymorphism, but a class supports both. By default, all the struct members are public but class members are by default private in nature
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
Void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
that the returned value will be a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
the inheritance of a class or certain class members that were previously marked virtual
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
it allows itself to be overwritten in a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
within the body of the class or the struct in which they are declared.
```