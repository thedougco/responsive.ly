---
layout: post
title: Use Cases for Vertical Media Queries
date: 2013-03-25
categories: [Responsive, Tools]
---

Anthony Colangelo [(@acolangelo)](http://www.twitter.com/@acolangelo) [wrote a post about vertical media queries](http://cognition.happycog.com/article/go-vertical/) last week. It  reminded me of Trent Walton's [(@trentwalton)](http://www.twitter.com/@trentwalton) [post from 2012](http://trentwalton.com/2012/01/11/vertical-media-queries-wide-sites/) and in general about a rare beast in responsive design: the height-based media query. 

These days, developers are mostly using width-based media queries. A common practice is to use media queries to collapse multiple columns to a single column in the mobile view, resulting in many long (sometimes ridiculously so), skinny mobile sites. There's nothing wrong with the long skinny single column. It is a design pattern mobile users are familiar with. Height-based queries are one way to finesse some of the layout elements that really don't need to be so tall. Instead of having our mobile displays filled with *ridiculously* long pages, they could just be *moderately* long pages.

There's as second place where vertical media queries come in handy: very wide displays. In a case where we are adjusting content for the full width of very large flatscreen, we have the opposite problem of the long, skinny experience: the short, wide webpage. If you've done much browsing of fully responsive sites on HDTVs you'll be familiar with the short, wide webpage phenomenon.

In Anthony's post, he notes the (iPhone landing page](http://www.apple.com/iphone/) uses a vertical media query to set the height of the hero shot. He also asks readers for examples via Twitter submission. I thought this topic could use a little a more depth, so I collected and categorized some different use cases for vertical media queries.

##Modifying the size (or viewable area) of large, horizontal graphics

<img src="../../../images/vertical_one.png" width="100%" alt="An old illustration of an historic US University." />

+[Bath & Body Works](http://banyan-bathandbody.pagodabox.com/adventure#)  
+[Environmental Defense Fund](http://www.edf.org/)  
+[Johan Ronsse](http://johanronsse.be/)  
+[Fairline Yachts](http://www.fairline.com/en/)
+[The University of Notre Dame](http://www.nd.edu/)

##Tightening line height and/or font size

<img src="../../../images/vertical_two.png" width="100%" alt="An old illustration of an historic US University." />

+[Trent Walton](http://trentwalton.com/2012/01/11/vertical-media-queries-wide-sites/)

##Removing height from whitespace between page elements
This is a rare example that alters white space of several elements proportionate to the amount of vertical space available.
+[Statamicist](http://statamicist.com/)

##Modifying number of feeds shown on tall, skinny displays

<img src="../../../images/vertical_three.png" width="100%" alt="An old illustration of an historic US University." />

There's a fourth case I can think of for a project I'm working on: changing the number of RSS feed items displayed based on available height. My thought on the project was that as long as a person is only one click or touch away from a full feed, large RSS feeds might get truncated in smaller views to prevent mobile pages from becoming ridiculously long. 

##Killer Combo
[CSS Tricks height-based bootstrap madness][http://css-tricks.com/examples/VerticalMediaQueries/bootstrap.html].

##Demos
[Philip Zastrow's Height Targeted Media Query](http://phanza.com/2012/08/24/media-min-height/)

*Posted by Doug Gapinski [(@thedougco)](http://www.twitter.com/@thedougco)*