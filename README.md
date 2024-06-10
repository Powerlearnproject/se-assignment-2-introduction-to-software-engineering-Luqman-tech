[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244881&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:

Define Software Engineering:
What is software engineering, and how does it differ from traditional programming?
Software engineering is the systematic application of engineering principles, methods, and tools to the development and maintenance of software systems. It has evolved from traditional programming languages largely due to growing complexity of software systems and the need for structured development methodologies.  
Software Development Life Cycle (SDLC):
This refers to a sequence of processes that ensure delivery of high-quality software products that meet the users needs, adhere to budget and time constraints, and maintain capability with the evolving technology platforms. It is made up of several processes including: Requirements, Design, Implementetion, Testing, Deployment, and Maintenance. 
Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
Requirements: Involves collection and documentation of user needs and system requirements. 
Design: Creating quality and detailed design of the software architecture and user interface.
Implementation: Involves writing the actual code and building the software according to design specifications. 
Testing: This refers to conducting tests to ensure the software meets quality standards and functional requirements. 
Deployment: Refers to the release of the software to users or customers. 
Maintenance: Refers to providing ongoing support, updates, and enhancements to the software after deployment. 

Agile vs. Waterfall Models: 
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?
Agile methodology refers to a project management approach that involves breaking the project into phases and emphasizes continous collaboration and inprovement.Teams will follow a cycle of planning, execution, and evaluation. The team takes the lead on deciding how to the work will be done, self-organizing around granular tasks and assignments.(https://www.atlassian.com/agile#:~:text=What%20is%20the%20Agile%20methodology,READ%20ON%20BELOW)
Waterfall methodology where each process phase cascades downward sequentially through the software development cycle. It is a rigid approach that doesn't allow for flexibility. Teams can't progress until they resolve any problems. (https://www.atlassian.com/agile/project-management/waterfall-methodology#:~:text=What%20is%20the%20Waterfall%20methodology,%2C%20verification%2C%20and%20maintenance)

Requirements Engineering:
What is requirements engineering?
Requirement engineering is a systematic and strict approach to defining, creating, and verifying the requirements for a software system.
Describe the process and its importance in the software development lifecycle.
The process of requirement engineering involve the following steps: Feasibility Study, Requirements Elicitation, Requirements Specification, Requirements Verification and Validation, Requirements Management. The Feasibility study focuses on Technical feasibility, Operational Feasibility, and Economic Feasibility. Requirements Elicitation is related to the various ways used to gain knowledge about the project domain and requirements. Requirement Specification is used to produce formal software requirement models. Requirement Verification refers to the set of tasks that ensure the software correctly implements a specific function. Requirement validation refers to the different set of tasks that ensure the software built is traceable to customer requirements. Requirement management is the process of analyzing, documenting and controlling the communication with relevant stakeholders. (https://www.geeksforgeeks.org/software-engineering-requirements-engineering-process/)
The entire process of Requirement Engineering is essential in the software development cycle as it steers the whole process of software development in developing the appropriate product. 

Software Design Principles:
Explain the concept of modularity in software design.
Modularity in Software Design refers to dividing a system into separate modules or components with each module handling a specific functionality and operating independently. 
How does it improve maintainability and scalability of software systems?
Modularity ensures that you can easily adapt, extend, or place parts of the system without affecting others. 


Testing in Software Engineering:
Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing).
Unit Testing- This is the process through which you test the smallest functional unit of code.
Integration Testing- This is the process where components of the software are gradually integrated and then tested as a unified group.
System testing- This is the process of testing the entire system to ensure thatit meets the specified requirements.
Acceptance Testing- This is the process of testing that evaluates whether a system meets its business and user requirements. 
Why is testing crucial in software development?
Software testing is crucial as it identifies potential issues before they reach end-users, reducing the likelihood of software failures and the associated financial and reputational risks. 

Version Control Systems:
What are version control systems, and why are they important in software development? 
Verson control systems are software tools that help software teams manage changes to source code over time. Version control systems help software teams work faster and smarter. 
Give examples of popular version control systems and their features.
1. Git
-Distributed VCS: Each user has a complete local copy of the repository.
-Branching and Merging: Easy creation, merging, and deletion of branches.
-Staging Area: Allows staging changes before committing.
-Support for Non-linear Development: Manages complex branching and merging operations efficiently.
-Lightweight: Fast and efficient performance.
-Extensive Tooling: Support for various platforms and integration with numerous IDEs and services (e.g., GitHub, GitLab, Bitbucket).
-Open Source: Free and open-source software.

2. Subversion (SVN)
-Centralized VCS: Uses a central repository that all users commit to.
-Atomic Commits: Ensures that commits are atomic, so either all changes are applied, or none are.
-Directory Versioning: Tracks entire directories, not just files.
-Efficient Handling of Binary Files: Better support for binary files compared to some other systems.
-Comprehensive Metadata: Allows for the inclusion of metadata with each revision.
-Rich Set of Features: Includes branching, merging, and access control.

3. Mercurial
-Distributed VCS: Similar to Git, with each user having a complete copy of the repository.
-Ease of Use: Designed to be user-friendly and easy to learn.
-Scalability: Efficient handling of large projects.
-Atomic Commits: Ensures consistency and integrity of commits.
-Cross-Platform: Works on multiple operating systems.
-Extensible: Supports extensions to enhance functionality.

4. Perforce (Helix Core)
-Centralized VCS: Uses a central server for all versioned data.
-Scalability: Handles large codebases and many users efficiently.
-Granular Access Control: Fine-grained permissions and security features.
-Strong Binary File Support: Good performance with binary assets.
-Parallel Development: Support for branching and merging to facilitate parallel development.
-Integrations: Integrates with a variety of tools and platforms.

5. ClearCase
-Centralized VCS: Developed by IBM, used mainly in enterprise environments.
-UCM (Unified Change Management): Provides a framework for managing changes.
-Branching and Merging: Supports complex branching and merging strategies.
-Versioned Object Base (VOB): Stores files and directories in a repository.
-Dynamic Views: Allows users to see different configurations of the repository.

 6. TFS/Azure DevOps
-Centralized and Distributed VCS: Supports both centralized (TFVC) and distributed (Git) version control systems.
-Integration with DevOps Tools: Built-in support for CI/CD, work item tracking, and project management.
-Branching and Merging: Robust support for branching and merging.
-Access Control and Permissions: Comprehensive security and access control features.
-Extensibility: Integrates with a wide range of development tools and services.

Software Project Management:
Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
A software project manager serves as a liason between the development team and the stakeholders in a software project. They are responsible for communicating project status, managing changes and requesting additional resources to help complete the project. Some of the challenges they face include lack of accountability, communicatin, misalignment between goals and business objectives, poor planning, and unrealistic deadlines.  

Software Maintenance:
Define software maintenance and explain the different types of maintenance activities.
Software maintenance refers to the process of changing, modifying, and updating software to keep up with customer needs. 

1. Corrective Maintenance
Purpose:Fixing bugs and errors identified in the software after it has been released.
Description:
-Bug Fixing: Addressing issues reported by users or detected through testing, such as software crashes, incorrect outputs, or security vulnerabilities.
-Error Correction: Modifying the code to correct faults, including logic errors, computational errors, and issues in the user interface.

2. Adaptive Maintenance
Purpose: Updating the software to accommodate changes in the environment where it operates.
Description
-Platform Updates: Modifying the software to run on new versions of operating systems, databases, or hardware.
-Integration with Other Systems: Ensuring compatibility with updated or new external systems, APIs, or third-party services.
-Compliance Updates: Updating the software to comply with new regulations, standards, or business rules.

3. Perfective Maintenance
Purpose: Improving or enhancing the software to increase performance or maintainability.
Description:
-Performance Enhancements: Optimizing code to improve execution speed, memory usage, or overall system efficiency.
-Feature Enhancements: Adding new features or expanding existing functionality to meet user needs or market demands.
-Refactoring: Rewriting or restructuring code to improve readability, reduce complexity, or facilitate future maintenance.

4. Preventive Maintenance
Purpose: Anticipating and preventing potential future problems in the software.
Description:
-Code Reviews: Conducting thorough reviews to identify and rectify potential issues before they manifest.
-Documentation Updates: Maintaining and updating documentation to reflect current code and processes, aiding future maintenance efforts.
-Upgrading Dependencies: Regularly updating libraries, frameworks, and tools to their latest versions to avoid obsolescence and potential security risks.
-Implementing Best Practices: Ensuring that the codebase adheres to best practices and coding standards to reduce technical debt.

5. Emergency Maintenance
Purpose: Rapidly addressing unforeseen issues that require immediate attention.
Description:
-Critical Bug Fixes: Urgent fixes for critical bugs that cause system failures or severe user impact.
-Security Patches: Quickly patching vulnerabilities that pose security threats to the system.
-Disaster Recovery: Implementing measures to restore functionality after major disruptions, such as data breaches or system outages.

6. Evolutionary Maintenance
Purpose: Continuously improving the software to adapt to evolving user needs and technological advancements.
Description
-Incremental Updates: Regularly adding small, incremental changes to improve functionality and user experience.
-Long-Term Improvements: Planning and implementing long-term strategies for significant improvements and redesigns based on user feedback and technological trends.
-User Feedback Integration: Actively collecting and integrating feedback from users to guide the evolution of the software.
Why is maintenance an essential part of the software lifecycle?
Software maintenance is essential as it ensures that a software doesn't get obsolete through updates.

Ethical Considerations in Software Engineering:
What are some ethical issues that software engineers might face?
-Privacy and Data Protection: Entails managing user data responsibly and ensuring privacy is respected. Issues arising include: Data storage, Data Usage, Data collection.
-Security: Entails implementing robust security measures to protect systems and data.Issues arising include: Vulnerability management, Balancing Security and Usability.
Software reliability: Entails delivering reliable and hih-quality software. Issues arising include:Quality assurance, Honest Representation.
-Intellectual Property: Entails respecting intellectual property rights and avoiding plagairism.Issues arissing include: property Licensing, Original Work.
How can software engineers ensure they adhere to ethical standards in their work?
This can be achieved by ensuring they consider ethical implecations throughout the development process and staying informed about emerging ethical challenges.
