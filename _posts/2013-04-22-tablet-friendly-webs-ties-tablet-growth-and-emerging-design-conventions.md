---
layout: post
title: Tablet-Friendly Web Sites: How and Why Tablet Growth is Changing Design Conventions 
date: 2013-04-22
categories: [Responsive, Tablets, Navigation]
author: doug
---

###The rise of the tablet  
2012 was a very good year for tablets. Tablet sales [increased almost over 78% from 2011](http://techcrunch.com/2013/03/27/idc-tablet-growth-2012-2017/) and tablets are expected to outpace desktop sales in 2013. Tablet growth [represents the fastest sales ramp-up for any device computing device in history.](http://www.businessinsider.com/bii-report-how-tablet-sales-are-exploding-this-year-2012-12).  

**Growth predictions**  
- tablet sales will grow more than 100% from 2012 to 2014 [(source: Gartner)](http://www.gartner.com/newsroom/id/2408515)  
- tablet sales will grow more than 200% from 2012 to 2017   [(source: Gartner)](http://www.gartner.com/newsroom/id/2408515)   

**Traffic and use**  
- Tablet traffic surpassed smartphone traffic in December 2012[(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  
- 100% or more increase in tablet traffic in all countries [(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  
- Visitors to web sites spend 54% more time on tablets than they do on smartphones [(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  
- Users browse view 70% more pages more on tablets than they do on smartphones [(source: Adobe)](http://blogs.adobe.com/digitalmarketing/digital-index/tablets-trump-smartphones-in-global-website-traffic/)  

**Tablet sales appear to be supplanting desktop sales** 
You will notice another trend from [the Gartner research](http://www.gartner.com/newsroom/id/2408515): laptops and desktop computers are predicted to decline. In Q1 of 2013 alone, [PC shipments posted the steepest decline ever in a single quarter](http://www.idc.com/getdoc.jsp?containerId=prUS24065413).  

**Sales drives web design decisions**  
As tablets sales rise, there is a growing case to be made for designing web sites with tablet use as a primary consideration. There are also a [growing number of tablet / laptop hybrids](http://www.webmonkey.com/2013/04/what-the-tablet-laptop-hybrid-means-for-web-developers/) offering both trackpad and touch input. 

###Designing for the Rise of the Tablet  
To accommodate for tablet and touch-hybrid laptops, site designs must be touch-friendly beyond just the mobile breakpoint. Touch input will drive design conventions because touch conventions are more restrictive than desktop conventions. As Josh Clark puts it, “[every desktop design has to go finger-friendly](http://globalmoxie.com/blog/desktop-touch-design.shtml).” 

With a mouse or trackpad, a small hand motion offers a wide range of motion. All primary OS cursors are much smaller than a human finger or thumb as well. The sensitivity level of input is much lower for touch input than it is for mouse and trackpad input, it is a 1 to 1 physical input ratio. It makes sense we would design for the less sensitive (and thus more difficult physical constraint) first.  

What does tablet-friendly design look in practice? Below are five tablet-friendly conventions that are changing site design, with live examples of each. 

###Navigation on the sides and bottoms  
Notice something consistent with the location of persistent navigation elements in the new Google+, the new Facebook News Feed, and new YouTube design modifications? *Commonly used navigation and is now located on the sides*. The sides are easiest for human digits to reach from a tablet. Luke W.’s post on [optimizing for touch across devices](http://www.lukew.com/ff/entry.asp?1649) lays this convention out in more detail.

**Examples:**  
[Google+](https://plus.google.com/)  
[YouTube](http://www.youtube.com/)  
[Yahoo](http://www.yahoo.com/)  
[New Facebook News Feed](https://www.facebook.com/about/newsfeed)  

###Flexible heights (via vertical media queries)  
Tablets use rectangular screens that are often turned from portrait to landscape orientation by users. Changes in height can be used to better prepare content as a user changes the orientation of the tablet from landscape to portrait. 

Changes of height in elements based on available space are accomplished using vertical media queries. At the time I’m writing this, [vertical media queries are fairly rare](http://responsive.ly/2013/03/use-cases-for-vertical-media-queries/). This is a convention I predict will change; height variations make sense for the dual portrait/landscape nature of a tablet display.

**Examples:**  
[Vertical media ](http://responsive.ly/2013/03/use-cases-for-vertical-media-queries/)  
[iPhone](http://www.apple.com/iphone/)  
[Fairline Yachts](http://www.fairline.com/en/)  
[Johan Ronsse Photography](http://johanronsse.be/)  

###Design Convention Change #4: Button sizes and touch targets applied to larger areas  
Touch input needs a different ratio than mouse/trackpad input due due to the size of a human digit vs. the size of a tiny cursor. Different manufacturers have different guidelines for touch ranging from around 28 pixels (Nokia’s standard) to 57 pixels (MIT’s largest range). A popular rule is 44 pixels (Apple’s standard). When designing buttons for a tablet-friendly site, consider [Microsoft’s research conclusion that errors decrease as button sizes increase](http://research.microsoft.com/pubs/75812/parhi-mobileHCI06.pdf).

**Examples:**  
[Good](http://www.good.is/)  
[Svbtle](https://svbtle.com/magazine)  
[Svpply](https://svpply.com/)  

###Left and Right Swiping and/or Arrow Navigation  
Tablet applications such as [Kindle](http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000493771) and [Flipboard](http://flipboard.com/) allow a reader to quickly flip through content sequentially by swiping left and right. In site design, this isn’t a replacement for traditional navigation, it’s just an alternate way to allow a user to quickly flip through content under a specific category.

Examples:  
[The New NY Times](http://www.nytimes.com/marketing/prototype/)  [Clearleft](http://clearleft.com/does/information-architecture)  
[Yale School of Management](http://explore.som.yale.edu/#/yale-experience/yale-university)  
[One Design Company](http://onedesigncompany.com)  

###Related content anchored to the sides of the browser  
Tablet-friendly responsive designs increasingly anchor related content (headlines, blurbs, articles) to the sides. This is not the same as running content down the side of the main copy block, a convention that has been popular since the inception of the visual web; the content still falls to the side of the main element, but is anchored or "stuck to the side of the browser window. The difference is subtle but important. By anchoring the content headlines to the sides, additional articles are easier to access with fingers and thumbs.

**Examples:**
[Quartz](http://qz.com/)  
[Smashing Magazine](http://www.smashingmagazine.com/)  

###Not necessarily new to tablets, just new to tablet-friednly web sites  
If some the web design conventions above look familiar, they should: you’ve probably seen some of these ideas before when using native tablet applications. Tablet application designers have been dealing with touch input sensitivity (or lack thereof), positioning for easy access of fingers, and dual orientation for years now. Designers must be ready to learn lessons from previous patterns that have worked on tablets and be creative enough to devise new conventions for a more tablet-friendly web.