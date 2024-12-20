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

PRAGMA allows projects to join the association. The process of accepting new projects is not formalized in PRAGMA's statutes.

## Motivation

Welcoming projects within PRAGMA needs rules to ensure that the projects are a good fit and the association's goals are met.  
The acceptance process should be transparent and fair.

## Decision

Acceptance will rely upon completing a set of criteria for each stage of the process with ultimate approval from the Administrative Board and the General Assembly.

> [!NOTE]
> If you want to know more about these deciding bodies you can check: </br>
> [.incorporation](https://github.com/pragma-org/PDRs/tree/main/.incorporation) for their composition and [Statutes](https://github.com/pragma-org/PDRs/blob/main/.incorporation/20240422_Attachment_Statutes_Statuten_PRAGMA_signed.pdf) for their mandate

Here is a high level overview of the entire process:
1. A project owner submits a PDR through a pull request on Github requesting to join.
2. The Administrative Board reviews the PDR created and confirms the compliance of the project with the acceptance criteria, potentially then approving for Incubation. A mentor is assigned.
3. The project (after several succesful quarterly meetings) is proposed to the General Assembly by the Administrative Board
4. The General Assembly accepts the project, the Maintainer Committee is created and the project is fully migrated to PRAGMA 

> [!TIP]
> The Pragma Decision Record will follow the process described here [PDR-0001-Process](https://github.com/pragma-org/PDRs/tree/main/PDR-0001-Process)  
> A reference template is available in [.github/PDR-Template.md](https://github.com/pragma-org/PDRs/blob/main/.github/PDR-TEMPLATE.md)

### A few definitions

PRAGMA differentiates between two types of projects:
 - PRAGMA Incubating Projects: projects that are not yet part of PRAGMA but are in the process of joining via Incubation.
 - PRAGMA Projects: projects fully recognized as part of PRAGMA and participate in the PRAGMA GitHub organization.

PRAGMA projects can have the state of "incubating", "active" and "archived"
- Incubating Projects are projects that are in the process of joining PRAGMA. They follow the same rules as active PRAGMA Projects but have yet to be fully accepted and do not yet have a PRAGMA Maintainer Committee.
- Active projects are projects that are part of PRAGMA.
- Archived projects are projects that were not approved or otherwise discontinued.</br>

Here is a representation of the incubation process:
![PRAGMA](https://github.com/user-attachments/assets/ed627a82-3700-4467-b990-d69eaf35f11b)

### Incubating Project phase

Becoming an "Incubating Project" is decided by the Administrative Board upon meeting specific criteria. </br>
After submitting a PDR to this repository, the project owner is invited to a meeting with the Administrative Board to review if the following conditions are met:
  - The project is aligned with PRAGMA's goals,
  - The source code original owners are willing to donate the project to PRAGMA and make every aspect of it open-sourced,
  - The project does not have any obvious legal issues, such as copyright infringement,
  - The project has a clear roadmap aligned with its objectives,
  - No other pressing reasons come up during the review.

The Administrative Board will then vote to accept or reject the project. An accepted Prospective Project then begins Incubation. During Incubation the Incubating Project will be assigned a mentor within PRAGMA's members to assist in navigating this process. 

Incubating Projects can use PRAGMA's resources and are allowed to use the PRAGMA brand. However, Incubating Projects must clarify that they are not yet part of PRAGMA and add a "Incubating" disclaimer to their communications.

> [!NOTE]
> The Administrative Board will vote according to the following rules: [PDR-0002-Voting](https://github.com/pragma-org/PDRs/tree/main/PDR-0002-Voting)

### Mentoring

Once becoming an Incubating Project, the project will have a mentor designated, it will be either: an Administrative Board member, a PRAGMA member, or a PRAGMA maintainer.   
The mentor will guide the project through the incubation phase and support it by answering any questions the project might have.  
The mentor will take care that the Administrative Board report is sent in time and clarify reporting related topics.  
The mentor will work with the project and provide them guidance and support to meet the requirements for a successful graduation.  

### Becoming a PRAGMA Project

After receiving succesful quarterly reviews, the Administrative Board can propose the Incubating Project to the General Assembly to become an active PRAGMA project and create a Maintainer Committee. The decision to accept or reject the project is based on meeting the following requirements:

> [!NOTE]
> This list of requirements is not yet finalised as we are still exploring the criterias to be met that goes in line with PRAGMA's ideas of open source projects

- The project must have more than three active contributors.
- The project must have demonstrated its ability to grow by offering a clear path to join its new contributors.
- The project made at least three, acceptable releases.
- The project provides timely quarterly reports.
- The project's name is clear and free of trademark disputes, cultural appropriation, and other issues.
- The source code was either only developed by project team members or accepted by using a DCO.
- The source code is licensed under a PRAGMA-approved license with PRAGMA as the owner.

As soon as there is a successful vote by the General Assembly, the project becomes an active PRAGMA Project.

### Retiring projects 

Archived projects are read-only, do not need to be reported, and will be labeled as archived in the GitHub repository. Archived projects will not be deleted but made accessible for future generations. PRAGMA Incubating Projects that have been "rejected" will also be labeled as archived and it will be explicitly mentioned that the project was not accepted by the Administrative Board or the General Assembly and was never accepted by PRAGMA.

## Discussion points

### Positive outcomes

- Clarity in accepting or rejecting projects
- Protection from legal issues
- Transparency in the process
- Fairness in the decision-making process

### Negative outcomes

- The process may slow down the acceptance of projects
