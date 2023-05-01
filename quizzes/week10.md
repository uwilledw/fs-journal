# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
A namespace helps control the scope of classes and methods.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
classes are reference types and structs are value types.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
the constructor
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
The type that will be returned
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
Abstract classes serve as a base class and can not be instantiated.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
The virtual allows this method to be modified.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Only code in that class or method.
```