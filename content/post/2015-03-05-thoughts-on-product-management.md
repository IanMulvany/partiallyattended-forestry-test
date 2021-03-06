---
categories:
- product development
- software
- product management
- lessons
- mendeley
- nature
- connotea
- elife
date: 2015-03-05T00:00:00Z
title: Some thoughts about product management
url: /2015/03/05/thoughts-on-product-management/
---

I moved into digital product management in 2007. I had no formal training, and for much of the last eight years I've been learning on the job. There are a huge number of resources out there, great lectures, books, conferences, blog posts. In this short post I just want to reflect a bit on what I've learned on this topic through direct personal experience. I continue to learn, and my thinking continues to evolve, so this post is more of a look back, than a look to the future. I've pinboarded a few of my favourite links under the tags [product development](https://pinboard.in/u:ianmulvany/t:product-development/) and [product management](https://pinboard.in/u:IanMulvany/t:product-management/). I also highly recommend [Marc Abraham's blog](https://marcabraham.wordpress.com) , he writes frequently on things he learns and on his experience putting those things into practice. 

# So what is product management/development, can we define it?

When I first heard the term I thought that there might be a single thing that one did as a product manager. However what one is dealing with at a fundamental level is an intrinsically complicated process involving many different moving parts, from people, to markets, to technology. It requires many different skills with opportunities for contributions from many different quarters, and as a result cannot be reduced to a one dimensional description. 

I really like 360 view on product management in Roman Pichler's post about [what is product management](http://www.romanpichler.com/blog/romans-product-management-framework/), and it's the kind of view that I have now internalised, but it took me a few years to get there. 

Anywhere people want to get things done, there is room for someone to look at the process with product development glasses on. You often hear this as referred to as _taking the voice of the user_. In addition to this I think we can break it down along another axis, one based on efficiency of effort. In recent years this has been codified under the _lean_ heading, _lean startup_, _lean UX_, _lean enterprise_. 


# Are there any commonalities around what we do? 

I think there are, I think that at any moment we need to:

- figure out what the best thing to do is  
- do that thing   

We often fail at both of these through a combination of doing things that are just the next thing in front of us, doing things that seem like a good idea but that have little evidence to support them, and then taking these sub optimal ideas and failing to execute on them. This is not a situation to bemoan too much, it emerges as a natural consequence of human optimism and desire to be productive, combined with operating in an environment where there is far from perfect information. 

There are two pathologies that I want to call out as being especially harmful 

- working on a project or idea, and then changing your mind later and throwing away all of that effort without getting to the point of deliver  
- doing a lot of effort, and in the end building something that no one uses   

The first of these sucks a lot more than the second one. At least with the second one you have a chance to learn something, and maybe get it better the next time. 

# What can help navigate us through this fog? 

I've just started reading [lean enterprise](http://shop.oreilly.com/product/0636920030355.do) and the authors make an early analogy to the uncertainty we face in creating systems and products with the uncertainty of war. They talk about the fog of war and how to mitigate against it. I think it's a very powerful analogy, and so the question in front of us is what activities or tools can help us to navigate through this fog in the context of product development? 

- Create a sense of direction.  
	You want to have confidence that you know the right way to be facing right now. That might change soon, and the right thing might be finding out more information, reducing uncertainty, or re-plotting your course, but you want to avoid rudderlessness, you want to avoid drifting. It's great to be able to identify when you need more information and to be able to act on that. It's OK to be in a state of uncertainty, but it's less OK to be blind to your lack of information or direction. There are many tools to help with this, from vision statements, roadmapping, using a ticket triaging system, user research, business model generation, lean experimentation, MVP. They can be applied at different stages in the product and business lifecycle, but they all attempt to give you guidance on what you should be doing right now.

- Find out what's working.  
	You can't do all the things (though you should automate all the things!!), and every thing that you do creates a level of maintenance that you have to support, and it represents potential technical debt that could get in the way of the next thing that you want to do, so after you do something, try and figure out if it's doing what you expected as well as you expected. Analytics, marketing, user testing, more user testing, revenue, buzz are all guides to this. 

- Feed back the stuff you have learnt into the next iteration.    
 Learn and iterate, you know what you should be doing, you know how successful your last iteration was, take what you learnt into your next iteration. One thing I've been often guilty of is releasing a thing, and leaving it and moving on to the next thing. Products mostly get better when they evolve, and systems mostly get more efficient and fit for purpose when they are given the freedom to change in the face of changing needs or new pain points (this often requries refactoring, and you should not consider refactoring to be an evil, but rather a consequence of working with software). Developer pain, user pain, 5% time, MVP, releasing not fully finished products early, show and tells, design crits, code sharing, code review, BDD are some of the tools that can help here.

Of course I've just described in a very loose way a rough workflow based on agile and on the lean manifesto. All I can say here is that these are lessons that I have learnt through direct experience, mostly though not doing these things. 

# My greatest hits/mistakes 

Here are some examples of product management _koans_ that I've internalised as a result of a direct experience. I might be wrong on some of these, and some of these might no longer represent as much of a risk as it once did, but these are where my current natural baseline of thinking sits right now, and so it's useful to be able to describe them, so that that they don't remain as sacred cows, but can be farmed, and perhaps taken out and replaced at some point by more useful lessons. 

- Focus on shipping product   
	At Mendeley we had three core products, web, desktop and data services. The desktop client had a slow release cycle compared to the other two product domains. Coordinating features across all three components was a challenge, and often we would drop work mid flow to focus on a new idea. This led to waste, frustration, and sometimes disagreements about priorities. We recognised that getting to a situation where we could ship updates sooner would be critical to overcome this. 

- Make the work visible  
	Sometimes work gets dropped because no one knows that it is happening. Making work visible through card boards, kanban, good retrospectives, or introspectives can be a real boon to not allowing work to go to waste. Often I would discover at Mendeley that there was a lot more effort than I had realised was going on around a feature, only after we had decided to modify or drop that feature, and when I made decisions to switch priorities I was annoying developers more than I had realised. 

- Keep your developers happy  
	Get them into a position where they can ship, remove technical debt where possible, keep scope clear and small and provide them as much contact to the end users as you can. Again at Mendeley we sometimes had occasions where the engineering team were despairing at some of the internal issues they had to deal with, while at the same time our users were ecstatic with what we were doing. There was a gap there. The story that gets built up internally about a product can often be very different from the story that the end user has created about that product. Reconciling these world views is only ever a good thing.  

- Keep track of user pain  
 A really great way to negotiate around what debt or bugs you deal with is to track [user pain](http://www.lostgarden.com/2008/05/improving-bug-triage-with-user-pain.html). It can be a good idea to roll developer pain into this too. Having a sense of what is the most painful aspect of the product, and continuously working to remove that gives you licence to negotiate leaving some of the less painful issues in place while you tackle the more painful ones. When we adopted this process at Mendeley it led to a significant increase in the overall quality of the product. We were able to focus piece by piece on the most important areas, rather than rushing to put out fires all over the place.  

- The human is harder than the technical   
  Every time that I have worked on a multi-company product or project, the overhead of communication and negotiation has always been much larger than any of the technical aspects. Be prepared, and bring your best patience pills with you. 

- Test with users   
  I've been guilty of shipping features without testing them, and I've been guilty of having grand plans and ideas that in the end didn't make any different to product adoption. The worst case was when working on Nature Network. We went away and created a business case around where we thought scientists might want to use in a product, then we locked ourselves in a room for several months writing detailed specs, and wireframes, and we launched after only doing some focus groups. No iterations were tested with real users, the product was a turkey, and was killed a few years later. 

- don’t use InnoDB for heavy read write apps  
  On Connotea we had a write heavy and read heavy app. The DB became a huge bottleneck, and the app slowly withered without the internal expertise or will to re-engineer it. This was not the only reason for the ultimate failure of that app, but it didn't help. 

- don’t over normalise your database, think about application views rather than pure data modelling   
  Again, with Connotea the DB was perfectly normalised, but that lead to excessively large queries when generating some of the most popular pages on the site. The data structure, when thinking about it as pure data, was perfect, but it didn't match the daily use of the system. Start with the user, and work backwards, not forwards from the data. 

- a product is not enough, it needs a supporting business model   
 This was the real reason Connotea failed (in my opinion), and I hold my hand up in a big way on this. We had great adoption, a great product, and were early to market, but I was unable to make the case on how we could get to sustainability with Connotea, and so it never got the support that it needed. That was mainly due to my inexperience, and it remains a huge lesson to me through to today. 

- a business model is not enough, it has to scale    
	We had a business model at Mendeley, and it was starting to get to scale, however there was certainly a lot of discussion around which approach to take, to seek continual individual conversions to a paid version vs going after the institutional or SAAS model. These two different business areas would require potentially different feature sets. We took on the task of pushing the product forward on all areas, we could potentially have made more progress with more focus. What business model will work is never a given, but if you have the opportunity to learn early then that can be a great boon to deciding product direction.  

- don’t leave your biggest opportunity on the table      
  With Nature Network the obvious product feature would have been to create a profile for every Nature author. Boom, you suddenly have the most influential online profile representation of science. This was too difficult to achieve at the time that we created Nature Network due to political and technical challenges, and we didn't do it, but it still craws at me that we left that on the table.  

- don’t be afraid to work outside your comfort zone
	When we launched eLife we worked with a design agency with no previous background in working in the STM sector. They had a lot of experience on commerical web sites. We ended up with a site design and interaction elements that have been widely copied, and highly praised.   

- even with API’s - think of users over the technology stack    
	At eLife when we launched we launched with an API built on top of fluid info, because I saw great potential in the technology, however the API interface was cumbersome, and the service response fairly slow. We didn't even built on top of it ourselves for internal purposes. We have dropped it, and are starting again, but building out from the service calls we need, as we need them. This was not the first time that I fell into this kind of trap, I had been an early advocate of google wave, an example of a great technology in search of a user problem. Start the other way, with the problems you want to solve for your customers, and bring the technology to those problems. I often suspect that the semantic web is a solution in search of a problem.  
	
- when you find really talented people, figure out how to get out of their way  
	Also give them the space and freedom to do amazing things. eLife Lens is the result of such an approach, and remains one of the best products that I've been involved in, even though my involvement mainly consisted of getting out of the way.  
