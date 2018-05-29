---
layout: single
title:  "Gatekeepers and their Role in Healthy Software Development"
date:   2018-05-29
---

*This is an x-post from Sokrati's engineering blog which can be found here: https://sokrati.com/engineering/*

What is a gatekeeper: A gatekeeper is a person who controls access to something […] individuals who decide whether a given message will be distributed by a mass medium.

The act of gatekeeping, in context of software development, is similar to the generic definition above – someone who acts as both a filter for feature requests and defines the future road-map for the project. This role is hugely important and can have a very real impact on the success or failure of any endeavour. Gatekeepers in modern software development can take multiple forms; senior SDEs, Tech Leads, Product Managers, CTOs are all gatekeepers at some level and need not necessarily have been the original developers of the project.

![Gandalf](/assets/images//output_crmkm6-1.gif)

A gatekeeper’s responsibilities would typically revolve around the following:

* Be the PoC for all Feature Requests
* Prioritization of said requests
* Stakeholder for every version of the product being planned – part of every design discussion

Typically, teams at Sokrati have 5-7 members including a Tech Lead plus a Product Manager attached to their function.

## The various levels at which gatekeepers can be present broadly fit in to these categories:

**Company Level –**
Typically a CTO/Engineering Head, defines the yearly road-map, quarterly sanity checks and oversees new requirements/pivots if needed – this is gatekeeping at the highest level.

**Team Level -**
Your Tech Leads and Product Managers, usually some combination of both to ensure all fronts are covered from both a business and tech perspective.

**Project Level -**
Less common, you can define module owners at this level, scope is mostly internal with respect to technologies to be used, coding patterns, etc.

Having a gatekeeper ensures you have someone with a clear understanding of what the piece of software is and what it is going to evolve into. Too often there is a tendency to add needless features to an existing product until it no longer holds a clear purpose anymore but is just a mash-up of a broadly related set of functionalities. It also allows for much more definitive clarity on whether the feature being requested is actually going to solve a business use case or is just the by-product of a larger problem that has snowballed due to a knee-jerk-like rush to react to every perceived lack of functionality with a new release.

That being said, a lot of care should be taken to ensure that a gatekeeper never devolves into a myopic dungeon master. In no way is a gatekeeper’s word final. The ‘role’ is an advisory one, one that promotes discussions that would otherwise fall by the wayside in a hectic environment where number of commits per day is often touted as a badge of honor. Another major gotcha is becoming so reliant on your gatekeeper that he/she becomes a Single Point of Failure (SPoF) – a gatekeeper is not a barrier but a funnel, channelling the product in the general direction you’ve chosen.
