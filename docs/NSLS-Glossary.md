# Glossary

### Credential LOA 
Credential Level of Assurance, or LOA, is a relative measure of the strength of the authenticator or authenticators being used to authenticate to a given system. This can range from username and password at LOA2 to strong cryptographic authentication at LOA4.

### Digital Service
The term used to describe what is being accessed and needs to be protected (e.g. NS Online).

### Identity LOA
Identity Level of Assurance, or LOA, is a relative measure of the strength of assurance that can be placed on an identity claim. Assurance levels correspond directly to the certainty one has with respect to an identity claim.

### OIDC - Open ID Connect
An authentication layer on top of OAuth 2.0, an authorization framework. The standard is controlled by the OpenID Foundation.

### Relying Party (RP)
The organization (e.g. government department) that uses (or relies upon) the identity services, e.g. Nova Scotia Online.

### SAML
Security Assertion Mark-up Language – An Authentication and Authorization standard developed and managed by the OASIS standards body.

### Service Provider (SP)
See Relying Party (RP). These terms are used interchangeably.

## Public Key Cryptography and Public Key Infrastructure

### Private and Public Keys
The private key is a hexadecimal number that must be closely guarded. 
The private key is used initially to generate a Certificate Signing Request (CSR), and later to secure and verify connections using the certificates created per that request. 
The private key is also used to create a digital signature. 
A public key is created at the same time as the private key and can be openly distributed without compromising security.

### Public Certificates
A public certificate is an electronic document used to prove the ownership of a public key.

### Certificate Signing Requests
Certificate signing request (also CSR or certification request) is a message sent from an applicant to a certificate authority in order to apply for a digital identity certificate. 

### Identity, Credential, and Access Management (ICAM)
A set of security disciplines that allows an organization to enable the right individual to access the right resource at the right time for the right reason. It is the tools, policies, and systems that allow an organization to manage, monitor, and secure access to protected resources. These resources may be electronic files, computer systems, or physical resources such as server rooms and buildings.

### Identity and Access Management (IAM)
A framework of policies and technologies for ensuring that the proper people in an enterprise have the appropriate access to technology resources.

### Metadata
The SAML metadata standard belongs to the family of XML-based standards known as the Security Assertion Markup Language (SAML) published by OASIS in 2005. A SAML metadata document describes a SAML deployment such as a SAML identity provider or a SAML service provider. Deployments share metadata to establish a baseline of trust and interoperability.

### Identity Provider (IdP) 
Identity providers offer user authentication as a service. Relying party applications, such as web applications, outsource the user authentication step to a trusted identity provider.
An identity provider is “a trusted provider that lets you use single sign-on (SSO) to access other websites.”[3] SSO enhances usability by reducing password fatigue. It also provides better security by decreasing the potential attack surface. Identity providers can facilitate connections between cloud computing resources and users, thus decreasing the need for users to re-authenticate when using mobile and roaming applications.

### Digital Certificate
In cryptography, a public key certificate, also known as a digital certificate or identity certificate, is an electronic document used to prove the ownership of a public key.[1] The certificate includes information about the key, information about the identity of its owner (called the subject), and the digital signature of an entity that has verified the certificate's contents (called the issuer). If the signature is valid, and the software examining the certificate trusts the issuer, then it can use that key to communicate securely with the certificate's subject.

### Signing Certificate
A digital signing certificate is an electronic document issued by a Certificate Authority (CA). It contains the public key for a digital signature and specifies the identity associated with the key, such as the name of an organization. The certificate is used to confirm that the public key belongs to the specific organization.

### Encryption Certificate
A digital encryption certificate is used to encrypt online data/information communications between an end-users browser and a website. After verifying that a company owns a website, certificate authority will sign their certificate so it is trusted by internet browsers.

### Identity Manager (IDM)
Under review

### Claim
Under review

### Assertion
Under review

### Cryptography
The conversion of data into a secret code for transmission over a public network. Today, most cryptography is digital, and the original text ("plaintext") is turned into a coded equivalent called "ciphertext" via an encryption algorithm. The ciphertext is decrypted at the receiving end and turned back into plaintext.

### Personally Identifiable Information (PII)
Personally identifiable information, or PII, is any data that could potentially be used to identify a particular person. Examples include a full name, driver’s license number, bank account number, passport number, and email address.

PII is often discussed in the context of data breaches and identity theft. If a company or organization suffers a data breach, a significant concern is what PII might be exposed—the personal data of the customers that do business or otherwise interact with the entity.

### Learn More
* https://en.wikipedia.org/wiki/Public-key_cryptography
* https://en.wikipedia.org/wiki/Public_key_infrastructure
