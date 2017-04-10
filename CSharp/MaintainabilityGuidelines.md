# Maintainability Guidelines
1. Methods should not exceed 7 statements
2. Make all members private and types internal by default
3. Avoid conditions with double negatives
4. Name assemblies after their contained namespace
5. Name a source file to the type it contains
6. Limit the contents of a source code file to one type
7. Name a source file to the logical function of the partial type
8. Use using statements instead of fully qualified type names
9. Don't use "magic" numbers
10. Only use var when the type is very obvious
11. Declare and initialize variables as late as possible
12. Assign each variable in a separate statement
13. Favor Object and Collection Initializers over separate statements
14. Don't make explicit comparisons to true or false
15. Don't change a loop variable inside a for loop
16. Avoid nested loops
17. Always add a block after keywords such as if, else, while, for, foreach and case
18. Always add a default block after the last case in a switch statement
19. Finish every if-else-if statement with an else-part
20. Be reluctant with multiple return statements
21. Don't use if-else statements instead of a simple (conditional) assignment
22. Encapsulate complex expressions in a method or property
23. Call the more overloaded method from other overloads
24. Only use optional arguments to replace overloads
25. Avoid using named arguments
26. Don't allow methods and constructors with more than three parameters
27. Don't use ref or out parameters
28. Avoid methods that take a bool flag
29. Don't use parameters as temporary variables
30. Always check the result of an as operation
31. Don't comment out code