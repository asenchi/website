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

The above quote is taken from Dr. Richard Cook's seminal treatise, ["How Complex
Systems Fail"][]. The full paper is a must read for anyone working on
infrastructure and complex systems. However, this sixth point is of particular
importance to me because it has become a fundamental approach to every system I
have worked on since reading Dr. Cook's paper nearly 12 years ago.

My experience has shown this statement to be true. No matter how hard teams
worked to build reliable systems there was always an event that surprised us,
one that typically meant many people were going to lose many hours of their day
working to resolve the underlying incident.

Approximately eight years ago I joined a new company that was in the middle of
a very large migration. The work had been in progress for 18 months. Even with all of that
preparation we still experienced a catastrophic event that impacted a large
portion of our customers for greater than 24 hours.

Perhaps the most surprising piece at the time was that our planning didn't just
fall apart from a technical perspective, but we also saw results of a massive
communication breakdown that led to the confusion of our coworkers and our
customers. We had done the work to put together checklists with specific points
of communication to ensure we were all on the same page. We had assigned the
Incident Commander role to a rotation of people who understood the work and
they did a reasonable job updating situation reports. Yet when we finished the
internal post-mortem and shared it with our coworkers, many of them were
shocked to find out what had happened. There was an obvious problem here, one
that we had thought we had prepared for.

Thankfully, the Director of our operations team at the time understood the
importance of finding a better way to deal with failure and gave me the space
to develop a method for our needs. I was deeply curious to find a better way
to engage our systems and support the teams across the company so that whenever
we faced a failure, whether planned or unplanned, my coworkers had the
information they needed to continue doing their job.

At the time three key areas stuck out to me:

- The burden of response: How can the process of incident response reduce the
  stress on those actively addressing the incident?
- Clear and concise communication: How to inform all impacted parties whether
  known or not?
- Non-technical Allies: How can the process of incident response support all
  teams at all levels in the company that may be impacted by the particulars of
  incident?

Any system that could solve these three issues would greatly improve our
ability to address not only catastrophic failures but any incident encountered.

The work we are doing at [Infrastellar Systems][] is an extension of that
initial development of an incident management system. It is one that I have
continued to develop throughout the years. I've built up a lot of experience
integrating my system into large organizations. What I've learned from those
experiences I hope to put into tooling for companies to improve their
experience around catastrophic failures and more deeply understand their
production systems.

Ultimately, the potential for failure exists in every system we develop. As
Dr. Cook says above, it is "always present by the system's own nature."
Incident management is an interface by which companies engage with their
systems in real-time. It isn't the only one, but it may just be the most
important one.

["How Complex Systems Fail"]: https://how.complexsystems.fail
[Infrastellar Systems]: https://infrastellar.systems
