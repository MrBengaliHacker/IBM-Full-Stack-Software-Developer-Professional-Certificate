# 1. Introduction to Software Architecture

## Overview
- Software architecture is the organization of a software system.
- It serves as a blueprint for developing software components.
- Software architecture guides design decisions, technology stack selection, and production environments.
- The design phase produces artifacts that communicate the software architecture to stakeholders.


## Software Architecture
- Software architecture is the organization of a software system.
- It serves as a blueprint for software development.
- Defines the fundamental structures and behavior of a software system.
- Specifies how components interact with each other.
- Defines the operating environment and design principles.
- Captures early design decisions that are costly to change after implementation.


## Importance of Software Architecture
- Balances the needs of stakeholders.
- Serves as a basis for communication among team members.
- Guides later implementation decisions.
- Supports changing requirements during development.
- Increases the lifespan of the software system.
- Addresses non-functional requirements such as:
  - Performance
  - Scalability
  - Maintainability
  - Interoperability
  - Security
  - Manageability


## Technology Stack
- Software architecture guides the selection of technology stacks.
- A technology stack includes:
  - Software
  - Programming languages
  - Libraries
  - Frameworks
- Architects evaluate the advantages and disadvantages of a technology stack to meet development requirements.


## Software Architecture Artifacts

### Software Design Document (SDD)
- A collection of technical specifications for implementing the software design.
- Includes:
  - Functional description
  - Assumptions
  - Dependencies
  - Constraints
  - Requirements
  - Objectives
  - Methodologies

### Architectural Diagram
- Displays software components and their interactions.
- Shows architectural patterns, constraints, and component boundaries.

### UML Diagrams
- Visually communicate structures and behaviors.
- Not constrained by a programming language.


## Deployment considerations
- Software architecture drives production environment choices.
- The production environment consists of the infrastructure that delivers the application to end users.
- Common components include:
  - Servers
  - Load balancers
  - Databases

---

# 2. Software Design and Modeling

## Overview
- Software design documents the structural components and behavioral attributes of software before development.
- Software modeling creates visual representations of a software system and its interactions.
- UML is a standardized modeling language used to represent software architecture, structure, and behavior.
- UML diagrams can be classified as **structural** or **behavioral**.


## Software Design
- Documents the structural components and behavioral attributes of software.
- Takes place before software development.
- Uses models to represent the overall system, its sub-components, and their interactions.


## Structured Design
- Breaks a software problem into smaller modules and sub-modules.
- Organizes software into well-structured solution elements.
- Modules should be:
  - **Cohesive** – Functionally related elements are grouped together.
  - **Loosely Coupled** – Modules are weakly associated, so changes in one module have minimal effect on others.


## Behavioral Models
- Describe what a system does without explaining how it does it.
- Represent the overall behavior of a software system.
- Common behavioral UML diagrams include:
  - State Transition Diagram
  - Interaction Diagram


## Unified Modeling Language (UML)
- A standardized modeling language.
- Visually represents software architecture, design, and implementation.
- Programming language agnostic.
- Can be used throughout the software development process.
- UML diagrams are classified as:
  - Structural
  - Behavioral


## Advantages of UML
- Helps plan features before coding.
- Saves time and money.
- Helps new team members understand the system quickly.
- Improves communication between technical and non-technical stakeholders.
- Makes it easier to understand relationships among software components.


## State Transition Diagram
- A behavioral UML diagram.
- Represents the different states of a system.
- Shows the events that cause transitions between states.


## Interaction Diagram
- A behavioral UML diagram.
- Models the dynamic behavior of a software system.
- Visualizes objects and their relationships.
- A sequence diagram displays communication between objects over time.


## Structured Design vs Behavioral Models

| Structured Design | Behavioral Models |
|-------------------|-------------------|
| Focuses on software structure | Focuses on system behavior |
| Organizes software into modules and sub-modules | Describes what the system does |
| Emphasizes cohesion and loose coupling | Does not explain how behavior is implemented |

---

# 3. Object-Oriented Analysis and Design (OOAD)

## Overview
- Object-Oriented Analysis and Design (OOAD) is an approach for analyzing and designing software systems using object-oriented programming.
- Objects contain data and behaviors.
- Classes serve as blueprints for creating objects.
- Class diagrams are structural UML diagrams that show relationships between classes.


## Object-Oriented Analysis and Design (OOAD)
- An approach for analyzing and designing software systems.
- Used when developing software with object-oriented programming languages.
- Plans a software system based on the behaviors of interacting objects.
- Enables multiple developers to work on different parts of the application simultaneously.


## Objects
- Objects contain data and behaviors.
- Behaviors define the actions an object can perform.
- A specific object is called an **instance**.
- Creating an object from a class is called **instantiation**.


## Classes
- A class is a blueprint or template for creating objects.
- Defines the generic properties and methods of an object.
- Property values are assigned when an object is instantiated.


## Class Diagram
- A structural UML diagram.
- Represents the structure of an object-oriented software system.
- Shows classes and their attributes.
- Displays relationships between classes.
- Shows properties (data) and methods (actions) of each class.


## Inheritance
- A subclass inherits the properties and methods of its parent class.
- A subclass can also add additional properties and methods.
