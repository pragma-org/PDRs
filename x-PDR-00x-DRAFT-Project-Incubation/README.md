---
PDR: 0003
Title: Accepting new projects to PRAGMA
Category: Process
Status: Proposed 
Authors:
 - Christian Grobmeier <cg@grobmeier.de>
 - Damien Czapla <damien.czapla@openthelead.com>
Created: 2024-08-01
---

## Context

PRAGMA allows projects to join the association. 
PDR-0003 describes the "direct acceptance" process of a new project through the board.
This PDR describes projects that want to join PRAGMA but cannot be accepted
by the process defined in PDR-0003.

## Motivation

Projects that cannot be accepted but are acceptable candidates in general,
need to undergo incubation before they can join PRAGMA.

Incubation is a process that protects the foundation and its developers from 
potential legal issues. Incubation defines the rules of entering, succeeding, or
failing the process of joining PRAGMA. 

## Decision

With this PDR, PRAGMA differentiates between two types of projects:

 - PRAGMA Projects: projects fully recognized as part of PRAGMA and part of the PRAGMA GitHub organization.
 - PRAGMA Incubating Projects are projects that are not yet part of PRAGMA but are in the process of joining.

PRAGMA Incubating Projects can have the state of "incubating," "graduated," and "rejected."

- Incubating projects are projects that are in the process of joining PRAGMA. 
 They follow the same rules as active PRAGMA Projects but have yet to be fully accepted.
- Rejected projects are projects that the board has rejected. Incubation efforts will stop, 
 and the project will be archived.
- Graduated projects are projects that the board has accepted. In the future, 
 graduated projects will be referred to as active PRAGMA Projects.

### Incubation Oversight

Incubation requires at least one board member, PRAGMA member, or PRAGMA maintainer to
step up as mentor for the project. The mentor will guide the project through the
incubation phase and support it by answering questions. 
The mentor will take care that the board report is sent in time and respond
to questions, if there are any.

### Incubation

- A project lead can submit a proposal to the board.
- The board will review the proposal and decide whether to work further with the project or reject it.
- If the project is accepted, one or more volunteer mentors will be assigned to the project.
- As soon as mentors are found, the incubation can start. Incubating projects 
 can use PRAGMA's resources and are allowed to use the PRAGMA brand. However, incubating
 projects must clarify that they are not yet part of PRAGMA and add "INCUBATING" to logos and their disclaimer.
- The mentor will work with the project and provide them guidance and support to meet the requirements
 for a successful graduation.
- The board will vote on acceptance once the project successfully votes for graduation and the mentor recommends graduation.
- The board votes on it and accepts or rejects the project. If rejected, the project 
 can continue to incubate.

### Requirements to graduate

- The project must have more than three active contributors.
- The project must have demonstrated its ability to grow by offering a clear
 path to join its new contributors.
- The project made at least one, but preferably three, acceptable releases.
- The project can provide reports on time.
- The project's name is clear and free of trademark disputes, cultural appropriation, and other issues.
- The source code was either only developed by project team members or
 accepted by using a DCO.
- The source code is published in the PRAGMA GitHub organization.
- The source code is licensed under a PRAGMA-approved license.
<!-- - TODO: add more requirements -->

## Discussion points
<!-- Summarizes, a posteriori, the major discussion points that gravitates around the decision -->

<!-- 
 TODO: define the term release
 TODO: define how to use DCOs
-->
[Archive]: https://github.com/pragma-org/PDRs/tree/main/.validityreview