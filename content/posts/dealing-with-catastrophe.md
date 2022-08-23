+++
title = "Dealing with Catastrophe"
date = "2022-08-23T15:58:59-04:00"
author = "asenchi"
authorTwitter = "asenchi"
cover = "/images/dealing-with-catastrophe.png"
tags = ["incident-management", "infrastellar", "complex-systems"]
keywords = ["infrastructure", "incident-management"]
+++

> 6 Catastrophe is always just around the corner.
>
> Complex systems possess potential for catastrophic failure. Human
> practitioners are nearly always in close physical and temporal proximity to
> these potential failures – disaster can occur at any time and in nearly any
> place. The potential for catastrophic outcome is a hallmark of complex
> systems. It is impossible to eliminate the potential for such catastrophic
> failure; the potential for such failure is always present by the system’s own
> nature.

The above quote is taken from Richard I. Cook's seminal treatise, ["How Complex
Systems Fail"][]. The full paper is a must read for anyone working on
infrastructure and complex systems. However, this sixth point is of particular
importance to me because it has become a fundamental approach to every system I
have worked on since reading Dr. Cook's paper nearly 12 years ago.

My experience has shown this statement to be true. No matter how hard teams
worked to build reliable systems there was always an event that surprised us,
one that typically meant many people were going to lose many hours of their day
working to resolve the underlying incident.

Approximately eight years ago within a few weeks of joining a new company we
experienced a catastrophic event that impacted a large portion of our customers
for greater than 24 hours. The reason this incident stood out to me was that
our engineering team had been developing this particular change for 18
months and we had put a considerable amount of work into preparing for
this day of the event. And yet, it still fell apart.

Perhaps the most surprising piece at the time was that our planning didn't
just fall apart from a technical perspective, but we also saw results of a
massive communication breakdown that led to the confusion of our coworkers and
our customers. We had done the work to put together checklists to ensure we
were all on the same page. We had assigned the Incident Commander role to
people who understood the work and they did a reasonable job updating situation
reports. Yet when we finished the internal post-mortem and shared it with our
coworkers many of them were shocked to find out what had happened. There was an
obvious problem here, one that we had thought we had prepared for.

Thankfully the Director of our operations team at the time understood the
importance of finding a better way to deal with failure and gave me the space
to develop a method for our needs. I wasn't new to incident management, having
worked on it at my two previous employers, but I was deeply curious to find a
better way than what I had experienced previously.

At the time two key areas stuck out to me:

- The burden of response: How does the process of response reduce the stress on
  those actively addressing the incident?
- Clear and concise communication: How to inform all impacted parties whether
  known or not?

Any system that could solve these two issues would greatly improve our ability
to address not only catastrophic failures but any incident encountered.

The work we are doing at [Infrastellar Systems][] is an extension of that
initial development of an incident management system that I have continued to
develop throughout the years. I've built up a lot of experience integrating my
system into large engineering organizations. What I've learned from those
experiences I hope to put into tooling for teams to improve their experience
around catastrophic failures and more deeply understand their production
systems.

Ultimately the potential for failure exists in every system we develop as
engineers. As Dr. Cook says above, it is "always present by the system's own
nature." Incident management is the interface by which engineers engage with
their systems in real-time. It isn't the only one, but it may just be the most
important one.

["How Complex Systems Fail"]: https://how.complexsystems.fail
[Infrastellar Systems]: https://infrastellar.systems
