# Assignment: Software Requirements and Requirements Engineering

## 1. Requirements

### Definition

In software engineering, requirements are the descriptions of the services, features, functions, and constraints that a software system must satisfy to meet the needs of its users and other stakeholders. They explain what a system should do, how it should behave under particular conditions, and what limitations must be considered during its development.

Requirements serve as the foundation of a software project because they provide a clear understanding of the problem that the software is intended to solve. Before designing or developing a system, software engineers must identify and document its requirements to ensure that the final product meets user expectations.

### Importance of Requirements

Requirements are important for the following reasons:

1. **Understanding user needs:** They help developers understand what customers and users expect from the software.
2. **Project planning:** They provide a basis for estimating the time, cost, resources, and effort required for development.
3. **System design:** They guide software architects and developers in selecting appropriate designs and technologies.
4. **Quality assurance:** They provide a foundation for testing whether the software satisfies its intended objectives.
5. **Communication:** They establish a common understanding between clients, developers, testers, managers, and other stakeholders.
6. **Risk reduction:** Clear requirements reduce misunderstandings, unnecessary changes, and project failure.
7. **Project control:** They help determine whether the software is being developed according to the agreed scope.

### Characteristics of Good Requirements

A good requirement should possess the following characteristics:

- **Clear:** It should be easy to understand.
- **Complete:** It should contain all the necessary information.
- **Consistent:** It should not contradict other requirements.
- **Unambiguous:** It should have only one reasonable interpretation.
- **Feasible:** It should be possible to implement within available resources and technology.
- **Verifiable:** It should be possible to test whether the requirement has been fulfilled.
- **Traceable:** It should be possible to link it to its source, design, implementation, and tests.
- **Prioritized:** Its importance should be identified to support planning and decision-making.

### Example of Requirements

Consider a university management system. Its requirements might include allowing students to register for courses, enabling teachers to upload marks, allowing administrators to manage student records, and generating examination results.

These requirements describe the expected capabilities of the system and guide its development.

---

## 2. Software Requirements

### Definition

Software requirements are the documented statements of the capabilities, behavior, quality attributes, and constraints that a software system must satisfy. They specify the services the system must provide and the conditions under which those services must operate.

Software requirements are generally classified into functional requirements, non-functional requirements, and domain requirements.

### 2.1 Functional Requirements

Functional requirements describe the specific functions and services that a software system must provide. They explain what the system should do in response to user actions, inputs, or particular events.

Examples include:

- A banking application shall allow customers to transfer money between accounts.
- A library management system shall allow librarians to issue and return books.
- An online shopping system shall allow customers to add products to a shopping cart.
- A university system shall calculate students' examination results.
- A login system shall authenticate users using valid credentials.

Functional requirements are essential because they define the core operations of a software application.

### 2.2 Non-Functional Requirements

Non-functional requirements specify the quality attributes, performance expectations, and operational constraints of a system. Rather than describing a particular service, they describe how well the system must perform its functions.

Important categories include:

**1. Performance:** The system should respond to requests within an acceptable time.

Example: The application should display search results within two seconds under the specified normal load.

**2. Security:** The system must protect information against unauthorized access.

Example: Passwords must be stored using an appropriate secure password-hashing algorithm.

**3. Reliability:** The system should operate correctly and consistently over time.

Example: A payment system should prevent duplicate transactions when a request is retried.

**4. Usability:** The system should be easy for intended users to learn and operate.

Example: A new user should be able to complete registration by following clear instructions.

**5. Availability:** The system should remain accessible for the required proportion of time.

Example: An online service may be required to maintain 99.9% monthly availability.

**6. Maintainability:** The software should be easy to modify, debug, and extend.

**7. Scalability:** The system should be able to handle growth in users, data, or workload.

**8. Portability:** The software should be capable of operating in different environments when required.

Non-functional requirements should be measurable wherever possible so that developers and testers can determine whether they have been satisfied.

### 2.3 Domain Requirements

Domain requirements arise from the specific business area, industry, or field in which the software operates. They may include industry rules, laws, formulas, policies, and specialized terminology.

For example:

- Banking software must follow applicable financial regulations.
- Hospital software must follow relevant patient-data protection requirements.
- University software must apply the institution's examination and grading policies.
- Tax software must calculate taxes according to applicable tax laws.

Domain requirements are important because a system may function correctly from a technical perspective but still be unsuitable if it violates the rules of its intended environment.

### Difference Between Functional and Non-Functional Requirements

| Functional Requirements | Non-Functional Requirements |
|---|---|
| Describe what the system does. | Describe how well the system operates or the constraints under which it operates. |
| Focus on features and behavior. | Focus on quality attributes and restrictions. |
| Often tested through functional tests. | Often tested through performance, security, usability, and reliability tests. |
| Example: A user can reset a password. | Example: A password-reset request must be processed within three seconds under specified conditions. |

---

## 3. Software Requirements Engineering

### Definition

Software Requirements Engineering (SRE) is the systematic process of discovering, analyzing, documenting, validating, and managing the requirements of a software system. It ensures that the needs of customers, users, and other stakeholders are understood and translated into clear requirements that can guide software development.

Requirements engineering connects the problem faced by stakeholders with the technical solution developed by software engineers. It helps ensure that the team builds the correct system before investing significant time and resources in implementation.

### Objectives of Requirements Engineering

The main objectives are:

1. To identify the actual needs of stakeholders.
2. To understand the problem that the software must solve.
3. To define the system's scope and boundaries.
4. To identify functional and non-functional requirements.
5. To resolve conflicting stakeholder expectations.
6. To document requirements clearly and systematically.
7. To validate requirements before implementation.
8. To control requirement changes throughout the software life cycle.

### Main Activities of Requirements Engineering

**1. Feasibility Study**

A feasibility study determines whether the proposed system is practical and worthwhile. It examines technical feasibility, economic feasibility, operational feasibility, legal feasibility, and schedule feasibility.

For example, a company may investigate whether it has the technology, budget, and staff needed to develop an online payment platform.

**2. Requirements Elicitation**

Requirements elicitation involves collecting information about stakeholder needs, expectations, problems, and constraints.

Software engineers may conduct interviews, distribute questionnaires, observe users, study existing documents, or build prototypes.

**3. Requirements Analysis and Negotiation**

During analysis, collected requirements are examined for completeness, consistency, feasibility, and relevance. Conflicts are identified and discussed with stakeholders.

For example, a client may demand advanced security features while also requiring extremely low costs. The development team must discuss priorities and acceptable trade-offs.

**4. Requirements Specification**

Requirements specification is the process of documenting the agreed requirements in a structured form. The resulting document is commonly called the Software Requirements Specification (SRS).

An SRS may contain the system's purpose, scope, functional requirements, non-functional requirements, interfaces, constraints, assumptions, and acceptance criteria.

**5. Requirements Validation**

Requirements validation checks whether the documented requirements accurately represent stakeholder needs and are suitable for development.

Common validation methods include reviews, walkthroughs, prototyping, and the creation of test cases.

**6. Requirements Management**

Requirements management involves monitoring, organizing, tracing, and controlling requirements throughout the project. It includes recording changes, assessing their impact, maintaining versions, and ensuring that approved changes are reflected in the design, implementation, and testing activities.

### Importance of Software Requirements Engineering

Requirements engineering reduces the likelihood of developing software that does not meet user expectations. It improves communication, supports accurate planning, reduces costly rework, and provides a basis for software testing and acceptance.

For example, if an online banking system's requirements do not clearly define transaction authorization, developers may implement an insecure or incomplete payment process. Proper requirements engineering helps identify such issues before they become expensive defects.

### Relationship Between Requirements Engineering and Software Development

Requirements engineering is closely connected to every phase of the software development life cycle (SDLC). Requirements guide design, determine implementation priorities, provide test objectives, and support maintenance decisions.

Although requirements are often gathered at the beginning of a project, they may continue to evolve as stakeholders learn more about the problem and the system.

---

## 4. Software Requirements Elicitation Techniques

### Definition

Software requirements elicitation is the process of discovering, collecting, and understanding the requirements of a software system from stakeholders, existing systems, documents, business processes, and other relevant sources.

The purpose of elicitation is not simply to record what a client says. It is also to identify underlying problems, clarify expectations, discover hidden needs, and understand the constraints that influence the proposed system.

Different elicitation techniques are suitable for different situations. A software engineer may combine several techniques to obtain more complete and reliable information.

### 4.1 Interviews

Interviews are one of the most widely used requirements elicitation techniques. In this method, a requirements engineer asks stakeholders questions to understand their needs, current practices, problems, and expectations.

Interviews may be structured, semi-structured, or unstructured. Structured interviews follow predetermined questions, semi-structured interviews allow follow-up questions, and unstructured interviews encourage open discussion.

**Example:** A developer interviews university teachers to understand how they record attendance and calculate examination marks.

**Advantages:**
- Provides detailed information.
- Allows immediate clarification of unclear answers.
- Helps uncover problems that stakeholders may not have documented.
- Supports direct communication and feedback.

**Limitations:**
- Can require considerable time.
- Responses may be influenced by personal opinions or incomplete knowledge.
- Interview results depend on the interviewer's skill.

### 4.2 Questionnaires and Surveys

Questionnaires and surveys collect information from many stakeholders through a predefined set of written questions. Questions may be closed-ended, such as multiple-choice questions, or open-ended, allowing respondents to provide detailed explanations.

This technique is particularly useful when stakeholders are geographically distributed or when a large number of users must be consulted.

**Example:** A university distributes a survey to students to determine which features they want in a student portal.

**Advantages:**
- Reaches a large number of people.
- Can be inexpensive and quick to distribute.
- Makes it easier to compare responses.
- Allows respondents to answer at a convenient time.

**Limitations:**
- Questions may be misunderstood.
- Response rates may be low.
- Open-ended answers can be difficult to analyze.
- Provides fewer opportunities for immediate clarification.

### 4.3 Observation

Observation involves watching users perform their normal tasks to understand actual workflows, interactions, and difficulties. It helps requirements engineers identify needs that stakeholders may forget to mention during interviews.

Observation can be passive, in which the engineer watches without participating, or participatory, in which the engineer takes part in the activity.

**Example:** A requirements engineer observes a librarian issuing books to understand the steps involved in checking availability, recording borrowers, and managing returns.

**Advantages:**
- Reveals real working practices.
- Identifies hidden requirements and unnecessary steps.
- Helps discover differences between documented procedures and actual behavior.

**Limitations:**
- Users may change their behavior when observed.
- Some tasks occur too rarely to be observed easily.
- The technique may be time-consuming.

### 4.4 Workshops

Requirements workshops bring stakeholders, users, developers, managers, and other relevant participants together to discuss and establish requirements collaboratively.

Participants share ideas, clarify disagreements, prioritize needs, and work toward a common understanding. A facilitator usually guides the discussion and ensures that important issues receive attention.

**Example:** A workshop involving students, teachers, and administrators is organized to agree on the main features of a university management system.

**Advantages:**
- Encourages collaboration.
- Helps resolve conflicting requirements.
- Speeds up decision-making.
- Promotes shared understanding.

**Limitations:**
- Requires careful planning and facilitation.
- Dominant participants may influence the discussion.
- Scheduling multiple stakeholders can be difficult.

### 4.5 Brainstorming

Brainstorming is a creative technique in which participants generate as many ideas as possible about a problem or proposed system. During the initial idea-generation stage, criticism is generally postponed so that participants can suggest possibilities freely.

Afterward, the ideas are reviewed, grouped, evaluated, and prioritized.

**Example:** A development team brainstorms features for an online learning platform, including quizzes, progress tracking, discussion forums, assignment submission, and notifications.

**Advantages:**
- Generates a wide variety of ideas.
- Encourages creativity and innovation.
- Can reveal features that were not initially considered.
- Helps teams explore alternative solutions.

**Limitations:**
- Some ideas may be impractical.
- Participants may focus on quantity rather than quality.
- Group pressure can discourage quieter members.

### 4.6 Prototyping

Prototyping involves creating an early model or simplified version of a software system to help stakeholders understand and evaluate its proposed features and interfaces.

A prototype may be a paper sketch, clickable interface, or partially functional application. Stakeholders examine the prototype and provide feedback, which helps refine the requirements.

Prototypes may be throwaway prototypes, created to clarify requirements and then discarded, or evolutionary prototypes, which are gradually developed into the final system.

**Example:** Developers create a sample login page and student dashboard so that university staff can suggest changes before full development begins.

**Advantages:**
- Makes abstract requirements easier to understand.
- Encourages early user feedback.
- Helps discover missing or incorrect requirements.
- Improves understanding of interface and workflow expectations.

**Limitations:**
- Stakeholders may mistake a prototype for a finished product.
- Frequent changes can increase project costs.
- A visually attractive prototype may hide technical difficulties.

### 4.7 Document Analysis

Document analysis involves examining existing documents to identify relevant rules, processes, data, and requirements. These documents may include manuals, forms, reports, policies, contracts, business procedures, and records from existing systems.

It is especially useful when replacing an old system or developing software for an established organization.

**Example:** A software engineer studies existing university admission forms, examination policies, fee records, and attendance registers before designing a university management system.

**Advantages:**
- Provides information about existing procedures.
- Helps identify business rules and regulatory constraints.
- Can reveal requirements that stakeholders overlook.
- Provides evidence for comparing current and proposed systems.

**Limitations:**
- Documents may be outdated or incomplete.
- Written procedures may differ from actual practices.
- Some documents may contain conflicting information.

### 4.8 Focus Groups

A focus group is a guided discussion involving a small group of selected users or stakeholders who share their opinions, experiences, preferences, and expectations about a proposed system.

A moderator encourages discussion and ensures that participants address the relevant topics.

**Example:** A company invites a group of customers to discuss their expectations for a new mobile banking application.

**Advantages:**
- Collects diverse opinions in one session.
- Reveals user preferences and common concerns.
- Encourages participants to build on one another's ideas.
- Can help identify important usability and feature requirements.

**Limitations:**
- Some participants may dominate the discussion.
- Opinions may not represent the entire user population.
- Group influence may discourage honest or independent responses.

### 4.9 Joint Application Development (JAD)

Joint Application Development (JAD) is a structured, collaborative approach in which users, managers, developers, and other stakeholders participate in facilitated sessions to define system requirements and reach decisions.

Unlike a general workshop, JAD typically uses a more formal process, with defined roles, agendas, preparation, documentation, and decision-making responsibilities.

**Example:** A bank organizes a JAD session involving branch managers, customer-service representatives, security specialists, and developers to define the requirements for a customer account management system.

**Advantages:**
- Encourages direct cooperation between business and technical teams.
- Helps resolve disagreements efficiently.
- Reduces communication gaps.
- Can shorten the requirements-gathering process.

**Limitations:**
- Requires substantial preparation.
- Involvement of senior stakeholders may be expensive.
- Scheduling all relevant participants can be difficult.

### 4.10 Use Cases and Scenarios

Use cases describe how an actor, such as a user or another system, interacts with the software to achieve a particular goal. A use case commonly identifies the actor, preconditions, main flow, alternative flows, and expected outcome.

Scenarios are specific examples of interactions that illustrate how the system behaves in a particular situation. They may describe normal operation, exceptional situations, or error conditions.

**Example:** In an online shopping system, a use case describes how a customer searches for a product, adds it to the cart, enters delivery details, and completes a purchase.

**Advantages:**
- Describes requirements from the user's perspective.
- Clarifies interactions between users and the system.
- Helps identify normal and exceptional behavior.
- Provides a useful basis for test-case development.

**Limitations:**
- May not adequately describe non-functional requirements.
- Complex systems may require many use cases.
- Poorly written scenarios can leave important conditions unclear.

### 4.11 User Stories

User stories express requirements in a short, user-centered format. They are widely used in Agile software development to describe the value a feature should provide.

A common format is:

"As a [type of user], I want [a capability], so that [a benefit]."

A user story is often supported by acceptance criteria that define the conditions under which the feature will be considered complete.

**Example:** "As a student, I want to view my examination results online so that I can check my academic performance without visiting the administration office."

**Advantages:**
- Easy to understand.
- Focuses on user needs and business value.
- Supports prioritization and incremental development.
- Encourages discussion between users and developers.

**Limitations:**
- Short descriptions may omit technical details.
- Large or complex features may require several stories.
- Inadequate acceptance criteria can cause misunderstandings.

### 4.12 Interface Analysis

Interface analysis examines the interactions between the proposed software and its users, external systems, hardware, or other software components. It identifies the information exchanged, the actions supported, and the constraints governing these interactions.

It may include user-interface analysis, API analysis, and the study of existing integration points.

**Example:** A shopping application must communicate with a payment gateway. The requirements engineer studies the payment gateway's API to determine the required request fields, response formats, authentication procedures, and error handling.

**Advantages:**
- Identifies integration requirements early.
- Clarifies input and output formats.
- Helps discover dependencies on external systems.
- Supports consistent and usable interface design.

**Limitations:**
- External interface documentation may be incomplete.
- Third-party systems may change their APIs.
- Complex integrations may require specialized technical knowledge.

### 4.13 Reverse Engineering and Existing-System Analysis

Reverse engineering examines an existing software system to understand its structure, behavior, data, and functionality. Existing-system analysis is a broader examination of the current software, processes, and operational environment to determine which capabilities should be retained, improved, replaced, or removed.

This technique is particularly valuable when developing a replacement system and when original requirements documents are unavailable.

**Example:** A company analyzes its old inventory application to discover how stock quantities are calculated, how purchase records are stored, and how low-stock alerts are generated.

**Advantages:**
- Helps recover undocumented requirements.
- Identifies useful existing features and business rules.
- Reduces the risk of losing essential functionality during replacement.
- Helps understand technical dependencies.

**Limitations:**
- Legacy systems may be difficult to understand.
- Existing behavior may contain errors that should not be reproduced.
- Old code may not accurately reflect current business needs.

### 4.14 Delphi Technique

The Delphi technique is a structured method for obtaining expert opinions through multiple rounds of questionnaires. Experts generally respond independently, and an organizer summarizes the responses and shares the results with participants between rounds.

Experts can reconsider their judgments after reviewing the summarized feedback. The process continues until an appropriate level of agreement is reached or the planned rounds are completed.

Unlike ordinary group discussion, the Delphi technique usually emphasizes anonymity to reduce the influence of authority, personal relationships, and dominant personalities.

**Example:** A software organization consults security experts, architects, and project managers through several rounds to establish requirements for a secure cloud-based system.

**Advantages:**
- Collects opinions from experienced specialists.
- Reduces the effect of dominant participants.
- Can be conducted when experts are geographically separated.
- Helps prioritize requirements in uncertain or complex situations.

**Limitations:**
- Multiple rounds may take considerable time.
- Results depend on the expertise of the selected participants.
- Agreement among experts does not necessarily guarantee correctness.
- Poorly designed questions may produce misleading conclusions.

---

## Conclusion

Software requirements and requirements engineering are fundamental elements of successful software development. Requirements describe what a system must accomplish, while requirements engineering provides a systematic approach to discovering, analyzing, specifying, validating, and managing those requirements.

Requirements elicitation is particularly important because the quality of the final software depends heavily on how accurately stakeholder needs are understood. The fourteen techniques discussed in this assignment provide different ways to gather information, identify hidden needs, clarify expectations, and establish agreement among stakeholders.

No single elicitation technique is appropriate for every project. Interviews may provide detailed individual insights, questionnaires can reach large groups, observation reveals actual working practices, and prototyping helps users evaluate proposed solutions. By selecting and combining suitable techniques, software engineers can develop clearer requirements, reduce misunderstandings, control development costs, and improve the quality and usability of the final software product.