# Overview of Software Engineering

## Learning Objectives

- Define **Software Engineering**
- Understand **Software Development Life Cycle (SDLC)**
- Learn Software Engineer responsibilities
- Understand software quality

---

# 1. What Is Software Engineering?

## Definition
- Software Engineering is the application of **scientific principles** to the design and creation of software.
- It follows a **systematic approach** to collect and analyze **business requirements**, then **​design, build, and test** software applications to satisfy them.

## History
- In the late **1950s**, ​software engineering was not a well-defined field.
- It became a recognized discipline in the **1960s**.
- Over time, it evolved with new technologies and more scientific development methods.

## Evolution
- Early software development relied on **ad hoc (unplanned)** programming.
- Over time, it shifted to **formal, structured, and standardized** development methods.

## Software Crisis
- Initially, the creation of software lacked a **formal development process**.
- As computer adoption grew worldwide, software became integral to more aspects of life.
- Inefficient development processes couldn't keep up with rising demand for **computing resources** and **complex software**.
- This led to what is known as the **Software Crisis**, which began in the **mid-1960s** and lasted until the **mid-1980s**.

### Common problems during this period:
- Projects ran **over budget** and **behind schedule**.
- Code was **unmanageable** and **buggy**.
- Older software became outdated due to rapid technological advancements, newer/faster tech had already emerged, forcing **refactoring** or **complete redesign**.
- Software solutions that worked for small systems didn't scale to large, complex projects.

## Current Status
Some issues still exist today, but to a much lesser extent.

### Reasons for improvement:
- Consistent application of **engineering principles** to software development.
- Wider availability of **computing resources**.
- Standardized methodologies enabling large, complex, scalable solutions.

## Resolution
- The **Software Crisis** was addressed by transforming unorganized coding efforts into an established engineering discipline.
- **Mid-1980s** saw the rise of **CASE (Computer-Aided Software Engineering)** tools, which also helped relieve the crisis.

### CASE Tools — Six Categories
1. **Business analysis and modeling**
2. **Development tools (e.g., debugging environments)**
3. **Verification and validation tools**
4. **Configuration management**
5. **Metrics and measurement**
6. **Project management**

## Software Engineer vs. Software Developer
Terms often used interchangeably, but subtle differences exist.
**Software engineers are developers**, but "software developer" is narrower in scope.

### Software engineers:

- They are also **software developers**
- Broader knowledge. 
- Take a systematic, big-picture approach.
- Use specialized knowledge to build entire systems.
- Usually work on larger-scale projects, focused on broad structure rather than an immediate problem.


### Software developers:

- **Narrower scope** than **Software engineers**.
- May take a **more creative approach**.
- Write code to implement **specific functionality** and solve **specific problems**

## Responsibilities of a Software Engineer
- Designing, building, and maintaining software systems.
- Writing and testing code.
- Consult with:
  - Clients and stakeholders
  - Third-party software vendors
  - Security specialists
  - Other team members

## Software Development Life Cycle (SDLC)
- Modern development is typically guided by the **Software Development Life Cycle (SDLC)**.
- Identifies the steps needed to develop high-quality software.

---

# 2. Introduction to the Software Development Life Cycle (SDLC)

- The **Software Development Life Cycle (SDLC)** is a systematic process for developing high-quality software within a **predictable timeframe and budget**.
- The goal of the SDLC is to develop software that meets **business and client requirements**.
- It defines phases of software development, each with its own processes and deliverables.
- It follows a cycle of **planning, design, and development** and can be implemented as an **iterative** approach.
- Adherence to SDLC minimizes risks and costs, producing high-quality, deployable software.

## History
- The SDLC began to take shape in the **mid-1960s**.
- It was introduced to manage the increasing complexity of software systems.
- Initially, it followed the **Waterfall Model**, a linear development approach.
- Later, it evolved to support **iterative models** for changing customer requirements.

## Advantages of the SDLC
1. Improves efficiency and reduces project risks.
2. Provides well-defined phases, so team members know what to work on and when.
3. Improves communication between developers, customers and stakeholders.
4. Clearly defines team roles and responsibilities.
5. Supports iterative development by allowing new or changing requirements to be incorporated.
6. Encourages early problem-solving by addressing issues during the design phase instead of coding.
7. Reduces conflicts and overlapping responsibilities among team members.

---

# 3. Phases of the Software Development Life Cycle (SDLC)

## Overview
- The **Software Development Life Cycle (SDLC)** consists of **six phases**:
  1. Planning
  2. Design
  3. Development
  4. Testing
  5. Deployment
  6. Maintenance
- Each phase is **discrete**, meaning that tasks from a previous phase do not overlap with ​tasks in the next phase.
- The original SDLC followed the **Waterfall Model (Linear Approach)**, but modern SDLCs often use **iterative approaches**.
- Some organizations may use different names or additional phases (e.g., **Planning** may be called **Requirements**, **Strategy** or **Analysis**).


## 1. Planning Phase
- Requirements are **gathered, analyzed, documented, and prioritized**.
- Factors to consider:
  - Users of the solution
  - Overall purpose of the solution
  - Data inputs and outputs
  - Legal and regulatory compliance
  - Risk identification
  - Quality assurance requirements
  - Allocation of human and financial resources
  - Project schedule
- Labor and material costs are estimated and weighed against time constraints.
- Define **project team** and responsibilities.
- **Prototyping** may occur here to tease out unclear requirements (small-scale replica used for stakeholder feedback and testing basic design ideas). Can also occur in later phases if needed.
- Requirements are compiled into a **Software Requirements Specification (SRS)** document.
- The **SRS** must be understood and approved by all stakeholders, including developers.


## 2. Design Phase
- Use the **SRS** to design the software architecture.
- Team members collaborate to design the software architecture.
- Create **prototypes** for stakeholder feedback.
- Review the architecture with stakeholders.
- Produce the **Design Document** for developers.

---

## 3. Development Phase
- Also called the **Implementation** or **Building** phase.
- Developers write code based on the **Design Document**.
- Coding tasks are assigned by project planners.
- Use programming languages, tools, frameworks, and software stacks.
- Follow organizational coding standards and guidelines.


## 4. Testing Phase
- Verify that the software is **stable**, **secure**, and meets **SRS requirements**.
- Testing can be:
  - Manual
  - Automated
  - Hybrid
- Bugs are reported, tracked, fixed, and the software is retested.

### Common Testing Levels
- **Unit Testing**
- **Integration Testing**
- **System Testing**
- **Acceptance Testing**


## 5. Deployment Phase
- Release the software to the **production environment**.
- May first be deployed to **User Acceptance Testing (UAT)**.
- After customer approval, release to production.
- Software can be deployed to websites, mobile app stores, or corporate servers.


## 6. Maintenance Phase
- Monitor the software after deployment.
- Fix newly discovered bugs.
- Improve the **User Interface (UI)**.
- Identify additional requirements and enhancements.
- Feedback and enhancements may initiate a **new SDLC cycle**.

---

# 4. Building Quality Software

## Overview
- Building **high-quality software** involves six common software engineering processes:
  1. Requirements Gathering
  2. Design
  3. Coding for Quality
  4. Testing
  5. Releases
  6. Documentation
- Together, these processes help build **reliable, maintainable, secure, and high-quality software**.


## 1. Requirements Gathering
- Collect and document software requirements in a **Software Requirements Specification (SRS)**.
- May include **use cases** describing business needs and user flows.

### Types of Requirements
Requirements fall into **four categories**:
- **Functional**
- **External & User Interface (UI)**
- **System Features**
- **Non-functional**


## 2. Design
- Transforms requirements into a software design that developers can implement.
- Defines the **system architecture**.
- The technical lead breaks requirements into related components with clearly defined:
  - Behaviors
  - Boundaries
  - Interactions
- Covers:
  - Business rules
  - Application logic
  - API design
  - User Interface (UI)
  - Database design
  - Performance
  - Security


## 3. Coding for Quality

### Code Quality
Quality code should be:
- **Maintainable**
- **Readable**
- **Testable**
- **Secure**
- **Efficient**
- **Well documented**
- **Clean and consistent**
- **Meets software requirements without defects**

### Best Practices
- Follow coding standards, conventions, patterns, and styles.
- Use **Linters** to detect coding and stylistic errors.
- Write meaningful comments for easier maintenance.


## 4. Testing
- Verifies that software meets established requirements and is **free of bugs**.
- Identifies errors, gaps, and missing requirements.
- Ensures:
  - Reliability
  - Security
  - Performance
  - Efficiency

### Testing Methods
- Manual
- Automated

### Testing Levels
1. **Unit Testing**
2. **Integration Testing**
3. **System Testing**
4. **User Acceptance Testing (UAT/Beta Testing)**

### Testing Types
- Functional
- Non-functional
- Regression


## 5. Releases

### Alpha Release (α)
- First working version.
- Released to a **select group of stakeholders**.
- May contain bugs and incomplete features.

### Beta Release (β)
- Released to users outside the development team.
- Tests software under **real-world conditions**.
- Should meet all functional requirements.

### General Availability (GA)
- Final stable release.
- Available to **all users**.


## 6. Documentation

Documentation is divided into **two types**:
### 1. System Documentation (Technical)
For developers, engineers, and architects.

Includes:
- README files
- Inline comments
- Architecture & design documents
- Verification information
- Maintenance guides

### 2. User Documentation (Non-Technical)
For end users.

Includes:
- User guides
- Manuals
- Instructional videos
- Online help
- Inline help

---

# 5. Requirements

## Overview
- **Requirement Gathering** is a **six-step process** for defining a problem and documenting how to solve it.
- It ensures the software meets **business** and **user requirements**.

---

## Requirement Gathering Process

### 1. Identifying Stakeholders
- Identify everyone affected by the software, including:
  - Decision-makers
  - End-users
  - System administrators
  - Engineers
  - Marketing
  - Sales
  - Customer support

### 2. Establish Goals and Objectives
- **Goals:** Broad, long-term achievable outcomes.
- **Objectives:** Specific, actionable and measurable actions that achieve the goals.

### 3. Elicit Requirements
Requirements are gathered using:
- Surveys
- Questionnaires
- Interviews

### 4. Document Requirements
- Ensure they align with the project goals and objectives.
- Must be easily understood by stakeholders and the project team.

### 5. Analyze & Confirm Requirements
- Requirements are analyzed for:
  - **Consistency**
  - **Clarity**
  - **Completeness**

- Review and obtain stakeholder approval.

### 6. Prioritize Requirements
Common priority levels:
- **Must-have**
- **Highly Desired**
- **Nice to Have**


> **Note:** Requirement elicitation, documentation, and confirmation are usually performed **iteratively**.
---

## Requirement Documents

### 1. Software Requirements Specification (SRS)
The **SRS** defines what the software must do and its expected performance.

### Includes
- Purpose
- Scope
- Constraints
- Assumptions
- Dependencies
- Requirements


### Purpose statement
- Intended use of the SRS
- Audience
- Scope (software benefits, goals, and objectives)

### Constraints, Assumptions, and Dependencies
- **Constraints** — operating conditions that limit design options (e.g., standards compliance, hardware limitations).
- **Assumptions** — e.g., required OS or hardware needed to function.
- **Dependencies** — reliance on other software products.

### Requirement (4 categories):
- **Functional Requirements** — core functionalities of the software.
- **External Interface Requirements** — behavior in relation to external entities (users, other hardware/software).
- **System Features** — subset of functional requirements; features required for the system to function.
- **Non-functional Requirements** — performance, safety, security, quality standards.


### 2. User Requirements Specification (URS)

The **URS** describes the business needs and expectations of end users.

- Requirements are written as **User Stories** or **Use Cases** answering:

  - **Who** is the user?
  - **What** functionality is needed?
  - **Why** is it needed?

- Verified during **User Acceptance Testing (UAT)**.
- Often **combined with the SRS** into a single document.


### 3. System Requirements Specification (SysRS)

- Outlines requirements of the **entire system — broader in scope** than the SRS.
- Often used interchangeably with SRS, but technically distinct.
- Most software projects develop an **SRS**, not a SysRS.

### Includes
- System capabilities
- Interfaces and User characteristics
- Policy requirements
- Regulatory requirements
- Personnel requirements
- Performance requirements
- Security requirements
- System acceptance criteria
- Hardware expectations

## SRS vs URS vs SysRS

| Document | Purpose |
|----------|---------|
| **SRS** | Defines software requirements and functionality. |
| **URS** | Defines user needs using user stories or use cases. |
| **SysRS** | Defines requirements for the complete system (hardware + software). |

---

# Summary
 
In this section, you learned:
 
- **Software Engineering** is a systematic approach to designing, developing, testing, and maintaining software; it became a recognized discipline in the **1960s**, shifting from **ad hoc** to **formal, standardized** methods.
- The **Software Crisis** (mid-1960s–mid-1980s) led to the adoption of structured engineering practices and the rise of **CASE tools**.
- A **Software Engineer** focuses on building complete systems, while a **Software Developer** focuses on implementing specific functionalities.
- The **Software Development Life Cycle (SDLC)** provides a structured process for developing high-quality software, originally following the **Waterfall Model** and now often **iterative**. Its advantages include improved efficiency, communication, and clearly defined roles.
- The SDLC consists of **Planning, Design, Development, Testing, Deployment, and Maintenance**.
- High-quality software is built through **Requirements Gathering, Design, Coding for Quality, Testing, Releases (Alpha, Beta, GA), and Documentation**.
- **Requirement Gathering** is a six-step process that produces documents such as **SRS, URS, and SysRS**.
### Key Terms
- Software Engineering
- SDLC
- Software Crisis
- Waterfall Model
- CASE Tools
- SRS
- URS
- SysRS
- Prototype
- UAT
- Alpha Release
- Beta Release
- General Availability (GA)
---