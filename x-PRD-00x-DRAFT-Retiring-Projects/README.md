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
Projects may fail incubation or become inactive.
This PDR describes of removing a project from PRAGMA, marking it as inactive or archiving it.

## Decision

PRAGMA differentiates between two types of projects:

 - PRAGMA Projects
 - PRAGMA Incubating Projects

PRAGMA Projects can have the state of "active" and "archived".

Archive projects are read-only, do not need to report and will be labeled as archived
in the GitHub repository. Archived projects will not be deleted, but made accessible
for future generations.

PRAGMA Incubating Projects can have the state of "rejected", which is the equivalent
to "archived" for PRAGMA Projects. Rejected incubating projects follow the same process 
as archived PRAGMA Projects.
In public communication, the term "rejected" will be used to express that the project
was not accepted by the board and never part of PRAGMA.

### Trademarks

Given a project was archived or rejected, no trademarks will be transferred to any third party. 

### Archiving a project

In the case a project is unresponsive to the board or no significant activity
is happening, the board can decide to archive the project. The board will vote on
the resolution through the PDR process and accept or reject the archiving.

### Rejected projects

In the case a project fails incubation, the board will vote on the resolution 
through the PDR process and accept or reject the rejection.


## Discussion points
<!-- Summarizes, a posteriori, the major discussion points that gravitates around the decision -->

[Archive]: https://github.com/pragma-org/PDRs/tree/main/.validityreview