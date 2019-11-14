# Data Science Take-Home Guide

This is a guide for preparing to do, and succeed at data science take-homes. It is intended 
as a non-technical guide.

## What are take-homes

If you're invited to do a take-home, you should be excited, they might be the most fun part of the whole data science interview process.
take-homes are--as you may have guessed from the name--a lengthy mini-project that a company asks you to do as part of their hiring
process, usually after a couple of less rigorous phone calls, but before an on-site meeting. In addition to being a great way for the 
company to learn about you, they're also probably the closest you'll get to experiencing that actual work at the company before you are 
hired, so they can be a useful way to assess for yourself whether the company is one you'd like to work for.

So what makes take-homes fun? Perhaps it's subjective, but because they're open-ended, take-homes are an opportunity for you to demonstrate
what you're best at, and to do so in a way that's much more creative than the usual high-stakes Q&A format of other parts of the interview process.

So what might you encounter in a take-home?

 * Data, usually! Often companies will provide you with some example data and ask you to show what you can do with it.
 * Time limits. Sometimes companies may ask you to limit the time you spend on a particular project.
 * Presentations. Companies will often ask you to create a presentation of your results, though they may alternatively ask you to build an API or create some other deliverable.
 * Ambiguity. Depending on how you react to no-right-answers ambiguous scenarios you may love or hate this, but you can bet if you do enough, you'll encounter 
  some take-homes that are ambiguous (maybe even deliberately so).

## What do take-homes measure?

One common pitfall that beginners to the world of take-homes fall into is thinking that the take-home is meant to measure _technical ability only_. This is definitely not the case!
Here's a list of other things that will be apparent from your take-home results, and that are at least as important as the technical wizardry on display in your solution:

 * Presentation skills
 * Time-management and ability to prioritize
 * Business thinking
 * Domain expertise (or, failing that, interest)
 * Ability to operate under ambiguity
 * Whether you utilize best-practices in doing work

## A framework for take-home success.

When viewed alongside all of these other things, hopefully it becomes clear that demonstrating technical mastery is just one tiny piece of the puzzle, and that doing that
without doing any of the other things is a sure path to rejections. So what should you do when somebody sends you a big scary take home with an impossibly short deadline? 
Here's a possible framework for thinking about such challenges:

### Use a workflow

CRISP-DM is a great uncontroversial workflow to hold yourself to so you don't get lost or forget a critical step. 

![](images/800px-CRISP-DM_Process_Diagram.png)

Start with *Business Understanding* and move to the subsequent steps, iterating back and forth often. The goal is to make many cycles through the entire process,
not to make a single perfect cycle through, think of starting simple and small and then building on that foundation.

### Plan your approach

Oftentimes the deadlines given to you will be on the honor-system, meaning you'll face the ethical dilemma of whether to spend more time than allowed, or whether to ignore that
guidance in order to make yourself comparable to the other people (who may well have taken more time than allotted). One way to have your cake and eat it too is to take a peek at
the questions and allow yourself to plan an approach without actually writing any code. You might even sleep on it to make sure your idea feels good in the morning; surely they
can't count sleeping against you--even if you do wake up with some brilliant ideas.

When planning, note any particular deliverables, so you don't fail to deliver on some objective. Then think of the simplest possible approach to those deliverables. In some cases, 
this may be quite naive, but naive may be ok as long as it's not both naive and a dead end.

Relative to CRISP-DM you might be able to do most of your first attempt at *business understanding* during this planning, you may even seek out outside resources to augment your current
understanding. 

**Don't** use this time to create an elaborate plan that you may not be able to finish in the allotted time. Use it instead to plan a sequence of increasingly ambitious things you might try, 
but any of which could be delivered.

### Plan your time

It may sound pedantic to suggest that you should set a timer for each phase of the take home, but it's not a bad idea! We've all had the experience of getting lost in the data and looking up 
hours later wondering what it was we started out to do. To avoid this you should stick to your original plan if possible. If you find it necessary to deviate from that plan, try to revise your
plan rather than scrapping it and going rogue. One plan may not work out, but that doesn't mean you should scrap the entire notion of a plan!

Think about the objectives you're trying to achieve, and then map out exactly how much of your allotted time you will devote to each of them. Revisit the list of "what do take-homes measure" 
and make sure that the tasks you're devoting time to will allow you to demonstrate all of those things!

Here's an example map for a 3 hour project:

- 30 mins: EDA, confirming feasibility of plan, modifying plan if necessary
- 60 mins: building model, grid-searching, feature engineering
- 30 mins: evaluating model interpreting results
- 60 mins: make presentation

You may not choose to use exactly the same breakdown, and every project may require different emphasis, but try to be realistic about how long it takes to do a good job of something. 
Always plan for something other than the best-case scenario; if it takes five minutes at best, it takes 30 minutes when you get a few realistic bugs. If you're lucky and 
the best-case 
comes to pass, think of the next most important thing in your plan and try to add that!

The last point is to guard your time! Try to be aware of how closely any task conforms to your plan and be prepared to abandon the task if it risks wrecking the whole thing. Some bugs just don't have ready solutions, so be prepared to cut and run because you're not progressing through your plan on schedule. Ultimately, abandoning a single point in your plan is better than missing everything else because you got hung up.

### Choose your best methods

Take-home presentations almost always result in some questions from your potential colleagues, so be strategic in using methods that you would be happy to talk further about. If you do the
most complex thing you barely know how to pull off, your answers to those questions aren't likely to be very satisfactory, so choose methods you're comfortable with and would be happy
to spend a few hours talking about. If that means you use a decision tree instead of a random forest, a linear model instead of neural net, or a frequentist hypothesis test instead of 
new Bayesian hotness, that's fine, as long as you're able to really confidently defend the choices you made!
That doesn't mean you can't mention you've got big plans for future developments that you think are promising but need to explore futher, and feel free to do so in a way that makes clear it's
something you haven't done yet but would like to explore futher.

### Practice your presentation

If you're giving a presentation, you should practice! With a live audience preferably, or in front of the mirror, or your phone, or a cat otherwise. Ask people if they understood it, or if they have advice. Even if you can't get a technical audience, you'll get great feedback from non-technical people on every other aspect of your well-rounded presentation. If you can find technical people
have them ask you questions, or ask them what they might expect to come up, who knows if it will, but it can't hurt to prepare a good answer.

Another part of this exercise is to know the weak spots of your presentation. There are bound to be some: you're probably new to the domain, have worked on your solution under duress and maybe some of your plans just didn't pan out. These are probably not fatal flaws, but these might be areas where you want be extra-prepared for some questions. Think of this preparation as being extra-able to describe what your thinking in this area was, not prepared to defend your result to the death. If you try to defend the weakest part of your presentation endlessly, you're likely to look delusional, but if you are able to acknowledge the weakness and mention that you know exactly what went wrong and what you might do to correct it, you won't look delusional, just unlucky! If you've turned around your take-home under time-constraints, you've got a perfectly good reason to be showing a presentation with a few warts. "That's something I'd have improved with more time" is a pretty good excuse under those circumstances especially when backed up by a good plan for improvement.

### Show your good work

Your future colleagues are definitely not interested in seeing **all** of your work. If you generated 500 charts during your project, do not show them all. If you do, your future colleagues might get the idea that you are the kind of person likely to turn up at their desk unannounced with 500 charts for them to look at, and they almost certainly have better things to do. Instead, be selective in showing the work that best shows what you did. In particular, does it concisely exemplify any of the bullet points above? In particular, don't try to overwhelm them with the volume of things
you produced, instead, think about whether you have a great reason for including every piece of your presentation.

Outside of your presentation you may be asked to share your code as well, so this is an opportunity to demonstrate that you've followed good work habits. Did you write a messy notebook whose cells are executed out of order, or did you write a script file with a `__main__` block that anyone can run to duplicate you work? Did you write comments in your code? Did you remove dead code, or commented out sections? Once you're on the job, you'll know the special pain of finding out that somebody else's work is in a labrynthine notebook, or whose code is chock full of commented out exceptions. Your future colleagues know this pain already, and they're not looking for any more, so don't give them reason to believe you'll contribute to it. Of course, writing good clean, DRY code takes time, so plan accordingly! It may mean you make less progress, but your progress will be much more ausipicious and clear to your reviewers.

If you did some research on the domain outside the parameters of the take home, be sure to mention this! You may not spend a lot of time on it, but demonstrating your enthusiasm for the subject, and your willingness to go deeper will send a positive signal about your likely success in the role.

Finally, don't let the nerves of presenting a big piece of work detract from your personality. Demonstrating that you're competent is great, but demonstrating that you're competent and pleasant is better still, so make sure that you let that show too. You might introduce yourself at the beginning of the presentation, and this might be a good opportunity to inject some personality into the presentation so your observers know that you're a dynamic colleague and human!


