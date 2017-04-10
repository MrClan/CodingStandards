# Member Design Guidelines
1. Allow properties to be set in any order
2. Use a method instead of a property
3. Don't use mutually exclusive properties
4. A method or property should do only one thing
5. Don't expose stateful objects through static members
6. Return an IEnumerable<T> or ICollection<T> instead of a concrete collection class
7. Properties, methods and arguments representing strings or collections should never be null
8. Define parameters as specific as possible
9. Consider using domain-specific value types rather than primitives