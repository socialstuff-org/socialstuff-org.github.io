# SocialStuff

# TODOs

- Jörn & Maurits:
    - connect services
    - implement handshake
    - fix minor issues
- Malte & Tobias:
    - admin panel (invite links)
    - 
- Dave:
    - todo


## Project Roles

* Product Owner: Jörn Neumeyer
* Project Management / Scrum Master:
  * Tobias Jansen
  * Maurits van der Zee
  
* Quality Management:
  * Dave Hoevenaars

* Frontend Developers:
  * Malte Castner [[Github]](https://github.com/HerrSvenson)
  * Dave Hoevenaars [[Github]](https://github.com/DaveHoevenaars)
  * Maurits van der Zee [[Github]](https://github.com/MauritsvanderZee)

* Backend Developers:
  * Tobias Jansen [[Github]](https://github.com/tobias-jansen-2411)
  * Jörn Neumeyer [[Github]](https://github.com/joernneumeyer)

## Introduction

***-- Add a detailed introduction on what socialstuff is all about --***

## Project Management

- [Changelogs](changelogs/index.md)
- [Project Management Plan](projectmanagement/project_management_plan.pdf) [[Source]](projectmanagement/project_management_plan.docx)
- [Project Charter](projectmanagement/project_charter.pdf) [[Source]](projectmanagement/project_charter.docx)
- [Work-breakdown-structure (WBS)](projectmanagement/WBS.pdf)

## Analysis

### Use cases

 - Use case [diagram](usecases/usecase-diagram.svg) [[Source](usecases/use-case.uxf)]
 - Use cases for [user](usecases/index-user.md)
 - Use cases for [admin](usecases/index-admin.md)

### High level architectural overview

***-- Add a description how socialstuff will work (high level, client Alice/Bob, multiple servers, etc.) --***

## Design

***-- description to be added --***

### Sequence diagrams

 - [Send message (best case)](design/sequence-diagrams/sequence-send-message_best-case.svg) [[Source](design/sequence-diagrams/sequence-send-message_best-case.uxf)]
 - [Send message (worst case)](design/sequence-diagrams/sequence-send-message_worst-case.svg) [[Source](design/sequence-diagrams/sequence-send-message_worst-case.uxf)]
 - [Send file](design/sequence-diagrams/file-transfer.svg) [[Source](design/sequence-diagrams/file-transfer.uxf)] ***-- create diagram --***

### State machine diagrams
 - [Message](design/state-machine-diagrams/message.svg) [[Source](design/state-machine-diagrams/state-machine-message.uxf)]

### Technology Stack

Finding the right technology stack for a project is a major part of the overall process of realizing a project. 
Multiple considerations should be taken into account which we will cover in this section. This section is a detailed 
of which technology stack we have gone with and why.

#### Factors taken into account
- [Keep it simple and agile](#keep-it-simple-and-agile)
- [Project requirements](#project-requirements)
- [Open-source technologies](#open-source-technologies)
- [Ecosystem](#ecosystem)
- [Long-term trends and support](#long-term-trends-and-support)
- [Final technology stack](#final-technology-stack)

##### Keep it simple and agile
Finding a proper technology stack starts with deciding a fitting solution for the actual context in which the project
should be realized. As the project will be developed in a short-term project of 5 months within software factory (SOFA)
at Fontys Venlo we had to go with an agile as well as easy to start with technology. This enables all team members to
get started quickly as well as to adapt accrodingly if something does not work out as planned.

We started with a small concept and some sketches of how the product could look like. The actual set of features was not
fixed at this point in time. We knew that the project scope would change during the project phase. That's why it is even
more important to choose for an agile technology.

##### Project requirements
As the project is focussing on secure as well as fast communication between several users across the internet, we wanted
to choose a technology stack that supports various system platforms as well as easy migration possibilities for a later
stage of the project. This would allow us to adapt our developed parts to be translated to further platforms and devices.
As more than 60% of all users are accessing the internet via mobile devices the focus should also lie on technologies which
are fully supported by mobile platforms and devices.

As security and privacy are our core principles we needed to take this into consideration for our technology stack. Our
focus was set to various technologies which have been around for quite some time already so we can be sure that major security
vulnerabilities have been eliminated beforehand.

##### Open-source technologies
Going with open-source technologies provides multiple benefits. First of all it enables to project team to focus on the
business part of the application. Most of time, there is already a good open-source solution for general tasks like front-end
frameworks, database systems or encryption algorithms. Those implementations enables the team to safe a lot of time as
the components do not have to be developed by ourselves. Last but not least are those already implemented solutions more secure
as more people have their eyes on it and report and fix bugs.

Important for using open-source software is, that it is properly documented and that is already known in the community.
This helps with later bug fixings and solution findings.

##### Ecosystem
***-- TODO --***

##### Long-term trends and support
***-- TODO --***

##### Final technology stack

- Frontend
  - Electron
  - Angular
  - Angular Material
  - SCSS
- Backend
  - NodeJS

## Visual Design

***-- description to be added --***

Please refer to the below listed files for more details.

 - Styleguide
    - [Grid & Measurements](visual-design/style-guide/grid.md)
    - [Message Styling](visual-design/style-guide/message-styling.md)
    - [Message States](visual-design/style-guide/message-states.md)
 - [Color palettes](visual-design/color-palette.md)
 - [Wireframes](visual-design/wireframes.md)

## Implementation

***-- description to be added --***

### Frontend Components
***-- TODO --***
- Auth
    - [Register]() ***-- TODO --***
    - [Login]() ***-- TODO --***
    - [Forgot Password]() ***-- TODO --***
- ***-- TODO --***

### Services

***-- TODO: add description  --***  
***-- TODO: more services to be added --***

- [List of ports](services/ports.md)

#### Backend services / APIs

 - [Authentication service](services/backend/authentication-service.md) ***-- TODO: file to be added --***
 - [Identity service](services/backend/identity-service.md) ***TODO***
 - [File service](services/backend/file-service.md) ***TODO***
 
#### Frontend services
 - [Crypto Storage Service](services/frontend/crypto-storage-service.md) ***TODO***
 - [Contact Service](services/frontend/contact-service.md) ***TODO***

