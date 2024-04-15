# Welcome to eclipse-kuksa

This Github organization contains artifacts developed by the [Eclipse KUKSA Project](https://projects.eclipse.org/projects/automotive.kuksa).

## Introduction to Eclipse KUKSA Project

See [kuksa-website](https://eclipse-kuksa.github.io/kuksa-website/).

## Repository Status


|   Status              | KUKSA Meaning                                               |
|-----------------------|-----------------------------------------------------------------|
| Planning              | No software/content exists
| Pre-Alpha             | In development, not expected to be functional.
| Alpha                 | Usable for internal use for demo and Proof-of-Concept purposes
| Beta                  | Usable for evaluation and testing purposes
| Production            | Usable for production purposes, actively maintained, new versions regularly released, new features may be added
| Mature                | Usable for production purposes, no new features planned, minimal maintenance
| Deprecated            | Minimal maintenance, End-of-Life date for the repository has been communicated.
| End-of-Life (Archived) | Product/Repo has reached End-of-Life. Pull Requests will not be accepted.
| N/A                   | Repositories not following regular repository life cycle


## Security and Vulnerability process

It is the ambition of the KUKSA project to monitor and address known vulnerabilities for repositories in
status Beta, Production, Mature and Deprecated. This is typically performed by enabling the Github features
for "Security advisories" and "Dependabot alerts".

Repositories in status Beta or Production may also occasionally be security audited by external parties.


## Repositories in the Github organization

### Hardware and Board Support Packages

### Databroker

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa-databroker](https://github.com/eclipse-kuksa/kuksa-databroker)| Production | KUKSA Databroker.

### General Use Clients and SDKs

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa-python-sdk ](https://github.com/eclipse-kuksa/kuksa-python-sdk)| Production | KUKSA Python Client and SDK

### Providers exchanging data with Databroker/Server

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa-can-provider](https://github.com/eclipse-kuksa/kuksa-can-provider)| Production | Python-based provider for CAN
| [kuksa-csv-provider](https://github.com/eclipse-kuksa/kuksa-csv-provider)| Beta | Python-based script to provide data from CSV file
| [kuksa-dds-provider](https://github.com/eclipse-kuksa/kuksa-dds-provider)| Beta | Python-based provider for DDS
| [kuksa-gps-provider](https://github.com/eclipse-kuksa/kuksa-gps-provider)| Beta | Python-based provider for gpsd
| [kuksa-someip-provider](https://github.com/eclipse-kuksa/kuksa-someip-provider)| Alpha | Python-based PoC provider for SOME/IP using vsomeip
| [kuksa-mock-provider](https://github.com/eclipse-kuksa/kuksa-mock-provider)| Alpha | Python-based provider for mocking VSS signals (to help testing VSS applications)

### Android Development

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa-android-sdk](https://github.com/eclipse-kuksa/kuksa-android-sdk)| Alpha | Android SDK for KUKSA
| [kuksa-android-companion](https://github.com/eclipse-kuksa/kuksa-android-companion)| Alpha | The KUKSA Companion App demonstrates the capabilities of the Android SDK


### Hardware and Board Support Packages

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa-hardware ](https://github.com/eclipse-kuksa/kuksa-hardware)| Mature | This repository contains information and manufacturing files for the CANOPi automotive prototyping platform.

### Administration and Common Resources

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [.eclipsefdn](https://github.com/eclipse-kuksa/.eclipsefdn)| N/A | Management of repositories in this organization
| [.github](https://github.com/eclipse-kuksa/.github)| N/A | Manages this README
| [kuksa-actions](https://github.com/eclipse-kuksa/kuksa-actions)| N/A | Actions used as part of Github Continuous Integration
| [kuksa-common](https://github.com/eclipse-kuksa/kuksa-common)| N/A | VSS catalogs and Certificates and Keys for test purposes.
| [kuksa-website](https://github.com/eclipse-kuksa/kuksa-website)| N/A | Sources of the KUKSA website

### Other Repositories

*Proof-of-Concepts, Demonstrators and other initiatives.*

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa-viss](https://github.com/eclipse-kuksa/kuksa-viss)| Deprecated (EoL 2024-12-31) | VISS2 compatible adapter for KUKSA Databroker
| [kuksa-incubation](https://github.com/eclipse-kuksa/kuksa-incubation)| Alpha | Proof-of-Concepts, Demonstrators and other contributions that not (yet) qualify for being separate repositories


## Other Eclipse KUKSA Repositories not in this organization

### Deprecated Repositories

*The repositories below contain outdated or deprecated content and should not be used unless you need to use a deprecated component*
*or an older version!*

|   Repository        | Status         | Content/Comment
|-----------------------|----------------|---------------------|
| [kuksa.val](https://github.com/eclipse/kuksa.val)| Deprecated | KUKSA Server and some more deprecated artifacts
| [kuksa.val.feeders](https://github.com/eclipse/kuksa.val.feeders)| Deprecated| Feeders/Providers, all except deprecated providers migrated.
| [kuksa.val.services](https://github.com/eclipse/kuksa.val.services)| Deprecated| Examples services using KUKSA, all migrated
