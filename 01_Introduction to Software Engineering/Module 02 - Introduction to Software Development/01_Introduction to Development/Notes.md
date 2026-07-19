# 1. Overview of Web and Cloud Development

## Overview
- Websites and cloud applications use **client-server communication**.
- A browser sends a request to a **server**, and the server returns the required content.
- Web development is divided into **Front-end**, **Back-end**, and **Full-stack** development.


## Client-Server Communication
- A user launches an internet browser (e.g., **Google Chrome, Microsoft Edge, Mozilla Firefox, Apple Safari**).
- A user enters a **URL** in a web browser.
- The browser sends a **request** to the server.
- The server processes the request and sends a **response** back to the client.

### Server Response
Typically includes:
- **HTML** – Defines the structure of a web page.
- **CSS** – Adds styling and layout.
- **JavaScript** – Adds interactivity and dynamic behavior.


## Static vs Dynamic Content

### Static Content
- Stored on the server.
- Same content is delivered to every user.

### Dynamic Content
- Generated when requested.
- May retrieve data from:
  - Databases
  - Other applications
  - External services

- Most modern websites use a combination of **static** and **dynamic** content.


## Cloud Applications
- Similar to websites, but built to work with **cloud-based infrastructure**.
- Utilize:
  - Cloud storage
  - Cloud processing
  - Cloud services
- Benefits:
  - High scalability
  - High reliability (resilience)


## Front-end Development
- Handles everything on the **client side**.
- Users can see and interact with it.

### Common Technologies
- HTML
- CSS
- JavaScript
- Frameworks and libraries


## Back-end Development
- Handles everything on the **server side**.
- Responsibilities include:
  - Business logic
  - Application functionality
  - Authentication
  - Database operations
- Works with:
  - Relational databases
  - NoSQL databases

---

## Full-stack Development
- Combines **Front-end** and **Back-end** development skills.
- Developers work with both the client-side and server-side of web applications.


## Development Tools
Developers use code editors and IDEs to write, build, compile, debug, and manage code.

### Code Editors
Used for writing source code.

Examples:
- Sublime Text
- Atom
- Vim
- VS Code

### Integrated Development Environments (IDEs)
Provide additional development tools such as:
- Code editing
- Building
- Compiling
- Debugging
- Git & GitHub integration
- Extensions and themes

Examples:
- Visual Studio Code
- Visual Studio
- Eclipse
- NetBeans

---

## Front-end vs Back-end vs Full-stack

| Front-end | Back-end | Full-stack |
|-----------|-----------|------------|
| Client-side development | Server-side development | Both client and server-side |
| HTML, CSS, JavaScript | Business logic, authentication, databases | Front-end + Back-end |
| User interface | Server functionality | Complete application development |

---

# 2. Front-end Development

## Overview
- **Front-end development** focuses on everything users **see and interact with** on a website.
- Front-end developers use **HTML**, **CSS**, and **JavaScript** to build attractive, responsive, and interactive web pages.


## HTML (HyperText Markup Language)
- Creates the **structure** of a web page.
- Defines elements such as:
  - Text
  - Links
  - Images
  - Videos
  - Buttons
  - Page dividers
- Ensures browsers display content consistently.


## CSS (Cascading Style Sheets)
- Adds **style** and visual appearance to websites.
- Controls:
  - Colors
  - Fonts
  - Layouts
  - Design
  - Look and feel
- Provides a standard way to manage website styling.
- Supports **cross-browser compatibility** across different browsers and devices.


## JavaScript
- An **object-oriented programming language** used with HTML and CSS.
- Adds **interactivity** and dynamic functionality.
- Example:
  - HTML creates a **Login** button.
  - CSS styles the button.
  - JavaScript adds the **login functionality**.


## CSS Extensions

### SASS (Syntactically Awesome Style Sheets)
- Extension of CSS.
- Compatible with all CSS versions.
- Features:
  - Variables
  - Nested rules
  - Inline imports
- Makes writing stylesheets faster and easier.

### LESS (Leaner Style Sheets)
- Enhances CSS with additional styles and functions.
- Backward compatible with CSS.
- **LESS.js** converts LESS styles into CSS.


## Website Design

### Adaptive Design
- Displays different versions of a website for specific screen sizes.
- Example:
  - Desktop version shows more information than the mobile version.

### Responsive Design
- Automatically adjusts the layout to fit different screen sizes.
- Works across desktops, tablets, and mobile devices.


## JavaScript Frameworks & Library

### Angular
- Open-source JavaScript framework maintained by **Google**.
- Features:
  - Fast HTML rendering
  - Routing
  - Form validation

### React.js
- JavaScript **library** maintained by **Facebook**.
- Builds reusable UI components.
- Requires third-party libraries for features like routing.

### Vue.js
- Community-maintained framework.
- Focuses on the **user interface (UI)** layer.
- Flexible, scalable, and easy to integrate with other frameworks.
- Can be used as both a **library** and a **framework**.


## Responsibilities of a Front-end Developer
- Build user interfaces using HTML, CSS, and JavaScript.
- Create responsive and interactive websites.
- Ensure compatibility across:
  - Browsers
  - Operating systems
  - Devices
- Continuously update websites as technologies evolve.


## HTML vs CSS vs JavaScript

| HTML | CSS | JavaScript |
|------|-----|------------|
| Creates structure | Adds style | Adds interactivity |
| Text, images, buttons | Colors, fonts, layouts | Dynamic behavior and functionality |
| Defines page elements | Improves appearance | Handles user interactions |

---

# 3. Back-end Development

## Overview
- **Back-end development** focuses on everything that happens on the **server side**.
- It processes client requests, manages data, and provides secure services to websites and cloud applications.
- Front-end and back-end developers work closely throughout the development lifecycle.


## Responsibilities of a Back-end Developer
- Process client requests.
- Manage server-side logic.
- Retrieve and store data.
- Handle authentication and authorization.
- Secure sensitive user information.
- Develop and maintain APIs, routes, and endpoints.
- Work with databases and cloud services.


## How the Back-end Works

When a user interacts with a website:

1. The user sends a request from the browser.
2. The request reaches the server.
3. The server processes the request.
4. The server retrieves data from a database (if needed).
5. The server sends the response back to the client.

Examples:
- User login
- Product search
- Adding items to a shopping cart
- Online payments


## Security
Back-end developers ensure secure handling of:
- User accounts
- Login credentials
- Payment information
- Credit card details
- Personal information


## APIs, Routes, and Endpoints

### API (Application Programming Interface)
- Allows applications to communicate with the back-end.
- Exchanges data using formats such as:
  - JSON
  - XML
- Follows predefined rules and structures.

### Route
- The path that connects a client request to the appropriate server service.
- Processes user requests and returns the required response.

### Endpoint
- A specific destination where an API or route receives requests.
- If an endpoint does not exist, the server returns a **404 Not Found** error.


## Back-end Technologies

### JavaScript
Popular server-side technologies:
- Node.js
- Express.js

### Python
Popular frameworks:
- Django
- Flask


## Databases

Back-end developers work with:
- Relational databases
- NoSQL databases

### SQL
- Used to query and manage relational databases.

### ORM (Object Relational Mapping)
- Connects applications with databases.
- Simplifies database operations.
- Helps retrieve and store data without writing complex SQL queries.

---

# 4. Teamwork and Squads

## Overview
- **Teamwork** is the collaboration of people working together toward a **common goal**.
- Software engineering teams combine different skills, experience, and expertise to build high-quality software.
- Good teamwork improves creativity, productivity, and code quality.


## Benefits of Teamwork
- Encourages creativity and idea sharing.
- Allows members to learn new skills from each other.
- Uses each member's strengths effectively.
- Improves code quality and maintainability.
- Reduces bugs through collaboration and reviews.
- Encourages adherence to coding standards and regular code documentation.
- Reduces stress by providing support from teammates.
- Helps members understand the overall project ("big picture").


## How to work well as a team
- Trust and respect among team members.
- Define and confirm goals.
- Define and confirm roles.
- Good communication.
- Working with each member's strengths.
- Celebrate successes and learn from problems.


## Teamwork in Software Engineering
Teams commonly perform:
- **Kick-off meetings** — plan the project, assign tasks, agree on goals.
- **Whole team / sub-team meetings** — review progress and plans throughout the project.
- **Design and code reviews** — requested at the team level, done by whoever is available.
- **Team walkthroughs** — team members present their areas of responsibility to give the whole team oversight.
- **Stakeholder walkthroughs** — key members present progress to stakeholders at various points.
- **Retrospective meetings** — held on project completion to review what went well and what could improve.
- **Mentoring** — may have or become a mentor; team mentoring helps everyone learn from each other.
- **Internal improvement projects** — teams may work on code standards, legacy code maintenance, or evaluating new software.


## Squad (Agile Team)

A **Squad** is a small Agile team, typically consisting of **up to 10 developers**.

### Typical Squad Members
- A Squad Leader (anchor developer and coach)
- A few Software Engineers
- One or two UX Designers / Developers (optional)

### Squad Practices
- Collaboration
- Pair Programming
- Regular communication
- Shared responsibility


## Benefits of Squads
- Faster collaboration.
- Better communication.
- Shared knowledge.
- Higher code quality.
- Efficient feature development.


## Team vs Squad

| Team | Squad |
|------|-------|
| General software engineering team | Small Agile development team |
| Can be large | Usually up to 10 members |
| Used in any development methodology | Common in Agile methodologies |
| Members have different project roles | Led by a Squad Leader with software engineers and optional UX designers |

---

# 5. Pair Programming

## Overview
- **Pair Programming** is an Agile development practice where **two developers work together on one computer**.
- They can work:
  - Physically at the same computer (preferred)
  - Virtually using video calls or screen sharing
- It promotes collaboration, better code quality, and knowledge sharing.


## Pair Programming Styles

### Driver-Navigator Style
- Most common style.
- **Driver**
  - Writes the code.
- **Navigator**
  - Reviews the code as it is written.
  - Provides guidance and directions.
  - Focuses on the overall solution.
- Roles should be switched regularly.

### Ping-Pong Style
- Based on **Test-Driven Development (TDD)**.
- One developer writes a **failing test**.
- The other developer writes code to make the test pass.
- Roles are swapped for each new task.
- Both developers refactor the code together after each task.

### Strong Style Pair Programming
- Ideal for mentoring junior developers.
- Rule:
  - **An idea must pass through someone else's hands before reaching the computer.**
- Experienced developer acts as the **Navigator**.
- Junior developer acts as the **Driver** and learns from implementation.
- The driver should avoid interrupting until the implementation is complete.


## Benefits of Pair Programming
- Encourages knowledge and skill sharing.
- Helps new team members get up to speed on a project.
- Builds soft skills (communication, problem solving) alongside technical skills.
- Reduces typos, logic errors, and bugs.
- Provides continuous code review.
- Leads to the optimal approach being chosen earlier in the process.
- Reduces overall testing and debugging effort.


## Challenges of Pair Programming
- Long focus periods can be exhausting.
- Scheduling can be affected by personal/work commitments.
- One developer may dominate the session.
- Personality differences can reduce effectiveness.
- Multiple pairs working together can create a noisy environment.


## Pair Programming Styles Comparison

| Style | Description | Best For |
|--------|-------------|----------|
| Driver-Navigator | One writes code while the other reviews and guides | General software development |
| Ping-Pong | Developers alternate between writing tests and implementation | Test-Driven Development (TDD) |
| Strong Style | Experienced developer guides while junior developer types | Mentoring and knowledge transfer |


## Benefits vs Challenges

| Benefits | Challenges |
|----------|------------|
| Knowledge sharing | Long periods of focus |
| Better code quality | Scheduling difficulties |
| Fewer bugs | One person may dominate |
| Continuous code review | Personality conflicts |
| Improved communication | Noisy work environment |

---
