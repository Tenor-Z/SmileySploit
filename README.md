# SmileySploit
A basic script that exploits CVE-2011-2523

# Overview
In 2011, an integrated backdoor was found on vsFTPd servers running version 2.3.4, in which using a smiley emoticon ":)" triggers a reverse connection to an attacker. With this, it is extremely easy to create an exploit script and gain access to a system vulnerable to this flaw. By using said emoticon during authentication, the backdoor is triggered, and the attacker can then connect to the shell on port 6200.

# How To Run
Just run Python with the exploit.py file. Make sure Pwntools is installed first using Pip.
