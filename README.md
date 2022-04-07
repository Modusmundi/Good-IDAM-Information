# Good-IDAM-Information
[//]: # (Greets: jr-pe, Redlegion, topperge, and everyone who gave contributions when I asked them on various platforms.)


The purpose of this document is to capture articles, courses, videos, books, or other forms of media that offer foundational information on Identity and Access Management topics.  These topics include, but are not limited to (As I'm certain I've missed a dozen subtopics):

* Directory Services (DS)
* Directory Virtualization
* Metadirectories
* Role Based Authorization (RBAC)
* Attribute Based Authorization (ABAC)
* Access Management 
* Federation
* Authentication Processes
* Single Sign-On (SSO)
* Certificate Management / Public Key Infrastructures
* Identity Governance and Administration (IGA)
* Privileged Access Management (PAM)
* Auditability, Compliance, and Event Management

<br>

**The Format**  

[//]: # (You absolutely need two spaces after the end of your content to make it line break in Github.  Keep that in mind when building this out.)
***
**Title** (Name of the media)  
**Type**: Book, Article, Course, Podcast, Application, Web application, Etc., etc.  
**Link**: A direct URL to the item.  
**Thoughts**: Notes about the item.  

<br>

## General Tools

### Bash
**Shellcheck**  
**Type**: Web Application  
**Link**: [https://www.shellcheck.net/](https://www.shellcheck.net/)  
**Thoughts**: A fantastic online (And installable / integratable) Bash shell script linter that gives actionable, in-depth rationale for why something is incorrect or provides guidance on how to do it better.  

### Markdown
**Dillinger**  
**Type**: Web Application  
**Link**: [https://dillinger.io/](https://dillinger.io/)  
**Thoughts**: Probably the best online markdown editor out there.  Can integrate with a wide range of services (Including Github!).  Potential downside: No dark mode/theme.  

### JSON


## General Security

**The Blue Team Handbook**  
**Type**: Book  
**Link**: [http://www.blueteamhandbook.com/](http://www.blueteamhandbook.com/)  
**Thoughts**: A condensed and valuable book on blue-team security concerns.  It covers an absolutely staggering amount of information, and offers a launching off point for additional research.  

**Defensive Security Handbook**   
**Type**: Book  
**Link**: [https://www.oreilly.com/library/view/defensive-security-handbook/9781491960370/](https://www.oreilly.com/library/view/defensive-security-handbook/9781491960370/)  
**Thoughts**: A solid book that addresses security topics from an enterprise-minded top-down perspective.  Don't expect this to get very deep on any particular topic, but if you're lacking a conceptual framework in security this is a great place to start.  


## IDAM Foundationals

**Identity Attack Vectors- Implementing an Effective Identity and Access Management Solution**  
**Type**: Book  
**Link**: [https://link.springer.com/book/10.1007/978-1-4842-5165-2](https://link.springer.com/book/10.1007/978-1-4842-5165-2)  
**Thoughts**: A book that covers a great deal of IDAM topics, and does so at a managable level.  It glosses over a lot of topics at the expensive of others (Federation isn't discussed, Authentication gets a few paragraphs, Identity Governance gets tens of pages), which is fair given how expansive IDAM is in terms of processes.

**Solving Identity Management in  Modern Applications**  
**Type**: Book  
**Link**: [https://link.springer.com/book/10.1007/978-1-4842-5095-2](https://link.springer.com/book/10.1007/978-1-4842-5095-2)  
**Thoughts**: An impressive effort that discusses the rammifications of Authentication, Authorization, and Federation within the context of applications.    It does so in a manner that is practical, free of vendor hype, and where possible is standards-driven.

## Directory Services

### LDAP

**Understanding and Deploying LDAP Directory Services, Second Edition**  
**Type**: Book    
**Link**: [https://www.oreilly.com/library/view/understanding-and-deploying/0672323168/](https://www.oreilly.com/library/view/understanding-and-deploying/0672323168/ )  
**Thoughts**: Called by some the LDAP Bible; it's coming up on 20 years old but still provides a rich set of information on LDAP and considerations around LDAP Directory Servers.  

## Metadirectories

## RBAC

## ABAC

## Access Management

## Federation

### OAuth 2 / OpenID Connect (OIDC)

**OAuth 2.0**   
**Type**: Website  
**Link**: [https://oauth.net/2/](https://oauth.net/2/)  
**Thoughts**: OAuth.net is a site maintained by Aaron Parecki.  He jams a lot of good information (Including all of the relevant IETF RFCs) into the site.  He also does a bunch of videos on the topic, if you're into that sort of thing.   

**An Illustrated Guide to OAuth and OpenID Connect**  
**Type**: Web Article  
**Link**: [https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc](https://developer.okta.com/blog/2019/10/21/illustrated-guide-to-oauth-and-oidc)  
**Thoughts**: David Neal does a great job of explaining OAuth and OIDC.    

**Which OAuth 2.0 Flow Should I Use?**  
**Type**: Web Article  
**Link**: [https://auth0.com/docs/get-started/authentication-and-authorization-flow/which-oauth-2-0-flow-should-i-use](https://auth0.com/docs/get-started/authentication-and-authorization-flow/which-oauth-2-0-flow-should-i-use)  
**Thoughts**: Auth0 does a great job of giving reasons to use a specific flow over another when constructing OAuth 2.0 flows.  


[https://youtu.be/996OiexHze0](https://youtu.be/996OiexHze0) - Need to review this

### SAML 2.0

**The Beer Drinker’s Guide to SAML**  
**Type**: Web Article  
**Link**: [https://duo.com/blog/the-beer-drinkers-guide-to-saml](https://duo.com/blog/the-beer-drinkers-guide-to-saml)  
**Thoughts**: A fantastic introductory article on SAML, what it is, and why it is within an approachable lens of Beer as a Service.  

**Security Assertion Markup Language (SAML) V2.0 Technical Overview**   
**Type**: Standards Document  
**Link**: [https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html](https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html)  
**Thoughts**: SAML, the grand-daddy of federation standards, has a technical document that covers the whole mess.  It's more information than you probably will ever need regarding SAML implementations (Libraries and Applications make it so easy these days!), but it's good to know where to go if you need it.  


## Authentication Processes
### Passwords

**The Usability of Passwords**  
**Type**: Web Article  
**Link**: [https://www.baekdal.com/trends/password-security-usability](https://www.baekdal.com/trends/password-security-usability)  
**Thoughts**: This is **very** outdated as far as time to crack under brute force mechanisms, but is a decent primer.   

**Guess Again (and Again and Again): Measuring Password Strength by Simulating Password-Cracking Algorithms**   
**Type**: Research Paper  
**Link**: [https://www.cylab.cmu.edu/_files/pdfs/tech_reports/CMUCyLab11008.pdf](https://www.cylab.cmu.edu/_files/pdfs/tech_reports/CMUCyLab11008.pdf)  
**Thoughts**: A paper on simulated password brute forcing attempts; the takeaway here is that longer passwords are superior in terms of time to crack, and pushed back against older NIST guidelines at the time. 

**NIST Special Publication 800-63B - Digital Identity Guidelines**  
**Type**: Government Publication  
**Link**: [https://pages.nist.gov/800-63-3/sp800-63b.html#memsecretver](https://pages.nist.gov/800-63-3/sp800-63b.html#memsecretver)  
**Thoughts**: NIST refers to passwords as "memorized secrets", and has a lot to say on them.  I have elected to link directly to the memorized secrets section of the publication here, since the topic is passwords.  These standards should be considered a minimum for any system that uses password-based authentication.

**OWASP Cheat Sheet Series - Password Storage Cheat Sheet**   
**Type**: Web Article  
**Link**: [https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)  
**Thoughts**: OWASP doing what they do best and offering a no-nonsense discussion on password storage mechanisms.  They raise something critical here, which is that once an attacker has access to password hashes they can and **will** be brute forced offline.

**Hash Crack**   
**Type**: Book  
**Link**: [https://www.netmux.com/blog/hash-crack-v3](https://www.netmux.com/blog/hash-crack-v3)  
**Thoughts**: A comprehensive book on the red-team side of passwords.  This is a no-nonsense exploration of how to compromise passwords, and any artisan of the craft should understand the other side to some degree.  

## PKI

## IGA

## PAM

## Auditability, Compliance, and Event Management

