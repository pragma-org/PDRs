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

PRAGMA allows projects to join the association. </br>
The process of accepting new projects is not formalized in PRAGMA's statutes.

## Motivation

Welcoming projects within PRAGMA needs rules to ensure that the projects are a good fit and the association's goals are met. </br>
Also, the acceptance process should be transparent and fair.

## Decision

The acceptance process will rely upon a set of criterias for each stage of the process, and the deciding bodies will be the Administrative Board and the General Assembly.

> [!NOTE]
> If you want to know more about these deciding bodies you can check: </br>
> [.incorporation](https://github.com/pragma-org/PDRs/tree/main/.incorporation) for their composition </br>
> [Statutes](https://github.com/pragma-org/PDRs/blob/Dam-CZ-patch-3/.incorporation/20240422_Attachment_Statutes_Statuten_PRAGMA_signed.pdf) for their mandate

You will find here the representation of the incubation process:
![PRAGMA](https://github.com/user-attachments/assets/8b4866ee-e165-440c-ac72-74d4be18788a)


Here are the steps to go through the whole process:
1. A project owner submits a PDR through a pull request on Github
2. The Administrative Board reviews the PDR created in their monthly meeting and check the compliance of the project with the acceptance criteria
3. The project (after several succesful quarterly meetings) is proposed to the General Assembly by the Administrative Board
4. The General Assembly accepts the project and the project is fully migrated to PRAGMA 

> [!TIP]
> The Pragma Decision Record will follow the process described here [PDR-0001-Process](https://github.com/pragma-org/PDRs/tree/main/PDR-0001-Process) </br>
> A reference template is available in [.github/PDR-Template.md](https://github.com/pragma-org/PDRs/blob/main/.github/PDR-TEMPLATE.md)

PRAGMA differentiates between two types of projects:
 - PRAGMA Prospective Projects: projects that are not yet part of PRAGMA but are in the process of joining.
 - PRAGMA Projects: projects fully recognized as part of PRAGMA and part of the PRAGMA GitHub organization.

PRAGMA projects can have the state of "prospective", "active" and "archived"
- Prospective projects are projects that are in the process of joining PRAGMA. They follow the same rules as active PRAGMA Projects but have yet to be fully accepted.
- Active projects are projects that are part of PRAGMA.
- Archived projects are projects rejected by the Administrative Board or the General Assembly and don't want to become PRAGMA projects, or projects that are no longer operating.

### Prospective Project phase

Becoming a "Prospective Project" is decided by the Administrative Board upon meeting specific criteria. </br>
After submitting a PDR to this repository, the project owner is invited to a meeting with the Administrative Board to review if the following conditions are met:
  - The project is aligned with PRAGMA's goals,
  - The source code original owners are willing to donate the project to PRAGMA and make every aspect of it open-sourced,
  - The project does not have any legal issues, such as copyright infringement,
  - Trademarks are cleared and the owners are willing to donate them to PRAGMA,
  - The project has a clear roadmap aligned with its objectives,
  - No other pressing reasons come up during the review.

The Administrative Board will then vote to accept or reject the project.

> [!NOTE]
> The Administrative Board will vote according to the following rules: [PDR-0002-Voting](https://github.com/pragma-org/PDRs/tree/main/PDR-0002-Voting)

Prospective projects can use PRAGMA's resources and are allowed to use the PRAGMA brand. </br>
However, prospective projects must clarify that they are not yet part of PRAGMA and add a "Prospective" disclaimer to their communications.

### Becoming a PRAGMA Project

After succesfully having quaterly reviews, the Administrative Board can propose the Prospective Project to the General Assembly to become an active PRAGMA project. </br>
What makes a PRAGMA project is the decision of the General Assembly. The General Assembly will invite the project and its maintainers to a review and accept or reject the project given the following requirements are met:

> [!NOTE]
> This list of requirements is not yet finalised as we are still exploring the criterias to be met that goes in line with PRAGMA's ideas of open source projects

- The project must have more than three active contributors.
- The project must have demonstrated its ability to grow by offering a clear path to join its new contributors.
- The project made at least three, acceptable releases.
- The project provides quarterly reports on time.
- The project's name is clear and free of trademark disputes, cultural appropriation, and other issues.
- The source code was either only developed by project team members or accepted by using a DCO.
- The source code is published in the PRAGMA GitHub organization.
- The source code is licensed under a PRAGMA-approved license.

As soon as there is a successful vote by the General Assembly, the project becomes an active PRAGMA Project.

### Retiring projects 

Archived projects are read-only, do not need to be reported, and will be labeled as archived in the GitHub repository. </br>
Archived projects will not be deleted but made accessible for future generations. </br>
PRAGMA Prospective Projects that have been "rejected" will also be labeled as archived and it will be explicitly mentioned that the project was not accepted by the Administrative Board or the General Assembly and was never accepted by PRAGMA.

## Discussion points

### Positive outcomes

- Clarity in accepting or rejecting projects
- Protection from legal issues
- Transparency in the process
- Fairness in the decision-making process

### Negative outcomes

- The process may slow down the acceptance of projects

## Future implementation ideas

The following items are not yet implemented but are part of the next evolution

### Mentoring

Once becoming a prospective project, the project will have a mentor designated, it will be either be: an Administrative Board member, a PRAGMA member, or a PRAGMA maintainer. 
The mentor will guide the project through the incubation phase and support it by answering any questions the maintainers might have. 
The mentor will take care that the Administrative Board report is sent in time and clarify reporting related topics.
The mentor will work with the project and provide them guidance and support to meet the requirements for a successful graduation.
