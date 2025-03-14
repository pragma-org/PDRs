---
PDR: 0002
Title: PRAGMA administrative board - Voting process 
Category: Process
Status: Accepted 
Authors:
    - Christian Grobmeier <cg@grobmeier.de>
    - Damien Czapla <damien.czapla@openthelead.com>
Created: 2024-06-03
---

## Context

In PRAGMA's statutes, the board is responsible for implementing, managing, and overseeing PRAGMA's administration of PRAGMA.
The statutes do not mention details in the decision-making process.

## Motivation

The rules behind the decision-making and voting process of the Administrative Board need formalization.
The approach used for this process should be based on a consensus mechanism.

## Decision

The board can only vote on procedural questions related to the association; they will use the [PRAGMA Decision Record process](../PDR-0001-Process/README.md) to document them.

The board will be voting using a "majority vote" rule, meaning once three board members have voted "in favor" a decision is accepted.

Each voting must comply with the following rules:

1. The voting will have to take place with a set agenda (normally sent out one week before the meeting), and the votes will be recorded in the minutes of the meeting by a designated Secretary for the meeting in [.validityreview][Archive].
2. A quorum will be required for the decision-making to happen: at least four of five board members have to be present; if a board member is aware in advance that they will be absent, they may nominate a proxy from the board members (via email) whom they will advise how best to represent their opinions.
3. The voting is done by show of hands or by equivalent electronic means; the vote can be "in favor" or "against".
4. If there's a tie (e.g., two votes accepted; two votes rejected), the decision will be postponed to a makeup meeting within two weeks, where the absent board member will have to be present to vote; during that meeting if there is a tie again, the Lead Administrator has a casting vote.
5. All Pull Requests in the PDR GitHub repository require the approval of 3 board members automatically before it can be merged. This should be completed before the meeting is concluded by the approving members. 

### Electronic Votes
1. Electronic votes should be held via the GitHub Pull Request approval process, also documenting the approval for all to see.
2. All Pull Requests in the PDR GitHub repository require the approval of 3 board members automatically before it can be merged. The remaining members should still cast their vote so it may be recorded. 

## Consequences
### Positive outcomes
- Clarity in decision-making: a public voting process ensures that all board members 
  and interested parties know how decisions are made. 
  This process will reduce confusion and improve governance.
- Transparency: Recording votes and maintaining minutes allow everyone to review the decision-making.
- Consistency: A formalized process helps that decision-making is consistent across different meetings.
- Efficiency: Clear rules for quorum and tie-breaking help to reduce the time on procedural issues.

### Negative outcomes
- More bureaucracy: the voting process may slow down the decision making due to the reliance on meetings.
- Attendance requirement: board members' attendance is more important, especially for the quorum and tie-breaking procedure.

## Discussion points
- Deadlocks: when there is a tie, absent members may cause further delays of important decisions

[Archive]: https://github.com/pragma-org/PDRs/tree/main/.validityreview
