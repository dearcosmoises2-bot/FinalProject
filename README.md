CS 3338 Final Project - Group 11 - Landfill e-Forms Application

Jira Project URL: https://cs3338group11.atlassian.net/jira/software/projects/C3FP/boards/133

**Team**
- Areli Arana
- Moises De Arcos
- Eric Lopez Perez
- Kanishq Nileshbhai Viradiya
- Miguel Sanchez Saenz

**Project Sponsor**
City of Los Angeles, Department of Sanitation

**Overview**
The Landfill e-Forms Application is our CS 3338 Final Project topic. The project is based on the approved Landfill e-Forms Application concept.

The purpose of the system is to convert a paper-based landfill methane-emission auditing workflow into a digital workflow. The project is intended to improve inspector efficiency, reduce human error, and support faster report generation.

**System Components**
The system is composed of two connected applications:
- A mobile application used by field inspectors for collecting inspection data in the field
- A web application used for data entry, review, management, synchronization, and report generation

**System Architecture**
The application follows a multi-part workflow. Field inspectors collect inspection data through the mobile application. That data is stored locally until it is transferred into the main system. The web application is then used to review, manage, search, and generate reports from submitted inspection records.

The design includes:
- A presentation layer for the web and mobile interfaces
- A business logic layer for processing application functions
- A data access layer for handling stored records
- A database layer for maintaining inspection and user data
- A synchronization process between mobile and web components

**Web Application Pages**
- Login: Authenticates users before system access
- Dashboard: Displays recent activity and navigation to core functions
- Inspection Form: Allows creation and editing of inspection records
- Inspection List: Displays submitted and draft inspections in a searchable list
- Inspector Management: Supports administrative management of inspector accounts
- Report Generator: Allows report creation based on selected criteria
- Sync Console: Displays synchronization activity and status
- Settings: Stores system configuration options

**Mobile Application Screens**
- Login: Authenticates users before access to the mobile system
- Home: Displays assigned inspection tasks for the current day
- Inspection Form: Allows inspectors to enter landfill-related inspection data
- Draft List: Displays saved but not yet submitted inspection entries
- Sync Status: Shows the status of pending and completed synchronization

**Main Features**
- Electronic inspection form entry
- Local data storage for field use
- Review and management of submitted inspection records
- Report generation
- User account access and management
- Synchronization between mobile and web application components

**Data and Record Management**
The system is designed to maintain centralized records for inspections, users, reports, and synchronization activity. Inspection data collected in the field is transferred into the main system where it can be reviewed, managed, and used in reporting workflows.

**Synchronization**
The system design includes a synchronization process that transfers data between the mobile and web application components. Inspection data collected on the mobile side is uploaded into the main system, and synchronization activity is tracked as part of the workflow.

**Security**
The design includes user authentication, controlled access to system functions, and protected handling of user and inspection records. Access to system features is based on authorized user roles.

**Project Goals**
- Improve efficiency in landfill inspection data handling
- Reduce errors caused by paper-based workflows
- Support better organization of submitted records
- Make stored inspection data easier to review and report on

**Repository Purpose**
This repository is used to organize the final project documents and related deliverables for the project.

