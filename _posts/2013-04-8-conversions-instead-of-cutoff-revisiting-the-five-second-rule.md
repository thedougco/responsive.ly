---
layout: post
title: Conversions Instead of Cutoff—Revisiting the Five-second Rule of Web Performance
date: 2013-04-08
categories: [Responsive, Tools]
author: doug
---

###Revisiting the oft-cited five-second rule
It may be true that [your site should load in five seconds or less or 74% of visitors will leave](http://www.gomez.com/wp-content/downloads/19986_WhatMobileUsersWant_Wp.pdf). But one thing to consider about this frequently cited Gomez/Equation Research study is the research is based on a survey of what users *said they expected, not on actual analytics.* I am not bringing this up to assume the statistic is faulty, but to point out that research based on surveys can be less accurate than applied research based on real use of technology.

The margin of error on what users *say* they are willing to tolerate could easily be one or two seconds in either direction of the five-second rule.<!-- more --> If participants in the Gomez/Equation survey underestimated their threshold of irritation by even one second, the cutoff starts to becomes even more punishing for pages with long load times.

###A design constraint that caps at a 74% loss of visitors is a mushroom cloud of failure
Let’s give the Gomez/Equation Research survey participants the benefit of the doubt for a minute and assume they have a perfect sense of exactly how many seconds they would be willing to wait for content to load before bailing out of a site. In this is true, by designing for the five-second rule *we are designing around a constraint that represents a worst-case scenario: a 74% loss of visitors due to load times.* To adequately act on this data we need to design for load times that are much, much less than this cap. If the data is accurate, the five-second rule is not nearly enough.

###Bounce to the ounce*: the difficulty of bounce vs. page weight 
In my process of questioning the five-second rule, I decided to do some investigation to track page load times vs. bounce rates. The trouble with this methodology is [website analytics measurements don’t register](http://rigor.com/2012/11/how-page-load-time-affects-bounce-rates/) until the page is partially loaded. So it becomes very difficult to correlate page weight vs. bounce. This led me to start thinking in terms of success rather than thinking in terms of failure.

###Better performance = more $
We can’t look at bounce vs. weight, but we can look at performance vs. conversions. [Amazon found that every 100 ms of load time reduced conversions by 1%](http://www.websiteoptimization.com/speed/tweak/psychology-web-performance/). In other words, they found a direct correlation between lighter page weight and more conversions. **Faster-loading content translates into more conversions on an incremental scale**. 

Measuring conversions is a way of thinking about web performance additively rather than a black-and-white cutoff. In concert terms, our goal should never be to keep people satisfied enough that they don’t walk out of the show. We want to perform so well that everyone buys our albums and t-shirts after the show.

###Web performance is a practice
I agree with Brad Frost [that performance is a *design feature*](http://bradfrostweb.com/blog/post/performance-as-design/). Performance is also a *design practice*. We should be thinking of web performance in terms of a positive, incremental scale of success, where better performance is more conversions.

Thinking incrementally means we have something productive to test for (conversions vs. page weight). [Page performance for a relaunch should be given a budget](http://clearleft.com/thinks/responsivedesignonabudget/), but conversion tracking gives us an incentive to revisit web performance every few weeks or months as new optimization techniques emerge. Because performance correlates directly with conversions, it’s also a case for paying a little bit extra for designers and developers who are willing to push the envelope on making pages ultra-light. [In the business world, they call this concept ROI](http://unsuck-it.com/return-on-investment-roi/).

*Apologies to [Zapp & Roger](http://www.youtube.com/watch?v=lK6wOG_aDl8)