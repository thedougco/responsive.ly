---
layout: post
title: The Tablet-Friendly Web—Why and How Tablet Growth is Changing Web Design Conventions 
date: 2013-04-22
categories: [Responsive, Tablets, Navigation]
author: doug
---

###The rise of the tablet  
2012 was a very good year for tablets. Tablet sales [increased almost over 78% from 2011](http://techcrunch.com/2013/03/27/idc-tablet-growth-2012-2017/) and tablet sales are expected to outpace desktop sales in 2013. Tablet growth [represents the fastest sales ramp-up for any device computing device in history](http://www.businessinsider.com/bii-report-how-tablet-sales-are-exploding-this-year-2012-12). <!-- more --> 

**Traffic and use growth**  
- Tablet traffic surpassed smartphone traffic in December 2012[(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  
- 100% or more increase in tablet traffic in all countries [(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  
- Visitors to web sites spend 54% more time on tablets than they do on smartphones [(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  
- Users browse view 70% more pages more on tablets than they do on smartphones [(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  

**Growth predictions**  
- tablet sales will grow more than 100% from 2012 to 2014 [(source: Gartner)](http://www.gartner.com/newsroom/id/2408515)  
- tablet sales will grow more than 200% from 2012 to 2017   [(source: Gartner)](http://www.gartner.com/newsroom/id/2408515)   

You will notice another trend from the Gartner research: laptops and desktop computers are predicted to decline. In Q1 of 2013 alone, [PC shipments posted the steepest decline ever during a single quarter](http://www.idc.com/getdoc.jsp?containerId=prUS24065413).  

**Sales drives web design decisions**  
As tablets sales rise, there is a growing case to be made for designing web sites with tablet use as a primary consideration. There are also a [growing number of tablet / laptop hybrids](http://www.webmonkey.com/2013/04/what-the-tablet-laptop-hybrid-means-for-web-developers/) offering both trackpad and touch input. 

###Designing for the rise of the tablet  
To accommodate for tablet and touch-hybrid laptops, site designs must be touch-friendly beyond just the mobile breakpoint. Touch input will drive design conventions because touch conventions are more restrictive than desktop conventions. As Josh Clark puts it, “[every desktop design has to go finger-friendly](http://globalmoxie.com/blog/desktop-touch-design.shtml).” 

With a mouse or trackpad, a small hand motion offers a wide range of motion. All primary OS cursors are much smaller than a human finger or thumb as well. The sensitivity level of input is much lower for touch input than it is for mouse and trackpad input because touch represents a 1 to 1 physical input ratio. Designing for the less sensitive (and thus more difficult physical constraint) takes care of the easier constraints of mouse and touchpad input.  

What does tablet-friendly design look in practice? Below are five tablet-friendly conventions that are changing site design, with live examples of each. 

**Navigation on the sides**  
Notice something consistent with the location of primary navigation elements in the new Google+, the new Facebook News Feed, and new YouTube design modifications? *Commonly used navigation and is now located on the sides*. The sides are easiest for human digits to reach from a tablet. Luke W.’s post on [optimizing for touch across devices](http://www.lukew.com/ff/entry.asp?1649) explains this convention out in more detail.

*Examples:*  
[Google+](https://plus.google.com/)  
[YouTube](http://www.youtube.com/)  
[Yahoo](http://www.yahoo.com/)  
[New Facebook News Feed](https://www.facebook.com/about/newsfeed)  

**Flexible heights to accommodate portrait and landscape**   orientation of a tablet display (via vertical media queries)  
Tablets use rectangular screens that are often turned from portrait to landscape orientation by users. Changes in height can be used to better prepare content as a user changes the orientation of the tablet from landscape to portrait. 

Changes of height in elements based on available space are accomplished using vertical media queries. At the time I’m writing this, [vertical media queries are fairly rare](http://responsive.ly/2013/03/use-cases-for-vertical-media-queries/). This is a convention that will change; height variations make sense for the dual portrait/landscape nature of a tablet display.

*Examples:*  
[iPhone](http://www.apple.com/iphone/)  
[Fairline Yachts](http://www.fairline.com/en/)  
[Johan Ronsse Photography](http://johanronsse.be/)  

**Larger button sizes and touch targets applied to larger surface areas**  
Touch input needs a different ratio than mouse/trackpad input due due to the size of a human digit vs. the size of a tiny cursor. Different manufacturers have different guidelines for touch ranging from a recommended touch target area of somewhere between 28 pixels (Nokia’s standard) and 57 pixels (MIT’s largest standard). A popular rule is 44 pixels (Apple’s standard). When designing buttons for a tablet-friendly site, consider [Microsoft’s research conclusion that errors decrease as button sizes increase](http://research.microsoft.com/pubs/75812/parhi-mobileHCI06.pdf).

*Examples:*  
[Good](http://www.good.is/)  
[Svbtle](https://svbtle.com/magazine)  
[Svpply](https://svpply.com/)  

**Left and right swiping and/or arrow navigation**  
Tablet applications such as [Kindle](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000493771) and [Flipboard](http://flipboard.com/) allow a reader to quickly flip through content sequentially by swiping left and right. In site design, side-to-side arrows aren’t a replacement for traditional navigation, it’s just an alternate way to allow a user to quickly flip through content under a specific category.

*Examples:*  
[The New NY Times](http://www.nytimes.com/marketing/prototype/)  [Clearleft](http://clearleft.com/does/information-architecture)  
[Yale School of Management](http://explore.som.yale.edu/#/yale-experience/yale-university)  
[One Design Company](http://onedesigncompany.com)  

**Related content anchored to the sides of the browser**  
Tablet-friendly responsive designs increasingly anchor related content (headlines, blurbs, articles) to the sides. This is not the same as running content down the side of the main copy block, a convention that has been popular since the inception of the visual web; the content still falls to the side of the main element, but is anchored or "stuck to the side of the browser window. The difference is subtle but important. By anchoring the content headlines to the sides, additional articles are easier to access with fingers and thumbs.

*Examples:*  
[Quartz](http://qz.com/)  
[Smashing Magazine](http://www.smashingmagazine.com/)  

###Not necessarily new to tablets, just new to tablet-friendly web sites  
If some the web design conventions above look familiar, they should: you’ve probably seen some of these ideas before when using native tablet applications*. Tablet application designers have been dealing with touch input sensitivity (or lack thereof), positioning for easy access of fingers, and dual orientation for years now. Because of tablet growth (sales, traffic, and use) designers and developers must be ready to learn lessons from previous patterns and be creative enough to devise new conventions for a more tablet-friendly web.

* [It's all been done](http://www.youtube.com/watch?v=Zs3xXlXSOKk) before, hasn't it?  