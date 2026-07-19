# 1. Interpreted and Compiled Programming Languages

## Overview
- Programming languages help humans communicate instructions to computers.
- Computers understand **machine code (binary: 0s and 1s)**, so programming languages are translated into machine code.
- Programming languages are broadly categorized into **Interpreted** and **Compiled** languages.
- The choice of programming language depends on the requirements of the project.


## Programming Languages
- Allow developers to write code in a human-readable format.
- The source code is translated into machine code before execution.


## Interpreted Programming Languages
- Also known as **scripting languages**.
- Source code is translated by an **interpreter** during execution.
- Requires an interpreter built into a browser or installed on the operating system.
- Generally easier to learn and more versatile.
- Can run on multiple platforms if the required interpreter is available.

### Examples
- JavaScript
- Python
- Lua


## Compiled Programming Languages
- Source code is translated into **machine code** by a **compiler**.
- The compiled code is packaged into an **executable file**.
- Programs generally execute faster because compilation happens before execution.
- Commonly used for larger and more complex applications.

### Compilation Process
1. Write source code.
2. Compile the source code into machine code.
3. Generate an executable file.
4. Run the executable program.

### Examples
- C
- C++
- C#
- Java


## Applications of Compiled Languages
Compiled languages are commonly used for:
- Operating Systems
- Desktop Applications
- Large Software Programs

Examples:
- Microsoft Windows
- macOS
- Linux
- Android


## Interpreted vs Compiled Languages

| Interpreted Languages | Compiled Languages |
|------------------------|--------------------|
| Uses an interpreter | Uses a compiler |
| Translated during execution | Compiled before execution |
| Requires an interpreter to run | Produces an executable file |
| More versatile and cross-platform | Faster execution |
| Best for scripting and automation | Best for large and complex applications |

---

# 2. Query and Assembly Programming Languages

## Overview
- Programming languages are broadly classified into **high-level** and **low-level** languages.
- **Query languages** are high-level languages used to communicate with databases.
- **Assembly languages** are low-level languages that use symbols to represent machine code.
- The choice of programming language depends on the requirements of the project.


## High-level Programming Languages
- Easier for humans to read and write.
- Use English-like syntax.
- Simplify coding, debugging, and maintenance.

### Examples
- SQL (Query Language)
- Pascal (Structured Programming Language)
- Python (Object-Oriented Programming Language)


## Low-level Programming Languages
- Closer to machine code.
- Use symbols and mnemonics to represent binary instructions.
- Closely tied to processor architecture.

### Examples
- ARM
- MIPS
- x86


## Query Languages
- Used to communicate with databases.
- Also called **Database Query Languages**.
- Predominantly used to:
  - Request data from a database.
  - Perform CRUD operations (Create, Read, Update, Delete).
- Database queries are written using predefined statements.

### Common Query Languages
- SQL
- AQL
- CQL
- Datalog
- DMX


## SQL vs NoSQL Databases

| SQL | NoSQL |
|-----|--------|
| Relational database | Non-relational database |
| Structured, predefined schema | Dynamic schema |
| Structured data | Unstructured data |


## CRUD Operations
CRUD represents the four basic database operations:
- **C** – Create (Add new data)
- **R** – Read (Retrieve data )
- **U** – Update (Modify existing data)
- **D** – Delete (Remove data)


## Types of SQL Statements

### Select Statements
- Retrieve data from a database.

### Action Statements
- Create
- Insert
- Update
- Delete

### Administrative Statements
- Create users.
- Modify permissions.

## Common Query Statements

| SQL Statement | Task |
|---------------|------|
| **SELECT** | Extract data from a database. All request queries start with a **SELECT** statement. |
| **WHERE** | Filter the query criteria to return results that match a specified condition (used with **SELECT**). |
| **ORDER BY** | Define the sort order of returned results. |
| **UPDATE** | Modify existing data in a database. |
| **INSERT INTO** | Add new data records to a database. |
| **ALTER TABLE** | Add or remove columns in a database. |
| **CREATE** | Create a new object in a database. Object options include **DATABASE**, **TABLE**, **INDEX**, and **VIEW**. |
| **DROP** | Delete an object from a database. Object options are the same as **CREATE**. |
| **SUM** | Return the total sum of a column of numeric data. |
| **COUNT** | Return the number of rows that match a condition. |
| **AVG** | Return the average value of a column of numeric data. |

### Query Statement Examples

```sql
SELECT * FROM suppliers;

SELECT name
FROM suppliers
WHERE name = 'Mike';

CREATE DATABASE products;

DROP TABLE suppliers;

ALTER TABLE suppliers;

DROP COLUMN firstname;

SELECT AVG(purchases)
FROM suppliers;
```

## Assembly Languages
- Low-level programming languages.
- Use **mnemonics** and **operands** to represent machine instructions.
- Each processor architecture typically has its own assembly language.
- Closely tied to processor architecture.
- Translated using an **assembler**, not a compiler or interpreter.
- One assembly instruction corresponds to one machine instruction.

### Common Mnemonics
- INPUT (INP)
- OUTPUT (OUT)
- LOAD (LDA)
- STORE (STA)
- ADD

### Assembly Language Syntax

- Simple readable format.
- Entered one line at a time.
- One statement per line.

#### Statement Format

```text
{label} mnemonic {operand list} {;comment}
```

#### Example

```assembly
mov TOTAL, 212
```
- **Mnemonic** specifies the instruction.
- **Operands** specify where the data is located.

## Query Languages vs Assembly Languages

| Query Languages | Assembly Languages |
|-----------------|--------------------|
| High-level language | Low-level language |
| Used with databases | Used with processors |
| Human-readable syntax | Mnemonics and operands |
| Translated by database systems | Translated by an assembler |
| One statement may translate into multiple machine instructions | One statement maps to one machine instruction |

---

# 3. Understanding Code Organization Methods

## Overview
- Code organization improves **readability, maintainability, and reliability**.
- Planning software before coding reduces bugs and errors.
- Two main code organization methods are **Flowcharts** and **Pseudocode**.
- Both methods help developers organize and plan software before implementation.


## Importance of Code Organization
- Produces cleaner and more reliable code.
- Improves software quality.
- Reduces bugs and errors.
- Provides a consistent and logical coding structure.
- Makes code easier to read, maintain, and modify.


## Algorithm
- An **algorithm** is a step-by-step sequence for solving a problem.


## Code Organization Methods

### Flowchart
- A graphical representation of an algorithm.
- Uses symbols, shapes, and arrows to show the execution flow.
- Commonly used for designing and documenting processes.
- Best suited for **smaller concepts and problems**.
- Easier to create during the initial planning stage.

### Pseudocode
- An informal, high-level description of an algorithm.
- Does not require programming language syntax.
- Language-independent.
- Acts as a bridge between the algorithm and actual code.
- Best suited for **larger programming projects**.
- Focuses on logic rather than programming syntax.


## Flowchart Symbols

| Symbol | Purpose |
|--------|---------|
| Start/End (Capsule) | Beginning or end of a process |
| Process (Rectangle) | Perform an operation |
| Decision (Diamond) | Make a True/False or Yes/No decision |
| Data (Parallelogram) | Input or Output |
| Connector (Arrow) | Show the flow of execution |


## Flowchart Software
- Microsoft Visio
- Lucidchart
- Draw.io
- DrawAnywhere


## Advantages of Flowcharts
- Easy to understand.
- Visual representation of program logic.
- Helps analyze problem-solving methods.
- Improves communication among team members.
- Good starting point for software design.


## Advantages of Pseudocode
- Focuses on program logic instead of syntax.
- Easier to write and modify.
- Language-independent.
- Easy for programmers and non-programmers to understand.
- Simplifies translation into any programming language.
- Helps different development teams collaborate.
- Easier to review than actual code.
- Usually shorter than one page.


## Flowchart vs Pseudocode

| Flowchart | Pseudocode |
|-----------|------------|
| Graphical representation of an algorithm | Textual description of an algorithm |
| Uses symbols and arrows | Uses plain English-like statements |
| Best for smaller problems | Best for larger projects |
| Easy to visualize program flow | Easy to translate into code |
| Good starting point during early planning | Easier to modify and review |

---
