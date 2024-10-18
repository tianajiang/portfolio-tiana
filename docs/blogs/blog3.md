---
title: Poor Visual Design in Reddit UI
layout: doc
---

# Poor Visual Design in Reddit UI

In class we discussed UI visual design, and how small changes to a UI can make big impacts on how users percieve the information on the page. For example, using a little bit more horizontal white space can help a user to percieve a grid of dots as lots of columns of dots instead. All of this made me think of Reddit's UI and the ways that it goes against intuitive, understandable, and usable visual design. I analyze some of the ways this happens below.


Here is the Reddit homepage with a few posts on it.

![Reddit Homepage](/images/redditHome.png){:width="300"}

A a quick glance, it is very difficult to distinguish what elements are a part of what post, and where one post end or the next one begins. This is because this breaks the principle of proximity, where related elements should be grouped while unrelated ones are spaced apart. The elements with a single post have about the same amount of whitespace as the whitespace between separate posts, leading to all of the components blending together into one.

Along with this, the UI also suffers from very fragmented and discontinuous content flow. As seen above, some posts have large preview images or embedded videos, while others consist of just text or links. This lack of predictability disrupts the user's rhythm, making it harder to scan through content smoothly. Users need to adjust their reading pattern constantly to interpret each post, which fragments the experience and violates continuity. 

When you click into a post, you can see the comments on this post, as seen below.

![Reddit comment section of a post](/images/redditComments.png){:width="300"}

You can see again that the principle of proximity is not used well here. It is difficult to tell which set of icons (upvote/downvote, reply, share) go with which comment. It is also difficult to tell when a comment ends or begins, as the whitespaces between lines in the same comment are larger than the whitespaces between comments. 

The discoverability of this interface is also low, as the structure and functionaliy of the comments is very unintuitive. The lines along the left side of the comment section are clickable to collapse or expand threads, but there is no visual cue or tooltip to indicate that they are interactive. As well as this, although replies are nested with slight indentation, the narrow margin between parent and child comments and the clutter of other information and visual elements makes it hard to track which reply belongs where—especially when conversations run several levels deep.

We can also dive deeper and consider not just the layout, but the design decisions of specific elements, such as the upvote and downvote element. Below are screenshots of this element after upvoting and after downvoting, respectively.
<br>
<div style="display: flex;">
  <div style="margin-right: 10px;">
    <img src="/images/redditUpvote.png" width="100"/>
  </div>
  <div>
    <img src="/images/redditDownvote.png" width="100"/>
  </div>
</div>
<br>

The colors chosen, red for upvote and purple for downvote, are unintuitive and don't align with common user expectations. Typically, red is associated with negative actions, like errors, warnings, or stop lights, and yet are the color for upvoting on Reddit. Purple has no universal association and only adds to the clutter and visual overload on the Reddit UI. 

All of the above examples show how Reddit's UI is unintuitive and violate many of the good design principles we talked about in class. 



