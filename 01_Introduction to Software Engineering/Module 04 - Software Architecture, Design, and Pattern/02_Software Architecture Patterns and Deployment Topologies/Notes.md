# 1. Approaches to Application Architecture

## Overview
- Component-based architecture organizes applications into reusable, independent components.
- Services are independently deployable units of functionality built from components.
- Service-Oriented Architecture (SOA) enables communication between services over a network.
- Distributed systems consist of multiple services running on different machines while appearing as a single system.


## Components
- A component is an individual unit of encapsulated functionality.
- Works together with other components to build an application.

### Characteristics of Components
- **Reusable:** reused in different applications.
- **Replaceable:** easily replaced with another component.
- **Independent:** doesn’t have dependencies on other components.
- **Extensible:** add behavior without changing other components.
- **Encapsulated:** doesn’t expose its specific implementation.
- **Non-context specific:** operates in different environments and receives its data from outside the component.


## Component-Based Architecture
- Decomposes an application into logical components.
- Provides a higher level of abstraction than object-oriented design.
- Defines, composes, and implements loosely coupled, independent components.


## Services
- A service is a unit of functionality designed to be deployed independently.
- Can be reused by multiple systems.
- Focuses on solving a business need.
- A service is made up of components.
- Components consist of objects.


## Components vs Services

| Components | Services |
|------------|----------|
| Unit of encapsulated functionality | Unit of functionality focused on a business need |
| Works as part of an application | Deployed independently |
| Consists of objects | Made up of components |
| Reusable within applications | Reusable by multiple systems |


## Service-Oriented Architecture (SOA)
- Services are loosely coupled.
- Services communicate over a network using a communication protocol.
- Supports building distributed systems.


## Distributed System Characteristics
- Consist of multiple services running on different machines.
- Appear as a single coherent system to the end user.
- Share hardware, software, and data.
- Are fault-tolerant.
- Support concurrent activities.
- Are scalable.
- Can use different hardware, operating systems, and programming languages.


## Nodes
- A node is any device on a network that can recognize, process, and transmit data.
- Distributed systems consist of multiple interconnected nodes.


## Common Distributed System Architectures
- Client-Server
- Three-Tier
- Peer-to-Peer
- Microservices

---

# 2. Architectural Patterns in Software

## Overview
- Architectural patterns are repeatable solutions to software architecture problems.
- Different architectural patterns organize software systems in different ways.
- Common patterns include 2-tier, 3-tier, peer-to-peer, event-driven, and microservices.
- Multiple architectural patterns can be combined depending on system requirements.


## Architectural Patterns
- An architectural pattern is a repeatable solution to a software architecture problem.
- Highlights common internal elements and structures of a software system.
- Different architectural patterns may share related characteristics.


## 2-Tier Architecture (Client-Server)
- Consists of a client and a server.
- The server hosts, manages, and delivers resources and services.
- The client provides the user interface and requests data or services from the server.
- Multiple clients can connect to a server over a network.

**Examples**
- Text messaging applications
- Database clients connecting to database servers


## 3-Tier Architecture
- The most common software architecture.
- Organizes applications into three logical and physical tiers.
- Each tier communicates only with the tier directly above or below it.
- Changes in one tier do not affect the other tiers.

### Tiers
- **Presentation Tier:** User interface.
- **Application Tier:** Processes business logic.
- **Data Tier:** Stores and manages data.

**Example**
- Web applications


## Peer-to-Peer (P2P) Architecture
- A decentralized network of nodes.
- Each node acts as both a client and a server.
- Peers both provide and consume resources.
- Does not require central server coordination.

**Examples**
- File sharing
- Instant messaging
- Collaboration
- High-performance computing
- Cryptocurrencies (Bitcoin, Ethereum)


## Event-Driven Architecture
- Focuses on producers and consumers of events.
- An event is anything that causes a change of state.
- Producers publish events.
- An event router directs events to consumers.
- Consumers process the events.
- Components are loosely coupled.

**Example**
- Ride-sharing applications


## Microservices Architecture
- Breaks an application into modular services.
- Services are loosely coupled.
- APIs enable communication between applications.
- API Gateway routes client requests to services.
- Orchestration manages communication between services.

**Example**
- Social media applications


## Combining Architectural Patterns
- Multiple architectural patterns can be combined within a system.
- A 3-tier architecture can also use microservices.
- A peer-to-peer architecture can also be event-driven.
- A peer-to-peer architecture cannot also be a 2-tier architecture.


## Architectural Patterns Comparison

| Pattern | Key Characteristic | Example |
|---------|--------------------|---------|
| 2-Tier | Client communicates with server | Text messaging app |
| 3-Tier | Presentation, application, and data tiers | Web application |
| Peer-to-Peer | Nodes act as both client and server | Bitcoin, Ethereum |
| Event-Driven | Producers and consumers communicate through events | Ride-sharing app |
| Microservices | Application divided into independent services | Social media platform |

---

# 3. Application Deployment Environments

## Overview
- An application environment is the combination of hardware and software resources required to run an application.
- Applications move through multiple pre-production environments before reaching production.
- Production environments are designed for end users and must meet non-functional requirements.
- Applications can be deployed on-premises or in public, private, or hybrid cloud environments.


## Application Environment
- An application environment is the combination of hardware and software resources required to run an application.
- Includes:
  - Application code or binary executables
  - Software stack (modules, libraries, middleware, operating system)
  - Networking components and infrastructure
  - Physical or virtual hardware (processing, memory, and storage)


## Pre-Production Environments

### Development
- Environment where the application is actively developed.
- May be the developer's workstation.

### Quality Assurance (QA)
- Also called the **testing** environment.
- Used by the QA team to test application components.

### Staging
- Closely replicates the production environment.
- Not intended for general users.


## Production Environment
- Contains the complete hardware and software solution stack.
- Intended for all users.
- Designed to handle application load.
- Must consider:
  - Security
  - Reliability
  - Scalability


## Deployment Options

### On-Premises Deployment
- Application and infrastructure reside within the organization's physical location.
- Usually protected by a firewall.
- Organization manages hardware, infrastructure, and maintenance.
- Provides greater security and control.
- Generally more expensive than cloud deployment.

### Public Cloud
- Infrastructure is owned by a cloud provider.
- Resources are shared with other organizations.
- Offers scalability and cost efficiency.
- Examples:
  - Amazon Web Services (AWS)
  - Microsoft Azure
  - Google Cloud Platform
  - IBM Cloud

### Private Cloud
- Infrastructure is dedicated to a single organization.
- Can be managed by the organization or a service provider.
- Provides increased security and greater flexibility.

### Hybrid Cloud
- Combines public and private cloud environments.
- Balances cost, security, scalability, and flexibility.


## Deployment Options Comparison

| Deployment Option | Key Characteristic |
|-------------------|--------------------|
| On-Premises | Managed within the organization's infrastructure |
| Public Cloud | Shared infrastructure provided by a cloud provider |
| Private Cloud | Dedicated infrastructure for one organization |
| Hybrid Cloud | Combination of public and private clouds |

---

# 4. Production Deployment Components

## Overview
- Production environments consist of multiple infrastructure components working together.
- These components improve security, availability, performance, and reliability.
- Common components include firewalls, load balancers, servers, proxy servers, and databases.
- Each component has a specific role in processing and managing application requests.


## Production Deployment Architecture
- The presentation tier contains front-end client applications.
- The web tier contains web load balancers and web servers.
- The application tier contains application load balancers (or proxy servers) and application servers.
- The data tier contains the database server.
- A high-availability database replica is often used to improve reliability.
- Not every deployment requires all of these components.


## Firewall
- A firewall is a security device that monitors traffic between networks.
- Permits or blocks data based on security rules.
- Protects the internal network from viruses, malware, and unauthorized access.


## Load Balancer
- Distributes network traffic among multiple servers.
- Prevents server overload.
- Located between clients and servers.
- Improves availability and responsiveness.
- Ensures no single server is overworked.


## Web Server
- Provides content to clients.
- Delivers:
  - Web pages
  - Files
  - Images
  - Videos
- Primarily responds to HTTP requests from web browsers.


## Application Server
- Runs the application's business logic.
- Provides the application to clients.
- Handles data creation, storage, retrieval, and updates.
- Determines transaction results.


## Proxy Server
- Acts as an intermediate server between two tiers.
- Routes requests between tiers.
- Can perform:
  - Load balancing
  - System optimization
  - Caching
  - Firewall functions
  - Encryption
  - Malware scanning
- Improves efficiency, privacy, and security.


## Database Server
- Stores and manages application data.
- Uses a Database Management System (DBMS).
- The DBMS connects applications to the database.
- Controls the flow and storage of data.


## Components Comparison

| Component | Purpose |
|-----------|---------|
| Firewall | Monitors and filters network traffic |
| Load Balancer | Distributes traffic across servers |
| Web Server | Delivers web content to clients |
| Application Server | Executes business logic |
| Proxy Server | Routes requests and provides additional services |
| Database Server | Stores and manages application data |
