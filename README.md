# SSO_Notes

**What is SSO ?**

- SSO stands for **Single-Sign On** 
       
- It is an authentication scheme which enables the user to securly access multiple applications and services using a single ID

- SSO is built on a concept called **federal identity**

- For example : Logging into google account will allow access to Gmail,Google drive,Youtube etc.

**How does SSO works?**

- Open autherization (OAuth) is the framework that enables an end user account information to be used by third-party services such as   facebook without exposing the user's password.

- SSO works by sharing and verifying login credentials between service and identity providers. A **service provider**  is typically a vendor who provides products, solutions, and services to users and organizations, such as an application or website. An identity provider  is a system that creates, manages, and maintains user identities and provides authentication services to verify users. These trusted providers enable users to use SSO to access applications and websites

- When a user is trusted by one system, they are automatically granted access to all others that have established a trusted relationship with it. This provides the basis for modern SSO solutions, which are enabled through protocols like **OpenID Connect** and **SAML**

**Protocols SSO uses**

- SSO has two common protocols : **SAML** , **OpenID connect**

- **SAML** - it stands for `Security Assertion Markup Language` 

- It is a XML base open standard for exchanging identity information
  
- Web applications use SAML to transfer authentication data between two properties : the identity provider(IDP) and the Service provider(SP)

- SAML was created to simplyfy the process of authentication prior to SAML, single sign-on (SSO) was achievable but relied on cookies that were only viable within the same domain. It achieves this objective by centralizing user authentication with an identity provider

- **OIDC** - it stands for `OpenID Connect`

- It is an authentication and authorization protocol used for customer-facing single sign-on, based on the OAuth 2.0 authorization standard 

- It allows Clients to verify the identity of the End-User based on the authentication performed by an Authorization Server, as well as to obtain basic profile information about the End-User in an interoperable


**Advantages of SSO**

- Risk of access to 3rd party sites are reduced as the website database do not store the user’s login credentials.

- No need of creating account and password for each and every application

- With SSO companies can strengthn identity security with techniques such as **Two-factor authentication**

**Disadvantages of SSO**

- If one account of SSO is cracked it is easier to access the rest of the applications

- If an SSO provider is breached or servers go down, all connected services stop and become open to attacks

- If there is a shared computer the user needs access to your password which risks every application


- Although there are some disadvantages in SSO it can be reduced by creating a strong password and improve the security by **two way authentication** 