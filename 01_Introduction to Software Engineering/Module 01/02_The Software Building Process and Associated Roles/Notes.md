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
