Interpreter and compiler for Lox, a dynamically-typed interpreted OOP programming language, made in C. To compile the project via the Command panel, place youself in the "Core" folder and use "gcc -o [executable_name].exe main.c [add all other .c files]" and execute using "lox ../Runtime/loxTest.txt".

Use the file loxTest.txt to input multiple lines of code in the interpreter. You can omit the file path to enter prompt mode, where you can input one line at a time.


This example prints the first 20 Fibonacci numbers onto the screen:

```
fun fib(n) {
 if (n < 2) return n;
 return fib(n - 1) + fib(n - 2); 
}

var before = clock();
print fib(40);
var after = clock();
print after - before;

```

