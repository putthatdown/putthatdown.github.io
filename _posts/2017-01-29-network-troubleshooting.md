---
title:  "Network troubleshooting"
date:   2017-01-29
categories: commands
---

Working with several AWS accounts and Route53, I often find myself having to verify networking configurations. Frequently used tools and commands are detailed below.

## Dig

[Dig](http://www.thegeekstuff.com/2012/02/dig-command-examples) is a DNS lookup utility.

Perform a DNS lookup and display the answers

        dig <URL_or_hostname>

Perform a DNS lookup and get brief answers

        dig uchiwa.cimpress.io +short

Perform a DNS lookup against a specific nameserver

        dig @<nameserver> <URL_or_hostname>

