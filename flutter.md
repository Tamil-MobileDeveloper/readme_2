**Advanced Flutter and Dart Concepts Evaluation Test**

**Instructions:** Select the most appropriate option for each question. Each question is worth one point.

**Section 1: Core Dart Concepts**

1. What is the result of the following expression in Dart?

```dart
3 + '2';
```

   a) 32
   b) "32"
   c) Type Error
   d) 5

2. In Dart, what is the purpose of the `is` keyword?

   a) To check if an object is an instance of a particular class
   b) To perform mathematical operations
   c) To create new instances of classes
   d) To access the index of a list

3. Which of the following Dart data types is used for handling fractional numbers?

   a) int
   b) double
   c) num
   d) var

4. What does the `??` operator do in Dart?

   a) It checks if an expression is null and returns true or false.
   b) It performs a bitwise OR operation.
   c) It is used to concatenate strings.
   d) It provides default values for nullable expressions.

**Section 2: Object-Oriented Programming (OOPs) Concepts**

5. What is the main benefit of using inheritance in object-oriented programming (OOP)?

   a) It reduces code complexity and redundancy.
   b) It enables the creation of abstract classes.
   c) It allows for dynamic method dispatch.
   d) It ensures data encapsulation.

6. In OOP, what is encapsulation?

   a) It is a way to create multiple instances of a class.
   b) It is the process of bundling data and methods that operate on that data into a single unit.
   c) It is the process of defining a class within another class.
   d) It is a way to access private variables from outside the class.

7. What is the primary purpose of an abstract class in Dart?

   a) To prevent the instantiation of the class
   b) To declare methods without providing an implementation
   c) To define a class that can be extended by other classes
   d) To create instances of the class

8. In Dart, what does the `super` keyword refer to within a subclass?

   a) It refers to the parent class.
   b) It refers to the current class.
   c) It refers to the superclass of the parent class.
   d) It is used to call a constructor of the same class.

**Section 3: Algorithmic & Functional Understanding**

9. What is the time complexity of finding an element in a sorted list using binary search?

   a) O(1)
   b) O(log n)
   c) O(n)
   d) O(n log n)

10. Which higher-order function in Dart is used to apply a function to each element in a list and return a new list?

   a) map
   b) reduce
   c) forEach
   d) filter

11. What is a closure in Dart?

   a) A function that is declared inside another function and captures variables from its enclosing scope
   b) A way to declare constant values
   c) A type of data structure
   d) A class that cannot be extended

12. What is the purpose of the `async` and `await` keywords in Dart?

   a) To define abstract classes
   b) To create custom widgets
   c) To work with asynchronous code and handle futures
   d) To define static methods

**Section 4: Program Outputs**

For the following questions, consider the code provided and determine the output.

13. What will be the output of the following Dart code?

```dart
void main() {
  print(1);
  Future(() => print(2));
  print(3);
}
```

   a) 1 2 3
   b) 1 3 2
   c) 1 2
   d) 1 3

14. What will be the output of the following Dart code?

```dart
void main() {
  final numbers = [1, 2, 3, 4];
  final sum = numbers.reduce((a, b) => a + b);
  print(sum);
}
```

   a) [1, 2, 3, 4]
   b) 10
   c) [10]
   d) [1, 2, 3, 4, 10]

15. What will be the output of the following Dart code?

```dart
void main() {
  final list = [1, 2, 3, 4];
  list.forEach((i) {
    if (i.isEven) {
      print(i);
    }
  });
}
```

   a) 2 4
   b) 1 3
   c) 1 2 3 4
   d) No output; it will result in an error.

16. What will be the output of the following Dart code?

```dart
void main() {
  print(5 ~/ 2);
}
```

   a) 5
   b) 2.5
   c) 2
   d) 3

**Section 5: Program Outputs**

17. What will be the output of the following Dart code?

```dart
void main() {
  final List<int> numbers = [1, 2, 3, 4];
  final result = numbers.fold(0, (acc, num) => acc + num);
  print(result);
}
```

   a) [1, 2, 3, 4]
   b) 10
   c) 0
   d) 1234

18. What will be the output of the following Dart code?

```dart
void main() async {
  await Future.delayed(Duration(seconds: 2), () => print("Delayed"));
  print("Immediate");
}
```

   a) "Immediate" "Delayed"
   b) "Delayed" "Immediate"
   c) "Immediate"
   d) "Delayed"

19. What will be the output of the following Dart code?

```dart
void main() {
  print(foo());
}

int foo() {
  try {
    return 42;
  } finally {
    return 84;
  }
}
```

   a) 42
   b) 84
   c) 126
   d) The code will result in an error.

20. What will be the output of the following Dart code?

```dart
void main() {
  final x = [1, 2, 3];
  final y = [1, 2, 3];
  print(identical(x, y));
}
```

   a) true
   b) false
   c) null
   d) The code will result in an error.
