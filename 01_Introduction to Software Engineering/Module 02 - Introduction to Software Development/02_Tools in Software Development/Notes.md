# 1. Introducing Application Development Tools

## Overview
- Application development involves several tools that help developers build, manage, and deploy software efficiently.
- Common development tools include **Version Control Systems**, **Libraries**, and **Frameworks**.


## Version Control
- Tracks changes made to source code.
- Records:
  - What changes were made
  - When they were made
  - Who made them
- Helps resolve conflicts between multiple developers.
- Allows developers to restore previous versions if needed.
- Commonly used with code repositories.

### Git and GitHub
- **Git** is a version control system.
- **GitHub** is a platform for storing and managing Git repositories.
- Features:
  - Track code changes
  - Create branches for development
  - Merge branches into the main project


## Libraries
- A **library** is a collection of reusable code.
- Used to add specific functionality without writing code from scratch.
- Developers choose **when** to call library functions.
- Multiple libraries can be added to the same project.

### Examples
- **jQuery** – Simplifies DOM manipulation.
- **EmailValidator** – Validates email addresses.
- **Apache Commons** – Collection of reusable Java components.


## Frameworks
- A **framework** provides a standard structure for building applications.
- Determines the application's architecture and workflow.
- Must be selected early in the development process.
- The framework calls the developer's code (**Inversion of Control**).
- Less flexible than libraries but provides standardization.

### Examples
- **Angular** – JavaScript framework for dynamic web applications.
- **Vue.js** – JavaScript framework focused on user interfaces.
- **Django** – Python framework for web development.


## Inversion of Control (IoC)
- A design principle where the **framework controls the program flow** instead of the developer.
- The framework decides **when** and **how** the developer's code is executed.


## Opinionated Frameworks
- Frameworks with predefined rules and conventions.
- Control:
  - Project structure
  - File organization
  - Naming conventions
  - Workflow
- Reduce configuration work and encourage standardized development.

---

## Libraries vs Frameworks

| Library | Framework |
|---------|-----------|
| Collection of reusable code | Complete application structure |
| Developer controls program flow | Framework controls program flow |
| Added when needed | Chosen before development begins |
| More flexible | Less flexible but standardized |
| Solves specific problems | Defines the application's architecture |

---

# 2. More Application Development Tools

## Overview
- Modern application development uses tools that automate building, testing, packaging, and deploying applications.
- Important development tools include:
  - CI/CD
  - Build Tools
  - Packages
  - Package Managers


## CI/CD

**CI/CD** stands for:
- **CI** – Continuous Integration
- **CD** – Continuous Delivery (or Continuous Deployment)

### Continuous Integration (CI)
- A DevOps practice that frequently integrates new code into a shared project.
- Automatically:
  - Builds code
  - Tests code
- Ensures all code components work together correctly.
- Developers typically integrate code daily or even hourly.

### Continuous Delivery (CD)
- Begins after the CI process.
- Automatically deploys successfully tested code to:
  - Testing environment
  - Staging environment
- Makes software ready for production deployment.


## Build Tools
- Transform source code into executable files (binaries).
- Help manage large software projects by automating development tasks.

### Build Tool Functions
- Download dependencies.
- Compile source code.
- Package applications.
- Run tests.
- Deploy applications.

### Categories of Build Tools

#### Build-Automation Utilities
- Generate build artifacts by compiling and linking source code.

#### Build-Automation Servers
- Execute build processes automatically on a schedule or when triggered.

### Examples of build tools
- **Webpack** – JavaScript module bundler.
- **Babel** – JavaScript compiler.
- **WebAssembly (Wasm)** – Binary instruction format that runs in web browsers.


## Packages
- A **package** is an archive containing everything required to install an application.

### Packages Contain
- Application files
- Installation instructions
- Metadata
- Version information
- Dependencies


## Package Managers
- Software used to install, update, maintain, and remove packages.

### Package management systems:
- Coordinate with file archivers to extract packages.
- Verify checksums/digital certificates for integrity and authenticity.
- Locate, download, install, or update software from a repository.
- Manage dependencies so a package installs with everything it requires.


## Common Package Managers

### Operating System Package Managers

| Platform | Package Manager |
|----------|-----------------|
| Linux | Debian Package Management System(DPKG), Red Hat Package Manager(RPM) |
| Windows | Chocolatey |
| Android | Package Manager |
| macOS | Homebrew, MacPorts |


### Language Package Managers

| Language | Package Manager |
|----------|-----------------|
| Node.js / JavaScript | npm |
| Java | Gradle, Maven |
| Ruby | RubyGems |
| Python | Pip, Conda |


## CI/CD vs Build Tools vs Package Managers

| CI/CD | Build Tools | Package Managers |
|-------|-------------|------------------|
| Automates integration and deployment | Compiles and builds applications | Installs and manages software packages |
| Builds and tests code | Creates executables | Manages dependencies |
| Supports Continuous Delivery | Produces build artifacts | Downloads and updates packages |

---

# 3. Introduction to Software Stacks

## Overview
- A **software stack** is a combination of technologies, including software and programming languages, used to create applications and solutions.
- Software stacks typically include **front-end** and **back-end** technologies.
- A **technology stack** is broader than a software stack because it also includes hardware and infrastructure.
- Software stacks support the development, functionality, and deployment of applications.


## Software Stack
- Technologies are organized in a hierarchy.
  - Higher layers provide services to users.
  - Lower layers interact with computer hardware.

### Typically Includes
- Front-end technologies
- Back-end technologies


## Technology Stack
- Includes everything in a software stack, plus:
  - Virtual Machines (VMs)
  - Containers
  - Storage
  - Load Balancers
  - Infrastructure


## Parts of a Software Stack

### Basic Three-Layer Stack
- **Presentation Layer** – User interface.
- **Business Logic Layer** – Application logic.
- **Data Layer** – Data storage and management.

More complex stacks may also include:
- Virtualization
- Scheduling & Orchestration
- Runtime Environments
- Database Connectivity
- Networking
- Security


## Common Software Stacks

### Python Django Stack
- Programming Language: **Python**
- Framework: **Django**
- Open-source
- Suitable for large-scale web applications.

### Ruby on Rails Stack
- Programming Language: **Ruby**
- Framework: **Ruby on Rails**
- Supports:
  - JSON
  - XML
  - HTML
  - CSS
  - JavaScript

### ASP.NET Stack
- Uses Microsoft technologies:
  - ASP.NET MVC
  - IIS Web Server
  - SQL Server
  - Microsoft Azure


## LAMP Stack

**LAMP** stands for:
- **L** – Linux
- **A** – Apache
- **M** – MySQL
- **P** – PHP

### Features
- Open-source.
- Loosely coupled architecture.
- Easy to replace components.
- Works well with relational databases.

Example:
- MySQL → PostgreSQL = **LAPP**
- PHP → Python (alternative implementation)


## MEAN Stack

**MEAN** stands for:
- **M** – MongoDB
- **E** – Express.js
- **A** – Angular
- **N** – Node.js

### Features
- Open-source.
- Platform-independent.
- Uses JavaScript throughout the stack.


## MERN Stack

**MERN** stands for:
- **M** – MongoDB
- **E** – Express.js
- **R** – React
- **N** – Node.js

### Features
- Replaces Angular with React.
- Flexible and high-performance front-end development.


## MEVN Stack

**MEVN** stands for:
- **M** – MongoDB
- **E** – Express.js
- **V** – Vue.js
- **N** – Node.js

### Features
- Uses Vue.js instead of Angular.
- Lightweight and high-performance.
- Community-driven framework.


## Software Stack Comparison

| Stack | Technologies | Best For |
|-------|--------------|----------|
| LAMP | Linux, Apache, MySQL, PHP | Traditional web applications |
| MEAN | MongoDB, Express.js, Angular, Node.js | JavaScript full-stack development |
| MERN | MongoDB, Express.js, React, Node.js | React-based web applications |
| MEVN | MongoDB, Express.js, Vue.js, Node.js | Vue.js-based web applications |


## MEAN vs MEVN vs LAMP

| MEAN | MEVN | LAMP |
|------|------|------|
| JavaScript throughout | JavaScript throughout | Multiple languages (PHP/Python + JavaScript) |
| Angular | Vue.js | PHP |
| MongoDB | MongoDB | MySQL |
| Platform-independent | Platform-independent | Linux-based |
| Good community support | Lightweight UI | Strong support for relational databases |


## Advantages and Challenges

| Stack | Advantages | Challenges |
|-------|------------|------------|
| MEAN | Single language (JavaScript), open-source, reusable libraries | Less suitable for very large applications, MongoDB has fewer relational features |
| MEVN | Lightweight, fast, flexible | Smaller ecosystem than Angular |
| LAMP | Mature, stable, excellent community support | Linux-dependent, multiple programming languages, limited support for unstructured data |

---

