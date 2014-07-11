MUA - Mail User Agent
=====================

## Sends email when supplied with mail server, to address, from address, subject, and message.
**Main: MailClient**

### Error checking:
* currently only checks for presence of '@' in email addresses

### Planned features:
* more error checking
  * valid addresses
  * authentication supports
  * better error recovery
* support for CC/BCC, multiple recipients
* more headers
  * see RFC 822
* support for different reply codes (e.g. 251)




