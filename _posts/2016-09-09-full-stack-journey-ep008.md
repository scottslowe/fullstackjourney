---
author: slowe
comments: true
date: 2016-09-09
layout: single
title: "Full Stack Journey Episode #008: Ivan Pepelnjak"
categories: Episode
explicit: "no"
block: "no"
duration: "48:13"
length: "25461117"
file: fullstackjourney.s3.amazonaws.com/full-stack-journey-episode-008.mp3
excerpt: In Episode 8, we dive into the world of networking with long-time expert Ivan Pepelnjak. Ivan shares some recommendations on expanding your skill sets for IT pros both within and outside the networking space.
tags:
- Networking
- Career
- Virtualization
- vSphere
- HyperV
---

Continuing in our series of episodes focusing on particular technologies within the broader journey to being a full stack engineer, episode #8 features Ivan Pepelnjak, well-known author, [blogger][link-1], [podcaster][link-2], and speaker. Ivan produces a phenomenal amount of content around networking and adjacent technologies (check it out [here][link-3]), and is active [on Twitter][link-4] as well.

As always, you can get the podcast [via iTunes][link-14], or you can [download the MP3 file directly][link-15]. Enjoy!

## Show Notes

* While there is value in talking about T-shaped skills, I-shaped skills, and Pi-shaped skills (see [this article][link-5] for a brief explanation of some of these terms, which may be new to you; Pi-shaped skills are like T-shaped but with an additional "leg" or area of expertise), Ivan believes it's really about being able to communicate with colleagues who are "right and left" of you (adjacent to your current role).
    - For networking professionals, this means you have to understand how servers and virtualization work, and how storage is different from TCP/IP (for example).
    - You can't be an expert in these adjacent areas, but you have to know enough to understand to communicate effectively and grasp their problems/challenges.
* Ivan uses a story about learning economics to illustrate that it's not about being an expert, but knowing enough to understand what others are saying.
* As concrete examples:
    - If you're a data center networking professional, you'd better understand how VMware's virtual switch works (because you'll see it in almost every enterprise data center).
    - If you're a server admin, you need to know what `ping` is, how ARP works, and how to take traces with `tcpdump` or Wireshark, and how to test to make sure your connections are actually going through.
* You won't learn anything unless you get out of your comfort zone. At the same time, find something reasonably close to what you're already doing to streamline the learning process. It also has to be hard.
* So where should today's network engineers start when trying to expand their skills?
    - For data center networking engineers, Ivan recommends learning virtualization and virtual switching.
    - For WAN engineers, Ivan would suggest working with VPN technologies.
    - For a campus network engineer, Wi-Fi would be a great start to expanding your knowledge.
    - Everyone should try to understand how applications work and what's going on behind a distributed application.
* "Mean time to innocence" - how long it takes to prove it's not the network's fault.
* For data center network engineers, Ivan strongly recommends learning [VMware vSphere][link-6]; or, for a purely Microsoft-centric organizations, [Hyper-V][link-7]. Why? These products are mature, they work as expected, and the documentation is typically complete, comprehensive, and well-organized.
* Open source projects may be more difficult for network engineers to learn because documentation may not be as complete or comprehensive, and it may not always work as expected.
* Use what your peers are using (when it comes to learning either vSphere or Hyper-V or choosing an automation tool); this helps when you get stuck or need help in your learning efforts.
* Should network engineers learn network automation first or virtualization first? Ivan believes network automation skills are _very_ important, and this is something a lot of network engineers haven't yet embraced.
    - To get started, choose some "low-hanging fruit"---things that are relatively easy to accomplish and will be low-impact (so you don't accidentally blow up the core switch).
    - Low-hanging fruit that will help network engineers get started with network automation: generating configurations from a template, and using a configuration management tool to perform simple configuration changes (like configuring a VLAN).
* Many network engineers haven't developed strong "computational thinking"---what exactly are the steps I have to take to get to the result? This can hinder efforts to embrace network automation tools.
* According to Ivan, when you can explain your troubleshooting process to an absolute idiot, you're ready for automation.
* The concept of data models is another area many network engineers haven't fully grasped---how to represent the data that is needed to perform a task in a series of steps.
* There are some great books (found in the "Additional Resources" section below) that may be helpful for non-network engineers to get started in networking.
* Always ask, "Why?" Ask yourself, "What is the problem this particular technology/feature/configuration is trying to solve?" This helps you understand the concepts and ideas behind a particular technology, feature, or configuration, and helps you understand when it is best used.
* Always try to build a mental model of where things fit in and how they relate to other technologies. (In other words, keep your mind like a tidy, well-organized closet.)
* Learning as many tools as possible so that you have the right tool for the job.
* Ivan believes it would be _very_ helpful for non-network engineers to understand the physical characteristics of networks: bandwidth, delay, latency, etc. See how those characteristics affect applications. Perform some packet captures to see how things are happening underneath.
* It would also be very helpful for application developers to better understand how to build resilient applications that work better across a network (or are better behaved across a network).
* Becoming a presenter is a great career move. It forces you to more fully learn the subject material, forces you to organize your mental model (how you think about something), and forces you to simplify things down (which in turns helps reinforce bigger picture thinking). Finally, it really helps you learn.
* You can also gain some of the same benefits from blogging, creating videos, etc.
* If you're wondering how to get presentation opportunities, think about making presentations within your own organization---talk to other IT groups, other colleagues, etc. This also helps build relationships across teams and silos within your organization.
* Take a presentation skills course.

## Additional Resources

_Computer Networks (5th Edition)_ by Andrew Tannenbaum  
_TCP/IP Illustrated, Vol 1: The Protocols_ by Richard Stevens (available [via Amazon][link-10])  
The _Routing TCP/IP_ books by Jeff Doyle ([volume 1][link-8] and [volume 2][link-9])  
_High Performance Browser Networking_ by Ilya Grigorik (available online [here][link-12])  
_Scalability Rules_ by Marty Abbott and Michael Fisher (see [here][link-13])



[link-1]: http://blog.ipspace.net/
[link-2]: http://www.ipspace.net/Podcast
[link-3]: http://content.ipspace.net/bin/start
[link-4]: https://twitter.com/ioshints/
[link-5]: https://bizthoughts.mikelee.org/t-shaped-skills-i-shaped-skills-and-dash-shaped-skills.html
[link-6]: http://www.vmware.com/vsphere.html
[link-7]: https://www.microsoft.com/en-us/cloud-platform/virtualization
[link-8]: https://www.amazon.com/Routing-TCP-IP-1-2nd/dp/1587052024/
[link-9]: https://www.amazon.com/Routing-TCP-IP-Professional-Development/dp/1587054701/
[link-10]: https://www.amazon.com/TCP-Illustrated-Vol-Addison-Wesley-Professional/dp/0201633469
[link-11]: https://www.amazon.com/Computer-Networks-5th-Andrew-Tanenbaum/dp/0132126958/
[link-12]: https://hpbn.co/
[link-13]: http://scalabilityrules.com/
[link-14]: https://itunes.apple.com/us/podcast/the-full-stack-journey/id1073172158?mt=2
[link-15]: http://fullstackjourney.s3.amazonaws.com/full-stack-journey-episode-008.mp3
