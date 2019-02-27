# Tor Web Docs #

Tor Web Docs are a collection of documents about privacy on the Web and developing for the privacy-friendly Web. The objective behind Tor Web Docs is to provide developers with the information and resources needed to understand privacy issues and build privacy-friendly projects on the web platform that can be rendered by Tor browser as by any other browser.

Tor Web Docs is an evolving resource for Web Privacy and related topics, included:
- Web technologies
- CSS/HTML JavaScript and other web standards
- Privacy-friendly web app development
- Tor Browser support across the web

## Overview ##

Tor is an important tool providing privacy and anonymity online. The property of anonymity itself is more than just providing an encrypted connection between the source and the destination of a given conversation. There is in fact a lot of information that can be still learned by just observing encrypted communications. 

The Tor Browser was designed to provide privacy while surfing the web and defend users against both network and local forensic adversaries, 

There are two main categories of requirements for the Tor Browser: Security Requirements, and Privacy Requirements. Security Requirements are the minimum properties in order for a browser to be able to support Tor and similar privacy proxies safely. Privacy requirements are primarily concerned with reducing linkability: the ability for a user's activity on one site to be linked with their activity on another site without their knowledge or explicit consent.

The Tor Browser is based on Mozilla's Extended Support Release (ESR) Firefox branch. We have a series of patches against this browser to enhance privacy and security. Browser behavior is additionally augmented through the Torbutton extension, and we also change a number of Firefox preferences from their defaults. 

## Scope ##

The privacy requirements set by Tor browser are primarily concerned with reducing the ability for a user's activity on one site to be linked with their activity on another site without their knowledge or explicit consent. The security requirements are primarily concerned with ensuring the safe use of the To network. Violations in these properties typically result in serious risk for the user in terms of immediate deanonymization and/or observability. In addition Tor browser has adopted a few more requirements dictated by some philosophical positions about technology.  If developers want to make their application accessible through .onion they necessarily have to consider how this is rendered via Tor browser. Tor browser is designed with some specific requirements regarding privacy and security that differ from other browsers and might impact the website/webapp user experience. 


