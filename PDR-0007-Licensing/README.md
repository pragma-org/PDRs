---
PDR: 0007
Title: PRAGMA Licensing
Category: Policy
Status: Proposed 
Authors:
 - Christian Grobmeier <cg@grobmeier.de>
 - Damien Czapla <damien.czapla@openthelead.com>
 - Sebastian Bode <sebastian.bode@cardanofoundation.org>
Created: 2024-08-01
---

## Context

Every Open-Source project needs a license (see discussion [here](https://opensource.stackexchange.com/questions/1720/what-can-i-assume-if-a-publicly-published-project-has-no-license) and more elaborate explanation [here](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#choosing-the-right-license)).
PRAGMA must decide whether one or multiple license types (e.g. MIT, MPL, Apache License version 2.0) are recommended or enforced on projects.
The decision subject to this PDR will impact the discussion about the *identity of the association*.

## Decision

Open source projects under PRAGMA will have to use the [Apache License version 2.0](https://www.apache.org/licenses/LICENSE-2.0) (ALv2) for their projects.
Projects under PRAGMA can use other open source license types but the decision and the reasonning behind choosing another license type will have to be agreed with the Administrative board of PRAGMA.
Projects under PRAGMA also have access to our legal partner (currently [PRINS](https://prins.swiss/en/)) who can advise on the best strategy regarding Intellectual Property rights.

## Consequences

This section is meant to be informative and will evolve depending on the usecases and understanding of the various licenses existing.
<!--- To do Christian: Rework that section to describe the types of protection that comes with use cases and licensing (copyleft) (copyright) and illustrate which types of licensing has which pros&cons for each situtation


Various Open Source Organizations solve this differently. 

- Apache Software Foundation: uses Apache License 2.0 exclusively.
- Free Software Foundation (FSF): GPL, LPGL, AGPL, FDL.
- Eclipse Foundation: EPL (others permitted with special approval)
- Mozilla Foundation: MPL mostly, but does not strictly enforce
- Linux Foundation: no licensing policy. 

Whether there is strict license enforcement or none at all, a foundation's face is shaped by it. 

For example, the FSF supports various solid political statements that can only be upheld with the licenses it provides. Other foundations check on enforcing a license so they know precisely about all legal implications. 
The Linux Foundation feels like a "Foundation to build Foundations," giving maximum freedom.

The following document outlines various aspects. 

### Enforcing single licenses

The ASF is very strict with a single license, the Apache License. Requiring all projects to use this license is not only because of the foundation's philosophy but also for other reasons.

- Legals and simplicity. When projects use only one license, the legal landscape 
  is often simplified. Everyone, including downstream users of PRAGMA, would need 
  to figure out exactly what to expect regarding rights and obligations. 
  Legal simplicity is also very business-friendly since auditors and advisors 
  will do less work to check the details.
- The Contributor License works well with the Apache License. All contributions 
  are easily applied to the Apache License.
- The risk of license incompatibility or conflicts can be handled very clearly. 
  Dependencies of dependencies may have licenses that the maintainer does not expect. 
  Using a single license, the foundation can create rulesets of what is safe and what is not.
- Avoiding fragmentation: Some PRAGMA projects could face problems in the future 
  when operating with other projects that use different licenses.
- Predictable: PRAGMA would create a predictable environment for contributors and 
  users by enforcing a single license. Contributors know how their work is licensed,
  and users know about their obligations.
- Focus on innovation: with a clearly defined environment, PRAGMA would allow 
  developers to focus on innovation rather than legal aspects.
- Philosophic consistency: whatever philosophy PRAGMA will adopt, the single license 
  should reflect it and support it.

A document that shows how projects can use the Apache License was crafted at the ASF:
https://www.apache.org/legal/resolved.html

### Allowing a limited set of licenses for PRAGMA projects

The FSF allows multiple licenses, and this model could also work for PRAGMA. 
In that case, PRAGMA would require projects to adopt licenses from a limited list, like 3 or 4.

- Projects would be given more freedom to choose their license. 
  Some may choose MIT, some GPL. Since projects are more flexible, the contributor 
  base could grow since developers may find their preferred license supported.
- License complexity: allowing multiple licenses may introduce risks of license incompatibility. 
  It could become complicated if two projects use different licenses but wish to interoperate. 
  Analysis needs to be done for all the supported licenses.
- Legal overhead: PRAGMA's legal team, downstream users, and auditors will 
  need to understand the differences between the licenses and verify whether 
  there are conflicts. With a limited set of licenses this might be doable, 
  but so bigger the list of supported licenses grows, so more complicated it will become.
- Contributors will need to be aware of the license they are working on. With CLAs, 
  they would need to sign multiple CLAs, based on the project's license. 
  Contributors will need to understand the various aspects of the licenses.
- Every license has a philosophy behind it; PRAGMA would allow projects to experiment with these philosophies.
- Allowing multiple licenses will change PRAGMA's nuance and give it a flexible and inclusive nuance. 
  However,PRAGMA's foundation philosophy might be less clear about open-source principles.
- Community fragmentation: different licenses may create silos within the PRAGMA community.
- Project interoperability: making PRAGMA project depend on other PRAGMA projects will be harder.

### Allowing any license

The Linux Foundation does not restrict licenses.

- Projects need specific licenses, attract diverse contributors, and be free 
  to experiment as they like. New licenses might be adopted as soon as they are published.
- There is a high risk of license incompatibility. Because more licenses are needed, 
  interoperability is more challenging. 
- Legal risk for users: Downstream users, especially organizations, may face 
  legal uncertainty or danger when using PRAGMA projects. Businesses could avoid 
  PRAGMA projects because of the legal overhead of auditing.
- Strong silo creation for communities. Different licensing philosophies 
  (permissive versus copyleft) will create divisions in the PRAGMA community.
- It might be harder to foster a unified identity. PRAGMA's identity might be 
  harder to communicate, and the mission or philosophy might be driven in different 
  directions as projects choose different licenses. This could weaken the 
  PRAGMA brand and the ability to promote a unified version of open source.
- The same problems with CLAs might occur as with multiple licenses.
- Without a clear stance on licenses, industry stakeholders may find it challenging 
  to understand what PRAGMA stands for, which can impact trust and engagement.

### Example: MIT and ALv2

Both licenses, MIT and ALv2, are considered very similar. However, the 

ALv2 makes it very clear that you have a license to the code but not to the trademark. This avoids confusion about branding and protects the foundation and the project maintainers to retain control of their trademark.
The MIT license does not make this very clear. While it does not mean you can use trademarks, the lack of explicit language can lead to legal risks.

The ALv2 explicitly grants patents. It clarifies that contributors to the project are also licensing relevant patents they own to users.
MIT does not do that, and it is not considered an immediate risk for patent lawsuits. Still, it can leave users in more vulnerable positions, mainly if the code is later found to infringe a patent held by one of the contributors.

The ALv2 is more robust about US copyright law. It defines what a contribution is and what is granted, which better protects contributors and users.
The MIT license does not handle copyright matters that well. It usually works straightforwardly but leaves room for interpretation, especially in the US.

In this example, if a project needs to decide whether to use MIT or ALv2, there are most likely no reasons to choose MIT over ALv2, especially when copyright, trademarks, or patents are a concern. 

### Hypothetical Example: Patent Right Assignment

Imagine ACME contributes code to a PRAGMA project under the Apache License 2.0 (ALv2). By doing so, ACME automatically grants a patent license to anyone using that code. This protects PRAGMA and downstream users from patent lawsuits related to ACME's contribution.

Now consider another company, BETA, that holds a patent relevant to the same code but didn't contribute anything. Since BETA didn't contribute, users don't get any patent rights from them. If BETA's patent is infringed, they could still come after PRAGMA or its users.

The ALv2 protects against patent claims from contributors like ACME, but not from BETA. If PRAGMA used MIT, which does not include an explicit patent grant, our users would be more vulnerable to legal issues.

With MIT:

 - Developers (contributors) and users can both be sued in patent lawsuits.

With ALv2:

 - Developers (contributors) cannot later sue users for patent infringement on code they contributed.
 - A third party can sue developers (contributors) if the code infringes on their patents.
 - Users are protected from developers (contributors), but they can be sued by third parties like BETA.

 --> 

### Outcomes

- Guidelines on what to use and what not
- A clear philosophy behind licenses (not restricting is also a philosophy)
- Preparation for legal questions, as seen in the example MIT versus ALv2

### Questions

- Which industry are projects under PRAGMA targeting? What are the preferred licenses?
- What kind of philosophy do we want to carry?
- Why do we need other permissive licenses, when ALv2 is already permissive?
- How do we handle the legal overhead?
- How does PRAGMA foster collaboration between various projects with different licenses?

## Discussion points
<!-- Summarizes, a posteriori, the major discussion points that gravitates around the decision -->

