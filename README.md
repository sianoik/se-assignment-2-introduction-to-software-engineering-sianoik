[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15236089&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?
Software Development Life Cycle (SDLC):

software engineering is a discipline with a systematic approach to the development, operation, maintenance and retirement of software. this includes design, development, testing, deployment and maintenance of software products. software engineering differs from traditional programming in different ways.
 software engineering                                                     traditional programming
 -encompasses a whole process of lifecycle from inception                  -often limited to coding and specific problems
 -follows a structured and systematic process which includes               -can be more ad hoc on coding and immediate results
 planning to maintenance.
 - involves larger teams with different roles such as analysts, and project managers  -often performed by small teams with overlapping roles
 -adheres to industry standards and quality assurance                      -quality and standards are less formal based on programmers discretion

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Agile vs. Waterfall Models:
PHASES OF THE SOFTWARE DEVELOPMENT CYCLE:

a) PLANNING
--this phase involves the deermination of the projects feasiability, scope and objectives. it involves determining project risks and management. 
planning in waterfall is done at the beginning and the plan is followed strictly. Agile planning is done continously and interactive.
b) ANALYSIS OF REQUIREMENTS
This stage involves gathering requirements from stakeholders to understand what the software should involve. this also involves validation of the requirements. for waterfall this stage involves all requirements are collected and documented before the project begins hence making adaptation of changes difficult. Agile involves requirements are collected and gathered continously. this means each sprint involves a backlog of features and can change with user feedback.
c)DESIGN
this phase outlines how the software will be built.it involves creation of system  architecture and detailed specifications
Waterfall; the design is completed in one phase before the implementation starts.it includes both high level design and detailed such as modules and interfaces.
Agile: design is incremental and often happens in parallel with the development.design decisions are revisited and reffered in each iteration.
d)IMPLEMENTATION
this involves writing the actual code of the design specifications.this phase transforms design specifications into functioning products.
waterfall: coding can only start after the completion of design phase.each module is developed in sequence.
Agile: coding happens in short iterative sequence.coding and testing is often intertwined.
e) TESTING
this involves veryfying if the software meets requirements, and identying any defects. this will include user acceptance testing, system testing.
waterfall:testing is conducted after the implementation work is done.defects could lead to significant rework
Agile:each sprint involves testing and any defects are worked on. testing is continous.
f) DEPLOYMENT
this involves releasing the product to users. it involves user training and configurations.
Waterfall: deployment is carried out at the end of the development process
Agile: deployment is done after every iteration. new features are released to users regularly.
g) MAINTENANCE
this stage ensures the software is functional and relevant.involves fixing bugs and providing support.
Waterfall: maintenance occurs after the software has been deployed.involves scheduled updates and patches
Agile: maintenance is continous with frequent updates and improvements based on user feedback.

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Requirements Engineering:
AGILE VS WATERFALL
Waterfall Model:                                                    Agile Model:
-follows linear and sequencial model                                iterative process(involves cycles)
-each phase must be completed before the other begins               each cycle involves all phases of development
-less flexible and changes are hard to incorporate                  it is highly flexible and adaptive to changes
-risks are identified and mitigated at the very beginning           continous risk assessment and management
-emphasizes  comprehensive documentation                             emphasizes softwre over comprehensive documentation 

KEY DIFFERENCES
a) process overflow 
waterflow involves a sequencial  and linear process of overflow while agile involve an iterative and incremental process of overflow.
b) requirements 
Waterfall requires all documents gathered and documented at the beginning of the project while Agile requirements are continous and are refined throughout the process
c) customer Involvement
waterfall has limited customer involvement while agile has continous customer involment
d) flexibility and adaptability
waterfall is less flexible while Agile offers high flexibility and allows changes  for future incorporations
e) delivery
waterfall delivery of final project at the end, single delivery while Agile has continous frequent small deliveries.
f)Testing 
waterfall involves testing after implementation phase is complete while Agile involves continous and intergrated throughout the project

SCENARIOUS WHEN PREFFERED
WHEN TO USE WATERFALL:
- projects where requirements are known and are likely not to change
- projects which are dependent, each phase requires the other
- projects such as healthcare where the industry requires documentation
- short term projects which have no time for iteration

WHEN TO USE AGILE
- projects whose requirements are expected to change from time to time
- projects which require frequent customer feedback
- projects which prioritize innovation and adaptability over rigid planning
- projects where quick customer delivery is required.

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Software Design Principles:
requirement engineering is a phase of software deveopment which involves defining, documenting, and maintaining software requirements.this ensures that the software being developed meets the requirements of the stakeholder.
 IMPORTANCE OF REQUIREMENTS ENGINEERING
 - ensures clarity and understanding of the stakeholders needs and requirements.
 -brings about scope definitions 
 - provides a solid foundation for design of the system, architecture and development
 - helps identify potential issues early to save time and reduce costs
 - ensures software quality by ensuring it meets user requirements
 - increase stakeholder satisfaction by delivering a product which is in line to their requirements.

 PROCESS OF REQUIREMENTS ENGINEERING
 a) Requirement Elicitation
 gathering stakeholder requirements using various techniques such as surveys, interviews and use of questionnarres
 b) requirement Analysis
 analysing the required data to identify ambiguities, conflicts and inconsistencies
 c)Requirement specifications
 documenting the requirements in concise, and comprehensive manner.creating detailed requirements that serve as referrence
 d) Requirement Validation
 ensuring the documented requirements meet the stakeholder needs.
 e) Requirement management 
 managing changes to requirements throught the project lifecycle.ensuring the projects changes are recorded and documented, analysed and approved.

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?
Testing in Software Engineering:
modularity in software design refers to the practice of diving a software system into discrete, independet units known as modules. key characteristics of modularity include;
a) encapsulation -each module exposes only what is necessary for other modules and interact with it
b) cohesion - each module is designed to relating tasks or same tasks
c) coupling -modules interract with each other through their interfaces, minimizing interfaces
 HOW MODULARITY IMPROVES MAINTAINABILITY

 a) Isolation of changes
when a change is required it is often limited to a single module.this makes it easier to the impact of the changes.
 b) Easier debugging and testing
 independent modules can be tested separately, facilitates throurough debugging and testing within specific modules.
 c)Clear structure and organization
 the modular structure provides a clear organized layout of the system.enables new team members to be able to learn the codebase easier.
 d) Reusability
 modules which have been designed in generality and reusabillity in mind can be reusable in different parts of the application, this helps in developing time.
 e)parallel development
 different developers can work on different modlarities concurently. this gives a chance for better resource allocation.

            HOW MODULARITY IMPROVES SCALABILITY
modularity enhances scalability in software in systems by allowing individual modules to be scaled independently based on their specific load and performance requirements. this means if one part of the system experiences higher demand, then resources are allocated to the that specific module without affecting the entire system. In a web application the user authentication module can be scaled differently from the product catalog module in the case of high traffic.
In addition, modularity supports the integration of new features as separate modules, which can be developed deployed and scaled separately.


Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development? 
Version Control Systems:
UNIT TESTING:
this involves testing individual components to ensure they function correctly.perfommed by developers during coding. the tools used include pytest, junit 
INTEGRATION TESTING:
involves putting together or intergrating individual units and testing them as a group to ensure the components work together. tools used include selenium, JUnit, NUnit
System Testing: 
tests the complete integrated system to verify that it meets the specified requirements.it involves both functional and non-functional testing.this is used to validate end to end functionality and software performance.
ACCEPTANCE TESTING:
this testing involves determining if the system is ready for acceptance and deployment.it ussualy involves clients and end to end users.it includes operational acceptance testing .

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
version control systems are tools which help developers manage changes to source code with time. they help developers work together on a project without overwriting each others work. 
IMPORTANCE OF VERSION CONTROL SYSTEM
-collaboration; version control systems enable developers to work on the same  project but independently without conflicting. this facilitates teamwork and coordination 
-tracking changes; version tracking keeps record of the changes made on the codebase. allows developers to see the changes made, who made the changes and at what time the changes were made.
-Backup and store ;protects against data loss and makes it easier to restore previous states
-Reverting changes ; this allows developers to revert to previous versions of the code.one is able to rectify and undo mistakes made from previous code. 
-Audit and compliance; this will ensure that the development practices meets all requirements. 

 EXAMPLES OF POPULAR version control system
 a) GIT
 features of git include:
 -each developer has a computer copy of the repo
 -allows branching and merging
 -has a staging arear
 -github allows developers to collaborate and project management

 b) SUBVERSION
 -centralised version control. a single central repository is used for all operations
 - Atomic commits commits are committed to single invisible operations
 - Directory versioning tracks changes to directories as well as files

 c) Mercurial 
 like git it allows the developer to have a full copy of the repository
 designed to be easy to use and learn
 efficient in handling of large repositories and histories




Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

roles of a software project manager:
-project planning ; define the project scope, objectives and deliverables. outline project plans which outlines tasks, timelines and milestones
this includes creting gantt charts, resource allocations and project scheduling. 
-Resource management; allocate and manage resources to all the necessary tools. 
-providing team leadership
- quality control 
- Risk management
- stakeholder management
- project monitoring and control

challenges faced by software project managers;
- scope creep which lead to delays, increased costs and resorce overutilization
- time management ensures project is completed on time and delays can affect project delivery
- resource constraints, resources can be in terms personnel, tools or budgets.
- Risk management; unmanaged risks can lead to project failure 
- managing stakeholder expectations, misaligned expectations can lead to dissatisfaction and conflicts.

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

software maintenance is the process of modifying and updating software appications after deployment.this involves adapting to new environment, improving performance and ensuring the software continues to function correctly. 

TYPES OF MAINTENANCE ACTIVITIES
- Corrective maintenance; involves correcting bugs in the software after release. ensures the software is reliable and functions correctly
- Adaptive maintenance ; modifying the softwre to work in a new environment such as hardware, third party integration.
- Perfective maintenance; involves enhancing and improving the software to provide better performnce and add new features.
IMPORTANCE OF SOFTWARE LIFECYCLE
- Ensures longevity and reliability
- ensures adaptability to changes
- enhances performance and efficiency
- ensures user satisfaction
Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?
-security of software against malicious attacks
- respect for intellectual property
- privacy concerns
- openness on software ability and limitations
- avoiding algorithime biasness
- considering societal impact of the software.

HOW SOFTWARE ENGINEERS ENSURE ADHERENCE TO ETHICAL STANDARDS
- they ensure to follow proffessional ethics
- pay respect to intellectual property
- Ensure security is a priority to every development stage
- be clear and transparent about what the software is all about including the limitations
- ensure they have prioritised on the quality andreliability of the software
Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
open ai
Submit your completed assignment by [due date].
