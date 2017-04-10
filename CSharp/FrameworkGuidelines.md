# Framework Guidelines
1. Use C# type aliases instead of the types from the System namespace
2. Properly name properties, variables or fields referring to localized resources
3. Don't hard-code strings that change based on the deployment
4. Build with the highest warning level
5. Properly fill the attributes of the AssemblyInfo.cs file
6. Avoid LINQ for simple expressions
7. Use Lambda expressions instead of delegates
8. Only use the dynamic keyword when talking to a dynamic object
9. Favor async/await over the Task