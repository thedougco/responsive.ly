---
layout: post
title: Use Cases for Vertical Media Queries
date: 2013-03-25
categories: [Responsive, Tools]
---

Anthony Colangelo [(@acolangelo)](http://www.twitter.com/@acolangelo) [wrote a post about vertical media queries](http://cognition.happycog.com/article/go-vertical/) last week. It  reminded me of Trent Walton's [(@trentwalton)](http://www.twitter.com/@trentwalton) [post from 2012](http://trentwalton.com/2012/01/11/vertical-media-queries-wide-sites/) and in general about a rare beast in responsive design: the height-based media query. 

Many responsive sites used width-based media queries to determine when content should stack. In a typical width-based scenario, as the browser gets narrower, multiple columns from a larger display fall inline to a single column in the mobile view, resulting in a long, skinny mobile display of content. There's nothing wrong with the long, skinny single column—it's is a design pattern mobile users are familiar with. 

With the width-based media query, we've based the decisions about displaying content on the fact that the width on smaller displays is limited and [the assumption that horizontal scrolling is bad](http://www.nngroup.com/articles/scrolling-and-scrollbars/). The thing to consider is that the available *height* in a mobile display is *also* smaller than it is on bigger displays for tablets, desktops, and televisions. 

In other words, a typical responsive design has media queries that do plenty of tweaking for width and almost none for height, even though height is a second, limiting constraint in smaller displays. Height-based queries are one way to finesse some of the layout elements based on a smaller height constraints. Instead of having our mobile displays filled with *ridiculously* long pages, they could just be *moderately* long pages.

There's a second obvious instance where vertical or height-based media queries could be used more often: very wide displays that aren't very tall. In a case where we are adjusting content for the full width of very large flatscreen, we have the opposite problem of the long, skinny experience: the short, wide webpage. If you've done much browsing of fully responsive sites on HDTVs you'll be familiar with this.

In Anthony's post, he notes the [iPhone landing page](http://www.apple.com/iphone/) uses a vertical media query to adjust the height of the hero shot. He also asks readers for examples via Twitter submission. I thought this topic could use a little a more exploration, so I collected and categorized some different use cases for vertical media queries, both from the Twitter responses to Anthony's post and other examples I was able to find by looking around.

##Modifying the size (or viewable area) of large images based on height

<img src="../../../images/vertical_one.png" width="100%" alt="Illustration of a vertical media query." />

Examples:  
+[Bath & Body Works](http://banyan-bathandbody.pagodabox.com/adventure#)  
+[Environmental Defense Fund](http://www.edf.org/)  
+[Johan Ronsse](http://johanronsse.be/)  
+[Fairline Yachts](http://www.fairline.com/en/)
+[The University of Notre Dame](http://www.nd.edu/)

##Tightening line height and/or font size based on height

<img src="../../../images/vertical_two.png" width="100%" alt="Illustration of a vertical media query." />

Examples:  
+[Trent Walton](http://trentwalton.com/2012/01/11/vertical-media-queries-wide-sites/)

##Removing height from whitespace between page elements based on height

Examples:  
+[Statamicist](http://statamicist.com/)

##Modifying number of feeds based on available height

Examples:  
<img src="../../../images/vertical_three.png" width="100%" alt="Illustration of a vertical media query." />

I couldn't find any live examples of this, but there's a fourth use case I can think of based on a project I'm working on now: changing the number of RSS feed items displayed based on height. My logic is that as long as a person is only one click or touch away from a full feed, large RSS feeds might get truncated in smaller views to prevent mobile pages from becoming ridiculously long.

##Demos
+[CSS Tricks height-based bootstrap madness](http://css-tricks.com/examples/VerticalMediaQueries/bootstrap.html)–a demo that shows a number of different page modifications based vertical media queries.

+[Philip Zastrow's height-targeted color changes](http://phanza.com/2012/08/24/media-min-height/)

*Posted by Doug Gapinski [(@thedougco)](http://www.twitter.com/@thedougco)*