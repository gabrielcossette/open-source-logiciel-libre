# Guides for Using Open Source Software

* Active and Fair Consideration
* Compliance
* Types of use
  * Without modification
    * Combination of components and development
  * With modification

## Active and Fair Consideration

### Enterprise Architectural Assessments

[Directive on Management of Information Technology](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249) indicates the required enterprise architectural direction for evaluating technology in a project, including software.

### Open Source Software Evaluation

The same factors applicable to an evaluation of the feature set and maturity of closed-source software also apply to OSS. A few additional criteria should be assessed when evaluating OSS:

#### User Community

A strong user community involved in a project provides people to answer questions, test the software, report bugs, suggest improvements and drive forward overall interest in the software.
Look at the software's public code repository and check the project popularity by looking at the number of likes and followers.
Check how active the project responds to users by looking at issues and the time between replies.

#### Developer Community

A strong developer community with a history of releases and continued involvement tends to demonstrate that fixes and improvements to the software will continue into the future.
Look at who are the core developers and who is supporting the project and community.
Look at when the project got started, the pace of releases and responses to requests to merge code from contributors.

#### Availibility of Support

Use of open source software introduces a different model of obtaining software than user licences. Since a financial transaction may not have occured, it is important to have a proper process and tracking mechanism in place to manage the introduction of open source software to ensure a secure maintenance of updates and upgrades.  The two major support models for open source software are self support, where the department or agency's IT team is responsible for maintenance and upgrade or professional support.

Availability Support considerations include user support (i.e., the availability of assistance with installation and usage) and maintenance (i.e., fixing problems in the software). Support for OSS can be provided by the community and/or paid support services businesses.

##### Self-support

* Maintain and track thorough lists of open source software used and ensure updates are applied carefully.
* Community support for issues and questions can be used but this model of support is essentially the same as for internally developed source code.
* [GCDevExchange](https://gcdevexchange-carrefourproggc.org/en) may be used to have some custom code written for the government of Canada as open source through a bidding process. Code developed through this platform should be published as open source. See [Publishing Open Source Code](../publishing-open-source-code.md) for more information.

##### Professional Support

Choosing an open source software and using the community version, then going for tender for professional support and maintenance is an option. However, proper guidance needs to be confirmed with legal and procurement teams.

It is possible to enter in contract with a company for professional services to provide maintenance, updates, warranty and liability, just like any other software. In fact, this is already in place in the government but clear guidance for scalable contracting needs to be worked out.

#### Documentation

User documentation provides important information to help users install software and use its features. Technical documentation provides requirements and instructions for installation, development, deployment and configuration of the software.

#### Security Assesments

Although OSS code is auditable, this does not necessarily mean it is secure. The quality of the code and the typical response time for patching security-related flaws help indicate the security level of the software. **Should have a process to list all packages and maintain versions, just like any other software.**

## Compliance

The use of open source software must be done in compliance with the terms and conditions under which it is released. Unlike closed-source software, the licences are provided publicly with a set of rights and constraints.

Depending on the intended use, the licence under which an open source software was released may put some specific requirements on the user.

## Types of use of open source software

* [Without modification](#without-modification)
  * [Combination of components and development](#combination-of-components-and-development)
* [With modification](#with-modification)

### Without modification

This section covers the use of open source software without modifications.
The software could be used for scripts, libraries, plugins, platforms, applications, services, databases and operating systems for servers, desktops and devices, essentially like Commercial Off-The-Shelf (COTS) software, solutions and tools.
This includes configurations and combinations of multiple open source software and it's use in development.

|                                          | Standalone | Combination of components | Development |
| ---------------------------------------- | ---------- | ------------------------- | ----------- |
| **Examples** | Web browser, HTTP server, Database management system, Container platform, Operating system and utilities (Window manager, Text editor, Shell (console)..), .. | Application and plugins with database and web server | Custom development using open source software programming languages and dependencies |

The following applies to all types of use of open source software without modifications.

#### Approvals

Approvals reside with each government department or agency's information management and technology group.

#### Licenses

All open source software licensed under an [Open Source Initiative approved license](https://opensource.org/licenses) can be used as long as its use is compliant with its terms and conditions.
Using open source software without modifications internally (within the Governemnt of Canada) and for public facing applications is not considered distribution and does not require that code be shared back.

#### Open Resource Exchange

Add all open source software your department or agency is using to the [Open Source Software section on the Open Resource Exchange](https://canada-ca.github.io/ore-ero/open-source-software.html).

Instructions for how to updated the data can be found on [GitHub](https://github.com/canada-ca/ore-ero/tree/master/_data).

#### Combination of components and development

##### Licences

* Be careful when combining code with different licenses (dynamicly linked dependencies or directly including code).
* Certain licenses are incompatible when combined in the same program.
* Maintain updates and need to log all licences for notices and legal audits.

Your legal team should be contacted to help understand the nuances of the licences.

See [Guides for Publishing Open Source Code](publishing-open-source-code.md) developped.

### With modification

This section covers the use of open source software with modification weather its scripts, libraries, plugins, platforms, applications, services, databases and operating systems for servers, desktops or devices.

#### Licences

All open source software licensed under an [Open Source Initiative approved license](https://opensource.org/licenses) can be used as long as its use is compliant with its terms and conditions.

Using open source software with modifications internally (within the Governemnt of Canada) and for public facing applications is not generally considered distribution and does not require that code be shared back.
See notes on AGPL below.

##### AGPL like reciprocal implications

The AGPL reciprocal licence and others like the EUPL require that source code for applications accessed through a network (like the Internet) be made available.

See [Guides for Publishing Open Source Code](publishing-open-source-code.md).