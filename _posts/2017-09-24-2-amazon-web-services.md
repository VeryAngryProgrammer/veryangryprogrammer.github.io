---
title: Amazon Web Services
heading: Amazon Web Services - Things That Make Me Angry
---

> _This post is the second in a series on things that make me angry. If this post on things that make me angry happens to make you angry, I've created an easy script that you can use to [send me hate mail](https://github.com/VeryAngryProgrammer/hate-mail-script)._

Amazon Web Services (AWS) is one of the most intentionally obstructive and irritating platforms that I have ever had the misfortune of working with. I can guarantee you that if I ever get the opportunity to do a tour of their headquarters my mugshot will end up on the evening news and you will be watching interviews of my neighbours saying "It's a big shock to us, we always thought he was such a nice man".

Here are the top three things about AWS that make me angry.

### 1. Service Naming

The other day somebody asked me what I would do if I won a million dollars on the lottery. My answer was that I would buy a $10 hammer and as many nails as I could for $999,990. I would then find the person who decided that Amazon Route 53 was a better name than Amazon DNS and drive every nail I had into their body.

Every service that AWS provides has a shit name that requires a click to find out what it actually fucking does.

Amazon EC2 is for setting virtual machines. Amazon S3 is for storage. Amazon RDS is for SQL databases. Amazon ECS is for Docker containers. Amazon SQS is for message queues and in a million years you would never guess what the fuck Amazon Elastic Beanstalk is for.

### 2. Pricing

Anybody who thinks that it is acceptable to present hosting service costs as hourly rates (without an immediately obvious monthly figure right next to it) should get a punch in the face (per hour).

When you actually try and use the provided [AWS monthly calculator](https://calculator.s3.amazonaws.com/index.html) you realise that you now need to learn what EBS volumes and Elastic IPs are. All you wanted to do was a cost comparison on a couple of virtual machines and now you need to obtain six different data transfer figures and the entire AWS glossary.

Even estimating how much it will cost to host an application on AWS requires a degree in mathematics, and this is by design. These tactics make it very easy for costs to creep out of control and this means that executives get to buy bigger yachts.

### 3. Barrier to Entry

Opinionated systems that guide you down an approved path are often much easier to get started with than larger more powerful systems. The more options you offer, the more ambiguity there is and the more difficult it is to make decisions.

I can understand why AWS has headed down the route of providing options rather than direction and this does not bother me. What does bother me is that having taken this path, they continue to make their services as opaque as possible and this exaggerates the effect needlessly.

Using AWS gives you the feeling that whenever the UX team submitted an idea, someone from higher up responded with "Yes that sounds great, but is there any way that we could make this more complicated so that we sold a few more certification training programs."


