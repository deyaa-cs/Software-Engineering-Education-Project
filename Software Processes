

**SOFTWARE PROCESSES**

**1. THE SOFTWARE PROCESS**
A software process is a structured set of activities required to develop a software system. Systems are either built from scratch or by extending/modifying existing ones.

Four fundamental activities in every software process:
- Specification – defining what the system should do and its constraints
- Design & Implementation – organizing and building the system
- Validation – checking it does what the customer wants
- Evolution – changing the system as customer needs change

Process descriptions may also include:
- Products – outcomes of an activity (e.g., architecture model)
- Roles – responsibilities of people involved (e.g., project manager, programmer)
- Pre/post-conditions – statements true before/after an activity

**2. PLAN-DRIVEN vs AGILE PROCESSES**
- Plan-driven: all activities planned in advance; progress measured against the plan
- Agile: planning is incremental, easier to adapt to changing requirements
- Most real processes mix both approaches — neither is "right" or "wrong"

**3. SOFTWARE PROCESS MODELS**
A process model is a simplified, abstract representation of a process, showing it from one perspective only.

**A) The Waterfall Model** (aka Software Life Cycle)
Plan-driven; phases done in strict sequence:
1. Requirements analysis & definition
2. System and software design
3. Implementation and unit testing
4. Integration and system testing
5. Operation and maintenance (longest phase — includes fixing errors, improving implementation, adding new requirements)

Each phase ends with signed-off documents before the next begins.
- Problems: rigid, hard to handle changing requirements; best for well-understood, stable requirements
- Best used for: large, multi-site systems engineering projects

**B) Incremental Development**
Specification, development, and validation are interleaved (not separate), with rapid feedback.
- Better than waterfall for most business/e-commerce/personal software
- Benefits vs waterfall:
  - Cheaper to accommodate changing requirements (less rework)
  - Easier to get customer feedback
  - Faster delivery of useful software

**C) Reuse-Oriented Software Engineering**
System built by integrating existing components or COTS (Commercial Off-The-Shelf) systems.
Process stages:
1. Component analysis – search for components matching requirements
2. Requirements modification – adjust requirements to fit available components
3. System design with reuse – design/reuse a framework around chosen components
4. Development and integration – build custom parts, integrate everything

Types of components: web services, object collections (.NET/J2EE), stand-alone COTS systems

Advantages: less software to build, lower cost/risk, faster delivery
Disadvantages: requirement compromises may not meet real user needs; less control over component evolution

*(In practice, most large systems combine elements of all three models above.)*

**4. PROCESS ACTIVITIES**

**Software Specification (Requirements Engineering)**
Goal: produce an agreed requirements document. Critical stage — errors here cause bigger problems later.
Four activities:
1. Feasibility study – is it technically/financially feasible?
2. Requirements elicitation & analysis – what do stakeholders need?
3. Requirements specification – document the detailed requirements
4. Requirements validation – check for errors, fix the document

**Software Design & Implementation**
Converts specification into an executable system.
- Software Design: designing structure, data models, interfaces, algorithms
- Implementation: translating design into executable code

Design activities:
- Architectural design – identify sub-systems and their relationships
- Interface design – define how sub-systems interact
- Component design – design how each component operates
- Data structure design – design data structures & database representation

Implementation notes: programming is personal, no fixed process; involves writing code + debugging (removing defects found in testing)

**Software Validation (Verification & Validation, V&V)**
Confirms the system meets spec and customer needs. Testing is the main V&V method.

Verification vs Validation:
- Verification = "Are we building the product right?" (matches specification)
- Validation = "Are we building the right product?" (meets user's real needs)

Testing stages:
1. Component/Development testing – individual components tested by developers
2. System testing – integrated components tested as a whole; catches interaction/interface errors
3. Acceptance testing – final stage using real customer data (not simulated); includes alpha/beta testing

**Software Evolution**
Software must change as business needs change — it must evolve to remain useful.
Cycle: Define requirements → Assess existing system → Propose changes → Modify system → repeat

**5. COPING WITH CHANGE**
Change is inevitable (business shifts, new tech, platform changes) and causes costly rework.

Two strategies to reduce rework costs:
- Change avoidance – anticipate changes early (e.g., via prototyping)
- Change tolerance – design process so changes are cheap to accommodate (e.g., incremental development)

**A) Software Prototyping**
An early version of a system to test concepts/design/requirements.
Uses: requirements elicitation & validation, exploring design options, UI design

Benefits: better usability, closer match to user needs, better design quality/maintainability, less overall effort
Limitations: test users may not be typical; limited training time during evaluation

Process: Establish objectives → Define functionality → Develop prototype → Evaluate prototype

Throwaway prototypes should be discarded, NOT reused as production code because:
- Non-functional requirements were ignored
- Usually undocumented
- Structure degrades from rapid changes
- Won't meet normal quality standards

**B) Incremental Delivery**
System built and delivered in increments, each adding functionality. High-priority requirements go first; changes to the current increment aren't accepted mid-build (future increments can absorb new requirements).

Advantages: early increments act as prototypes, customers gain value sooner, high-priority parts get more testing (lower risk)
Problems: hard to identify shared/common facilities early; conflicts with fixed-contract procurement models

**6. BOEHM'S SPIRAL MODEL**
A risk-driven framework represented as a spiral (not a straight sequence). Each loop = one phase; no fixed phase order — chosen based on risk.

Four sectors per loop:
1. Objective setting – define goals, constraints, risks, management plan
2. Risk assessment & reduction – assess and mitigate key risks
3. Development & validation – pick and apply a development model
4. Planning – review progress, decide whether to continue

Note: influential concept but rarely used exactly as published in practice.

**7. THE RATIONAL UNIFIED PROCESS (RUP)**
A modern process model combining elements of waterfall, incremental development, and spiral models.

Four phases:
1. Inception – establish business case, identify external interactions; project may be cancelled if not worthwhile
2. Elaboration – understand the problem, set architecture, plan project, identify risks
3. Construction – design, code, and test; produces a working system ready for delivery
4. Transition – deploy system into real operating environment

Iteration types:
- In-phase iteration – each phase itself is iterative
- Cross-phase iteration – the whole phase cycle can repeat

---

**KEY TAKEAWAYS**
- Requirements engineering = developing the software specification
- Design & implementation = turning spec into an executable system
- Validation = confirming the system meets spec AND real user needs
- Evolution = software must change to stay useful
- Change is unavoidable — good processes plan for it (prototyping, incremental delivery)
- RUP = modern process combining phases (inception/elaboration/construction/transition) with separate activities (requirements, design, etc.)

---
