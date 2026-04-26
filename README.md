# CS-255 DriverPass System Analysis & Design

Portfolio for CS-255 System Analysis and Design

## Project Overview
This repository contains system analysis and design documentation for DriverPass, a comprehensive driver training platform designed to improve DMV exam pass rates through online practice tests and in-person driving lessons.

## Repository Contents

### Business Requirements Document
**File**: `Business-Requirements-Document.docx`

Comprehensive requirements analysis including:
- System Purpose & Background
- Goals & Objectives (5 goals with measurable objectives)
- Functional Requirements
- Nonfunctional Requirements (Performance, Security, Platform Constraints)
- User Interface Requirements for 5 user roles
- Assumptions & Limitations
- Project Gantt Chart (Jan 22 - May 10, 2024)

### System Design Document
**File**: `System-Design-Document.docx`

Technical design specifications including:
- System Design Overview
- UML Diagrams (Use Case, Activity, Sequence, Class)
- Technical Architecture
- Design Constraints
- System Recommendations

## Reflection

### Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?

The client was DriverPass, a new company founded by Liam that provides driver training services. They wanted a comprehensive web-based system combining online DMV practice tests with in-person driving lesson reservations. The system needed to address the low 46% DMV exam pass rate by providing better preparation through online practice tests, professional driving instruction, and up-to-date content synchronized with DMV requirements. Key requirements included automated reservation management for 10 cars and 10 instructors, three tiered service packages (Basic: $199/30 days, Intermediate: $449/60 days, Premium: $799/90 days), role-based access for five user types (customers, secretary, instructors, IT officer, owner), and cloud-based infrastructure ensuring 24/7 availability.

### What did you do particularly well?

I excelled at translating interview insights into detailed technical requirements by creating comprehensive UML diagrams that effectively communicated system interactions to both technical and non-technical stakeholders. My functional requirements used precise "The system shall..." statements that were measurable and testable. The Gantt chart accurately captured the 110-day project timeline with all 12 tasks from the interview transcript, showing clear dependencies and resource allocation. I also successfully balanced technical constraints with business needs, particularly in designing role-based access controls and ensuring security compliance (PCI DSS, SSL/TLS encryption) while maintaining user-friendly interfaces tailored to each user type's specific workflows and needs.

### If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

I would revise the nonfunctional requirements section to include more specific quantitative metrics and success criteria. While I specified "page load times <2 seconds" and "99.9% uptime," I would add more detailed performance benchmarks such as database query response times (<100ms for simple queries, <500ms for complex reports), API endpoint latency targets, concurrent user session limits with specific auto-scaling thresholds (e.g., scale up at 80% capacity), and detailed failover/disaster recovery procedures with RTO (Recovery Time Objective) and RPO (Recovery Point Objective) specifications. I would also expand the security section to include specific penetration testing schedules, vulnerability scanning procedures, and incident response protocols with defined SLAs for different severity levels.

### How did you interpret the user's needs and implement them into your system design? Why is it so important to consider the user's needs when designing?

I interpreted user needs by carefully analyzing the interview transcript to identify pain points and workflows for each user role. For customers, I designed self-service booking capabilities and 24/7 practice test access because the interview revealed they need flexibility and convenience. For the secretary, I created streamlined reservation management tools optimized for phone and walk-in support since she handles customer service. For instructors, I designed a mobile-optimized interface for schedule viewing and lesson notes because they need on-the-go access. For the IT officer (Ian), I included comprehensive administrative controls, user management, and security monitoring. For the owner (Liam), I designed business intelligence dashboards with revenue analytics and performance metrics. Considering user needs is critical because a technically perfect system that doesn't match how users actually work will fail in practice—the 46% pass rate problem can only be solved if students actually use the practice tests and complete their driving lessons, which requires interfaces designed around their workflows, motivations, and technical skill levels.

### How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?

My approach follows user-centered design principles: (1) **Requirements Gathering** - conducting stakeholder interviews and analyzing business processes to understand problems before proposing solutions; (2) **UML Modeling** - creating use case, activity, sequence, and class diagrams to visualize system interactions and structure before writing code; (3) **Iterative Refinement** - starting with high-level architecture and progressively adding detail based on feedback; (4) **Constraint Analysis** - identifying technical, business, and regulatory constraints early to avoid costly redesigns. In future projects, I would incorporate rapid prototyping and user testing earlier in the design phase to validate assumptions, use established design patterns more explicitly to solve common problems (MVC, Repository, Factory patterns), conduct security threat modeling during design rather than as an afterthought, and create detailed API specifications alongside UML diagrams to ensure frontend-backend alignment. I would also implement more robust traceability matrices linking requirements to design elements to test cases, ensuring every requirement is addressed and testable.

## Key System Features

- **Online Practice Tests**: 500+ DMV-aligned questions with automated scoring and progress tracking
- **Reservation Management**: Real-time scheduling for driving lessons with instructor and vehicle assignment
- **Tiered Service Packages**: Three levels to meet different customer needs and budgets
- **Role-Based Access Control**: Five distinct user types with appropriate permissions
- **Cloud Infrastructure**: Scalable, secure hosting with 99.9% uptime guarantee
- **DMV Content Synchronization**: Automatic updates within 48 hours of regulatory changes
- **Multi-Channel Access**: Online, phone, and in-person reservation options
- **Business Analytics**: Comprehensive reporting for owner decision-making

## Technical Specifications

- **Platform**: Cloud-based web application (AWS/Azure/GCP)
- **Access**: Responsive browser-based interface (mobile and desktop)
- **Security**: PCI DSS Level 1 compliant, SSL/TLS encryption, multi-factor authentication
- **Database**: Relational database (PostgreSQL/MySQL) for structured data storage
- **Integration**: Payment gateway (Stripe/PayPal), Email/SMS notifications (SendGrid/Twilio), DMV content API

## Project Timeline

- **Duration**: January 22, 2024 - May 10, 2024 (110 days)
- **Key Phases**:
  - Requirements Gathering: 14 days
  - System Design: 23 days
  - Development: 52 days
  - Testing: 11 days
  - Deployment: 4 days

## Course Information

- **Course**: CS-255 System Analysis and Design
- **Institution**: Southern New Hampshire University
- **Student**: Isela Flores
- **Email:**: isela.flores@snhu.edu

---

*This portfolio demonstrates skills in requirements analysis, UML modeling, system design, and technical documentation developed through the CS-255 course.*
