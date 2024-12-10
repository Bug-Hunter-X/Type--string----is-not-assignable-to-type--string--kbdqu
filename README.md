# Type 'string[]' is not assignable to type 'string'
This TypeScript code demonstrates a common type error where an array of strings is passed to a function expecting a single string.
The `greeter` function is defined to accept a single string argument, but the `user` variable is an array of strings.  This results in a type error because the function cannot process the array as a string.
The solution involves either modifying the function to accept an array or modifying the user variable to be a single string.