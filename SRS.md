Software Requirements Specification (SRS)

Introduction Purpose This Software Requirements Specification (SRS) document describes the functional and non-functional requirements of the Student Registration System. It serves as a reference for project stakeholders, including developers, project managers, lecturers, and system administrators.

Scope The Student Registration System is a web-based application that manages student enrollment and course registration processes within an academic institution. The system allows students to register for courses, lecturers to manage courses and view enrolled students, and administrators to oversee users, courses, and reports.

Definitions, Acronyms, and Abbreviations SRS: Software Requirements Specification Admin: System Administrator UI: User Interface

Overview This document outlines the system overview, functional requirements, non-functional requirements, user types, and major system components.

Overall Description Product Perspective The Student Registration System is a standalone web application that interacts with a central database to store and manage academic records. User Classes and Characteristics Student: Registers, logs in, enrolls in courses, and views enrolled courses. Lecturer: Manages courses and views enrolled students. Admin: Manages users, courses, and generates reports.

Operating Environment Web browser (Chrome, Firefox, Edge) Server-based backend system Relational database system Functional Requirements

FR-01: The system shall allow students to create and manage user accounts. FR-02: The system shall authenticate users using a username and password. FR-03: The system shall allow students to register for available courses. FR-04: The system shall prevent students from registering for duplicate courses. FR-05: The system shall allow lecturers to view students enrolled in their courses. FR-06: The system shall allow administrators to create, update, and delete courses. FR-07: The system shall allow administrators to manage user roles and permissions. FR-08: The system shall generate reports on student enrollment.

Non-Functional Requirements NFR-01 (Performance): The system shall respond to user requests within 2 seconds. NFR-02 (Security): All user passwords shall be encrypted. NFR-03 (Availability): The system shall be available 99% of the time. NFR-04 (Usability): The system shall be easy to use with minimal training. NFR-05 (Scalability): The system shall support an increasing number of users.

System Overview Key Stakeholders Students Lecturers System Administrators Academic Management

Major System Modules User Management Module Course Management Module Registration Module Reporting Module

Assumptions and Dependencies Users have internet access. The system depends on a reliable database server. Conclusion:SRS document defines the requirements and scope of the system and guides further design and project planning.

This SRS document defines the requirements and scope of the Student Registration System and will guide further system design and project planning.
