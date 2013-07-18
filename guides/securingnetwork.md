---
layout: guide
title: Securing Your Network
permalink: /guides/securingnetwork/
---

To secure your network, we will use OpenDNS to filter content at the DNS level. This will require signing up for the OpenDNS service. Don't worry OpenDNS is free and is used by many schools, churches, businesses, and other home users to block content and speed up DNS queries.

With this done, you will then set up your router to use OpenDNS's DNS servers. This will ensure that any device that connects to your network will use the filtering you set in place.

## DNS Filtering
Behind the scenes of every domain name, like StarvetheSumo.com, is an IP address, like X.X.X.X. This IP address is what computers use to communicate over the internet. But obviously, a series of numbers can't easily be remembered by people and makes navigating the internet quite difficult. So, domain names are used and then a Domain Name Server (DNS) translates the real word internet address into a numeric IP address and provides that back to the computer requesting the information. All the traffic is done using IP addresses, but the user gets to see the domain name.

By filtering at the DNS level, any request for a known explicit domain name will be blocked and the IP address will not be returned so the computer requesting the site will not be able to visit it.

<div class="tip">
  <h5>No Filter is Perfect</h5>
  <p>Despite the great job that OpenDNS does keeping its list of explicit sites up to date, it can't cover all the internet and all the new sites popping up daily. Fortunately, OpenDNS still does a very good job.</p>
  <p>But to really keep explicit content out of your home, make sure to move your computer and other electronic devices into a well trafficked area of your house. When anyone can see what's on the screen, it keeps people from being tempted to visit anything inappropriate.</p>
</div>