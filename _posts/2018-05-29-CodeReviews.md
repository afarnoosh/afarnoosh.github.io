---
layout: single
title:  "Code Reviews in an Agile, Fast-Paced Environment"
comments: true
date:   2018-05-29
---
*This is an x-post from Sokrati's engineering blog which can be found here: https://sokrati.com/engineering/*

Code Reviews are a tricky minefield to navigate. Many developers (especially those fresh out of college) seem to have an inherent fear of both reviewing and being reviewed.

Common concerns I’ve heard revolve around either seeming too aggressive and offending the other person(s) with a deluge of review comments or a twist on that all consuming plague that affects so many in our profession – the Impostor Syndrome.

Both reactions are instinctive and IMO, tightly coupled to each other. Both reactions stem from an unhealthy sense of ownership – an almost paternal need to protect both your reputation and your body of work – and are a side effect of being unprepared to deal with the stresses of working in a high pressure environment.

![XKCD](/assets/images/good_code.png)

Consider this, if you may; a developer working in team A has been assigned a task X. He starts work on X and is beset – quite common in most developers’ days – by a myriad of interruptions, setbacks in the form of other smaller tasks that need his attention. This contributes to a delay and the original deadline is almost impossible to meet by this point in time. So, what does this developer do? He cuts a couple of corners, skips a few edge test cases, strives to meet the important deadline all the while smothering his programming conscience that is feverishly eating away at whatever remains of his peace of mind. He ends up being defiantly proud of the fact that he was able to deliver despite all the interruptions to his work.

At that point in time, two things have happened:

* The developer is already on the defensive, a siege mentality has built up as every little interruption adds to his subconcious stress of a looming deadline and seems like an attack on his ability to deliver the project on time

* The piece of code is obviously not in the best shape; what’s more, the developer knows this before he sends out the review which puts him on alert and adds to his defensiveness

So, the situation is now tightly strung, all it needs is a spark to bring the whole house tumbling down.

Go through this cycle a few times and you will invariably start feeling burned out. You’ll start dreading the mention of a review even if you’ve had all the coding time in the world in a relatively stress free environment. You do your best to not cause waves in the hope that the same dubious courtesy is extended to you.

This is a toxic cycle that has no winners. To guard against falling into such a pattern, I’d recommend incorporating the following into your review regimen:

* Always communicate delays. Do not agree to ship rushed code to production, just don’t do it. Karma is scarily real in the programming world and it will come back to kick your ass at some point in time.

* Force yourself to look forward to a code review. Treat it as a milestone similar to firing a commit. Indulge in a (silent!) mini hooray. Rewire your brain!

* If you struggle with treating comments as constructive criticism, this is the point at which you consciously distance yourself and attempt to address all comments from a 3rd person’s view.

* When you’re the one doing the reviewing, do not treat it as a witch hunt. You’re not going to have your promotion delayed if you don’t find an issue with the code.

* On the other hand, if you do find issues that need to be addressed, your attitude should be one of helpfulness rather than glee. Be constructive and firm; if you truly believe a part of the code can be refactored to make it more efficient for instance, state your points concisely. There is no need to bash the other person. Once you’ve made this a habit, the compulsion to find something to criticise will no longer factor in.

![XKCD2](/assets/images/code_quality.png)

Keep reminding yourself, the point of a code review is never a competition to find a maximum number of bugs just like cutting corners to meet a deadline defeats the whole purpose of having a timeline.

Here at Sokrati, we’ve seen code reviews having a deep and lasting impact on quality of code shipped. It acts as an excellent tool for mentoring of new hires, for setting a clear coding standard that helps keep our code base clean and consistent and as a bonus, it even helps promote re-usability of existing modules that developers may not have been aware of!
