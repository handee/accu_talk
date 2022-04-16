# accu_talk

This repo contains my keynote slides for accu talk

 * Uses Beamer (LaTeX) for slides
 * Has some hacky python to make a figure
 * Includes links to references etc.

I used an animation for the first time in this talk -- via the Beamer \multiinclude command; it involved exploding an animated gif into frames, then incorporating these. It means that when you build the pdf it looks like it has over 100 pages, but a lot of these will autoplay when you get to the appropriate page.

## keynote style?

Lots of tech talks these days go for a not-many-words-on-the-slide approach. In
these talks, the slides are illustrations rather than support, I think. I've
done a few talks like this but have drifted back towards a more wordy slide
layout, using Beamer.
 
I like Beamer for slides for a couple of reasons:
 
 * The incoporation of structure is trivial:
    * You can use LaTeX sections to break up your talk conceptually
    * Structuring the talk is then easier (you can decide sections and move around sections as you write) 
 * References and footnotes and figures just work, and I like giving backup data and evidence rather than just opinion
 * I can write my slides in vim 

### for the viewer
 * The incorporation of nav stuff (dots across top of screen, page #) gives instant location in time
 * Incorporating section info in nav helps lots as presenter and viewer
 * Autogenerating section start slides makes it effortless to include explicit signposting (I've spoken about x and now I'm going to discuss Y) in the talk itself
 * I've had some interesting chats with some ADHD folk who like the signposting A LOT - if their attention drifts they don't come back to a single word and have to work out where they are / what they've missed
