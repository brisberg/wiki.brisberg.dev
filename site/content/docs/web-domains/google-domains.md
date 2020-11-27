---
weight: 1
title: "Google Domains"
---

# Google Domains

[Google Domains](https://domains.google.com) is Google's Domain Name Registrar and Domain Name Server offering.

Google Domains offers a single location to manage Domain Name purchases, and DNS configurations for purchased domains.

## Features

- [Privacy Protection](https://support.google.com/domains/answer/3251242?hl=en) - Google uses a third-party service to alias your personal information in the [WHOIS](https://whois.icann.org/en/about-whois) internet registry.
- Google DNS Servers & Configs
- SSL/TLS certificates (for HTTPS)
- Custom Email
- Advertisements

## DNS Configuration


### DNS Servers
Google Domains defaults to using Google owned Domain Name Servers. You can specify your own if you wish.

### DNSSEC
Domain Name System Security Extensions (DNSSEC) protect your domain from attacks such as DNS cache poison attacks and DNS spoofing. [More](https://support.google.com/domains/answer/6387342?hl=en)

### Syntetic Records
Synthetic records allow you to add common features, such as domain forwarding or Google Workspace, to your domain in one step. Each synthetic record is an automatically-generated collection of resource records related to a specific feature.

These records are groupings of DNS directives to accomplish common tasks. I could not get the `subdomain forwarding` synthetic records to work with [GitHub Pages](https://pages.github.com/) hosting.

### Custom Resource Records
Resource records define how your domain behaves. Common uses include pointing your domain at your web server or configuring email delivery for your domain.

Resource Records are common features to all DNS services. They include things like CNAME, Alias, and Ipv6 Alias records for configuring a Domain.
