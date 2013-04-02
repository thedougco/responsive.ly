---
layout: post
title: Session Notes for Josh Clark’s Designing for Touch
date: 2013-04-01
categories: [Responsive, Tools]
author: doug
---
*Notes taken at An Event Apart Seattle on April 1, 2013*

“Science. We're here to study the storied science of web design. But sometimes we discover we've been doing it wrong.”

There is no one true input for the web. Responsive design meant a shift in displays, but device fragmentation has meant fragmentation in input types.

We've been designing for touch for several years. But 31% of US adults own tablets now. It's up from 12% a year ago. 

“Every desktop design has to be touch-friendly.” A lot of us see our design work as visual design. When we design for touch we go beyond the visible and into the physical. It's not only how pixels look but how they feel. You're now an industrial design, it's a craft of designing a physical thing. We now have to consider ergonomics and how designs feel in the hand.

There are basically three ways to hold a phone:  
holding with one hand, interfacing with thumb from same hand (49%)  
holding with one hand, using fingers from other hand for interface(36%)  
Holding / interfacing with both hands (15%)  
(according to Steven Huber study)

With this data, we see that we're not actually designing for fingers. We're designing for thumbs. Thumbs are awesome.

Josh points out the area of interface that is most comfortable for single-hand, same-thumb interface: the lower left of the screen. He also points out this is exactly opposite of most desktop design. This pertains to the right-handed grip.

**Stacking controls at the bottom**  
Josh points out hardware buttons are often located at the bottom. The hardware engineers got the premium real estate first, and as a result some software interfaces web/app put the controls at the top. 

Examples:
Foursquare app
Twitter app

Both of these apps locate primary navigation in the lower part of the browser, where data access controls are safely tucked in the upper right, an area difficult to push unintentionally using  single-hand, same-thumb input.

**Content at the top, controls at the bottom**  
There are three problems with pinning the nav to the bottom area of the screen:  
1) Postion-fixed: is often used and it's very buggy in mobile browsers.  
2) You begin to choke out content. Real estate becomes limited. Position-fixed: elements interfere with touch. See: [Barney's New York](http://www.barneys.com/on/demandware.store/Sites-BNY-Site/default/Home-Show)
3) Stacking problem: there can be hardware and software controls at the bottom. 

Because of these problems, there's a common pattern of having a menu icon in the upper right. It points to an anchored navigation at the bottom of the screen. 

“It's not so much about staking out screen bottom, but page bottom in mobile designs.”  

**Emerging standards for mobile navigation locations:**

*iOs*  
Controls at screen bottom

*Android apps*  
Controls at screen top

*Web*  
Controls at page bottom, potentially with an icon in screen upper left / right)

**Tablet touch**  
In tablet design, controls are better located on the sides, for ergonomic reasons. These areas are most easily touched when holding a tablet; areas in the middle require arm movement. The bottom is also favorable real estate. In the tablet environment, the center space is best used for content, and the top of the screen is hardest to reach. 

**Rules of thumb**  
Favor sides and corners  
avoid top center  

**The hybrids**  
What about laptops with trackpads and touch input? In hybrid environments where people have multiple input choices, they will tend to prefer touch. Touch input does not work well on desktops because it requires a user to lift the arms in an unnatural way. But when touch input is on a laptop, it becomes much more ergonomic. Because of how people hold laptops, the side real estate remains an important common area and it tends to be thumb interface.

Josh reiterates the importance of thumb-friendly design: design for devices tends to be about keeping fingers and arms out of the way and permitting use of the thumbs.

Screen size is a lousy way to detect a touchscreen.

**CSS4 media queries**  
We can use pointer:coarse to change input types. But it's not a great solution when devices have more than one input type.

**All desktop designs have to be touch-friendly now**
“If we don't know if a device has touch input or not, we have to assume it is.“ We also have to assume this is where things are headed.

Windows 8 has taken this approach with the whole OS. They are thinking about input types from the beginning, including speech. Rest in peace, hover events…  

Examples:  
[Quartz](quartz.com)  

Put the things people use at the sides, not necessarily the main navigation. Josh makes a point that the main navigation is where people go when they can't find what they want in the main canvas. 

**How big should touch targets be?**  
Seven millimeters – study by Microsoft on touch miss rates vs millimeter target size. Millimeters are poor unit of measurement.

1 pixel = 1/96 inch  
7mm = 26.457 pixels  
it should be 30 pixels  

Unfortunately this measurement doesn't accommodate for dynamic viewports… browsers that resize.  

**Rules of thumb for touch input**  
44 pixels == 1 millimeter == 2.75 ems in most browsers  
44 pixels x 29 pixels is another rule of thumb  
iOs doubles the 44 pixel measurement for icons, default icons are 88 pixels

As we make links and other touch targets we lose density. But consider that too much of a good thing really can be too much.

Clarity trumps density.  

**Complexity is not a dirty word**  
Complexity is different from *complication*. First you have to understand what kind of complexity people want.

**Progressive disclosure**  
Progressive disclosure is the practice of changing the amount of information displayed based on available screen real estate. 

Examples:
Offscreen patterns
People magazine's collapsing of content into carousels

**New desktop design guidelines**
- hovers is an enhancement
- bottom left for controls
- big touch targets
- 44px rhythm
- use of progressive disclosure

“Sometimes the best touch interface is no touch at all.“

"Gesture + speech  = magic." Working at a distance to transform and manipulate the world around us. internet of things. 

Example:  
[Grab magic](http://www.youtube.com/watch?v=eYveEdhTgBs)

**Gestural input**   

Example:  
[Leap motion](https://www.leapmotion.com/)  

**Next gen audio input** 
bitly.com/tabledrum
It moves the whole interaction off screen. That's the promise for all this put… we can get our faces out of these glowing rectangles and into the environment, interacting with space and each other in a more natural way.

Digital is growing more physical, and physical is growing more digital. We have to challenge new patterns and embrace new inputs.
