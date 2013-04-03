---
layout: post
title: Session Notes for Eric Meyer’s Strong Layout Systems
date: 2013-04-01
categories: [Responsive, Tools]
author: doug
---
*Notes taken at An Event Apart Seattle on April 1, 2013*

Eric opens with “in the beginning, Tim said, let there be markup, and Tim saw the markup, and it was good.”

The web was designed to be for visual devices. Most mediums are really obsessed with appearances. In the old days, what a thing was was divorced from how it was presented.

**This fallen web**  
As with all creations, there was a fall, and as usual a reptile (Netscape) was to blame. In the ancient tongue, “Mozilla” or creator of inconsistencies" was to blame. 

They began to introduce extension to HTML, everything that mad things visual. The HR and IMG tags. “Netscape should now properly  deal with the awful comments sequence.” And it didn't stop there. Pretty soon it became tables all the way down. <!-- more -->

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
Eric points out measurement attributes of viewports. VH and VW being used for layout, and likens them to CSS REMS. These aren't magic units and they can break with incorrect measurements. 

Vmax and Vmin can be used to size fonts proportionate to the viewport. If you thought font sizing was difficult before.

**CSS flexible boxes (Flexbox)**  
Eric shows a visual example Using flex box and justify-content:space-between; to set equal widths between navigation items.

Eric points out flexbox picks up equal parent item heights. This might be advantageous for certain applications like photo galleries.

**Flexbox allows unit mixing**  
Eric points out an example where %width measurement is used with a 10 em width to flex horizontal divs used side by side.

**The Holy Grail: flexbox edition**  
Eric walks through a layout using full-width headers, footers, and three column layout using flexible reordering.

Flex-start and flex-end can used to create height variations on three column design and set alignment for an individual box using: center, baseline, flex-end.

**Grid definition**   
“Grid syntax is going to be a whole new world.” 

Eric shows a layout example using Grid-definition-columns: grid-definition-rows and grid-definition-columns. 

**Regions**  
In the old days, four divs would be used to arrange a quadrant of boxes. With regions, you can define layout areas and have content flow from one box to the next.

**The end of hacks**  
Layout by design and the ability to control grids are changing radically with new CSS tools. “If there's one thing I want you to take away from this is to challenge your own assumptions.” 
