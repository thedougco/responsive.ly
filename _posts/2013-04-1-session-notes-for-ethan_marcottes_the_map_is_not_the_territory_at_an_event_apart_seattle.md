---
layout: post
title: Session Notes for Ethan Marcotte’s The Map is Not the Territory
date: 2013-4-1
categories: [Responsive, Tools]
author: doug
---

*Notes taken at An Event Apart Seattle on April 1, 2013*

Ethan’s session is about the map, the territory and the need for wide open roads. First he tells us of the first map he ever saw, at his grandmother’s house, and then proceeds into a story about William Fairfield Warren.

## William Fairfield Warren

[William Fairfield Warren](http://en.wikipedia.org/wiki/William_Fairfield_Warren) was a minister whose life was radically altered by Charles Darwin’s work. He wondered what questions to ask in the wake of the revelations about evolution and decided to go in search of the physical location of Eden.<!-- more -->

He did some research about where Eden could be on the globe, and he deduced there was only one possible location: the North Pole.  The irony in the story is what man's incomplete understanding of the territory leads to. 

Ethan draws a parallel between the emergence of multi-screen use in the web as the discovery of evolution. “Mobile kind of broke everything.” But maybe it didn't break everything, maybe it pointed out a that we needed to question our own assumptions and “consensual hallucinations.”

## Definitions of responsive design

1. Fluid grids  
2. Flexible images  
3. Media queries  

“We can design for the ebb and flow of things” --John Allsop

Reading:
[The New Multi-Screen World Study](http://www.google.com/think/research-studies/the-new-multi-screen-world-study.html)

Mobile computing is personal to an extent we've never had before. It's new territory, so we're filling in the landscape. But our work is only beginning. Our map is far from complete

## Alfred Korzybski

Alfred Korzybski was a Polish-American philosopher and scientist. The issue of a rhetorical divide and object and a representation between it. He created a construct of the map/ territory relationship. But first, what's a rhetorical divide? 

## Rhetorical divides

Let’s say you were to explain to Ethan the experience of drinking a cup of coffee. You might start in any number of places… with a specific sensation, or with a mug, or a with a cup of tea. But something will always get left out. And the more words we use, the greater that divide becomes. A rhetorical divide is why we have the expression, “something gets lost in translation.”

According to Alfred Korzybski,  
> The map is not the territory it represents, but, if correct, it has a similar structure to the territory.

We obsess over the map, without stopping to consider the territory it represents. This is true in the field of web design and development; a rhetorical divide exists between the solutions we create and the reality of the people on the other end of the solution.

## The web is

Our own definitions are framed in western terms. We think of the mobile web in terms of the iPhone. We’ve mistaken the map for the territory.

## Dhaka, Bangladesh
It's officially classified as a megacity. It has a large population and a high population density.
Some facts about Dhaka:

- 15.4 M inhabitants
- 134 square miles
- 115,000 people per square mile
- It is the 6th most unlivable in the world
- in 2011, the number of mobile users grew by 900%
- In Dhaka, mobile phones are often rented out by individuals. 

90% of new mobile penetration happening in developing countries. 

United Nations Deputy-Secretary General Jan Eliassan states:
>Of the worlds seven billion people, six billion have mobile phones.

Developing countries are succeeding radically with mobile advertising, as opposed the US model where we've struggled to make it work.

Rapid urbanization + cheap devices is changing what the web means from people. The divide is between a western mode of thinking and the reality of where mobile technology is growing the most.

## Examples of mobile technology in developing countries

- [Hatari](http://www.hatari.co.ke/): an app for reporting corruption in Kenya  
- [Mimiboard](http://www.mimiboard.com/): an example for localized reporting of food sources, weather, deals  
- [M-maji](): mobile water in Swahili, a service designed to improve clean access to water  

## Reach

These apps are designed for reach. It's easy to write these off as being specific to developing countries. But these area represent an emerging new normal that presents with an opportunity to think about how we design. By providing solutions, the apps shorten the rhetorical divide between solution and problem. They are addressing use.

Framed differently, a majority of the world is now coming online for the first time using non-precious devices.    

## John Randel, Jr., Mapmaker

In the last years of the 1700s, the population of NYC was around 125k people. The population was mostly concentrated in Manhattan. North of that southmost point, much of area was expansive estates. It was not an effective division of space The most populous areas on the southmost point of the island were a mess. They were fire hazards, disease hazards, and difficult to police.

## Mapped Over
John Randel, mapmaker, was tasked with mapping a solution. He would walk the length of the island every day with a board, planting marble / iron posts for city planning. He and his team produced a series of 9ft x 30in wide maps. This was a grid of streets that became a perfectly orthogonal grid for the plan of modern-day New York. His team was harassed, but they were also notoriously uncompromising about their plan for new streets. The uncompromising acts of planning were called "mapping over," and critics called the plan woefully unimaginative and geometric. 

But it was a system designed for use. A system designed for the health of the city. The Randel map was a map in reverse: a map designed to change the territory.

## Relative sizes: the territory in web design

- In 2009, the average site was around 320kb  
- In 2012, it's 1.1MB  
- Consider we managed to put a man on the moon with 64KB of software  
- The average original NES console game was 256KB  
- Teehan + Lax site: 3 MB  
- NY Times homepage: 3 MB  

For too long, we treated performance and accessibility as separate ideas. Complexity is not a thing to be avoided. We just have to be intelligent about it.

Ethan refers to the [Chris Zacharias blog post about page weight](http://blog.chriszacharias.com/page-weight-matters)… web performance used to improve life for YouTube users.

## Editorially
Ethan founded a company last year on the idea that writing becomes better when it is collaborative. It is a fully responsive, web-based app that allows for collaborative writing using Markdown.  

Ethan walks through a brief study of applying the three fundamental of #rwd to Editorially. 

## Priorities for Editorially

- Logo  
- Account  
- Ability to create a new document  
- Document access  

They chose to place the menu at the bottom.

Responsive design isn’t just about layout. We don’t just think about screen sizes, we try to plan for different input devices.

Ethan walks through some examples of how touch input works in the Editorially preview, including how they ended up questioning the decisions they made about the timeline because the UI stemmed from mouse-based input.

>“Accept the ebb and flow of things”
> --John Alssopp

We need a new definition of beautiful. We need greater craftsmanship and clutter-free interfaces but we need greater awareness that our designs may not make it the user we're designing for.  

Example:  
[BBC News](http://www.bbc.com/news/) as an example of a site the successfully deploys progressive enhancement: designing for the high-end experience, but also meets users successfully on devices with limited bandwidth  

We often forget how fragile the elements of our design are. Ethan refers to Tim Berners-Lee's law of Least Power:
> “Choose the least powerful computer language suitable for a given purpose”

We should design for the least power. We should be interrogating the tools we use. But this applies to design, not just code. 

When we design for the web, we surrender so much control over to the people who use it.

## Allowing the user to see the seams

“Seamful design” – points out filament group HD / SD image toggle. It invites the user into the design, and affords the user a little more freedom of control over the experience. The user can see the seam and is afforded a greater degree of control.

## Conclusion

Some of our solutions might lie with the person on the other end of the screen
