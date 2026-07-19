# 1. Branching and Looping Programming Logic

## Overview
- There are two major types of programming logic: **Branching** and **Looping**.
- Both types use **Boolean expressions** and **variables**.
- Branching decides **what action to take**, while looping decides **how many times to perform an action**.


## Boolean Expressions
- A Boolean expression is a programming statement with only two possible values:
  - **True**
  - **False**
- Computers use Boolean logic to make decisions.
- The action performed depends on whether the Boolean expression evaluates to **true** or **false**.


## Variables
- A variable stores a value that can change.
- Variables have assigned values that are passed into a function or subroutine.
- The value of a variable depends on conditions or information passed to the program.
- Variables and Boolean logic form the basis of programming.


## Branching Logic
- Branching allows a program to make decisions during execution.
- Different sets of instructions are executed depending on whether conditions are met.
- Each possible execution path creates a branch.
- There is no limit to the number of branches in a program.
- Parameter values may come from user input or previous program output.


## Common Branching Statements

### if
- A decision-making construct.
- Executes one code block if a specified condition is **true**.
- Executes another code block if the condition is **false**.

### if-then-else
- A conditional construct.
- Executes the statement after the **then** keyword only if the condition is **true**.
- Extends the **if** statement by specifying an action when the condition is **false**.
- Always executes either the true block or the false block.

### Switch
- A selection control statement.
- Changes the control flow based on the value of a variable or expression.

### GoTo
- Transfers control to another line of code.
- Performs a one-way transfer of control.


## Looping Logic
- A loop repeatedly executes a sequence of instructions until a specified condition is reached.
- Commonly used for tasks such as retrieving and modifying data.
- After each iteration, a condition is checked.
- If the condition is not met, the loop repeats.
- If the condition is met, execution continues with the next instruction.


## Types of Loops

### While Loop
- Evaluates the condition before executing the loop body.
- Executes only if the condition is **true**.

### For Loop
- Performs initialization only once.
- Tests the condition after each iteration.
- Stops when the condition becomes **false**.

### Do-while Loop
- Executes the loop body before checking the condition.
- Also known as an **exit-controlled loop**.


## Branching vs Looping

| Branching | Looping |
|-----------|---------|
| Makes decisions during program execution | Repeats a sequence of instructions |
| Executes different code paths based on conditions | Executes the same code multiple times |
| Uses Boolean expressions to select a branch | Uses conditions to control repetition |
| Decides what action to take | Decides how many times to perform an action |

---

# 2. Introduction to Programming Concepts – Part 1

## Overview
- Identifiers are used to reference program components.
- Identifiers that store data can be either **constants** or **variables**.
- Containers store multiple elements efficiently.
- The two common container types are **arrays** and **vectors**.


## Identifiers
- An identifier is a custom named label used to reference a program component.
- It can reference a stored value, method, interface, or class.
- Identifiers improve code readability and organization.
- Identifiers store mainly two types of data values
  - Constants
  - Variables


## Constants
- A constant is a data item whose value does not change during program execution.
- Also known as a **named constant**.
- A value is assigned when the constant is defined.
- Can store numerical values or text strings.

### Advantages of Constants
- Improves code readability.
- If the value changes, it only needs to be updated once.


## Variables
- A variable is an identifier whose value can change during program execution.
- Variables can store text, numbers, or other data types.
- Useful for storing unknown values such as user names, file names, or user input.
- Variables can be assigned a data type and an initial value when defined.
- Initial values can also be assigned later during program execution.


## Containers
- Containers are special identifiers that store multiple elements.
- They eliminate the need to create separate variables for each element.
- Make programs more efficient when handling large amounts of data.
- The two common container types are **arrays** and **vectors**.


### Arrays
- An array stores a fixed number of elements.
- All elements must be of the same data type.
- Elements are stored in sequential order.
- Indexing starts from **0**.
- The maximum size is specified when the array is declared.


### Vectors
- A vector has a dynamic size.
- Automatically resizes as elements are added or removed.
- Also known as a **dynamic array**.
- Uses more memory than an array.
- Elements take slightly longer to access than array elements.
- No maximum size is specified during declaration.


## Arrays vs Vectors

| Arrays | Vectors |
|--------|---------|
| Fixed size | Dynamic size |
| Size specified during declaration | Size changes automatically |
| Less memory usage | More memory usage |
| Faster element access | Slightly slower element access |
| Index starts at 0 | Index starts at 0 |

---

# 3. Introduction to Programming Concepts – Part 2

## Overview
- Functions are reusable blocks of code that perform specific tasks.
- Functions are a result of modular programming.
- Object-Oriented Programming (OOP) focuses on objects rather than functions.
- Software objects consist of properties and methods.


## Functions
- A function is a structured, stand-alone, and reusable block of code.
- Performs a single specific action.
- Helps divide large and complex programs into smaller, manageable components.
- May also be called **subroutines**, **procedures**, **methods**, or **modules** in some programming languages.
- Accepts data as input, processes it, and returns the result as output.


## Types of Functions

### Standard Library Functions
- Built-in functions provided by the programming language.
- Example: **Print** function.

### User-Defined Functions
- Created by programmers.
- Can be reused whenever needed.


## Using Functions

### Define a Function
- Create the function.
- Provide a function keyword.
- Give the function a unique name.
- Write the statements that form the function body.

### Call a Function
- Invoke the function.
- Executes the specified actions using any provided parameters.

### Declare a Function
- Required in some programming languages such as **C** and **C++**.


## Object-Oriented Programming (OOP)
- A programming methodology focused on **objects** rather than functions.
- Objects contain both data and code.
- Data is stored as **properties (attributes)**.
- Code is implemented as **methods (procedures)**.


## Objects
- Software objects are conceptually similar to real-world objects.
- Objects consist of **properties** and **methods**.
- Properties are stored in **fields** (called variables in some programming languages).
- Behaviors are exposed through **methods** (called functions in some programming languages).
- Examples include:
  - Windows service
  - User account
  - Database table
  - System folder


## Procedural Programming vs Object-Oriented Programming

| Procedural Programming | Object-Oriented Programming |
|------------------------|-----------------------------|
| Focuses on functions | Focuses on objects |
| Methods operate on separate data structures | Objects combine data and methods |
| Separates data and behavior | Packages data and behavior together |
