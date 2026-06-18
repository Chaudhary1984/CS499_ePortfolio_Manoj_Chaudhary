# Professional Self Assessment
## CS 499 Capstone - Southern New Hampshire University

## Introduction ##
My journey through the Computer Science program at Southern New Hampshire University has been transformative, shaping me from a general software enthusiast into a focused backend and data engineer. This self-assessment serves as an introduction to my skills, experiences, and career aspirations, demonstrating how my coursework and ePortfolio enhancements have prepared me for a professional career in computer science.

## Coursework and ePortfolio Impact ##
Completing my coursework throughout the program and developing this ePortfolio has helped me showcase my strengths in several ways. First, the program's curriculum provided a strong foundation in programming logic, object-oriented design, data structures, algorithms, and database management. I gained hands-on experience with Python, Java, MongoDB, SQL, and full-stack development through courses like CS 340 (Advanced Programming Concepts), CS 260 (Data Structures and Algorithms), and DAD 220 (Introduction to SQL).

Second, the ePortfolio development process forced me to revisit and critically evaluate my previous work. I identified weaknesses in my original CS 340 project—hardcoded credentials, lack of modularity, missing documentation, and inefficient algorithms—and systematically addressed each issue. This reflective practice taught me to view my code through an employer's lens, asking "Does this demonstrate professional-quality work?"

Third, the capstone project helped shape my professional goals and values. I discovered that I am most engaged when building scalable, data-driven applications that solve real problems. I also learned to value code quality, documentation, security, and user experience as essential components of professional software development.

## Collaboration in Team Environments ##
Throughout the program, I developed strategies for building collaborative environments. In CS 250 (Software Development Lifecycle), I participated in Agile/Scrum simulations, attending daily stand-ups, sprint planning, and retrospectives. I learned to write user stories, estimate story points, and collaborate with team members to deliver working software incrementally.

In CS 320 (Software Testing, Automation, and Quality Assurance), I worked with peers to review code and provide constructive feedback. I learned to write clear bug reports, suggest improvements respectfully, and incorporate feedback from others. These experiences taught me that successful software development requires effective communication, mutual respect, and shared accountability.

For example, during a team project, I collaborated with three classmates to build a web application. We used GitHub for version control, conducted code reviews for each pull request, and held weekly check-ins to track progress. I learned to resolve merge conflicts, articulate my technical decisions, and compromise when team members had different approaches.

## Communicating with Stakeholders ##

I developed professional communication skills across multiple formats: written, oral, and visual. I learned to adapt my communication style based on audience and context, a skill essential for working with diverse stakeholders.

Written Communication: I wrote technical documentation, system design documents, and user guides in courses like CS 250 and CS 340. My code review narratives in this capstone demonstrate my ability to explain technical concepts clearly to instructors and potential employers.

Oral Communication: I presented project findings in CS 330 and delivered my code review video in this capstone. I learned to organize my thoughts, speak clearly, and use visual aids effectively.

Visual Communication: I created UML diagrams in IT 315, data visualizations in CS 340, and designed my ePortfolio using GitHub Pages. I learned to present complex information in accessible, visually appealing formats.

For example, when explaining my pagination enhancement, I created a flowchart illustrating the before-and-after memory complexity, helping stakeholders understand why the improvement mattered.

## Data Structures and Algorithms ##

My understanding of data structures and algorithms developed progressively throughout the program. In CS 260, I studied fundamental data structures—arrays, linked lists, stacks, queues, trees, and hash maps—and learned to analyze algorithm efficiency using Big O notation.

I applied this knowledge in my capstone when enhancing the Animal Shelter project. I recognized that the original read() method loaded all records into memory at once, creating O(n) memory complexity. I implemented server-side pagination to reduce memory usage to O(page_size), demonstrating my ability to evaluate algorithmic trade-offs and choose appropriate data structures.

I also created B-tree indexes in MongoDB, transforming query time from O(n) full collection scans to O(log n) logarithmic lookups. I implemented LRU caching using Python's functools.lru_cache, enabling O(1) retrieval for repeated queries. These enhancements demonstrate my ability to design and evaluate computing solutions using algorithmic principles (Course Outcome #3).

According to MongoDB (2024), B-tree indexes are fundamental to query optimization in database systems. I applied this industry-standard technique to improve performance, showing my ability to use well-founded techniques in computing practices (Course Outcome #4).

## Software Engineering and Databases ##

My software engineering skills matured through courses like CS 340 and CS 250. I learned the software development lifecycle, from requirements gathering to design, implementation, testing, and deployment.

Software Engineering: I demonstrated my software engineering abilities in Milestone Two by refactoring a monolithic Jupyter Notebook into a modular MVC architecture. I separated concerns into Model, View, and Controller components, added comprehensive docstrings, implemented logging, and moved hardcoded credentials to environment variables. This enhancement showcases my ability to create industry-standard software designs and deliver value through clean, maintainable code.

Databases: In Milestone Four, I implemented MongoDB schema validation to enforce data integrity, created an audit logging collection with TTL indexes for security and compliance, and built aggregation pipelines for server-side analytics. These enhancements demonstrate my ability to use database tools and techniques professionally.

My database work directly supports Course Outcome #5 (security mindset). I recognized that hardcoded credentials were a critical vulnerability and remediated them. I also implemented audit logging to track data modifications, enabling forensic analysis if unauthorized changes occur. According to the Python Software Foundation (2024), cache invalidation is critical for data consistency, a lesson I learned when implementing LRU caching.

## Security Mindset ##

Developing a security mindset has been a key focus throughout the program. In CS 405 (Secure Coding) and CS 340, I learned to anticipate adversarial exploits, identify vulnerabilities, and implement mitigations.

Credential Management: In my original CS 340 project, I hardcoded database credentials in the Jupyter Notebook. Anyone with access to the notebook could see the password. In Milestone Two, I moved credentials to a .env file excluded from version control, following industry best practices.

Input Validation: The original create() method accepted any data without validation. I added explicit checks to ensure data is a non-empty dictionary before insertion, preventing injection attacks and data corruption.

Audit Logging: In Milestone Four, I created an audit log collection that tracks every CREATE, UPDATE, DELETE, and READ operation with timestamp, action, user, and query details. This enables forensic analysis and compliance with data governance requirements.

Defensive Programming: I blocked empty delete queries, preventing accidental deletion of all documents. I also added validation for age ranges, geographic coordinates, and required fields using JSON Schema.

According to MongoDB (2024), schema validation is essential for maintaining data quality and preventing security issues. I applied this principle throughout my database enhancements.

## Summary: How the Artifacts Fit Together ##

My ePortfolio demonstrates the full range of my computer science abilities through three interconnected enhancements to the Animal Shelter Dashboard:

Software Design and Engineering shows I can create professional, maintainable code by applying MVC architecture, logging, and secure credential management. This enhancement demonstrates my ability to design and implement industry-standard software solutions (Course Outcome #4).

Algorithms and Data Structures shows I can optimize performance by analyzing time and space complexity, implementing B-tree indexes, and using LRU caching. This enhancement demonstrates my ability to evaluate algorithmic trade-offs and improve efficiency (Course Outcome #3).

Databases shows I can secure and optimize data by implementing schema validation, audit logging, and aggregation pipelines. This enhancement demonstrates my security mindset and database expertise (Course Outcome #5).

Together, these enhancements show a developer who can build, optimize, and secure data-driven applications. The code review video demonstrates my communication skills (Course Outcome #2), and the self-assessment demonstrates my collaborative abilities (Course Outcome #1).

My career specialization is backend and data engineering, and this portfolio provides tangible evidence of my skills. Employers can see my actual code, read my reflections, and understand my growth as a developer.

###### References

MongoDB, Inc. (2024). Indexes in MongoDB. MongoDB Documentation. https://docs.mongodb.com/manual/indexes/

Python Software Foundation. (2024). functools — Higher-order functions and operations on callable objects. Python Documentation. https://docs.python.org/3/library/functools.html

U.S. Bureau of Labor Statistics. (2024). Occupational Outlook Handbook: Software Developers, Quality Assurance Analysts, and Testers. https://www.bls.gov/ooh/computer-and-information-technology/software-developers.htm
