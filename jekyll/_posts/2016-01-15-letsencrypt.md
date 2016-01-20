---
layout: post
title: "Letstencrypt"
excerpt: "The kickass &amp; less painful Certificate Authority"
author: thayoz
tags: [ssl/tls,certificates,encryption]
share: true
comments: true
---
About a couple of weeks ago [Let's Encrypt](https://letsencrypt.org/) went on the public beta phase. Let’s Encrypt is a new zero-cost X.509 Certificate Authority that supports the Automated Certificate Management Environment (ACME) protocol.
ACME reduces the effort of dealing with x509 certificates. This protocol allows to automatically create and retrieve SSL/TLS certificate using a challenge-response pattern between the CA and the host requesting the certificate.

The official client is also really efficient, since it has the abilities to parse your web server configuration and detect the hostnames (i.e subdomain.txa.io,), it can automatically obtain the certificates and finally update put in place the freshly obtain certificate in production on your apache or nginx. How neat !
