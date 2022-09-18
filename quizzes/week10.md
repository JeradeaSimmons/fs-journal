# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```

```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structure is a value type in the stack, Class is a reference type stored in the heap.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
a constructor
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
the return value to be a string
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
an override
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
to extend or modify the method.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public private protected and default.
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only code in the same class.
```