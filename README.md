# SSH certificates talk
A talk to be given at the WA chapter meeting of [SAGE-AU][]
(The System Administrators Guild of Australia)

  [SAGE-AU]: http://www.sage-au.org.au/

## Blurb

Commonly, servers are configured such that the SSH daemon disallows the use of
passwords to log in.  Instead, SSH keys (using public key cryptography) are
often used, which are created per user and require installation of the public
key onto each server that the user needs to log in to.

SSH user certificates have been supported by OpenSSH for many years.  They
allow more centralised management of users' SSH public keys (through a PKI
mechanism) and require less work due to better scalability when dealing with
significant numbers of servers.  This talk will take the form of a tutorial and
demo, after which attendees should be able to quickly roll out SSH user
certificate infrastructure for their own servers.

## Outline

  1. Intro
  1. Support
     - OpenSSH only
     - Since OpenSSH v5.4 
  1. ...

## Presenter bio

Alastair is a Software Engineer and system administrator by trade.  He has a BSc in Computer Science from Curtin University.

His computer-related interests lie in various areas within his trade; suffice to say that he is a "geek of many colours". :)  Alastair is a die-hard FOSS user and Linux fan.

He is also a freelancer with his own business.  [Warpspace IT](http://www.warpspace.net/) is a consultancy with a fairly broad focus on the technical side of IT.

## Slides

**TBA**
