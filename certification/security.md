---
title:  Fair Web Services Certification - Security
layout: certification
---
## Security

Applying standard security measures should go without saying for any service. But it's even more important to also establish trust with the user. When relying on a service run by somebody else, users can't check for themselves what is done to keep the service secure. So the service provider has to build trust by being transparent and reactive about security.

### Encrypting traffic

The service only uses https and not http.

***Rationale:** Using https makes sure all data traffic is encrypted and clients can make sure that they are talking to the actual service. This keeps private data secure and prevents man-in-the-middle attacks.*

### Two-factor authentication

The service provides two-factor authentication or another mechanism which is at least as secure.

***Rationale:** Hacking passwords is one of the most simple and common way to break into user's accounts. Using two-factor authentication prevents that users account can be compromised by hacking only the password.*

### Policy for reporting security issues

There is a documented way how to report security issues and how they are handled.

***Rationale:** Every service will have some security issues at some time. Providing a way to report them and having a defined procedure how to handle them allows users and security experts to improve the security of the service.*

### Transparency about security issues

The service provider keeps an ongoing report of security issues and how they were fixed.

***Rationale:** Transparency about how security issues are handled allows users to judge how the service is dealing with their data and their security. This is the base for building trust.*
