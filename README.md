# Nova Scotia Login Service
Tools, templates and documentation to help developers integrate their products with the Nova Scotia Login Service

## What is the Nova Scotia Login Service (NSLS)? 
The NSLS is an Identity and Access Management system (IAM) designed to provide individuals access to Nova Scotian digital services. 

The NSLS provides a single, centrally managed credential and identity to users. NSLS functionality includes:

* account creation
* authentication
* authorization
* revocation
* single sign-on
* global logout 
* profile management

## Who uses the NSLS?
The system is currently being used by over 100,000 users (citizen, non-citizen and Nova Scotia provincial employees) who require access to online government services. 

Individuals can create an NSLS username and password to login, while employees can use their Active Directory (STS or Health ADFS) credentials. 

## What features can the NSLS provide Department Applications?
In addition to the core authentication and identity management features, the NSLS has several configurable features that Department Applications (further defined as Relying Parties) can choose from. These features include:

* role-based access controls;
* Relying Party (RP) affiliations and;
* authentication source control (citizen and/or employee)

## How does your application integrate with the NSLS?
Relying Parties will need to ensure their application is either SAML 2.0 or OIDC 1.0 compliant, i.e. they must have the ability to send, receive and process SAML or OIDC requests/responses. See our [RFP Requirements documentation](./RFP%20Documentation/Digital%20Identity%20-%20RFP%20Requirements%20-%2020190314.docx).

## What information is provided in the SAML/OIDC messages?
The NSLS will send a SAML or OIDC response message back to Relying Parties after a successful authentication. Included in that message is a configurable set of user attributes including:

* the user’s name
* email address
* a unique identifier/GUID 

Applications will also receive logout, revocation and change notification messages.

## What types of applications can be integrated with the NSLS?
Any web or mobile application that has access to the internet can be integrated with the NSLS. 

## What if it is necessary to keep existing users’ accounts?
While the migration process will vary between RPs, DPS will work with any new RR to create a unique, automated user migration process to ensure historic user accounts are not lost when the service is connected to the NSLS.

## What other Services are provided with the NSLS?
As part of the managed service, the NSLS provides: 

* a bilingual customer facing (Tier 1) Service Desk 8AM – 8PM AT
* Monday to Friday to provide end user support
* online self-serve options
* group membership management

##	High Level  Overview

The NSLS is architected to rely on industry leading technologies which meet and exceed the requirements defined by the Province of Nova Scotia's Digital Platform Services (DPS) team. The architecture has been influenced by relevant Canadian standards such as:

* [Pan-Canadian Trust Framework (DRAFT)](https://diacc.ca/pan-canadian-trust-framework/)
* [Pan-Canadian Assurance Model](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=30678&section=html) 
* [Cyber Authentication Technology Solutions (CATS 2.0)](https://canada-ca.github.io/CATS-STAE/archive/CATS_V2_0_Deployment_Profile_Final_r8_2_en.pdf)
