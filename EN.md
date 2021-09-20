![Riigi Infosüsteemi Amet](https://github.com/e-gov/RIHA-Frontend/raw/master/logo/gov-CVI/lions.png "Riigi Infosüsteemi Amet")

[ET](https://github.com/e-gov/NT) | EN

# Consent Service

Consent Service is an initiative led by the Estonian Information System Authority to build a universal, decentralized and scalable solultion for managing consents used for data processing. Reference architecture along with the first prototype was published in December 2019 and several pilots are planned in the second half of 2020 with healthcare data as the first priority. Main use cases include sharing personal data from public sector databases to private sector entities for the purpose of creating highly personalized value adding services. 

## Solution prototype

This initial prototype is slightly different from the real solution, but gives a good overview of Consent Service functioning.

The aim of the prototype is to validate the initial consent service architecture and protocol through demonstrating potential use-cases from health sector. The prototype demonstrates the setup phase, end-user interfaces and the messages exchanged between the involved parties, providing a better understanding of such a system.

Service provider - Health Information System, containing the protected health data
Client - HealthStartup, wants access to the protected data in order to provide personalized services
Consent Service at TEHIK (Health and Welfare Information Systems Centre) - the provider of consent service

The required information in the setup phase (declaring services and purposes) is largely predefined.

[Link to the prototype](https://e-gov.github.io/NT "prototype")

## Consent giving use case prototype

The prototype shows consent giving proscess and was used in testing of visual solution and UX. The prototype consists of mobile views that can be navigated between by clicking on "active" buttons. The prototype is based on the Medikeep mobile application use case. The process begins in Medikeep application, from there the user is redirected to the Consent Service to give the consent, and ends also in Medikeep application, to which the user is redirected after giving the consent.

[Link to the prototype](https://www.figma.com/proto/AOLWfaI9YWXYouwbksDtos/NT%3A-Medikeep%3A-n%C3%B5usoleku-andmine-ver-03.03.2021?node-id=3%3A1863&scaling=min-zoom "prototype")

## Architecture
[Architecture specification 1.1](https://github.com/e-gov/NT/blob/master/Consent_Service_Architecture.md "architecture")

## Feedback and suggestions

If you want to be a part of the development process by raising issues and providing feedback, please use the "Issues" tab in this repository. Even if the majority is in Estonian, the Estonian Information System Authority will deal with translations once it becomes necessary.


[Link to the "Issues" tab](https://github.com/e-gov/NT/issues "issues")
