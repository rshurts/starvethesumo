---
layout: guide
title: Securing Your Network
permalink: /guides/securingnetwork/
---

To secure your network, we will use OpenDNS to filter content at the DNS level. This will require signing up for the OpenDNS service. Don't worry OpenDNS is free and is used by many schools, churches, businesses, and other home users to block content and speed up DNS queries.

With this done, you will then set up your router to use OpenDNS's DNS servers. This will ensure that any device that connects to your network will use the filtering you set in place.

<div class="tip">
  <h5>How DNS Filtering Works</h5>
  <p>Behind the scenes of every domain name, like StarvetheSumo.com, is an IP address, like 204.232.175.78. IP addresses are what computers use to communicate to one another. But people use names and words to communicate. So, web site use domain names.</p>
  <p>A Domain Name Server (DNS) translates the human readable internet address, the domain name, into a numeric IP address and provides that back to the computer requesting the information. All the network traffic happens using IP addresses, but the user gets to see a friendly domain name.</p>
  <p>By filtering at the DNS level, any request for information from a known explicit domain name will be blocked and the IP address will not be returned. So the computer requesting the site will not be able to visit it.</p>
</div>
