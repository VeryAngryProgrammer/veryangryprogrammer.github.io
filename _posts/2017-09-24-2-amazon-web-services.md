---
title: Amazon Web Services
heading: Amazon Web Services - Things That Make Me Angry
---

> _This post is the second in a series on things that make me angry. If this post on things that make me angry happens to make you angry, I've created an easy script that you can use to [send me hate mail](https://github.com/VeryAngryProgrammer/hate-mail-script)._

I can guarantee you that if I ever get the opportunity to do a tour of the Amazon Web Services HQ my mugshot will end up on the evening news.

### Service Naming

The other day somebody asked me what I would do if I won a million dollars on the lottery. My answer was that I would buy a $10 hammer and as many nails as I could for $999,990. I would then find the person who decided that Amazon Route 53 was a better name than Amazon DNS and drive every nail I had into their body.

Every service that AWS provides has a shit name that requires a click to find out what it actually fucking does.

Amazon EC2 is for setting virtual machines. Amazon S3 is for storage. Amazon RDS is for SQL databases. Amazon ECS is for Docker containers. Amazon SQS is for message queues and in a million years you would never guess what the fuck Amazon Elastic Beanstalk is for.

### Pricing

Anybody who thinks that it is acceptable to present hosting service costs as hourly rates (without an immediately obvious monthly figure right next to it) should get a punch in the face.

If you actually try and use the provided monthly calculator you realise that you now need to find out about EBS volumes and Elastic IPs. All you wanted to do was a cost comparison on a couple of virtual machines and now you need to know six different data transfer figures and the entire AWS glossary.

Trying to work out how much it will cost to setup an application on AWS is like trying to guess how many dependencies a node project has.
