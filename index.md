# Professional Self Assessment
## Introduction: My Journey to Software Engineering
My academic career at Southern New Hampshire University has been more than just a series of classes; it has been a journey of understanding where my abilities and interests intersect with the discipline of computer science. Early in the program, I experimented with a few technological topics, but with time, I grew particularly interested in backend systems and database administration. Programming, databases, security, testing, and software design were all integrated into coherent learning experiences through my projects. My technical skills and critical thinking were enhanced by these obstacles. My development and the skills I now use in my professional work are reflected in my portfolio.

## Artifact Overview
All three enhancements to my ePortfolio are based on the Animal Shelter Dashboard from CS 340 (Advanced Programming Concepts). Each improvement aims to achieve a different program objective and showcases a different aspect of my computer science talents.

1. Software Design & Engineering Enhancement:
   1. Artifact: Animal Shelter Dashboard (CS 340)
   2. Focus: A single Jupyter Notebook was transformed into an MVC architecture, complete with strong logging, input                 validation, and secured credential storage.
   3. Skills Demonstrated: Professional documentation, separation of concerns, PEP 8 compliance, and modular design
   4. Course Outcome: #4 (well-founded techniques) and #5 (security mindset)
   
2. Algorithms & Data Structures Enhancement:
   1. Artifact: Animal Shelter Dashboard (CS 340)
   2. Focus: Integrated server-side pagination, B-tree indexing, and LRU caching, resulting in demonstrated Big O                    performance benefits.
   3. Skills Demonstrated: Analyzing algorithmic efficiency, adjusting performance, selecting key data structures, and                             refining database queries.
   4. Course Outcome: #3 (algorithmic principles) and #4 (well-founded techniques)
   
3. Database Enhancement:
   1. Artifact: Animal Shelter Dashboard (CS 340)
   2. Focus: Implemented schema validation, audit trails, and MongoDB aggregation pipelines.
   3. Skills Demonstrated: Data integrity enforcement, audit trail architecture, server-side analytics, and TTL indexes
   4. Course Outcome: #4 (well-founded techniques) and #5 (security mindset)

These three improvements design (Software Engineering), optimization (Algorithms), and security (Databases) showcase a whole software development lifecycle. They demonstrate my ability to create, enhance, and safeguard data-driven applications exactly the abilities needed for backend and data engineering positions. Through this well-organized portfolio, employers may view my real code, read my reflections, and comprehend my development as a developer.

## The Code Review Process

My upgrade approach began with a comprehensive code examination of the original Animal Shelter Dashboard, which is shown in a video linked to my ePortfolio. This tour reviews the application's current state, finds weaknesses in structure, performance, security, and documentation, and outlines the precise changes I want to make in each category. This careful review revealed technical debt that required attention: hardcoded secrets, closely linked logic, inadequate logging, expensive database queries, and missing input checks. The code review provided the foundation for all subsequent changes, showcasing my ability to objectively analyze current systems and plot intentional, significant improvement paths. The video is accessible at: https://youtu.be/rep2oc2STIE

## Software Engineering and Database Integration
My technical skill set was greatly influenced by my studies in database administration and software engineering. I learned how to create SQL queries, operate with relational databases, and comprehend how data integrity supports dependable information systems with DAD 220. I used those ideas while creating Python apps that communicated with MongoDB databases in later classes, especially CS 340. This process made it clear to me that developing functional code is only one aspect of successful software development; careful system design and effective data management are equally necessary. My understanding of database technologies has expanded because of working with both SQL and NoSQL settings, which has also improved my capacity to choose the best strategies for certain application requirements. My confidence in developing and maintaining cutting-edge data-driven systems has increased because of these experiences.

Working on the capstone project allowed me to see my own academic work as a legacy system in need of updating. When I returned to the Animal Shelter Dashboard from CS 340, I discovered severe technical debts: hardcoded authentication, complicated procedural code, insufficient error protections, and no logging architecture. I carefully redesigned the solution, converting the Jupyter Notebook to a structured MVC framework that separated data, display, and business logic. I added logging for debugging and monitoring, validated all input paths, and protected credentials by using environment variables via python.env. This approach was more than just a technological improvement; it paralleled the reality of maintaining and upgrading current systems, reinforcing behaviors that will serve me well in my professional future.

Recognizing the significance of strong data governance, I tackled the upgrade with two complementing protections. First, JSON Schema validation now enforces field requirements and data types, resulting in fewer inconsistent entries. Second, I implemented an audit logging collection that records every transaction, as well as user and timestamp information. This combination assures data integrity while allowing for post-hoc analysis and regulatory compliance a realistic illustration of the security attitude outlined in Course Outcome #5.

One of my most instructional problems was cache invalidation. Caching answers appeared to be efficient until database modifications stopped displaying on the dashboard. I restored consistency by selectively emptying the cache after each create, update, and delete. This showed me that performant system’s necessitate careful synchronization across storage levels, balancing speed with the unavoidable requirement for current data.

## Algorithms and Data Structures
The algorithms course completely changed the way I think about addressing problems. I learned how to use Big O analysis to balance implementation complexity and efficiency by studying fundamental structures like binary trees and linked lists. Using this foundation as a guide, I chose trees for ordered operations and hash maps for quick lookups when the capstone required architectural decisions. These choices, which were based on extensive theoretical research, transformed my work from functional to carefully designed.

In the Animal Shelter project, I discovered three algorithmic inefficiencies: putting all data into memory at once (O(n) memory), doing complete collection scans for each query (O(n) time), and continually running similar queries without caching. I approached each topic in a methodical manner.

I took a methodical approach to performance improvement. By retrieving only fifty records at a time instead of all ten thousand, pagination reduced memory use. By doing away with linear scans, strategic B-tree indexing sped up query processing. I also used LRU caching to store frequently occurring results, guaranteeing instantaneous responses to repeated queries. When combined, these modifications turned a resource-intensive operation into a responsive, effective data retrieval procedure.

I confirmed these theoretical improvements through empirical benchmarking, which involved measuring real execution times. The findings revealed meaningful gains: page loads with tailored queries exceeded full-record retrieval, and cache hits outperformed misses. These results demonstrate my ability to build and evaluate computational solutions using algorithmic reasoning while negotiating the inherent trade-offs of design choices, which directly addresses Course Outcome #3.

## Communication, Collaboration, and Security
Professional communication and cooperation evolved as key qualities during my academic career. Agile/Scrum frameworks in CS 250 provided formal possibilities for collaboration on incremental delivery, ranging from sprint planning to retrospective meetings. Crafting user stories and assessing complexity enabled me to strike a balance between technological feasibility and user benefit. Peer criticisms and project collaboration highlighted the need of clarity, receptiveness, and shared accountability. These experiences have equipped me to negotiate team dynamics and make good contributions in stakeholder-driven development contexts.

I discovered in CS 320 that quality assurance and testing are fundamentally cooperative activities. I developed my ability to write accurate bug reports and provide considerate, useful criticism when working with classmates. Every pull request for our team project, a web application created with GitHub, had to pass stringent code reviews. This real-world experience strengthened my conviction that joint responsibility and efficient communication are just as important as technical expertise. The capacity of a team to hold one another to high standards and freely share ideas is essential to successful development.

My experience in CS 320 demonstrated that software quality is a shared responsibility. Collaborating with peers on code reviews taught me how to make useful ideas and gracefully absorb external opinions. During a collaborative web application project, we used GitHub's pull request protocol to carefully examine each other's contributions. These exchanges demonstrated that technical achievement is dependent on psychological safety and shared ownership. I now approach development with the notion that transparent communication and shared accountability are essential for creating dependable, maintainable software.

To improve my defense as an engineer, the program constantly pushed me to think like an attacker. I worked on finding vulnerabilities and creating countermeasures in CS 405 and CS 340. This change is demonstrated by my improvements, which include transferring secrets to.env, verifying all inputs, and stopping risky deletions. Data reliability and forensic preparedness were further guaranteed by adding schema validation and audit logging. When taken as a whole, these modifications reflect not just technical improvements but also a long-term security perspective that is in line with Course Outcome #5.

## Conclusion: A Cohesive Portfolio
My ePortfolio is anchored by the Animal Shelter Dashboard improvements, each of which addresses a distinct aspect of my computer science skills. My secure credential management and MVC design were guided by software engineering concepts. B-tree indexing, pagination, and LRU caching were all implemented using algorithmic thought to improve speed. Meanwhile, database integrity was assured by schema validation and audit logging. These enhancements represent a path toward comprehensive, production-ready development capabilities.

The code review video demonstrates my abilities to evaluate existing systems and offer important enhancements with foresight. When paired with the subsequent refinements and narrative comments, these aspects represent my whole development arc, which progresses methodically from critical evaluation to careful design to executable solutions.

This portfolio offers concrete evidence of my development as a developer who strikes a balance between security, dependability, and performance elements crucial to backend programming. To assess my skills and level of professional development, potential employers can go at my work and reflections. After completing this program, I feel well-prepared and truly eager to create safe, scalable solutions that address actual industry issues.
