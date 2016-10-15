---
author: slowe
comments: true
date: 2016-10-15
layout: single
title: "Full Stack Journey Episode #010: Alex Galbraith"
categories: Episode
explicit: "no"
block: "no"
duration: "52:28"
length: "27497243"
file: fullstackjourney.s3.amazonaws.com/full-stack-journey-episode-010.mp3
excerpt: In episode 10, I'm joined by Alex Galbraith to talk about how to wrap your mind and your skill set around the extensive set of services offered by Amazon Web Services (AWS).
tags:
- Cloud
- AWS
---

Public clouds and public cloud services have been a recurring theme in almost every episode of the Full Stack Journey podcast. To help listeners address that need in their portfolio of skills, this episode focuses on expanding your knowledge of and skill with Amazon Web Services (AWS). Our special guest to help drive that discussion is Alex Galbraith. Alex is a solutions architect working for a global service provider. You can find him online as [@alexgalbraith on Twitter][link-3], or visit his blog at [http://tekhead.it][link-2].

The podcast episode is [available via iTunes][link-1], or you can listen directly in your browser (assuming your browser supports HTML5 audio):

<audio controls>
  <source src="http://fullstackjourney.s3.amazonaws.com/full-stack-journey-episode-010.mp3" type="audio/mpeg">
If you're seeing this message, your browser does not support HTML5 audio elements.</audio>

## Show Notes

* Alex has been writing quite a bit of AWS-related stuff on his site; see [this page][link-4] for an index to the AWS-related posts.
* You have to invest in yourself; you can't just expect your employer to invest in you without some effort on your part.
* What is Alex's view of a "full stack engineer"?
    * It's a goal, an aspiration, something to help drive you forward.
    * Is a full stack engineer like an architect? Alex thinks there's a lot of similarity between the idea of a full stack engineer and a well-versed architect.
    * There's an element of "jack of all trades," but you'll have a couple really deep anchors of skill and expertise.
    * Another aspect of being a full stack engineer is learning to step back from the technology and be a bit more technology-agnostic. Instead, the technology should be selected based on the problem.
    * The "Input" strength from [Gallup Strengths][link-5] may also apply to full stack engineers (or the journey to being a full stack engineer).
* Public cloud services are rapidly becoming a "bread-and-butter" category for IT professionals (along with automation and orchestration).
* If you have a strong Microsoft background, Azure may be the right place for you to start. If you have more of a UNIX/Linux background, AWS or GCP might be better.
* Also, align your public cloud learning efforts with what your peers are doing (leverage the power of your community).
* AWS has a _lot_ of services! Where should folks start?
    * 55 primary services on the front page of the AWS services (with multiple sub-services and configurations for each).
    * You don't need to know _every_ single service.
    * The key services you really need, according to Alex, are these:
        * Networking (VPCs, Route 53)
        * Security (IAM [Identity and Access Management] permissions)
        * Compute (EC2)
        * Storage (EBS [Elastic Block Storage] and S3 [object storage])
        * Databases (RDS, including Microsoft SQL Server, MySQL, Oracle)
        * Monitoring/management (CloudWatch, CloudTrail)
    * Most of these services target the 80% of the functionality users use the most
* Many of the challenges Alex ran into while learning AWS were rooted in the differences between how on-premises infrastructure works versus how AWS works
* When designing for the cloud, you need to design for ephemeral infrastructure that scales out---instead of applying design principles rooted in on-premises concepts and ideas
* Be aware of terminology (for example, a "dedicated VPC" means all EC2 instances launched in that VPC will be running on dedicated hardware)
* Good training resources that Alex used:
    * [Udemy][link-6]
    * [A Cloud Guru][link-7] (a bit exam-focused)
    * [Linux Academy][link-8]
    * [Cloud Academy][link-9]
    * [AWS white papers][link-11]
    * [AWS documentation site][link-10]
    * Meetups via [meetup.com][link-12]
        * AWS meetups
        * Serverless meetups
        * "CloudCamp" (in the UK)
    * Content from AWS re:Invent ([video recordings][link-13] or [slide presentations][link-14])
* Hands-on experience is critical! Don't be afraid to experiment---you can spin things up on demand and destroy them on demand.
* Automation and orchestration are essential once you move past a few dozen instances
    * Use templates everywhere possible (AWS CloudFormation or [Terraform][link-15]; Alex recommends learning Terraform first)
    * With regards to automation, don't try to boil the ocean---start small and build from there.
* Are there related technologies that Alex feels are a good "fit" for use with AWS?
    * Configuration management tools ([Ansible][link-16], [Chef][link-17], [Puppet][link-18], [SaltStack][link-19])---doesn't matter which one, just pick one and go
    * Container technologies ([Docker][link-20])
    * Container orchestration ([Kubernetes][link-21], Docker Swarm, [Mesosphere][link-22])---doesn't matter which one, pick the one that "shouts" at you the most and for which you can find the most resources in your circle of friends/colleagues
    * DevOps (try not to get caught up in the hype around the name)
    * [Git][link-23]---a strong "bread and butter" technology moving forward
    * CI ([Jenkins][link-24])
* [Open Home Lab][link-25] and [Open Tech Cast][link-26] are focused on home lab discussions---not just vSphere, but also Hyper-V and public cloud resources



[link-1]: https://itunes.apple.com/us/podcast/the-full-stack-journey/id1073172158?mt=2
[link-2]: http://tekhead.it
[link-3]: https://twitter.com/alexgalbraith
[link-4]: http://tekhead.it/blog/2016/07/index-of-tekhead-it-blog-posts-on-amazon-aws/
[link-5]: http://strengths.gallup.com/default.aspx
[link-6]: https://www.udemy.com/
[link-7]: https://acloud.guru/
[link-8]: https://linuxacademy.com/
[link-9]: https://cloudacademy.com/
[link-10]: https://aws.amazon.com/documentation/
[link-11]: https://aws.amazon.com/whitepapers/
[link-12]: https://www.meetup.com/
[link-13]: https://www.youtube.com/user/AmazonWebServices
[link-14]: http://www.slideshare.net/AmazonWebServices/
[link-15]: https://www.terraform.io/
[link-16]: https://www.ansible.com/
[link-17]: https://www.chef.io/
[link-18]: https://puppet.com/
[link-19]: https://saltstack.com/
[link-20]: https://www.docker.com/
[link-21]: http://kubernetes.io/
[link-22]: https://mesosphere.com/
[link-23]: https://git-scm.com/
[link-24]: https://jenkins.io/index.html
[link-25]: https://openhomelab.org/index.php?title=Main_Page
[link-26]: http://www.opentechcast.com/
