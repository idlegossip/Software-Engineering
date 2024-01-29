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
 
 It is also referred to as a linear-sequential life cycle model.In a waterfall model, each phase must be completed before the next phase can begin and there is no overlapping in the phases.   
🔦 ***Requirement analysis ---> System Design ---> Implementation ---> Testing ---> Deployment ---> Maintenance**

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
            
        
          
        


