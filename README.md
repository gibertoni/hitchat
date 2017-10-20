# hitchat
Personal project to hit up with a friend using our own, hopefully secure, IM client

**Idea:**
To communicate with a friend using authenticated and encrypted channels on a P2P architecture without the need for a central server, certification authority, etc.

**Challenge:**
To register each other the first time and to reliably and cost effectively ensure that the messages are not being tampered with.
Also attempt to minimize impact of spoofing, message replication and related protocol attack

**Literature:**
* RSA: pure python implementation - https://github.com/sybrenstuvel/python-rsa
* CGA: protocol description - https://tools.ietf.org/pdf/rfc3972.pdf
