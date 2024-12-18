---
PDR: 1
Title: PRAGMA Decision Record Process
Status: Accepted
Category: Process
Created: 2024-05-24
Authors :
    - Damien Czapla <damien.czapla@openthelead.com>
    - Christina Gianelloni <christina@blinklabs.io>
    - Christian Grobmeier <cg@grobmeier.de>
    - Daniel Gonzalez <dan@sundaeswap.finance>
    - Federico Weill <federico@txpipe.io>
    - Sebastian Bode <sebastian.bode@cardanofoundation.org>
---

## Context
A Pragma Decision Record (PDR) is a formalised decision-making document for the Pragma organisation. A PDR describes a change within Pragma processes, a policy for maintainers, or a project guideline. In this PDR, we explain what a PDR is; the PDR workflow within Pragma current organisation, to include the role of the PDR Authors and how users should go about proposing, discussing and structuring a PDR. 

## Motivation : Why is this PDR necessary?
PDRs aim to address the discussion and agreement on a common set of processes, rules and guidelines that embodies PRAGMA.

## Decision
PRAGMA will use this workflow to monitor and record all decisions regarding processes, policies & guidelines.

We currently recognise and record four types of decisions:

- `Process`: decisions related to the overall process that must be applied by the PRAGMA organisation.
- `Policy`: decisions that creates a rule that all lead maintainers must apply within their project environment
- `Guidelines`: decisions that formalise a best practice from a project as a recommendation
- `Proposals`: decisions that propose a new project to become part of PRAGMA

## Consequences
The items described below detail the workflow, the stakeholders, and the documentation required to run the process.

### Table of Contents
   * [Process](#process)
      + [1. Submitting a decision proposal](#1-submitting-a-decision-proposal)
         - [1.a. Authors open a pull request](#1a-authors-open-a-pull-request)
         - [1.b. An Authors role](#1b-an-authors-role)
      + [2. Validity review](#2-validity-review)
      + [Board members](#board-members)
   * [PDRs must include](#pdrs-must-include)
   * [Structure related items](#structure-related-items)
      + [Repository Organization](#repository-organization)
      + [Versioning](#versioning)

### Process

![Process image](Process.png)

#### 1. Submitting a decision proposal

##### 1.a. Authors open a pull request
PDRs must be submitted to the [pragma-org/PDRs][PullRequest] repository as a pull request, named after the requests title. The pull request title **should not** include a PDR number (and use `?` instead of a number); the board members will assign one.

##### Link in original comment
In the original comment for your pull request, please include a link to the directory or the `README.md` for the PDR in your working branch so readers and reviewers can easily follow your work. 

##### 1.b. An Authors Role
Authors are people that deemed necessary to transform a group discussion they were having into a decision request for PRAGMAs consideration. Authors shall champion their decision proposals, seeking and being receptive to input from the community. Discussions and comments shall mainly happen on Github, in pull requests. Authors will report back a summary of external discussions to the original pull request, ensuring a singular place for critical conversations.

By opening pull requests or posting comments, commenters and authors agree to our [Code of Conduct][CoC]. Any comment infringing this code of conduct shall be removed or altered without prior notice.

#### 2. Validity review

On a monthly basis, PRAGMA board members will review selected PDRs (based on their readiness and the stability of the discussions) and assess if more information is required or if a decision, accept or reject, can be made. 

PDRs that do not meet a sufficient level of quality/information or that do not abide by the process will be deemed 'Incomplete' until their authors address review comments.

PDRs that are rejected by the board will have the reasons behind rejection documented in the PDR section _'Discussion points'_.

#### Board members

Current board members are listed here below:

| Christina Gianelloni <br/> [@musik-c][] | Christian Grobmeier <br/> [@grobmeier][] |Daniel Gonzalez <br/> [@gonzalaga][] | Federico Weill <br/> [@federicoweill][] | Sebastian Bode <br/> [@cleanerm5][] |
| --- | --- | --- | --- | --- |

[@musik-c]: https://github.com/musik-c
[@grobmeier]: https://github.com/grobmeier
[@federicoweill]: https://github.com/federicoweill
[@gonzalaga]: https://github.com/gonzalaga
[@cleanerm5]: https://github.com/cleanerm5

### PDRs must include

PDRs must include the following information:

Name                                            | Description
---                                             | ---
Preamble                                        | Headers containing metadata about the PDR ([see below](#header-preamble)).
Context                                         | A short (\~200 word) description of the context, explaination of the discussions where the decision came from.
Motivation                                      | A clear explanation of "Why it's necessary to make that decision" introducing the purpose of the decision.
Decision                                        | Clarify the content of the decision by explaining its scope of application with sufficient details to be self-explanatory.
Consequences                                    | Describe the result/consequences of applying that decision; both positive and negative outcomes <br/> If the decisions is a *Policy*, elaborate in that section on how to measure the application of the policy on a project (qualitative or quantitative) by using metrics that can be understood by any internet user.
Discussion points                               | Summarizes, a posteriori, the major discussion points that gravitates around the decision
_optional sections_                             | May appear in any order, or with custom titles, at author and board members discretion:<br/>**Versioning**: to point out majors changes<br/>**References**<br/>**Appendices**<br/>**Acknowledgements**

The document must be formatted into YAML.
> [!TIP]
> A reference template is available in [.github/PDR-Template.md][PDR-Template.md]

### Structure related items

#### Repository Organization

A PDR must be stored in a specific folder named after its number (4-digit, left-padded with `0`) and in a file called `README.md`.


Additional supporting files (such as diagrams, binary specifications, dialect grammars, JSON schemas etc.) may be added to the PDR's folder under freely chosen names.

For example:

```
PDR-0010
├── README.md
├── registry.json
└── registry.schema.json

```

#### Language

PDRs must be written in English.

#### Versioning

Accepted PDRs are final in their content. Any subsantial change must go through another PDR. A previously accepted PDR may be superseded by a new one and its status changed to `Rejected`.

[PDR-TEMPLATE.md]: https://github.com/pragma-org/PDRs/blob/main/.github/PDR-TEMPLATE.md
[Markdown]: https://en.wikipedia.org/wiki/Markdown
[PullRequest]: https://github.com/pragma-org/PDRs/pulls
[CoC]: https://github.com/pragma-org/PDRs/blob/main/CODE_OF_CONDUCT.md
[Discord]: https://discord.gg/fUyPWjBcKE
