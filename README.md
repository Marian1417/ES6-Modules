# ES6 Modules

## Lesson Objectives

1. What is npm?
2. What is npm init and package.json
3. Know how to install packages using npm
4. Explain what "transpiling code" is
5. Exporting values from a module
6. Importing values into a module
7. Exporting and importing multiple values
8. Exporting and importing a default value

### What is npm?

- node package manager
- is a command-line tool that gives us access to repository of plugins, libraries and tools.

### What is ES6 Modules?

- ES6 modules are a way to organize code into reusable, independent units, and to share code between different JavaScript files.
- They are the standard way to do modular programming in JavaScript
- ES6 Modules is similar to Object Constructors, Factory Functions, and Class Syntax

### Exporting Values from a Module

- To export a value from a module, you need to use the export keyword followed by the value you want to export.

### Importing Values into a Module

- To import a value from a module, you need to use the import keyword followed by the name of the module and the name of the value you want to import.

### Exporting and Importing Multiple Values

- You can also export and import multiple values at once using a comma-separated list.

### Exporting and Importing a Default Value

- Sometimes, you may want to export a single value as the default export from a module. To do this, you can use the export default syntax.

### Exercise 1

1. Create a new file called greeting.js in your project directory.
2. Create a new function called greet that accepts a name parameter and prints it to the screen
3. Export the greet function from the greeting.js and import it in the main.js
4. Inside the main.js file, use the greet function and pass in the argument "world"

### Exercise 2

1. Create a new file called math.js in your project directory.
2. Create two functions inside called add and subtract
   (x, y)
3. Import both add and subtract from math.js using the import statement
4. Create a new function called multiply in math.js
5. Import the multiply function from math.js
6. Call all three functions with appropriate arguments and log the results to the console
