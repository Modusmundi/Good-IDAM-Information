# Good-IDAM-Information

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


## General Security

http://www.blueteamhandbook.com/ - The Blue Team Handbook, a condensed and valuable book on general blue-team security concerns.




## Foundationals

## Directory Services

### LDAP

https://www.oreilly.com/library/view/understanding-and-deploying/0672323168/ - Called by some the LDAP Bible; it's coming up on 20 years old but still provides a rich set of information on LDAP and considerations around LDAP Directory Servers.

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

https://www.cylab.cmu.edu/_files/pdfs/tech_reports/CMUCyLab11008.pdf - A paper on simulated password brute forcing attempts; the takeaway here is that longer passwords are superior in terms of time to crack, and pushed back against older NIST guidelines at the time.

https://pages.nist.gov/800-63-3/sp800-63b.html#memsecretver - NIST refers to passwords as "memorized secrets", and has a lot to say on them.  These standards should be considered a minimum for any system that uses password-based authentication.

https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html - OWASP doing what they do best and offering a no-nonsense discussion on password storage mechanisms.  They raise something critical here, which is that once an attacker has access to password hashes they can and **will** be brute forced offline.

https://www.netmux.com/blog/hash-crack-v3 - A book on the red-team side of passwords

## PKI

## IGA

## PAM

## Auditability, Compliance, and Event Management
