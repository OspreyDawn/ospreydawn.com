---
layout: post
title: 'Why UX is so Important'
date: 2014-01-13 23:00
description: A retelling of how I learned to appreciate and eventually advocate great UX design.
keywords:
comments: false
categories: [UX]
published: true
sharing: true
---

One of the assignments I worked on during the final year of my degree opened my eyes to User Experience Design. It wasn't intentional and what I learnt wasn't strictly the purpose of the assignment - I learnt far more. I've carried on with UX design (and more) over the last year though I can't really make any of that public yet. Anyway I liked the result of this particular project so capturing the process and results in one place seems like a good idea. Not quite a project post-mortem per-se, more a reflection that this assignment's experience was the time where I truly appreciated and understood the importance of good UX design, so I wanted to capture some of that.

Here's the App "pitch" video developed over a couple of days that shows the app in action - at least what we wanted it to be - and shows in summary the results of the design work.

{% vimeo 52553458 %}

This was a team project (a team of three), however all the work presented here was my contribution to the effort. We were tasked with creating an App that could "help people for the better" in one of three categories - food, shelter or safety - and about forty hours each spread over five weeks. Not much time considering there were new methods and technologies to learn, figure out what to do, and design it. Added to that three other course related projects to work on as well.


##Choosing the idea

We chose to focus on designing an App and Website to bring organic food to the tables of urban dwellers.

Organic food is a conscious life style option. Going organic is generally considered better for you, better for the environment, and better for taste. There are many factors that prevent local and organic from being the standard choice among city urbanite. The most significant is perceptions around cost. Judged entirely on price organic food is more expensive than it's processed counterparts. Another problem is availability; it’s hard to find what you want or you just adjust your diet to suit. Likewise Farmers markets are infrequent, too far away or don’t line up with your schedule. Basically convenience and certainty are the main reason for shopping at supermarkets so any App would be competing mostly on convenience. 

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.005.jpg" alt="Sero Website Hifi Mockup" />
</div>

When you think about it, good organic food shouldn’t be hard to find - at least not in New Zealand. Many people have space to grow something of value that can be shared with their neighbourhood in some capacity. There’s just no convenient way to reliably coordinate supply and demand. To us this was a "help people for the better" problem that we felt could be solved with a little bit of mobile technology and simple design. If only everything was so easy.

A couple of organisations already exist in New Zealand trying to solve this problem: [BuckyBox](http://www.buckybox.com/) and [Ooooby](http://www.ooooby.org/). [BuckyBox](http://www.buckybox.com/) helps farmers set-up and sell food directly. They manage all the administrative hassles associated with business management, sales and distribution via a Cloud based solution. [Ooooby](http://www.ooooby.org/) is a community of growers and consumers. It connects consumers and growers; a customer orders the food, the farmers prepare it and [Ooooby](http://www.ooooby.org/) makes sure the exchange and delivery takes place. [BuckyBox](http://www.buckybox.com/) and [Ooooby](http://www.ooooby.org/) focus on either end of the spectrum, grower focused or consumer focused respectively. 

Since [BuckyBox](http://www.buckybox.com/) are Wellington based we arranged to meet with Sam Rye during our investigation phase. We also spent sometime going to the local farmers market and looking around the local whole-foods supermarket. We didn't have time to do proper user research however, but Sam gave us a really good overview of the current problems with locally small-lot grown food distribution. While Sam wasn't our target customer he'd had plenty of exposure to the problem space and helped to narrow the scope and pointed us into lines of enquiry that we could take. One of the main points of discussion was the idea of time and location. 

In my hometown of Tauranga you would often see street-side [honesty boxes](http://www.flickr.com/groups/1223007@N23/) and pop-up street trucks/vans selling all sorts of locally grown foods. There is a bit of a NZ tradition for country road-side honesty boxes too. The thing is you're never sure what is available locally and many people don't plan what they'll be eating for dinner until the 5pm drive home. Could we help local neighbourhood growers advertise availability and locality in a way to make it easier for someone to plan a meal? It seemed like problem worth solving. In a sense could we provide a distributed yet connected community garden?

##Initial UX

We had found our apparent market need. Realistically we'd done absolutely zero market research into the market potential but then this was a design paper not a market research paper. Now to define the specific design problem we were to solve. 

Given our time budget the ambition for our little project was quite large so we narrowed the focus on selling just the vision, how it would work, and provide a rudimentary working prototype. I ended up working on the user experience; well what we thought of as User Experience. In reality we all saw user experience as being the App and Website's visual design. I still get the sense this is what most people think User Experience design is. I'd had a little bit of exposure to Interaction Design earlier in the year working on a pervasive gaming concept for Start-Up weekend and earlier assignment work. As far as User Experience design was concerned however I'd never really practiced any, so I was interested in learning some principles and methods. 

Ideally time performing some user research would have been nice. To go out talk with customers, question them, to observe in order to find out who the potential customers were, their needs, their lifestyle and their traits. Looking at their environment, routine, their meal planning. None of that was realistically possible so the process defaulted to a bit of genius design - guess work based on intuition. Imagination if you will.

I started by scribbling numerous lists and sketching out some concept/mind maps of the various potential users of the App. 

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.001.jpg" alt="The Farmer" />
</div>
 
I'd been reading material from [Adaptive Path](http://www.adaptivepath.com/ideas), Indy Young's book [mental models](http://rosenfeldmedia.com/blogs/mental-models/) and was loosely familiar with the idea of Persona. Based on the thoughts developed doing the concept maps some small persona - semi-fictional atypical characterisations based on real people and their contextual life scenarios - were sketched out. Except in this case they were completely fictional, not based on any research. Regardless as a tool the creation of the Personas helped to focus the effort. Personas provide a way to consolidate understanding around arch-types of our customers and to keep them human. I suspect you can spend a good amount of time researching, developing and documenting persona but in this case the persona were just some fairly basic descriptions of the people.

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.002.png" alt="Primary Persona" />
</div>

With the persona done I listed out the many different things each of these persona would want to achieve and broke them down into groups that were common. That lead to building a framework for the information architecture of the App.

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.003.jpg" alt="Listing out a framework" />
</div>

##Better UX

Next was working out what I thought would be an appropriate focus and direction for the User Interface. Working up a rough first draft of the interfaces for the App and Website in a lo-fi wireframe form. We iterated on the initial UI design several times. As a part of class process regular class sessions with our course coordinator and the rest of the class were held. During these sessions we would critique each others work and solicit feedback. This was a stable practice for all the design papers and itself a key design method for UX too. It was in these sessions I started see issues with the focus of the App. 

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.004.png" alt="Initial Lofi Wireframe" />
</div>

In what was a very literal, somewhat narrow interpretation of customers' perspective, the App UI reflected customer modes. Customers were either a buyer or a seller. Our paper coordinator was confused by the separation. What appeared to be a natural translation to each need - the marketplace and the storefront - he insisted it wasn’t necessary and ultimately confusing. Secondly when my teammate was implementing the interface she found it hard to navigate; adding to criticisms that it was far too cluttered. At that point I honestly wasn't sure how to rectify the design.

It was back to the drawing board, trying to identify missteps in the process. The personas were sound for the most part and provided sufficient detail for this project. I had gone through and identified features that seemed necessary but they were wrong. Discussing the problem I was pointed toward a talk [“Application Interface Design.”](https://speakerdeck.com/garrettdimon/application-interface-design-2008) by [Garrett Dimon](http://garrettdimon.com/). 

Dimon goes in to great detail about his design process where his primary tool for investigating the task flow of the App was understanding users' constituent goals. This is actually the primary message of Young's book [Mental Models](http://rosenfeldmedia.com/blogs/mental-models/) mentioned previously though that hadn't sunk in and I hadn't made the connection. By identifying how people processed their goals when shopping or selling food and aligning them I could find patterns. As a result I stepped back from wire-framing and started to look more at each persona's goals and tasks. 

To help in this task I concocted a rudimentary diagram which upon reflection is kind-of a cross between swim-lane task flow and a concept map. A little quirky but they served the purpose. An example of one is below. Keep in mind I had no need to produce polished design deliverables other than the finished UI and visuals. So these diagrams were tools to help me think about the problem space and not specifically for communication - to the team or otherwise.
  
<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.006.png" alt="Persona Goals" />
</div>

I started by identifying primary goals. Something the User was really trying to achieve. Trying to describe each goal as succinctly and clearly as possible helped to clearly understand each goal. The primary goal is placed in the centre of the diagram. Then I thought about what the result of achieving that goal would be, the outcome. I labelled that as output because at the time that is how I viewed it - the output of achieving one goal was typically another related sub-goal. Likewise there were sub-goals that needed to be achieved before-hand as inputs to the primary goal. 

By identifying my two most important personas - Julia as the buyer and Dan as the seller. From these two persona’s I was able to break down their goals and workout what was important to them when it came to buying or selling food. Getting out and briefly questioning some people on how they chose to buy food also added insight to the goals and persona. Julia would now choose her food based on recipes she had made previously or liked the idea of making. Her food buying decisions were based on that goal. For Dan, his decisions would be based on preparing for a day of sale and updating his progress as the day went by.

I created these goal diagrams for the primary persona, refining as I went. I whittled down the goals progressively fine tuning them until I was happy I'd captured the essence. The take away from [Dimon’s talk](https://speakerdeck.com/garrettdimon/application-interface-design-2008): the simpler the underlying structure of the application, the simpler it would be as you moved up through the levels of design.

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.007.png" alt="Some of the taskflows" />
</div>

Proceeding on from identifying my primary personas' main goals I then started working on taking these goals and fleshing out a very basic set of steps; a task-flow. Again these diagrams were for my own thought process so I did the basics. Just enough to help design the task-flow and to keep it simple. Each input to the primary goal was broken down into appropriate actions that would be taken in the App and aligned these inputs with other personas to see if it followed through for each.

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.009.png" alt="Revised Lowfi Wireframes" />
</div>

The key insight obtained from working on the goals and and task-flow was that most of the goals amounted to maintain lists. The list metaphor and goals structured the User Interface. As a result a completely new interface was developed and from it you can clearly see the improvement. To help develop the new interface I mapped the task-flows using the [Interactive Sketch Notion](http://www.linowski.ca/sketching.php) onto the Wireframes. This helped to refine the interface but the process of working on the abstract goal centred task-flow prior to this really simplified and speed-up the whole process.

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/Sero-Image.011.png" alt="Wireframe and taskflow" />
</div>

Once the UI was locked down I worked on the visual aspects of the design producing a high fidelity version of the App UI and long with all the assets required to build it. Part of creating the visual language for the App was tied directly to developing the Brand of the App - the name, the colour schemes, logo and typeface etc. While really important to the final appeal of the App and it's User Experience fundamentally it was secondary to getting the purpose of the App and it's core focus right first that really made the difference.

<div id="seromobileui_hype_container" style="position:relative;overflow:hidden;width:211px;height:400px;left:50%;margin-left:-105px;">
	<script type="text/javascript" charset="utf-8" src="{{ root_url }}/assets/images/work/blog/great-ux/SeroMobileUI.hyperesources/seromobileui_hype_generated_script.js?11113"></script>
</div><br/>

Since the structure was so simple and sound, I was able to use it again to design  the desktop web interface. It meant it would function the same as the mobile version yet completely redo it's visual layout and aesthetic to suit the expanded medium with great success. The low-fi wireframe is shown below and the final hi-fi visuals of the home page is shown near the top.

<div class="post-thumb">
	<img src="{{ root_url }}/assets/images/work/blog/great-ux/website-wireframes.jpg" alt="Some of the Website Wireframes" />
</div>

Finally we were required as part of our hand-in to produce a video of the App that is included at the top of this post. Overshooting the requirement by a long shot I decided to create an App pitch video, the type of video common today. Producing the video really made me think about how to communicate the motivation for the whole App and it's User Experience. It was also a great way to help consolidate a design. If you can't communicate to your audience what your design does and why, then it is properly not well designed. Once again actually doing that for Sero was fairly straight forward because I'd taken the step back to understand the underlining user motivations - even if they were almost entirely imagined.

##Conclusion

I came away from this small project realising that UX design is the most important step to get right when designing something. It makes sure you focus on the people using your product. To make sure the final result is not just usable but enjoyable too. Tying into peoples goals is key. My main interest is in game design so I'd never really considered user experience in that context before. I was far more concerned about game mechanics and the visual aesthetic. What I learned doing this project was User Experience design is just as applicable to games and the principals and methods are also directly usable. Games make it very easy for us to identify our goals and reward us for accomplishing them. In a real life sense it means letting the user achieve what they set out to do without a hitch and enabling them to do it on their own. By focusing on the user, you can create an elegant framework that scales upwards through the design process making the experience seamless no matter where you take it. It doesn’t matter how good your product looks, if it doesn’t have a good foundation people will not want to use it; it’s universal. That’s why UX is powerful and learning it first hand has made me an advocate for great UX design across the board.

*Get the [full sized versions]({{ root_url }}/assets/other/Sero-Images.zip) of the images and video used in this post.* 
