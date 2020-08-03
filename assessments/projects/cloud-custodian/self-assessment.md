# Cloud Custodian Security Self-assessment

Last Updated: TODO
Authored by: Robert Ficcaglia (@rficcaglia)

Contributors: TODO

Security Reviewers: Justin Cappos (@JustinCappos)

This document details the design goals and security implications of Cloud Custodian to aid in the security assessment by CNCF SIG-Security.

## Metadata

TODO



## Overview

TODO

### Background

TODO

### Goals

TODO

### Non-Goals

TODO

## Intended Use

TODO
### Target Users

For **operators and security administrators** ...

For **application developers*** ...

For **platform implementers*** ...

For **third party security products and systems*** ...

For **compliance officers and auditors** ...

Others TODO

### Use cases

Examples of common use cases for Cloud Custodian include:

#### UC #1

#### UC #2


## Operation

TODO

## Project Design

### Cloud Custodian Architecture

#### COMPONENT #1

#### COMPONENT #2


## Configuration and Set-Up


### Security Considerations when operating in Kubernetes

### Considerations when using third party plugins

### Considerations when using third party services

### Scaling Cloud Custodian


### Third Party and Cloud Platform Integrations

### Federation Support ?

## Compliance

TBD: Cloud Custodian does/does not  document meeting particular compliance standards?

## Security Analysis

### Attacker Motivations

TODO

### Critical Functions

TODO

### Attacks

#### ATTTACK/THREAT # 1


#### ATTTACK/THREAT # 2


#### ATTTACK/THREAT # 3


### Attack Risks and Effects

TODO

## Secure Development Practices

Cloud Custodian does/does not have a documented development workflow ?

Some questions:

-   All source code is checked into GitHub?

-   Every pull request kicks off a build which performs unit tests, benchmark tests and language best practices enforcement?

-   Each pull request requires an approval from a reviewer member before merging?

    -   The reviewer makes sure all checks and tests are passing?

    -   The reviewer pays close attention to any new exported methods or interface definitions?

    -   Based on the changes made, reviewer sees that the docs are updated accordingly?

-   Pushes to master are forbidden by convention?

-   Project asserts that it meets the passing criteria in the Core Infrastructure Initiative (CII) badging process?

-  Documented Release process?

    -   releases are numbered with the changelog and binaries published ?

    -   Release process is automated?

    -   Checksum files for release artifacts are provided?

**CII Best Practices**

Is Cloud Custodian adhering to the Core Infrastructure Initiative (CII) best practices badging program?

## Communication Channels

-   Slack ?

-   Meetings?

Announcements about SPIFFE and SPIRE releases, new features, and general updates are shared through ?

## Security Issue Resolution

Security vulnerabilities are reported by sending an email to TBD. 

Project Response Team?


## Ecosystem

Relevant/required open-source projects:

TODO

## Roadmap

TODO 

# Appendix

## Prior Security Assessment?


## Case Studies/User Stories?

TODO

## Related Projects / Vendors

TODO

## References/links:

TODO
