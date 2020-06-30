### Summary

- Lambdas, also known as anonymous functions, are small, restricted functions which do not need a name (i.e., an identifier).
- Every lambda function in Python has 3 essential parts:
- The lambda keyword.
- The parameters (or bound variables), and
- The function body.
- The syntax for writing a lambda is: lambda parameter: expression
- Lambdas can have any number of parameters, but they are not enclosed in braces
- A lambda can have only 1 expression in its function body, which is returned by default.
- At the bytecode level, there is not much difference between how lambdas and regular functions are handled by the interpreter.
- Lambdas support IIFE thru this syntax: (lambda parameter: expression)(argument)
- Lambdas are commonly used with the following python built-ins:
- Filter: filter (lambda parameter: expression, iterable-sequence)
- Map: map (lambda parameter: expression, iterable-sequences)
- Reduce: reduce (lambda parameter1, parameter2: expression, iterable-sequence)
- Do not write complicated lambda functions in a production environment because it will be difficult for code-maintainers.