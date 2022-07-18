# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace is used for organizing many classes to handle the application very easily. It is helpful for keeping a set of names separate from another.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types and classes are reference types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
An abstract method
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
string is an indication of the data type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents from being instantiated
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It's used to modify the declaration of any property, method or event to allow overriding in a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
Public, Internal, Protected, Private
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Private Methods can only be used inside the class.
```