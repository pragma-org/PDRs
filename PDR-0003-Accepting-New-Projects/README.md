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
The process of accepting new projects is not formalized in PRAGMA's statutes.

## Motivation

Accepting projects needs rules to ensure that the association's goals are met 
and that the projects are a good fit for PRAGMA. Also, the process should be transparent and fair.
A clear process to accept projects will protect the foundation from potential legal issues.

## Decision

PRAGMA differentiates between two types of projects:

 - PRAGMA Projects: projects that are fully recognized as part of PRAGMA and are part of the PRAGMA GitHub organization.
 - PRAGMA Incubating Projects: projects that are not yet part of PRAGMA but are in the process of joining.

PRAGMA Projects can have the state of "active" and "archived".

- Active projects are part of PRAGMA and have to report to the board regularly.
- Archived projects are read-only, do not need to be reported and will be sent to the PRAGMA attic,
a project that makes projects accessible for future generations. 

PRAGMA Incubating Projects can have the state of "incubating", "graduated" and "rejected".

- Incubating projects are projects that are in the process of joining PRAGMA. They follow the same
rules as active PRAGMA Projects but are not yet fully accepted.
- Rejected projects are projects that have been rejected by the board. Incubation efforts will stop, and the project will be archived.
- Graduated projects are projects that have been accepted by the board. In the future, graduated projects will be referred to as active PRAGMA Projects.

### Incubation and Attic workgroups

Interested board members and also PRAGMA maintainers can join the working group "I&A" (Incubation & Attic).
This working group is responsible for defining the rules for incubation and the attic.

While the board will vote on the acceptance of projects, the board will not interfere
in the discussions of the I&A working group. 

The I&A working group will send quarterly reports to the board about their activities.

### Accepting new projects

Projects aiming to join PRAGMA must follow one of the two following processes:

### Process 1: Direct acceptance

- A project lead can submit a proposal to the board.
- The board will review the proposal and accept the project given the following reasons:
  - The project is aligned with PRAGMA's goals.
  - The source code was developed solely by one or more members of PRAGMA
  - The source code original owners are willing to donate the project to PRAGMA
  - The project is not a fork of an existing project
  - The project does not have any legal issues, such as copyright infringement
  - Trademarks are cleared and the owners are willing to donate them to PRAGMA
  - No other pressing reasons come up during the review
- The board will vote on the resolution through the PDR process and accept or reject the project.

As soon as there is a successful vote on the resolution, the project becomes
an active PRAGMA Project and the transfer can start.

### Process 2: Incubation

- A project lead can submit a proposal to the board.
- I&A will review the proposal and decide whether to propose to project to the board 
  or to work further with the project lead or reject it.
- The board will review the proposal and accept or reject the project for incubation.
- As soon as the project is accepted, the incubation can start. Incubating projects 
  can use PRAGMA's resources and are allowed to use the PRAGMA name. However, incubating
  projects need to make it clear that they are not yet part of PRAGMA and add the
  word "INCUBATING" to logos and their disclaimer.
- I&A will work with the project and provide them guidance and support to meet the requirements
  for a successful graduation. The requirements will be defined by the I&A working group.
- Once I&A is satisfied with the project, they will propose the project through the PDR process to the 
  board for graduation.
- The board votes on it and accepts or rejects the project. If rejected, the project 
  can continue to incubate.

## Consequences
<!-- Describe the result/consequences of applying that decision; both positive and negative outcomes. -->
<!-- If category is a Policy, describe how to measure the application of the policy on a project (qualitative or quantitative) by using metrics that can be understood by any internet user. -->

### Positive outcomes

- Clarity in accepting or rejecting projects
- Motivation for projects to join PRAGMA  
- Protection from legal issues
- Transparency in the process
- Fairness in the decision-making process

### Negative outcomes

- The forming of the I&A working group may lead to more bureaucracy
- The process may slow down the acceptance of projects

## Discussion points
<!-- Summarizes, a posteriori, the major discussion points that gravitates around the decision -->

[Archive]: https://github.com/pragma-org/PDRs/tree/main/.validityreview