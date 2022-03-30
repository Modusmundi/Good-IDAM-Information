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



The Format
***

[//]: # (You absolutely need two spaces after the end of your content to make it line break in Github.  Keep that in mind when building this out.)

**Title** (Name of the media)  
**Type**: Book, Article, Course, Podcast, Application, Web application, Etc., etc.  
**Link**: A direct URL to the item.  
**Thoughts**: Notes about the item.  


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

[http://www.blueteamhandbook.com/](http://www.blueteamhandbook.com/) - The Blue Team Handbook, a condensed and valuable book on blue-team security concerns.

[https://www.oreilly.com/library/view/defensive-security-handbook/9781491960370/](https://www.oreilly.com/library/view/defensive-security-handbook/9781491960370/) - Defensive Security Handbook, a great high-level book about security from a top-down perspective.




## IDAM Foundationals

## Directory Services

### LDAP

[https://www.oreilly.com/library/view/understanding-and-deploying/0672323168/](https://www.oreilly.com/library/view/understanding-and-deploying/0672323168/ ) - Called by some the LDAP Bible; it's coming up on 20 years old but still provides a rich set of information on LDAP and considerations around LDAP Directory Servers.

## Metadirectories

## RBAC

## ABAC

## Access Management

## Federation

### OAuth 2 / OpenID Connect (OIDC)
[https://youtu.be/996OiexHze0](https://youtu.be/996OiexHze0) - Need to review this

## Authentication Processes
### Passwords
[https://www.baekdal.com/trends/password-security-usability](https://www.baekdal.com/trends/password-security-usability) - This is **very** outdated as far as time to crack under brute force mechanisms, but is a decent primer. 

[https://www.cylab.cmu.edu/_files/pdfs/tech_reports/CMUCyLab11008.pdf](https://www.cylab.cmu.edu/_files/pdfs/tech_reports/CMUCyLab11008.pdf) - A paper on simulated password brute forcing attempts; the takeaway here is that longer passwords are superior in terms of time to crack, and pushed back against older NIST guidelines at the time.

[https://pages.nist.gov/800-63-3/sp800-63b.html#memsecretver](https://pages.nist.gov/800-63-3/sp800-63b.html#memsecretver) - NIST refers to passwords as "memorized secrets", and has a lot to say on them.  These standards should be considered a minimum for any system that uses password-based authentication.
[https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html) - OWASP doing what they do best and offering a no-nonsense discussion on password storage mechanisms.  They raise something critical here, which is that once an attacker has access to password hashes they can and **will** be brute forced offline.

[https://www.netmux.com/blog/hash-crack-v3](https://www.netmux.com/blog/hash-crack-v3) - A book on the red-team side of passwords

## PKI

## IGA

## PAM

## Auditability, Compliance, and Event Management
