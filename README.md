# CS-255 System Analysis and Design Portfolio

## DriverPass Project

### Project Overview
This repository contains my work from CS-255 System Analysis and Design, showcasing my ability to gather business requirements, analyze user needs, and design comprehensive system solutions.

---

## Repository Contents

- **Business Requirements Document** - Analysis of client needs and system requirements gathered from stakeholder interviews
- **System Design Document** - Complete UML diagrams and technical specifications for the DriverPass system
- **UML Diagrams** - Use case, activity, sequence, and class diagrams illustrating system design

---

## Project Reflection

### Project Summary

The DriverPass project was designed for a driver training company seeking to improve student success rates on driving exams. The client, represented by the owner Liam and IT officer Ian, wanted a comprehensive web-based system that would provide students with both online practice tests and in-person driving lesson scheduling capabilities.

The system needed to address several key business challenges: helping students better prepare for DMV exams through online practice tests with current content, streamlining the reservation process for driving lessons to reduce administrative overhead, and providing robust reporting tools to track business performance. The client emphasized the importance of staying current with DMV testing requirements and offering multiple training package options to meet different student needs.

### What I Did Particularly Well

I excelled at translating the client's business needs into clear, comprehensive UML diagrams that accurately represented system functionality. My use case diagram effectively captured all user roles and their interactions with the system, ensuring nothing from the client interview was overlooked. I also did well in designing workflows that addressed real pain points the client mentioned, such as the activity diagram for making reservations that eliminates manual schedule coordination and prevents double-booking.

Additionally, I was thorough in addressing both functional requirements (what the system does) and nonfunctional requirements (how well it performs). I made sure to include security measures, accessibility features, and compliance considerations that the client might not have explicitly mentioned but are essential for a professional system handling sensitive customer data and payment information.

### Area for Revision and Improvement

If I could revise one part of my work, I would enhance the sequence diagram to include more error handling scenarios. While the current diagram shows the happy path where everything works correctly, real-world systems need to handle failures gracefully. I would add alternate flows showing what happens when the authentication service is unavailable, when the database connection fails, or when payment processing encounters an error.

I would improve this by creating supplementary sequence diagrams for exception cases, showing how the system recovers from errors, provides meaningful feedback to users, and maintains data consistency even when operations fail partway through. This would demonstrate more mature thinking about system reliability and user experience beyond just the primary use cases.

### Interpreting and Implementing User Needs

I interpreted user needs by carefully analyzing the client interview transcript and identifying both explicit requests and implicit requirements. For example, when the client mentioned wanting to reduce failed driving exam attempts, I understood this meant the system needed comprehensive practice test functionality with progress tracking and performance analytics. When they expressed frustration with scheduling coordination, I designed an automated reservation system with real-time availability checking.

I implemented these needs by creating specific use cases for each user role (student, instructor, secretary, IT officer, owner), designing workflows that eliminate the manual steps they complained about, building in the DMV integration they requested to keep content current, and including reporting capabilities that give the owner business insights without requiring IT support.

Considering user needs is critical because systems that don't match how people actually work will fail regardless of how technically sophisticated they are. If we design a system based on what we think users need rather than listening to their actual requirements, we'll create software that's difficult to use, doesn't solve the real problems, and ultimately won't be adopted. The DriverPass client specifically mentioned competing with other driving schools - if our system doesn't make their business more efficient and help students succeed, it won't provide competitive advantage.

### Software Design Approach

I approach software design by starting with thorough requirements gathering through stakeholder interviews and documentation review. I believe in understanding the business problem before jumping into solutions. For DriverPass, I carefully reviewed the interview transcript multiple times, noting not just what they explicitly asked for but also pain points they mentioned that could be addressed through good design.

My technique involves creating multiple UML diagrams to view the system from different angles - use cases show who does what, activity diagrams show workflow and business logic, sequence diagrams show component interaction, and class diagrams show data structure. Each diagram reveals different aspects of the system and helps identify gaps or inconsistencies in the design.

In the future, I would continue using UML diagramming as it provides a standardized way to communicate design decisions. I would also incorporate prototyping earlier in the process - creating mockups of key interfaces and walking through them with stakeholders to validate that the design meets their needs before committing to full development. I would make more use of user stories written from the perspective of each user role to ensure I'm capturing all scenarios. Finally, I would emphasize iterative design, creating an initial design, gathering feedback, and refining rather than trying to perfect everything upfront.

I also learned the importance of considering nonfunctional requirements from the beginning rather than treating them as afterthoughts. Security, performance, accessibility, and scalability need to be built into the architecture, not added later. For DriverPass, designing role-based access control from the start, planning for cloud deployment to ensure availability, and incorporating PCI-compliant payment processing were all crucial to creating a viable system.

---

## Skills Demonstrated

- Requirements gathering and analysis
- UML diagramming (use case, activity, sequence, class diagrams)
- System architecture design
- Technical requirements specification
- User-centered design thinking
- Business process analysis
- Stakeholder communication

---

## Tools and Technologies

- Lucidchart for UML diagram creation
- Microsoft Word for documentation
- GitHub for version control and portfolio management

---

## About This Course

CS-255 System Analysis and Design focused on the full lifecycle of analyzing business requirements and designing system solutions. The course emphasized understanding user needs, translating those needs into functional specifications, and creating technical designs that can be implemented by development teams.

---

## Contact

Isela Flores  
Southern New Hampshire University  
CS-255 System Analysis and Design  
isela.flores@snhu.edu

---

*This portfolio demonstrates my ability to analyze complex business requirements, design comprehensive system solutions, and communicate technical concepts clearly to both technical and non-technical stakeholders.*
