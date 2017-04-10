# Miscellaneous Design Guidelines
1. Throw exceptions rather than returning some kind of status value
2. Provide a rich and meaningful exception message text
3. Throw the most specific exception that is appropriate
4. Don't swallow errors by catching generic exceptions
5. Properly handle exceptions in asynchronous code
6. Always check an event handler delegate for null
7. Use a protected virtual method to raise each event
8. Consider providing property-changed events
9. Don't pass null as the sender argument when raising an event
10. Use generic constraints if applicable
11. Evaluate the result of a LINQ expression before returning it