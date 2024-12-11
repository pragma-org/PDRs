---
PDR: 0003
Title: Accepting new projects to PRAGMA
Category: Process
Status: Proposed 
Authors:
    - Christian Grobmeier <cg@grobmeier.de>
    - Damien Czapla <damien.czapla@openthelead.com>
    - Christina Gianelloni <christina@blinklabs.io>
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

PRAGMA Incubating Projects can have the state of "incubating", "graduated" and "rejected".

- Incubating projects are projects that are in the process of joining PRAGMA. They follow the same
rules as active PRAGMA Projects but are not yet fully accepted.
- Rejected projects are projects that have been rejected by the board. Incubation efforts will stop, and the project will be archived.
- Graduated projects are projects that have been accepted by the board. In the future, graduated projects will be referred to as active PRAGMA Projects.

### Accepting new projects

Projects aiming to join PRAGMA must follow this process:

- A project lead can submit a proposal to the board.
- The board will review the proposal and accept the project as Incubating given the following reasons:
  - The project is aligned with PRAGMA's goals.
  - The source code original owners are willing to donate the project to PRAGMA
  - The project is not a fork of an existing project
  - The project does not have any legal issues, such as copyright infringement
  - Trademarks are cleared and the owners are willing to donate them to PRAGMA
  - No other pressing reasons come up during the review
       - While an incubating project, the project will have to demonstrate itself by a 1.0 release and two quarterly reports to the board of directors. Upon completion, the vote to accept the project will be added to the next board agenda. 
- The board will vote on the resolution through the PDR process and accept or reject the project.

As soon as there is a successful vote on the resolution, the project becomes
an active PRAGMA Project and the transfer can start.

## Consequences
<!-- Describe the result/consequences of applying that decision; both positive and negative outcomes. -->
<!-- If category is a Policy, describe how to measure the application of the policy on a project (qualitative or quantitative) by using metrics that can be understood by any internet user. -->

### Positive outcomes

- Clarity in accepting or rejecting projects
- Protection from legal issues
- Transparency in the process
- Fairness in the decision-making process

### Negative outcomes

- The process may slow down the acceptance of projects

## Discussion points
<!-- Summarizes, a posteriori, the major discussion points that gravitates around the decision -->

[Archive]: https://github.com/pragma-org/PDRs/tree/main/.validityreview
