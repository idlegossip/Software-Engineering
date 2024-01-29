# Software-Engineering 💻
![Software engineering picture](https://private-user-images.githubusercontent.com/65750784/300335664-ee9ac178-f8f0-4f48-9d07-b62241c39f34.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MDM2OTAsIm5iZiI6MTcwNjUwMzM5MCwicGF0aCI6Ii82NTc1MDc4NC8zMDAzMzU2NjQtZWU5YWMxNzgtZjhmMC00ZjQ4LTlkMDctYjYyMjQxYzM5ZjM0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDA0NDMxMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTEzNDE5YjBjMjcxMjFjNGZhNDQ0MWYyMjBmNWI0MTA0Nzk4ZTNhZjNlZGY0YjY5ZDc5Y2EzMTc5M2Q3NWUwYTgmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.3XC7IO0_oAh3weXW2v_-XiTRSUO8QChfrmz8tH60eEE)

Software Engineering is the process of  designing, developing, testing, and maintenance of software using a systematic and structured approach.
- [x] **Aims of SE :**  Builds High quality,reliable,maintainable software.
- [x] **Main Goals SE :** Improving quality,Budget, Time efficiency.
- [x] **Key principle of SE :** Modularity, Abstraction, Encapsulation, Reusability,Maintenance, Testing, Design pattern, Agile Methodologies , Continuous.
## **SDLC :** 💻 
Software development life cycle, is a methodology that defines the entire procedure of software development step-by-step.
  + The goal of the SDLC model is to deliver high-quality,maintainable software that meets the user’s requirements. 
  + SDLC stages are planning and requirement analysis,Defining requirements, Design, Development,Testing and Integration,Deployment and Maintenance.
#### 1. **Planning and requirement analysis :** 🟥
🔦 ***Planning —> define project scope —>objectives and goals —>Resource planning.***    
The first phase of the SDLC is the project planning stage where you are gathering business requirements from your client or stakeholders. This phase is when you evaluate the feasibility of creating the product, revenue potential, the cost of production, the needs of the end-users, etc.

+ ***Software product :*** 📘 A software product is a piece of software that is developed and maintained to be sold to users. Users pay for a license to use the software. Software Products are nothing but software systems delivered to the customer with the documentation that describes how to install and use the system.

+ ***Requirement Analysis :*** 📘 Software requirement means requirement that is needed by software to increase quality of software product. These requirements are generally a type of expectation of the user from a software product that is important and needs to be fulfilled by software.
Clarifies the required features and overall vision of a new product. Clarifies stakeholder expectations for that product. Prevents conflict and communication gaps during development and testing.

- [x] ***Steps of the requirement analysis :*** 🟠 
1. ***Draw context Diagram :*** It identifies the entities outside the proposed system that interact with the system. 
1. ***Development of the Prototype :*** One effective way to find out what the customer wants is to construct a prototype, something that looks and preferably acts as part of the system they say they want.We can use their feedback to modify the prototype until the customer is satisfied continuously.
1. ***Model the requirements:*** This process usually consists of various graphical representations of the functions, data entities, external entities, and the relationships between them.Such models include the Data Flow diagram, Entity-Relationship diagram, Data Dictionaries, State-transition diagrams, etc.
1. ***Finalize the requirement :*** After modeling the requirements, we will have a better understanding of the system behavior. The inconsistencies and ambiguities have been identified and corrected.

+ ***Project Scope :*** 📘 The project scope is the total amount of work that needs to be done to complete a project. To define it, project managers must break down the project into the tasks and deliverables that’ll be executed to meet goals and stakeholder requirements and deliver the project successfully.

### **Software Requirements Specification(SRS):** 📙
The production of the requirements stage of the software development process is SRS(also called a requirements document). This report lays a foundation for software engineering activities and is constructed when entire requirements are elicited and analyzed. SRS is a formal report, which acts as a representation of software that enables the customers to review whether it (SRS) is according to their requirements.

- [x] ***Following are the features of a good SRS document:*** 🟠
+ ***Correctness :*** 📘 SRS is said to be perfect if it covers all the needs that are truly expected from the system.
+ ***Completeness:*** 📘 The SRS is complete if, and only if, it includes the following elements:
   1. All essential requirements, whether relating to functionality, performance, design, constraints, attributes, or external interfaces.
   1. Definition of their responses of the software to all realizable classes of input data in all available categories of situations.
   1. Full labels and references to all figures, tables, and diagrams in the SRS and definitions of all terms and units of measure.
+ ***Consistency :*** 📘  The SRS is consistent if, and only if, no subset of individual requirements described in its conflict. There are three types of possible conflict in the SRS:
  1. The specified characteristics of real-world objects may conflict. For example,
        - The format of an output report may be described in one requirement as tabular but in another as textual.
        - One condition may state that all lights shall be green while another states that all lights shall be blue.
   1. There may be a reasonable or temporal conflict between the two specified actions. For example,
        - One requirement may determine that the program will add two inputs, and another may determine that the program will multiply them.
        - One condition may state that "A" must always follow "B," while another requires that "A and B" co-occurs.
   1. Two or more requirements may define the same real-world object but use different terms for that object. For example, a program's request for user input may be called a "prompt" in one requirement and a "cue" in another. The use of standard terminology and descriptions promotes consistency.
+ ***Unambiguousness :*** 📘  SRS is unambiguous when every fixed requirement has only one interpretation. This suggests that each element is uniquely interpreted. In case there is a method used with multiple definitions, the requirements report should determine the implications in the SRS so that it is clear and simple to understand.
+ ***Ranking for importance and stability:*** 📘 The SRS is ranked for importance and stability if each requirement in it has an identifier to indicate either the significance or stability of that particular requirement.

#### 2. **Defining Requirements :** 🟥 
🔦 ***Defining —> Functional requirement—>Technical requirement —>Requirements reviewed and approved.***
In this stage, all the requirements for the target software are specified. These requirements get approval from customers, market analysts, and stakeholders. This is fulfilled by utilizing SRS (Software Requirement Specification). This is a sort of document that specifies all those things that need to be defined and created during the entire project cycle. 
- ***Functional Requirements :*** 📘 Functional requirements are product features or functions that developers must implement to enable users to accomplish their tasks. So it's essential to make them clear both for the development team and the stakeholders. Generally, functional requirements describe system behavior under specific conditions.
- ***Technical requirements :*** 📘 Technical requirements are the technical issues that must be considered to successfully complete a project. These can include aspects such as performance, reliability, and availability.
> [!note]
> In software projects, technical requirements typically refer to how the software is built, for example: programming language,operating system (OS),standards.

#### 3. **Designing Architecture :** 🟥 
🔦 ***Design —> HLD —> LLD***   

SRS is a reference for software designers to come up with the best architecture for the software. Hence, with the requirements defined in SRS, multiple designs for the product architecture are present in the Design Document Specification (DDS). This DDS is assessed by market analysts and stakeholders. After evaluating all the possible factors, the most practical and logical design is chosen for development.

- ***High Level Design :*** 📘 HLD is a general system design. In software development, HLD is the process of creating an abstract representation of a software system before detailing the low-level design.
  + HLD :> Capacity estimation, HTTP methods, web sockets, pooling, server-sent events, Filtering and logging, Rate limiting, Resiliency, paging and filtering, Logging.
  Network Diagram
  1. Architectural Diagrams
  1. Data Flow and use cases
  1. Brief mention of all the platforms, systems, services, and processes the product would depend on.
  1. Brief description of relationships between the modules and system features.

- ***Low Level Design :*** 📘 Low-level design is a component level design process that follows a step-by-step refinement process.It involves detailed design and logic of the modules.It’s where the actual software components are designed, and it’s closer to the actual coding.
  
🔦 ***OOP —> Process of analyzing and design —> Design pattern —> UML —> SOLID principle***
#### 4. **Developing product :** 🟥 
🔦 ***Development —> Coding standard —> Scalable code —> Version control —> code review.***

At this stage, the fundamental development of the product starts. For this, developers use a specific programming code as per the design in the DDS.
- ***Scalable code :*** 📘
Scalability can be judged on how many lines of code you need to modify to make the code implement the new requirement.
Scalable code is code that can handle increasing amounts of data, traffic, or complexity without compromising performance, reliability, or maintainability. Writing scalable code is a crucial skill for product engineers, especially in fast-growing or dynamic environments.
  1. Optimize data structure.
  1. Efficient algorithm selection.
  1. Modularisation and code reusability.
  1. Caching and memoization.
  1. Avoiding global variables.
  1. Asynchronous programming.
  1. Handling errors gracefully.
#### **5. Product  testing and Integration:** 🟥 
🔦 ***System Testing —> Manual Testing —> automated Testing***

After the development of the product, testing of the software is necessary to ensure its smooth execution. Although, minimal testing is conducted at every stage of SDLC. Therefore, at this stage, all the probable flaws are tracked, fixed, and retested. This ensures that the product confronts the quality requirements of SRS. 
- ***Documentation, Training, and Support:*** 📘 Software documentation is an essential part of the software development life cycle. A well-written document acts as a tool and means to the information repository necessary to know about software processes, functions, and maintenance. Documentation also provides information about how to use the product.
- ***Manual Testing :*** 📘 Manual is a process in which test cases are executed manually without the help of any automated tool.
- ***Automated Testing :*** 📘 Automation is a technique that uses tools to write scripts and execute test cases. example : unit testing,Integration Testing, Regression Testing, performance testing, Security testing.

#### **6. Deployment and Maintenance:** 🟥
🔦 ***Deployment and maintenance —> Release Planning —> Deployment automation —> Maintenance —> Feedback.***

After detailed testing, the conclusive product is released in phases as per the organization’s strategy. Then it is tested in a real industrial environment. It is important to ensure its smooth performance. If it performs well, the organization sends out the product as a whole. After retrieving beneficial feedback, the company releases it as it is or with auxiliary improvements to make it further helpful for the customers. However, this alone is not enough. 

## **SDLC MODEL :** 💻
 #### 1. **WaterFall Model :** 🟥
 ![](https://private-user-images.githubusercontent.com/65750784/300380572-1fc7279a-dd1f-4fd3-a361-5a9728ee5fbd.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MTY3MzAsIm5iZiI6MTcwNjUxNjQzMCwicGF0aCI6Ii82NTc1MDc4NC8zMDAzODA1NzItMWZjNzI3OWEtZGQxZi00ZmQzLWEzNjEtNWE5NzI4ZWU1ZmJkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDA4MjAzMFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTk2ZWU2N2FjN2UzNmNkZGVjZGMwMDdkMTVlN2E5NDZmMDNmYWE4NDg5OWU3YjQzNjA0YmEzMDZmMzg4N2U2OTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.1MvbcLWAhC9InBBukRDL92xXDRw9v-Os-ev55Euj8bY)

It is also referred to as a linear-sequential life cycle model.In a waterfall model, each phase must be completed before the next phase can begin and there is no overlapping in the phases.   
🔦 ***Requirement analysis ---> System Design ---> Implementation ---> Testing ---> Deployment ---> Maintenance***

- [x] **Application:** 🟠
- Requirements are very well documented, clear and fixed.
- Product definition is stable.There are no ambiguous requirements.
- The project is short.
- The situation is calm.
- Where the tools and technology used is consistent and is not changing.
- When resources are well prepared and are available to use.
- People understand technology.
- There are no unclear prerequisites.
- there are many resources with the necessary knowledge readily available.

- [x] **Advantages :** 🟠
- A schedule can be set with deadlines for each stage of development and a product can proceed through the development process model phases one by one.
- Simple and easy to understand and use.
- Easy to manage due to the rigidity of the model. Each phase has specific deliverables and a review process.
- Phases are processed and completed one at a time.
- Works well for smaller projects where requirements are very well understood.
- Clearly defined stages.
- Well understood milestones.
- Easy to arrange tasks.
- Process and results are well documented.    The requirements are simple and explicitly declared; they remain unchanged during the entire project development.
- The start and end points for each phase are fixed, which makes it easy to cover progress.
- The release date for the complete product, as well as its final cost, can be determined before development.   

- [x] **Disadvantages :** 🟠
1. The disadvantage of waterfall development is that it does not allow much reflection or revision. Once an application is in the testing stage, it is very difficult to go back and change something that was not well-documented or thought upon in the concept stage.   
1.  No working software is produced until late during the life cycle.
2.  High amounts of risk and uncertainty.
3.  Not a good model for complex and object-oriented projects.
4.  Poor model for long and ongoing projects.
5.  Not suitable for the projects where requirements are at a moderate to high risk of changing. So, risk and uncertainty is high with this process model.
6.  It is difficult to measure progress within stages.
7.  Cannot accommodate changing requirements.
8.  Adjusting scope during the life cycle can end a project.
9.  Integration is done as a "big-bang. at the very end, which doesn't allow identifying any technological or business bottleneck or challenges early.
            

#### 2. **Iterative Waterfall Model:** 🟥  
![](https://private-user-images.githubusercontent.com/65750784/300389315-4cac19c3-9202-42f6-970a-4332bd1059a5.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MTgwNDMsIm5iZiI6MTcwNjUxNzc0MywicGF0aCI6Ii82NTc1MDc4NC8zMDAzODkzMTUtNGNhYzE5YzMtOTIwMi00MmY2LTk3MGEtNDMzMmJkMTA1OWE1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDA4NDIyM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWMwM2M5YTIzMjA1YjEwOWZiNzZmMjgwZDQ3ZTRjNDRkNTVlZTllNDljN2ZkMzE1NzNmMTBhNDAxZDRlZTJkYWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.hLhvx6YwmKLzb8J4ScxQzfh_FVJoVjlhZYiKcR6B_u8)   
🔦 ***Requirement---> Analysis --->Design ---> Testing ---> Implementation ---> Review --->  
Design ---> Implementation ---> Review --->  
Design ---> Testing ---> Implementation ---> Review ---> Deployment ---> Maintenance.***

The Iterative Waterfall Model is a software development approach that combines the sequential steps of the traditional Waterfall Model with the flexibility of iterative design. It allows for improvements and changes to be made at each stage of the development process, instead of waiting until the end of the project. 

- [x] ***Main Difference with classical waterfall model :*** 🟠
The iterative waterfall model provides feedback paths from every phase to its preceding phases, which is the main difference from the classical waterfall model. 
- When errors are detected at some later phase, these feedback paths allow for correcting errors committed by programmers during some phase.
- The feedback paths allow the phase to be reworked in which errors are committed and these changes are reflected in the later phases.
- But, there is no feedback path to the stage – feasibility study, because once a project has been taken, one does not give up the project easily.
- It is good to detect errors in the same phase in which they are committed.
- It reduces the effort and time required to correct the errors.
- A real-life example could be building a new website for a small busines

- [x] **Application of Iterative Waterfall Model :** 🟠 
- When requirements are defined clearly and easy to understand.
- When the software application is large.
- When there is a requirement of changes in future.
- [x] ***Advantages :*** 🟠 
- Some working functionality can be developed quickly and early in the life cycle.
- Results are obtained early and periodically.
- Parallel development can be planned.
- Progress can be measured.
- Less costly to change the scope/requirements.
- Testing and debugging during smaller iterations is easy.
- Risks are identified and resolved during iteration; and each iteration is an easily managed milestone.
- Easier to manage risk - High risk part is done first.
- With every increment, an operational product is delivered.
- Issues, challenges and risks identified from each increment can be utilized/applied to the next increment.
- Risk analysis is better.
- It supports changing requirements.
- Initial Operating time is less.
- Better suited for large and mission-critical projects.
- During the life cycle, software is produced early which facilitates customer evaluation and feedback.
- [x] ***Disadvantages :*** : 🟠
- More resources may be required.
- Although the cost of change is lesser, it is not very suitable for changing requirements.
- More management attention is required.
- System architecture or design issues may arise because not all requirements are gathered in the beginning of the entire life cycle.
- Defining increments may require definition of the complete system.
- Not suitable for smaller projects.
- Management complexity is more.
- End of the project may not be known which is a risk.
- Highly skilled resources are required for risk analysis.
- Project progress is highly dependent upon the risk analysis phase.

#### **3. Spiral Model:** 🟥
![](https://private-user-images.githubusercontent.com/65750784/300391233-0c24af7c-b4cf-4e5c-9c52-b2d10588386e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MTg0MzYsIm5iZiI6MTcwNjUxODEzNiwicGF0aCI6Ii82NTc1MDc4NC8zMDAzOTEyMzMtMGMyNGFmN2MtYjRjZi00ZTVjLTljNTItYjJkMTA1ODgzODZlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDA4NDg1NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTU0MWVlM2U0Y2Q1YzA2Y2FkYzgyZDY4ZjE3Y2E4NzA0NzRkNjIyZjhmYWVlNzE0NDBmOTIyMTM4MGQ2OGQyZmQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.z-H5YdGPBT7xGhiad1dgo3k3cjGbLBWNGGm2BZNQTr8)
![](https://private-user-images.githubusercontent.com/65750784/300391250-76dc3832-3ebb-4bf9-ba02-59d549da4dcb.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MTg0MzYsIm5iZiI6MTcwNjUxODEzNiwicGF0aCI6Ii82NTc1MDc4NC8zMDAzOTEyNTAtNzZkYzM4MzItM2ViYi00YmY5LWJhMDItNTlkNTQ5ZGE0ZGNiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDA4NDg1NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTlkZTMzMWU2ZDAzYzEwMmIxZmQzOWQ1NTU5MmYzMjk3NzE3MTQwZmQ4YWNjYWExMWM4ZmViOTAyYjBjOGRmZDUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.XWbY1HUHffgNmCDUTVH6NDbSgcxTuodo8d72V2oCqQ4)   
The spiral model is a systems development lifecycle (SDLC) method used for risk management that combines the iterative development process model with elements of the Waterfall model. The spiral model is used by software engineers and is favored for large, expensive and complicated projects.When viewed as a diagram, the spiral model looks like a coil with many loops. The number of loops varies based on each project and is often designated by the project manager. Each loop of the spiral is a phase in the software development process.
The spiral model enables gradual releases and refinement of a product through each phase of the spiral as well as the ability to build prototypes at each phase. The most important feature of the model is its ability to manage unknown risks after the project has commenced; creating a prototype makes this feasible.

- [x] **Uses of the spiral model:** 🟠

As mentioned before, the spiral model is best used in large, expensive and complicated projects. Other uses include:
- projects in which frequent releases are necessary.
- projects in which changes may be required at any time.
- long term projects that are not feasible due to altered economic priorities.
- medium to high risk projects.
- projects in which cost and risk analysis is important.
- projects that would benefit from the creation of a prototype.
- projects with unclear or complex requirements.

- [x] ***Spiral model phases:*** 🟠

When looking at a diagram of a spiral model, the radius of the spiral represents the cost of the project and the angular degree represents the progress made in the current phase. Each phase begins with a goal for the design and ends when the developer or client reviews the progress.
***Every phase can be broken into four quadrants:***
1. identifying and understanding requirements.
2. performing risk analysis.
3. building the prototype and
4. evaluation of the software's performance.
   
- **Phases begin in the quadrant dedicated to the identification and understanding of requirements.**  The overall goal of the phase should be determined and all objectives should be elaborated and analyzed. It is important to also identify alternative solutions in case the attempted version fails to perform.
- Next, **risk analysis** should be performed on all possible solutions in order to find any faults or vulnerabilities -- such as running over the budget or areas within the software that could be open to cyber attacks. Each risk should then be resolved using the most efficient strategy.
- **In the next quadrant, the prototype is built and tested.** This step includes: architectural design, design of modules, physical product design and the final design. It takes the proposal that has been created in the first two quadrants and turns it into software that can be utilized.
- **Finally, in the fourth quadrant, the test results of the newest version are evaluated.** This analysis allows programmers to stop and understand what worked and didn’t work before progressing with a new build. At the end of this quadrant, planning for the next phase begins and the cycle repeats. At the end of the whole spiral, the software is finally deployed in its respective market.

- [x] ***Steps of the spiral model:*** 🟠

While the phases are broken down into quadrants, each quadrant can be further broken down into the steps that occur within each one. The steps in the spiral model can be generalized as follows:
- The new system requirements are defined in as much detail as possible. This usually involves interviewing a number of users representing all the external or internal users and other aspects of the existing system.
- A preliminary design is created for the new system.
- A first prototype of the new system is constructed from the preliminary design. This is usually a scaled-down system, and represents an approximation of the characteristics of the final product.
- A second prototype is evolved by a fourfold procedure:
   - (1) evaluating the first prototype in terms of its strengths, weaknesses, and risks;
   - (2) defining the requirements of the second prototype;
   - (3) planning and designing the second prototype;
   - (4) constructing and testing the second prototype.
- The entire project can be aborted if the risk is deemed too great. Risk factors might involve development cost overruns, operating-cost miscalculation and other factors that could result in a less-than-satisfactory final product.
- The existing prototype is evaluated in the same manner as was the previous prototype, and, if necessary, another prototype is developed from it according to the fourfold procedure outlined above.
- The preceding steps are iterated until the customer is satisfied that the refined prototype represents the final product desired.
- The final system is constructed, based on the refined prototype.
- The final system is thoroughly evaluated and tested. Routine maintenance is carried out on a continuing basis to prevent large-scale failures and to minimize downtime.

- [x] ***Benefits of the spiral model:*** 🟠
      
As mentioned before, the spiral model is a great option for large, complex projects. The progressive nature of the model allows developers to break a big project into smaller pieces and tackle one feature at a time, ensuring nothing is missed. Furthermore, since the prototype building is done progressively, the cost estimation of the whole project can sometimes be easier.  
Other benefits of the spiral model include:
- [ ] ***Flexibility -*** Changes made to the requirements after development has started can be easily adopted and incorporated.
- [ ] ***Risk handling -*** The spiral model involves risk analysis and handling in every phase, improving security and the chances of avoiding attacks and breakages. The iterative development process also facilitates risk management.
- [ ] ***Customer satisfaction -*** The spiral model facilitates customer feedback. If the software is being designed for a customer, then the customer will be able to see and evaluate their product in every phase. This allows them to voice dissatisfactions or make changes before the product is fully built, saving the development team time and money.

- [x] ***Limitations of the spiral model:*** 🟠
      
- [ ] ***High cost -*** The spiral model is expensive and, therefore, is not suitable for small projects.
- [ ] ***Dependence on risk analysis -*** Since successful completion of the project depends on effective risk handling, then it is necessary for involved personnel to have expertise in risk assessment.
- [ ] ***Complexity -*** The spiral model is more complex than other SDLC options. For it to operate efficiently, protocols must be followed closely. Furthermore, there is increased documentation since the model involves intermediate phases.
- [ ] ***Hard to manage time -*** Going into the project, the number of required phases is often unknown, making time management almost impossible. Therefore, there is always a risk for falling behind schedule or going over budget.


> [!note]
> The Spiral Model is called a Meta-Model because it includes all other SDLC models and it main benefit is the risk management.

#### **Incremental Model :** 🟥  
[very good resources](https://thestudygenius.com/incremental-model/) 

![](https://private-user-images.githubusercontent.com/65750784/300437641-daf09ede-3e20-430c-9659-9839c4066aea.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MjgyNTgsIm5iZiI6MTcwNjUyNzk1OCwicGF0aCI6Ii82NTc1MDc4NC8zMDA0Mzc2NDEtZGFmMDllZGUtM2UyMC00MzBjLTk2NTktOTgzOWM0MDY2YWVhLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDExMzIzOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTA5MGEyNTFhZjFkMjY1YjQ4NGFlY2JmMGFlNTYyMzQ2N2JhM2NkZGRiODg1YjQyMDk0ZjljNDg4YTNhNzczOWQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.eaEpyxxZWt6qP-r73_XzCCkrd4eoXQxwSWVEil_nRK8)   
Incremental Model is a process of software development where requirements are divided into multiple standalone modules of the software development cycle. In this model, each module goes through the requirements, design, implementation and testing phases. Every subsequent release of the module adds function to the previous release. The process continues until the complete system is achieved.

![](https://private-user-images.githubusercontent.com/65750784/300437628-20ec4e25-7924-4d3d-b48f-dfd1dcbc9f0e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDY1MjgyNTgsIm5iZiI6MTcwNjUyNzk1OCwicGF0aCI6Ii82NTc1MDc4NC8zMDA0Mzc2MjgtMjBlYzRlMjUtNzkyNC00ZDNkLWI0OGYtZGZkMWRjYmM5ZjBlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDAxMjklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwMTI5VDExMzIzOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM2ZWE2MjYxNTNjNjgxZDJiNjdmZjRlOTQyNzQyYWQxMjNhYThmYTBkYzU3ODNlZTkyYTY5ZDQwZmI3YTdlYzkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.3DDB7GqVBNrWxwqeQ3TTzEPWaXjeeu_iLooBfOExrE0)

- [x] ***Life Cycle Activities:*** 🟠  
Requirements of Software are first broken down into several modules that can be incrementally constructed and delivered.

- At any time, the plan is made just for the next increment and not for any kind of long-term plan. Therefore, it is easier to modify the version as per the need of the customer.
- The Development Team first undertakes to develop core features (these do not need services from other features) of the system.
- Once the core features are fully developed, then these are refined to increase levels of capabilities by adding new functions in Successive versions.
- Each incremental version is usually developed using an iterative waterfall model of development.
- As each successive version of the software is constructed and delivered, now the feedback of the Customer is to be taken and these were then incorporated into the next version.
- Each version of the software has more additional features than the previous ones.
- After Requirements gathering and specification, requirements are then split into several different versions starting with version 1, in each successive increment, the next version is constructed and then deployed at the customer site.
- After the last version (version n), it is now deployed at the client site.

- [x] ***Types of Incremental Model:*** 🟠
1. ***Staged Delivery Model:*** Construction of only one part of the project at a time.
2. ***Parallel Development Model:*** Different subsystems are developed at the same time. It can decrease the calendar time needed for the development, i.e. TTM (Time to Market) if enough resources are available. 

- [x] ***When to use Incremental Process Model:*** 🟠
1. Funding Schedule, Risk, Program Complexity, or need for early realization of benefits.
2. When Requirements are known up-front.
3. When Projects have lengthy development schedules.
4. Projects with new Technology.
5. Error Reduction (core modules are used by the customer from the beginning of the phase and then these are tested thoroughly).
6. Uses divide and conquer for a breakdown of tasks.
7. Lowers initial delivery cost.
8. Incremental Resource Deployment.
9. Requires good planning and design.
10. The total cost is not lower.
11. Well-defined module interfaces are required.


- [x] ***Characteristics of Incremental Process Model :*** 🟠
1. System development is divided into several smaller projects.
2. To create a final complete system, partial systems are constructed one after the other.
3. Priority requirements are addressed first.
4. The requirements for that increment are frozen once they are created.

- [x] ***Advantages of Incremental Process Model:***
1. Prepares the software fast.
2. Clients have a clear idea of the project.
3. Changes are easy to implement.
4. Provides risk handling support, because of its iterations.
5. Adjusting the criteria and scope is flexible and less costly.
6. Comparing this model to others, it is less expensive.
7. The identification of errors is simple.
- [x] ***Disadvantages of Incremental Process Model:*** 🟠
1. A good team and proper planned execution are required.
2. Because of its continuous iterations the cost increases.
3. Issues may arise from the system design if all needs are not gathered upfront throughout the duration of the program lifecycle.
4. Every iteration step is distinct and does not flow into the next.
5. It takes a lot of time and effort to fix an issue in one unit if it needs to be corrected in all the units.




          
        


