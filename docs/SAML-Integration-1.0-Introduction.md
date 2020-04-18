# SAML Integration - Introduction

In order to connect your application to the Nova Scotia Login System (NSLS) there are several cryptographic elements that need to be created in order to ensure secure communication between the Identity Provider (IdP) and your application (also known as a Relying Party (RP)).

Securing communication between the Nova Scotia Login Service and your application involves both digital encryption and signing. 

* Encryption is the process of encoding messages in order to ensure that the message is only accessed by authorized people or systems. 
* Signing ensures the messages came from people or systems that we trust.

## SAML 
Security Assertion Markup Language (SAML) is an XML-based framework for authentication and authorization between two entities: an RP and IdP. The RP agrees to trust the IdP to authenticate users. In return, the IdP generates an authentication assertion, which indicates that a user has been authenticated.

SAML is a standard single sign-on (SSO) format. Authentication information is exchanged through digitally signed XML documents, enabling seamless authentication.
