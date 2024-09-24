Topic: POLYMORPHISM

Definition:
Compile time polymorphism occurs when multiple methods in the same class have the same name but differ in the type or number of parameters.

Description:
Compile time polymorphism is all about choosing which method to use before the program runs. This decision happens while the program is being compiled (the process of turning your code into an executable program).
How It Works:
•	Same Name, Different Parameters: You can have multiple methods with the same name in the same class, but they must have different parameters. This means they can differ in:
o	The number of parameters (e.g., one method takes two numbers, another takes three).
o	The type of parameters (e.g., one method takes two integers, while another takes two doubles).
•	Example: Imagine you have a method called add:
o	add(int a, int b) adds two integers.
o	add(double a, double b) adds two decimal numbers.
o	add(int a, int b, int c) adds three integers.
When you call add(5, 10), the compiler sees that you are using two integers, so it chooses the first method. If you call add(5.5, 10.5), it picks the method that works with doubles. The compiler knows which method to use right away based on the arguments you provide.
