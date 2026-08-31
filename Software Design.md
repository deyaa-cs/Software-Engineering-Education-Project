===================================================
SOFTWARE DESIGN — SUMMARY NOTES
===================================================

===================================================
PART 1: THE SOFTWARE DESIGN PROCESS
===================================================

WHAT IS THE SOFTWARE DESIGN PROCESS?
- The stage where developers plan HOW to turn requirements into
  a working system — essentially the blueprint of the software.
- Purpose:
  - Breaks complex requirements into smaller, manageable
    modules/components.
  - Bridges the gap between requirements (functional & non-
    functional) and actual coding, preventing costly rework.
  - Defines the system's architecture and how components
    interact with one another.


---------------------------------------------------
1. LEVELS OF SOFTWARE DESIGN
---------------------------------------------------

A) INTERFACE DESIGN
   - Focuses on how the system interacts with its environment
     (users, devices, and other systems — collectively called
     "agents").
   - The system is treated as a black box; internal workings
     are ignored at this stage.
   - Should define:
     - Events/messages coming from agents that the system must
       respond to.
     - Events/messages the system must produce in return.
     - The data and data formats going in and out.
     - The timing/order relationships between incoming and
       outgoing events.

B) ARCHITECTURAL DESIGN
   - Defines the system's major components, their
     responsibilities, interfaces, and how they relate/interact.
   - The overall structure is decided, but internal details of
     each component are still ignored at this stage.
   - Key concerns:
     - Breaking the system down into major components.
     - Assigning functional responsibilities to each component.
     - Defining component interfaces.
     - Component performance, scalability, resource use, and
       reliability.
     - How components communicate with each other.

C) DETAILED DESIGN
   - Specifies the internal elements of each major component —
     their properties, relationships, algorithms, and data
     structures.
   - May include:
     - Breaking components down into individual program units.
     - Assigning specific responsibilities to each unit.
     - User interface details.
     - Unit states and state transitions.
     - Data/control flow between units.
     - Data structuring, scope, and visibility of program
       elements.
     - The actual algorithms and data structures used.


---------------------------------------------------
2. PHASES OF THE SOFTWARE DESIGN PROCESS
---------------------------------------------------

1. Understanding Project Requirements
   - Confirms the team understands user needs, business goals,
     and potential challenges before design begins.

2. Research, Analysis & Planning
   - Gathering data through interviews, surveys, and focus
     groups to design with real user needs in mind.

3. Designing the Software
   - Creating wireframes, user stories, and flow diagrams to
     map out the system. Prototypes are built and refined based
     on feedback.

4. Technical Design
   - Producing a detailed technical document describing exactly
     how the software will be implemented and how its
     components will work together.

5. User Interface Design
   - Focused on usability — designers shape visuals, navigation,
     and overall experience to keep the interface intuitive.

6. Prototyping
   - Building prototypes (from simple low-fidelity wireframes to
     fully interactive high-fidelity models) to visualize design
     and functionality before full development starts.


---------------------------------------------------
3. CORE ELEMENTS OF SOFTWARE DESIGN
---------------------------------------------------

- ARCHITECTURE: The conceptual model defining the system's
  structure, behavior, and views (often shown via flowcharts).
  Good architecture keeps a system flexible, stable, and
  maintainable.

- MODULES: The system's building blocks — each handles one
  specific task/feature. Breaking a system into modules makes
  it easier to develop, test, and maintain. Combined, modules
  form the full system.

- COMPONENTS: Provide a function or group of related functions,
  built from modules. Organizing a system into components keeps
  code clean and the system adaptable.

- INTERFACES: The shared boundary where components exchange
  information — smaller functional units within modules that
  focus on specific tasks.

- DATA: The core of any system — how information is stored,
  accessed, shared, and how data flow is managed.


---------------------------------------------------
4. WHERE DESIGN FITS IN THE SDLC
---------------------------------------------------

Software design happens after requirements gathering and right
before development begins:

1. Design the system architecture — overall structure, modules,
   components, and their interactions.
2. Prepare design artifacts — wireframes, UI/UX designs, data
   flow diagrams (DFDs), and database designs.
3. Define component functionality — how each part works
   together for smooth, efficient functionality.
4. Begin development — once the design is finalized and
   approved, coding/implementation starts.


---------------------------------------------------
5. COMMON SOFTWARE DESIGN TOOLS
---------------------------------------------------

- Figma
- Balsamiq
- Axure RP
- Sketch
- InVision Studio


===================================================
PART 2: THE SOFTWARE DESIGN DOCUMENT (SDD)
===================================================

WHAT IS A SOFTWARE DESIGN DOCUMENT?
- A technical blueprint/detailed plan describing a software
  system's architecture, components, and data models BEFORE
  development starts.
- It turns big-picture ideas into a concrete plan, connecting
  what the software should do with how it will be built.
- Ensures every team member — developers, project managers, and
  stakeholders — shares the same understanding of requirements
  and technical standards.
- Helps catch potential technical problems early, reducing the
  chance of expensive rework later.


---------------------------------------------------
1. BENEFITS OF A SOFTWARE DESIGN DOCUMENT
---------------------------------------------------

- BETTER COMMUNICATION: Keeps everyone aligned on goals and
  decisions, improving stakeholder communication throughout the
  project.

- BETTER PROJECT PLANNING & MANAGEMENT: Gives project managers
  a clear picture of the system's structure, components, and
  interfaces — helping build accurate timelines, assign
  resources, and catch problems early.

- EASIER MAINTENANCE & SCALABILITY: A clear architecture and
  data structure gives developers a roadmap for writing
  modular, flexible code that's easy to update, extend, or fix
  without breaking the overall system.


---------------------------------------------------
2. KEY SECTIONS OF A SOFTWARE DESIGN DOCUMENT
---------------------------------------------------

1) INTRODUCTION & OVERVIEW
   - Sets the stage for the whole document: project summary,
     goals, scope, and main features.
   - Explains the document's purpose and intended audience.
   - Should include: a short description of the system, its
     objectives/key requirements, a summary of what's covered
     in the document, and relevant background info.

2) SYSTEM ARCHITECTURE
   - Describes the system's overall structure — its major
     components/subsystems and how they relate to each other.
   - Should include: a high-level architecture diagram,
     descriptions of major components, the design
     patterns/architectural styles used, and key design
     decisions with their trade-offs.

3) DATA DESIGN
   - Covers how the system stores, manages, and processes data.
   - Should include: database structure and table layout, data
     flow diagrams, data validation/integrity rules, and how
     data is stored and retrieved.

4) INTERFACE DESIGN
   - Describes how different parts of the system communicate
     with each other and with external systems/services
     (internal interfaces and external APIs).
   - Should include: API specifications/protocols, message
     formats and data structures, error/exception handling, and
     security/authentication methods.

5) COMPONENT DESIGN
   - Details each individual module/component: its function,
     required inputs/outputs, and the algorithms or data
     structures it uses.
   - Should include: purpose and responsibilities, input/output
     specs, algorithms/processing logic, and dependencies on
     other components or external systems.

6) USER INTERFACE DESIGN
   - Focuses on how users interact with the software — layout,
     navigation, functionality, and usability requirements.
   - Should include: wireframes/mockups of key screens,
     descriptions of user workflows, and accessibility
     considerations.

7) ASSUMPTIONS & DEPENDENCIES
   - Lists assumptions made during design and any external
     dependencies/constraints that could affect implementation.
   - Should include: technical assumptions about the dev
     environment, dependencies on external libraries/services,
     hardware/software/infrastructure constraints, and
     regulatory/compliance requirements.

8) GLOSSARY OF TERMS
   - Especially important for complex or industry-specific
     systems.
   - Should clearly define technical terms, acronyms, and
     jargon used throughout the document.


---------------------------------------------------
3. STEPS TO CREATE A SOFTWARE DESIGN DOCUMENT
---------------------------------------------------

1. Gather requirements & initial information
   - Collect project requirements, stakeholder input, technical
     constraints, and any existing system documentation. A
     solid information base ensures the document truly reflects
     the project's goals.

2. Outline the system architecture
   - Identify major components/subsystems, define how they
     relate, and choose the design patterns/architectural
     styles that will guide development.

3. Detail the data design
   - Design the database structure, build data models and
     entity-relationship diagrams, define validation/integrity
     rules, and plan how data will be stored/retrieved with
     scalability and performance in mind.

4. Specify the interface & component design
   - Define API specs and protocols for internal/external
     communication; describe each component's functionality,
     responsibilities, inputs/outputs, and algorithms/data
     structures.

5. Review and refine with stakeholders
   - Share the draft with the team, project managers, and other
     relevant parties. Gather feedback, resolve questions, and
     update the design until everyone agrees before finalizing.


---------------------------------------------------
4. BEST PRACTICES FOR WRITING AN SDD
---------------------------------------------------

- Use clear, simple language — avoid unnecessary jargon; define
  technical terms in the glossary when needed.
- Include visuals — diagrams and flowcharts make complex ideas
  and relationships easier to understand.
- Be consistent — keep formatting, terminology, and structure
  uniform throughout.
- Keep it current — review and update the document regularly as
  the project evolves.
- Make it easy to access — store it centrally so the whole team
  can find and reference it.
- Encourage teamwork — use collaborative tools (editing,
  commenting) so the whole team can contribute and share
  knowledge.
- Consider future growth — design with flexibility for how the
  system might expand or change later.
- Include traceability — link requirements to design decisions
  and implementation details, so the reasoning behind choices
  stays clear.
- Share context asynchronously — pairing the written design
  with a short recorded walkthrough helps reviewers understand
  complex diagrams/trade-offs faster, and reduces back-and-forth
  during review.
-----------------------------------------------------------------------------
