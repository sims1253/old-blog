---
layout: post
title: "GSoC 2017 Postmortem Part 2: Org Application"
categories: coala
tags: ["gsoc"]
image:
  feature:
  teaser:
  credit:
  creditlink:
---

In the beginning, there was an organization application.
And with it, the need for someone responsible.
That one was me.
I always wanted to help with GSoC but felt that my coding skills and
codebase understanding were not good enough to be a mentor as good as
I'd like to be.
So I followed the call for main admin and on the story went.

Google Application Form
-----------------------
The most obvious piece of the application process is the application
form every organization has to fill on the GSoC page.
The problems I encountered while drafting the first version of our org
profile and "Ten Reasons Why You Should Take coala"-text were
essentially the same as for every application I had ever written.
How does one sell themselves without making things up.

Although coala had two years of GSoC experience, those were as a sub
org under the PSF umbrella.
This year should be the first under our own flag, so everything had to
be perfect.
Again and again I asked for feedback on my drafts and input on things
where I didn't know enough about. Both Lasse and John were very helpful,
both with plenty more GSoC experience than I have.
We felt that we were in a pretty good position.
Our community has a strong connection with the GSoC program, many of our
long time members were students once upon a time.
We had a total of 10 students over the two years with PSF, and from
what I have heard, they were more than pleased with our performance as
an organization, both the students and the PSF.
The only thing that we felt went against us was us being a novice
independent org, and us not having failed any of our students so far.
Yup, this is a thing.
From what I understood, Google expects around 20% failure rate across
all organizations.
If an org deviates from that too much for too long, then they are either
too strict with their students, not strict enough, or there is another
problem with their process.
We actually were quite worried about this point but from what I have
learned, there is no real reason to worry about this.
Document what you and your students are doing and as long as you have
good reasons for the decisions you are making, everything should be
fine in the end.
About the novice part, there wasn't really anything we could do besides
pointing to our past GSoC experience and hoping that Terry Oda, a PSF
GSoC admin, would vouch for us.

Projects Page
-------------

Another, big, part of the application is the projects page.
It is a list of project ideas that students can apply for.
Although it is encouraged that students come up with their own project,
most applications will come from the project list.
And a nice project list is a must have, from what we were told, to get
into GSoC.
We felt that the project page should be the most well fleshed out part
of our application, as it is actually useful during the following parts
of the program and offers a lot of value to the students and us when
the student application phase comes around.
This lead to our web frontend hero Hemang building our new and awesome
[Project Page](projects.coala.io).
Before this, we just used a GitHub wiki page with some project drafts
but the new page was much easier to use, gave a better overview about
the projects and it gives us the possibility to add features to it in
the future.
During this early phase, we included the old projects from the wiki and
asked mentors and community members for other projects ideas they might
be interested in mentoring.
For those who haven't read any of the project ideas on our page, the
structure always is something like this:
Introduction and motivation, sometimes followed by some additional
information about how to solve the problem if we already had some idea
about it.
Then we show a time line following the GSoC 4 phase model, that holds
some milestones and gives a rough idea about when to deliver the single
parts.
Finally, we link all additional information we have about the project,
like issues or cEPs, add mentors as contact persons, and some more meta
information.
In addition to the project ideas the page also holds a faq section,
where we started to collect questions we received again and again or
just felt were important.
We had close to twenty project idea drafts at this point and felt that
we were more than ready to hand everything in to Google and be accepted.
Before we move on to the next part, I want to point out that we also
built the projects page so other orgs could use it and we have received
some good feedback on it.

FOSSDEM and Feedback from Stephanie
-----------------------------------

In February, a few weeks before the application deadline, we went to
FOSSDEM with coala.
We had a stand where we promoted what we did but most important, our
stand was right next to the GSoC stand.
A great opportunity to get feedback and ask some questions we figured,
and so I walked over in a calmer minute to show Stephanie what we had
so far.
Starting with the projects page, she liked it a lot.
She liked the idea of it and how it was structured and could help to
introduce students even easier.
The only improvement she asked for with it were the project
descriptions.
Flesh out the motivation for most projects and just write a little more
to make it easier for students was what I took away for the projects
age.
But overall this part gave me a very good feeling!

Then we talked about our chances to get into the program with the
experience we had under our belt and our expectations and wishes for
slots we would get.
As I said before, we had 10 students over the last two seasons.
First 2, then 8.
We felt, that we could probably grow some more with the mentor power we
had amassed but also didn't expect too much as we had some challenges
coming up, that we didn't have the last two times.
What I asked was probably something along the lines of "how high are
our chances to get around 12 students this year with what I just showed
you + improvements I'll implement?".
And here is where the not-so-fun part started.
She essentially looked at me as if I asked for a million dollars out of
nowhere.
Turns out, that first time organizations usually get 1 or 2 students.
And even with our past experience as a sub org, we kind of counted as
a first time org.
I pointed out that we had 8 students under PSF last year and received
great feedback from their admins for our work and Stephanie couldn't
believe that we did get such an enormous number of students as such a
young org.
I came out of that part of our conversation with the feeling that we'd
probably not get more than 4 slots no matter what we did.
Not a great takeaway.

### Implementing Feedback
I rewrote a lot of our application texts to focus more on the things
Stephany pointed out as important factors after we returned but the
main part of work I did was essentially rewriting all twenty something
project proposals we had.
Although I wrote some of them myself, most of them were actually written
by students or mentors and I did all the review work.
The reason or this was that even though I probably would have been
faster just writing everything myself, I wouldn't be able to get enough
reviews to merge everything in time.
So the solution was to poke students that were interested in the
projects and mentors to rewrite it and me reviewing it.

During this time I also struggled with the expected slots we would get.
While yes, we would finally be our own organization, with all the pros
that would bring with it long term, it also felt like a step backwards
to loose students slots compared to last year.
But the fact that we couldn't grow further under the PSF and had plans
to act as an umbrella for smaller linter projects made the investment
in our long term growth worth it in our eyes.
I should probably add that we had more than 5 newcomers per week during
this time that were interested in GSoC with us.
This meant that the newcomers from one week might be more than we would
get.
And there were quite some students that came to us end of last year and
had contributed a lot.
Hard time deciding whom to take on the horizon already.

After completing the projects rewrite we called it done and handed
everything in for the final time.
Now all that was left was to wait and get to know the possible students.

Result Day, Slots and Thoughts
------------------------------
We were accepted.
And although it doesn't quite fit here chronologically, we received 10
slots.
We were happy when we were accepted and a huge weight left my shoulders.
But the real joy came when we received those 10 slots.
Apparently Terry gave us one hell of a recommendation and all the
mentors we had collected and project ideas we had prepared were worth
something after all.

So what do I think about how everything went down?
I feel like the projects page was a great idea and will serve us (and
maybe other orgs) well in the future.
There are some downsides to it in my opinion that I will cover in the
next part more in depth but the main thing is that all those super
defined projects left the students with nothing to think about in some
cases.
In the future, we will focus more on presenting the problem and why we'd
like to fix it and less about the how to fix it in detail.
This way we give students a chance to shine during their application
phase by working on the specifics with the respective mentors and take
some of the work off of us.

About the meeting with Stephanie at FOSSDEM, I would recommend that to
everyone!
Stephanie is a lovely person and helped us a lot with her feedback I
feel.
She is also just a nice human to talk to.

Overall I feel like this part of GSoC went pretty well and without real
problems beside our panic of getting too few slots.
Things won't stay this rosy in the next phase sadly so if you want some
drama and more interesting "things we could have done better" things,
make sure to come back.
I'm not sure when I will find the time to finish the next part as
I have some university to catch up on and it takes me a good 2 hours to
 write one of these, at least so far, but I'll try to keep at least a
weekly schedule for this series until I am done.

Thanks again to Terry Oda from the PSF and Stephanie Taylor from Google
for your support during this phase that definitely helped us to get
into GSoC and learn a lot as an org.
