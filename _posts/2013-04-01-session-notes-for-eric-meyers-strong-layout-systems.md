---
layout: post
title: Session Notes for Eric Meyer’s Strong Layout Systems
date: 2013-04-01
categories: [Responsive, Tools]
author: doug
---
*Notes taken at An Event Apart Seattle 2013*

Eric opens with “in the beginning, Tim said, let there be markup, and Tim saw the markup, and it was good.”

The web was designed to be for visual devices. Most mediums are really obsessed with appearances. In the old days, what a thing was was divorced from how it was presented.

**This fallen web**  
As with all creations, there was a fall, and as usual a reptile (Netscape) was to blame. In the ancient tongue, “Mozilla” or creator of inconsistencies" was to blame. 

They began to introduce extension to HTML, everything that mad things visual. The HR and IMG tags. “Netscape should now properly  deal with the awful comments sequence.” And it didn't stop there. Pretty soon it became tables all the way down. 

“Why did the web designer leave the restaurant? Because he was offended by the table layout.”

**CSS to the rescue**  
CSS came along and had all these properties that tables could not match. The box model added new elements.

CSS added all these capabilities. You could do new things, but something was always missing. A layout system. Floats had to be used for layouts. You could sort of use floats for layouts. But floats weren't meant for layout. We went from one hack to another.  

**CSS2 was going to fix the layout problems**  
CSS2 introduced new properties with positioning. But you had to be careful so things wouldn’t get repositioned in strange ways. Here’s the other thing about positioning. There was a small limitation.

We forget a lot what we were up against at the time and how that shapes how we solve now. Situations and constraints that no longer pertain shape how we develop now. We don’t do equal height columns anymore. 

Over time, markup became better. We weren't using tables, but we were still hacking layouts. CSS table display is also a hack. We just kept using tools for purposes they weren't meant for.

We are leaving that era behind. Tools, features, capabilities of CSS are evolving that are solely meant for layout. 

We have these design patterns that we’ve internalized that are based on the limitations of our hacks. Conceptually, as you look  at your designs, try to see your own assumptions.

**Viewport Units**

“ ” ’