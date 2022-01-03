# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Prevent class names in one namespace from conflicting with class names in another.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are value types. Classes are reference type.
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
The return data type of the method
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents the class from being instantiated
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
this method can be overridden by any class that inherits it
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
Code in the same class or struct
```