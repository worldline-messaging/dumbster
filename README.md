# dumbster
> The Dumbster is a very simple fake SMTP server designed for unit and system testing applications that
> send email messages. It responds to all standard SMTP commands but does not deliver messages to the user.
> The messages are stored within the Dumbster for later extraction and verification.

**This repository is a fork of http://quintanasoft.com/dumbster/ (https://sourceforge.net/projects/dumbster/).**

I forked it for two reasons:

1. I wanted to have typed lists as return values.
2. I wanted the server to be able to just pick a port itself and then tell me which port it got.

And while I'm at it, using slf4j instead of stdout is also nice.

Aside from that, the actual smtp logic is completely unchanged.

