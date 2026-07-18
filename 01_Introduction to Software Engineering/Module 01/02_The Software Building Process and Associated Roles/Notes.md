# 1. Software Development Methodologies

## Overview
- A **software development methodology** defines how software is planned, developed, tested, and delivered.
- It improves **communication**, **collaboration**, and **information sharing** among development teams.
- Three common methodologies:
  1. **Waterfall**
  2. **V-Shape Model**
  3. **Agile**


## 1. Waterfall Model

Waterfall was the original methodology used when the **Software Development Life Cycle (SDLC)** was first conceived.
 
### Characteristics
- A **sequential** method of software development.
- The output of one phase becomes the input for the next phase.
- Work on the next phase begins only after the previous phase is complete.
- All planning, including requirements definition and architectural design, is completed up front.
- The customer typically does not see the product until it reaches the testing phase.
- For major version releases, the entire process is repeated, resulting in long intervals (often years) between releases.

### Pros
- Team members understand their responsibilities due to discrete, well-defined stages.
- Easier to estimate budget and allocate resources.

### Cons
- Lacks flexibility.
- Change is hard to accommodate.


## 2. V-Shape Model

### Overview
- A **sequential** methodology based on the **Waterfall Model**.
- Forms a **V-shape** with:
  - **Verification** (left side)
  - **Validation** (right side)

### Verification Phases
1. Planning
2. System Design
3. Architecture Design
4. Module Design

### Coding
- Coding occurs at the **bottom of the V**.

### Validation Phases
1. Unit Testing
2. Integration Testing
3. System Testing
4. Acceptance Testing

### Pros
- Easy to use.
- Test plans are designed upfront, saving development and testing time.

### Cons
- More rigid than Waterfall.
- Does not accommodate changing requirements.


## 3. Agile
### Overview
- An **iterative** and **collaborative** development approach.
- Development occurs in short cycles called **Sprints** (usually **1–4 weeks**).
- Each sprint includes planning, development, testing, and feedback.
- Ends with a **Sprint Demo** where stakeholders review the working software.
- Multiple sprints produce a **Minimum Viable Product (MVP)**.

### Agile Manifesto – Four Core Values
- **Individuals and interactions** over processes and tools.
- **Working software** over comprehensive documentation.
- **Customer collaboration** over contract negotiation.
- **Responding to change** over following a plan.

### Pros
- Changing requirements are handled easily.
- Customer feedback is incorporated regularly.

### Cons
- Budgeting and resource allocation are challenging.
- Project scope may not be clearly defined initially.


## Waterfall vs V-Shape vs Agile

| Feature | Waterfall | V-Shape | Agile |
|---------|-----------|---------|--------|
| Development Style | Sequential | Sequential | Iterative |
| Flexibility | Low | Very Low | High |
| Customer Feedback | Late | Late | Continuous |
| Testing | After Development | Planned Early | Every Sprint |
| Requirement Changes | Difficult | Very Difficult | Easy |
| Release Cycle | Long | Long | Frequent |


---


# 2. Software Versions

## Overview
- **Software versioning** is used to track software releases, updates, and patches.
- Version numbers help users identify the software version they are using.
- They also help developers communicate changes made to the software.


## Version Numbers
- Version numbers indicate:
  - Software releases
  - Updates
  - Bug fixes (patches)
- Versions may contain **2, 3, or 4** number sets separated by periods (`.`).
- The first official release is often **1.0**.
- Beta versions may have version numbers **below 1** (e.g., **0.9**).
- Some software uses **dates** for versioning (e.g., **Ubuntu 18.04.2**).


## Semantic Versioning

A semantic version number may contain **four parts**:

| Version Part | Meaning |
|--------------|---------|
| **1st** | Major release or major changes |
| **2nd** | Minor changes or new features |
| **3rd** | Patches or bug fixes |
| **4th** | Build number or build date |


## Software Compatibility
- Compatibility issues between old and new software versions are common.
- Updating software may resolve compatibility problems.
- Some software is **backward compatible**, allowing older files, programs, or systems to work with newer versions.

---

# 3. Software Testing

## Overview
- **Software Testing** is the practice of integrating quality checks throughout the **Software Development Life Cycle (SDLC)**.
- Ensures the software:
  - Meets requirements.
  - Is free of errors.
- Testing is performed using **test cases**.

---

## Test Cases

A **test case** contains:
- Steps
- Inputs
- Data
- Expected outputs

- Test cases are written after **requirements are finalized**.
- They can be created during different SDLC phases.

---

## Types of Software Testing

### 1. Functional Testing
- Verifies that software meets **functional requirements**.
- Usually uses **Black-Box Testing** (tests inputs and outputs without viewing source code).
- Can be **manual** or **automated**.
- Ensures the application is:
  - Usable
  - Accessible
  - Handles invalid inputs with appropriate error messages


### 2. Non-Functional Testing

Tests software quality attributes such as:
- Performance
- Security
- Scalability
- Availability

Answers questions like:
- How does the application perform under stress?
- How does it handle multiple users?
- Is it secure?
- Does it behave consistently across operating systems?
- Does it support disaster recovery?


### 3. Regression Testing
- Also called **Maintenance Testing**.
- Ensures recent changes (e.g., bug fixes or new features) do **not break existing functionality**.
- Performed after:
  - Requirement changes
  - Bug fixes

### Regression Test Case Selection

Commonly selected test cases include:
- Frequently failing features
- Frequently used functionality
- Recently modified features
- Complex test cases
- Edge cases
- Randomly successful or failed test cases

---

## Testing Levels

### 1. Unit Testing
- Tests individual functions or small code units.
- Performed by developers during the **Development** phase.
- Detects errors before integration.

### 2. Integration Testing
- Tests interactions between integrated modules.
- Identifies communication issues between:
  - Modules
  - Databases
  - External hardware
- Usually performed after **Unit Testing**.

### 3. System Testing
- Tests the complete integrated system.
- Verifies compliance with specified requirements.
- Includes both **Functional** and **Non-Functional** testing.
- Performed in a **staging environment**.

### 4. Acceptance Testing
- Final testing performed by customers or stakeholders.
- Verifies user requirements and business processes.
- Determines whether the software is ready for release.

---

### Testing Types

| Type | Purpose |
|------|---------|
| Functional | Verifies functional requirements. |
| Non-Functional | Tests performance, security, scalability, and availability. |
| Regression | Ensures new changes don't break existing functionality. |

### Testing Levels

| Level | Purpose |
|-------|---------|
| Unit | Tests individual functions or code units. |
| Integration | Tests interactions between modules. |
| System | Tests the complete integrated system. |
| Acceptance | Validates user requirements and business processes. |

---

# 4. Software Documentation

## Overview
- **Software Documentation** is information that describes what a software product is and how to use it.
- Documentation supports all phases of the **Software Development Life Cycle (SDLC)**.
- It can be created for different audiences, including:
  - End users
  - Software developers
  - QA engineers
  - System administrators
  - Other stakeholders

---

## Documentation Formats

Software documentation can be in three formats:
- **Written**
- **Video**
- **Graphical**


## Documentation Categories

### 1. Product Documentation
- Describes the **functionality** of the software product.
- Explains what the software does and how it works.

### 2. Process Documentation
- Describes **how to complete a task**.
- Provides guidance for implementing business processes.
- Often accompanied by **Standard Operating Procedures (SOPs)**.


## Types of Product Documentation

### 1. Requirements Documentation
- Created during the **Planning** phase.
- Describes expected software features and functionality.
- Includes:
  - Software Requirements Specification (SRS)
  - System Requirements Specification (SysRS)
  - User Acceptance Specification

### 2. Design Documentation
- Created by software architects and developers.
- Explains how the software will be built.
- Includes:
  - Conceptual design documents
  - Technical design documents

### 3. Technical Documentation
- Helps developers understand the code.
- Includes:
  - Code comments
  - Working papers
  - Engineering notes and ideas

### 4. Quality Assurance (QA) Documentation
- Describes the testing strategy, progress, and metrics.
- Includes:
  - Test plans
  - Test data
  - Test scenarios
  - Test cases
  - Test strategies
  - Traceability matrices

### 5. User Documentation
- Intended for end users.
- Explains how to install, use, and troubleshoot the software.
- Includes:
  - FAQs
  - Installation guides
  - Help guides
  - Tutorials
  - User manuals


## Standard Operating Procedures (SOPs)

- **SOPs** are detailed, organization-specific instructions for completing common tasks.
- More detailed than general process documentation.
- Can be presented as:
  - Flowcharts
  - Hierarchical outlines
  - Step-by-step instructions


## Documentation Maintenance
- Documentation should always be **kept up to date**.
- Updated during the **Maintenance** phase of the SDLC.
- Should be reviewed periodically to ensure accuracy.


## Product Documentation vs Process Documentation

| Product Documentation | Process Documentation |
|------------------------|-----------------------|
| Describes product functionality. | Describes how to complete a task. |
| Focuses on the software product. | Focuses on business processes and procedures. |
| Intended for users and development teams. | Intended for people performing organizational tasks. |

---

# 5. Roles in Software Engineering Projects

## Overview
- Software engineering projects involve **multiple roles**, each with specific responsibilities.
- Role names may vary depending on the development methodology (e.g., **Agile** or **Waterfall**) or the organization.
- Not every project includes all roles.

---

## Common Roles

### 1. Project Manager / Scrum Master

#### Project Manager (Traditional SDLC)
Responsibilities:
- Planning, scheduling, and budgeting
- Allocating personnel and resources
- Executing the software plan
- Facilitating team communication

#### Scrum Master (Agile)
Responsibilities:
- Ensures team and individual success
- Facilitates communication
- Removes obstacles affecting the team
- Supports Agile principles and practices

---

### 2. Stakeholder
Stakeholders are the people for whom the software is being developed.

Examples:
- Customers
- End users
- Decision-makers
- System administrators
- Other key personnel

Responsibilities:
- Define project requirements
- Provide feedback and clarification
- Participate in Beta Testing and Acceptance Testing

---

### 3. System / Software Architect

Also called:
- Software Architect
- Solution Architect

Responsibilities:
- Design the software architecture
- Define the technical structure of the system
- Communicate the architecture to the development team
- Provide technical guidance throughout the SDLC

---

### 4. UX (User Experience) Designer

Responsibilities:
- Design the software from the user's perspective
- Make the application intuitive and easy to use
- Define user interactions and interface behavior
- Balance usability with business requirements

---

### 5. Software Developer

Responsibilities:
- Write application code
- Implement the software architecture
- Follow the Software Requirements Specification (SRS)
- Implement UX design requirements

---

### 6. Tester / QA Engineer

Responsibilities:
- Ensure software quality
- Write and execute test cases
- Identify bugs and defects
- Report issues to the development team
- Verify software meets customer requirements

---

### 7. Site Reliability Engineer (SRE) / Ops Engineer

Responsibilities:
- Bridge development and operations
- Automate systems and processes
- Monitor incidents
- Assist with troubleshooting
- Ensure system reliability and availability

---

### 8. Product Manager / Product Owner

Responsibilities:
- Define the product vision
- Understand customer and user needs
- Lead product development
- Ensure the product delivers stakeholder value

---

### 9. Technical Writer / Information Developer

Responsibilities:
- Create documentation for end users
- Explain technical concepts to non-technical audiences
- Write:
  - User manuals
  - Reports
  - White papers
  - Press releases

---

## Role Comparison

| Role | Primary Responsibility |
|------|-------------------------|
| Project Manager | Planning, scheduling, budgeting, communication |
| Scrum Master | Team success and Agile facilitation |
| Stakeholder | Define requirements and provide feedback |
| Software Architect | Design system architecture |
| UX Designer | Improve user experience and interface |
| Software Developer | Build the software |
| Tester / QA Engineer | Test software quality |
| SRE / Ops Engineer | Ensure reliability and operations |
| Product Manager | Define product vision and value |
| Technical Writer | Create user documentation |

---


