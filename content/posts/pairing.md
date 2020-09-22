---
title: "To pair or not to pair?"
date: 2018-04-06T14:37:57+01:00
draft: true
---

> Note to the reader: This was written in April 2018.

I have pair programmed on a daily basis for over two and a half years now, a year and a half of that being in the [IBM Cloud Garage](https://www.ibm.com/cloud/garage/).

In this blog I would like to discuss some of the successes and failures of pair programming as part of an approach to software development, and the insights the approach has left me with.

### Common Arguments Against Pairing

To the uninitiated, pairing may seem a daunting prospect. I’ll go through some common lines of resistance:

> “You mean I have to ***talk to people!?*** This isn’t what I signed up for…”

A very common assumption to make is that everyone who works in software is an introvert. Introverts generally find social situations draining, and require their own space to recuperate. Thus, as long as software is seen of as a solitary activity, introverts will be drawn to it.

However, my answer to this would be to just give it a fair chance. I see myself as an introvert with extrovert tendencies, and I found pairing hugely draining for the first few months that I tried it.

But the results we delivered were more aligned with the team goals, and the experience that I gained from more senior developers was *far* more extensive than I could’ve hoped to teach myself in the same time.

In short :- It can be an easy way to become a better developer.

And if you’re not doing the learning, you are likely explaining or teaching your own learnings to others, which is…? Another key skill!

> “We’ll spend the ***whole time discussing approaches*** without doing anything…”

This depends somewhat on the nature of the task. Assuming that the task is well understood, provides a small yet tangible increment in value, and is sized appropriately… in practice, I found that this one doesn’t really occur more than once, unless you really do work with some very uncompromising developers.

Likely you will have some experience where no code is written because you are busy “discussing”, I don’t know, which direction the mouse wheel should move the page, or if the code should have tabs or spaces in it. If you’re lucky it will actually be something related to your code.

But the outcome of these sort of discussions is fairly arbitrary. OK, we can use tabs. OK, we can put our code in this file.

Often the time that it takes to start one approach, realise it is wrong, and try the other approach, is going to be less than the time it takes to explain it.

Using this insight, personally I even prefer to let a partner try an idea that I hadn’t thought of myself, as it either teaches me something new, or decisively wins any debate over approach that we may have been drawing out.

> “I have to continuously work with someone? Well played, you’ve just ***halved the team’s speed***...”

I sympathise. From a project management perspective it makes total sense. We now have half as many active work items, the project is going to take twice as long. And therefore at twice the cost. However in practice it doesn’t really work like that.

Instead, what starts to occur is an increase in focus and concentration levels. It’s a lot harder to slack off onto Facebook whenever you feel like if you are sitting working with someone.

And while on balance the speed of delivery may go down slightly if you have two mid to senior level devs pairing, a pair will likely produce a better quality piece of work, which fits the project goals more tightly, and doesn’t go off on a tangent into “saving the world” at the same time.

> “I know how to do this, you don’t have success in mind, ***you’re holding me back***…”

This one typically comes from senior developers who believe they are incentivised on their own speed of delivery, not on the efficiency or enablement of the team they are working within.

While both are important, great software generally comes from efficient teams, not efficient individuals.

And when the seniors can skill up the juniors, the organisation becomes healthier and more efficient. Pairing can be a great way to teach new developers the ropes.

Plus when working solo, you are going to be more susceptible to scope creep than if someone is “holding you back”, or keeping you along the straight and narrow path of the task you are working on.

> I ***hate*** the way Jim writes code, whenever I see his code I refactor it. I cannot work with him.

Everyone has a slightly different coding style. Because everyone thinks in a slightly different way. But through pairing, the style of the code is actually made more consistent, as the niggles you may have about your fellow developers are ironed out through discussions, which would hopefully aid both of your understandings.

### Project Management and Pairing

From a project management perspective, pairing can help out or simplify in many ways.

* Skills handover? Pairing.
* Instilling the team culture? Pairing.
* Teaching the repository management strategy to a newbie? Pairing.
* Co-ordination of the team? With half as many working on a problem as before, your life becomes a bit easier.
* Code reviews? Well, pairing is a constant code review. Less important.
* Silos of information, which may be lost when a team member moves on? 
Well, pairing can help you mitigate this, because if you are pairing consistently, you have more eyeballs on the code, and the code lives on in the memories of more of your developers.

### Pairing and Personal Development

From a personal perspective, pairing could help you to:

* Articulate your ideas more clearly
* Improve your code quality
* Know your colleagues better
* Have more fun
* Overcome your ego

In a good pair, the reassurance of having someone to “catch” you when you are going wrong could even help you to think more creatively.

### When not to Pair

In some offices, pairing can become a practice to follow at all costs, to the extent where it is not useful or productive.

Here, in my opinion, are some of the cases where pairing could be harmful:

* Novice to novice pairing. When neither of you have much idea of the problem space, constant questioning, or constantly fielding questions, can interrupt learning.
* “Spiking” — e.g. some exploratory work which will not result in production grade code. This is not necessarily useful to pair on, as having to justify choices for your actions is difficult when you yourself are exploring.
* Reading/understanding documentation, as everyone does this at their own pace.
* Jenkins/Travis/other similar DevOps tasks. These are typically dull to pair on, as they aren’t very technically challenging, and typically have long turnaround times between attempts to get it right.
* Creation of supporting materials for your project (diagrams, schematics).

### Valid Criticisms of Pairing

If you are, for whatever reason, demotivated, that can demotivate your partner. A demotivated pair is at least twice as bad as demotivated soloist. Which moves me into taking breaks.

Working alone in software, the norm is to take a break whenever you like. But when you’re pairing, your breaks need to be co-ordinated, or you end up taking twice the time off. The better you know your pair, the better you are at choosing your breaks. And ideally, you will be able to spot when your pair needs a break, and politely suggest it, even before they might’ve done.

However, if you’re remote, these subtleties become a lot harder. You can’t easily assess the wellbeing of your pair through video link. In my personal experience, remote pairing means working harder and longer than you otherwise would, with all of the niggling annoyances that video linking brings.

That being said, there are some excellent remote desktop applications which can really help to bring remote pairing to life. If you’re on Slack, try out [Screenhero](https://screenhero.com/), or if not, try [zoom.us](https://zoom.us/). Or, if you both use visual studio code, [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare).

But if you’re not careful, the “perfect storm” of all of the points above can create an awful pairing experience. A bit of confidence and a can do attitude will go a long way to negate these problems.

## Conclusions

After having worked with a pair for so long, it feels strange now to not be pairing. How would I know if I am erring on the side of over-engineering? Or if there is a way of doing something five times quicker than I am doing it?

Now that I lead teams more frequently, it has come to the point where having people soloing in the team is uncomfortable, and pairing seems like an easy way to avoid having to achieve a degree of rigour (or at least shared understanding) over what you produce.

Sometimes it can come down to *just trying pairing*. I don’t mean for an afternoon as a one-off. I mean for a sprint, or a project, or as a team. Be open with it, discuss with your colleagues what is difficult and what is easy. Make changes if needs be.

Because if you end up in a team which can successfully pair, that team is more aligned, both with each-other and with the health of the project. Ultimately, a well aligned team means a lower project risk.