# Nova Scotia Login Service
Tools, templates and documentation to help developers integrate their products with the Nova Scotia Login Service

## What is the Nova Scotia Login Service (NSLS)? 
The NSLS is an Identity and Access Management system (IAM) designed to provide individuals access to Government of Nova Scotia digital services. 

The NSLS provides a single, centrally managed credential and identity to users. NSLS functionality includes:

* account creation
* authentication
* authorization
* revocation
* single sign-on
* global logout 
* profile management

## Who uses the NSLS?
The system is currently being used by over 100,000 users (citizen, non-citizen and Government of Nova Scotia employees) who require access to online government services. 

Individuals can create an NSLS username and password to login, while employees can use their Active Directory (STS or Health ADFS) credentials. 

## What features can the NSLS provide Department Applications?
In addition to the core authentication and identity management features, the NSLS has many configurable features that Department Applications (further defined as Relying Parties) can choose from.

These other features include role-based access controls, Relying Party (RP) affiliations and authentication source control (citizen and/or employee).

## What changes need to be made in order to integrate with the NSLS?
Relying Parties will need to implement minor front-end changes to their application to allow users to login and logout of the NSLS, as well as to access their profile. With respect to required back end changes, RPs will need to ensure their application is either SAML 2.0 or OIDC compliant, i.e. they must have the ability to send, receive and process SAML or OIDC requests/responses. 

## What information is provided in the SAML/OIDC messages?
The NSLS will send a SAML or OIDC response message back to Relying Parties after a successful authentication. Included in that message is a configurable set of user attributes including the user’s name, email and a unique identifier/GUID (PAI). Applications will also receive logout, revocation and change notification messages.

## What types of applications can be integrated with the NSLS?
Any web or mobile application that has access to the internet can be integrated with the NSLS. 

## What if it is necessary to keep existing users’ accounts?
While the migration process will vary between RPs, DPS will work with any new Relying Party to create a unique, automated user migration process to ensure historic user accounts are not lost when the service is connected to the NSLS.

## What other Services are provided with the NSLS?
As part of the managed service, the NSLS provides a Level 1 Service Desk 8AM – 8PM AT, Monday to Friday to provide end user support. In addition, RPs have access 24x7x365 to a Level 2 Service Desk for incident reporting and information requests.
