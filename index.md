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

