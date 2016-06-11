---
author: slowe
comments: true
date: 2016-05-19
layout: single
title: "Full Stack Journey Episode #005: Patrick Kelso"
categories: Episode
explicit: "no"
block: "no"
duration: "44:12"
length: "23529565"
file: fullstackjourney.s3.amazonaws.com/full-stack-journey-episode-005.mp3
excerpt: Episode 5 features Patrick Kelso, a former storage/NAS guy who embraced "infrastructure as code" and similar technologies and methods during a couple transitions in his career.
tags:
- Storage
- Puppet
- DevOps
- Docker
- Career
- AWS
- Azure
---

Episode #5 of the Full Stack Journey Podcast features Patrick Kelso, an independent consultant based in Australia. (Patrick is [patrickkelso on GitHub][link-1] and [on Twitter][link-13].) He works predominantly in the UNIX/virtualization/cloud space. He spent quite a number of years at EMC, then branched out and made the move to [Puppet][link-3]. Since then, he's started working on his own. Patrick is based on Sydney, Australia.

## Show Notes

* Patrick's view of a full stack engineer is similar to my own---an engineer who's comfortable working across multiple technology domains. A full stack engineer doesn't restrict himself or herself to one silo; instead, they understand multiple silos: networking, APIs, automation, etc.
* This broader view of the various silos and layers of the data center stack gives a full stack engineer the ability to communicate more effectively with other IT teams.
* As opposed to a generalist, a full stack engineer typically has one technology domain where he or she is strongest and deep technical expertise. For Patrick, he's currently focusing on automation.
* Patrick references a presentation by John Mark Troyer (recording [here on YouTube][link-2]) talking about a "pie-shaped" skill set. In a pie-shaped skill set, you have deep knowledge on one thing with more general knowledge on other things, but you're already cultivating/building the deep skill set on "the next thing."
* Patrick was pulled into using Puppet through a job he was doing for a client, where the use of Puppet made compliance audits incredibly simple and easy.
* Other things he's spending time with now: other configuration management tools, cloud providers ([AWS][link-5], [Azure][link-6]), and even some "non-sexy" technologies like Oracle Solaris and HP OpenView.
* However, even when using "older" technologies he always asks about how that tool or technology can be automated. It's an "automation first" approach.
* In making the transition from storage-focused person to "infrastructure as code"-focused person, one big challenge Patrick faced was sticking with something long enough to build expertise. He had to battle the "ooh look something shiny" mentality that is common among IT professionals.
* [Docker][link-7] has been very helpful to Patrick---it helps him get to the point where he can evaluate the value of a technology instead of getting stuck in the minutiae of installing or configuring the product.
    - You still need to go back and understand the minutiae, but that can be done _after_ you've figured out whether it's worth the time and effort (instead of being forced to invest that time and effort up front when you don't even know if this technology will be useful).
    - Setting up ELK (ElasticSearch, LogStash, and Kibana) using Docker is one example of being able to evaluate the tool before having to invest time in getting it running.
    - It's faster to "getting business value" out of a particular technology.
    - [Vagrant][link-11] also does this, but in some cases Docker does it faster.
    - Don't skip out on going back to understand the details of how these things work!
* [Pluralsight][link-9] is a great resource for keeping up with technologies.
* Patrick's also found [Linux Academy][link-8] to be helpful. Being able to watch informational/instructional videos while offline has worked well for him.
* Patrick is a fan of David Allen's GTD, specifically the simplified "WSD" variant ("Write Stuff Down")---he finds it very helpful jot down notes of technologies to investigate, things to research or look up, products or projects that might deserve more attention. Don't forget to go back and review the notes!
* He uses [Evernote][link-10] to track all these notes he captures, but pen and paper is highly recommended.
* Podcasts are also a great source of information; he finds it useful to listen to podcasts while out running.
* RSS feeds from various blogs are a fabulous source of _practical_ information (this helps balance the onslaught of vendor information).
* You've got to do some hands-on learning; Patrick really highly recommends the use of a home lab to help cement your learning. Consuming lots of content won't do any good if you don't try to put that knowledge to work in a lab.
* Most of Patrick's research/investigation centers around problems that he's trying to solve at work.
* When allocating time for your own self-development, you have to balance the need for the immediate (where you are now) versus where you want to be.
* Stay interested in "what's next".
* When you attend an industry conference, attend sessions that are "outside your comfort zone." This is how you grow and avoid irrelevance.
* If you are limited in which conferences you can attend, pick the conference that's going to give you value and help you learn something entirely new.
* What would Patrick have done differently?
    - He wouldn't have gone to ten straight EMC conferences in a row.
    - He would have taken more interest in how a career progresses, especially when he was younger. He would have paid a bit more attention to the future with a more forward-looking forward.
    - He would have spent more time trying other technologies to expand his horizons. Don't get caught up in ideological absolutes---choose the right tool for the job.
    - He would have looked for mentors---career and technical---much earlier in his career.
    - Sometimes this "mentorship" is entirely virtual, and consists of folks you're watching/listening to/reading in their own careers.
* What tips or advice can Patrick provide to folks?
    - Pick your battles. Making a new technology relevant to your day job---in a way that solves a real problem---can eliminate a lot of hassle.
    - Pay attention to business value. Show the value of what you're doing or trying or learning.
    - Use technologies regularly. This is especially helpful with coding, whether that be coding in Python, building Ansible playbooks, or writing regular expressions. (Patrick likes RegEx Golf.)
    - Always Be Coding. Create something every day.
* Big Data is really on Patrick's mind right now; he thinks this will be really important moving forward.
* Security is finally becoming a first-class citizen, and it's finally becoming something into which more companies are going to invest more money and more resources.

## Additional Resources

John Mark Troyer's presentation at Melbourne VMUG UserCon 2015: [https://www.youtube.com/watch?v=iNmeXOKH05M][link-2]

Useful tool for learning regular expressions: [http://regex.alf.nu/][link-4]

[_The Little Book of Talent: 52 Tips for Improving Your Skills_ by Daniel Coyle][link-12]

Patrick's ["DevOps Workflows" repository][link-14]


[link-1]: https://github.com/patrickkelso/
[link-2]: https://www.youtube.com/watch?v=iNmeXOKH05M
[link-3]: https://puppet.com/
[link-4]: http://regex.alf.nu/
[link-5]: https://aws.amazon.com/
[link-6]: https://azure.microsoft.com/en-us/
[link-7]: https://www.docker.com/
[link-8]: https://linuxacademy.com/
[link-9]: https://www.pluralsight.com/
[link-10]: https://evernote.com/
[link-11]: https://www.vagrantup.com/
[link-12]: https://www.amazon.com/Little-Book-Talent-Improving-Skills/dp/034553025X/ref=sr_1_1?ie=UTF8&qid=1465597027&sr=8-1&keywords=little+book+of+talent+daniel+coyle
[link-13]: https://twitter.com/patrickkelso
[link-14]: https://github.com/patrickkelso/devops-workflows
