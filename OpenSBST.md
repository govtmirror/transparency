---
title:  'How we should work?: A DRAFT aspirational standard operating procedure for behavioral insights teams working within governments.'
author:
- name: Jake Bowers
  affiliation: University of Illinois at Urbana-Champaign and White House Social and Behavioral Sciences Team
...


# Why this document?

Governments are hiring social and behavioral scientists under the idea that such people will improve the operation of government. For example, on in September of 2015 President Barak Obama referred to the work of the new White House Social and Behavioral Sciences team when he issued Executive Order 13707 "Using Behavioral Insights To Better Serve the American People" saying:

> A growing body of evidence demonstrates that behavioral science insights --- research findings from fields such as behavioral economics and psychology about how people make decisions and act on them --- can be used to design government policies to better serve the American people.

>Where Federal policies have been designed to reflect behavioral science insights, they have substantially improved outcomes for the individuals, families, communities, and businesses those policies serve. For example, automatic enrollment and automatic escalation in retirement savings plans have made it easier to save for the future, and have helped Americans accumulate billions of dollars in additional retirement savings. Similarly, streamlining the application process for Federal financial aid has made college more financially accessible for millions of students.

How should scientists working to improve government act? We have a good sense for how scientists should act in general. In general, science helps us solve problems and answer questions via a kind of impersonal and asynchronous collaboration: the idea is that each individual scientist is pretty ignorant, but that groups of scientists, working across time, space, language, and technique, will gradually improve what we know. This idea, that no single person ought to have authority can be seen in Richard Feynman's 1955 address to the National Academy of Arts and Sciences:

> "I would now like to turn to a third value that science has. It is a little less direct, but not much. The scientist has a lot of experience with ignorance and doubt and uncertainty, and this experience is of very great importance, I think. We have found it of paramount importance that in order to progress we must recognize our ignorance and leave room for doubt. Scientific knowledge is a body of statements of varying degrees of certainty --- some most unsure, some nearly sure, but none absolutely certain.

> Now, we scientists are used to this, and we take it for granted that it is perfectly consistent to be unsure, that it is possible to live and not know. But I don’t know whether everyone realizes this is true. Our freedom to doubt was born out of a struggle against authority in the early days of science. It was a very deep and strong struggle: permit us to question --- to doubt --- to not be sure. I think that it is important that we do not forget this struggle and thus perhaps lose what we have gained. Herein lies a responsibility to society. (Feynman 1955, page 4--5)

We also see this idea in the very recent discussions about open science, for example the idea that scientific claims should be available to be evaluated broadly and with minimal barriers:

> "Trust is not a scientific value.  Transparency is a replacement for trust.  The irrelevance of trust is facilitated by having no central authority for truth, and by making evidence and its source available publicly.  In principle, anyone can evaluate the basis of claims, and reproduce the procedures in order to verify the claims." (Center for Open Science: Strategic Plan, page 5)

So, as social and behavioral scientists, we should be 



# Mission

We aim to improve the way that government serves the people (including the
people of the government) by using insights and methods from the behavioral and
social sciences.

We hope to work as a force for good directly by working with agency partners to
propose policy changes and assessing whether those changes did, in fact, change
the world for the better.  We also hope to develop the ability and desire to
use theory, findings, and method from behavioral and social sciences among
people who have pursued civil service as a profession instead of the behavioral
and social sciences. That is, we have a mission to build capacity even as we
have a mission to design and evaluate policy changes ourselves. In fact, we,
ourselves, have no authority to implement changes in the ways in which agencies
serve the public, nor do we have authority to collect data on the outcomes of
these changes. It is only working together with agencies that we can do our
job: so, building capacity is as central a concern as reporting on how the
behavioral and social sciences improved the lives of Americans.

Our mission requires that we work in ways that engender trust: we have to trust
in ourselves and the literatures on which we build enough to make proposals for
policy changes and research designs to assess our ideas, our agency partners
must trust that we will help them (even if we discover no effects, even if no
past scientific literature provides guidance), the people served by the agency
must trust us (directly or indirectly through the agency) to make their lives
better.

Trust in ourselves requires that we work in a collaborative yet asynchronous
fashion: we have to be able to collaborate with our future selves as well as
with others. Trust in us from agency partners and their populations requires
openness about what we do and why we do it.

These basic requirements for our work lead to a series of operational
commitments or prioritized ways of working.

## The Ways and Virtues

### Work in the open

Working in the open can mean typing memoranda or research designs or data analysis code in public GitHub repositories using plain text.^[GitHub itself is not 100% open source, but it is free for public repositories and so far, is the best tool for working in the open that we've seen.] It might also mean publishing our work in open access scientific journals where citizens outside of academia can learn about our work.

Wherever possible we should work in the open. Agency partners, the people they serve, and others around the world, should be able to see our process. What are the virtues of this way of work?

### Virtue 1: Enable Citizen Science to increase quality quickly and build trust.

We want to enable citizen science because we have seen how openness
improves quality quickly within open source projects (cite) and because we
believe that citizens involved in citizen science come to see government
as a force for good (even if an often frustrating and slow force for
good). Citizens have paid us to do this work by making the work accessible to the public we are showing came of their investment.

### Virtue 2: Open work speeds learning (by others from us and us from others)

We want to increase the ability of people in government agencies to use
insights and methods from the behavioral and social sciences to improve their
policy outcomes. Openness enables others to learn from us: if we make our
memos, reports, research designs and code public, then others can more easily follow
our example (and, as we noted above, if we use the right tools and nurture the
right norms, then others can more easily improve our examples).

### Reduce barriers to learning

Because of our mission to expand the ability of others to do what we do,
we want to avoid barriers to adoption of our ways or working (or
barriers to our ability to learn from constructive criticism). This means
we use open-source, free, multiplatform tools and services whenever
possible.

### Empower Partner Agencies to work in the open.

We do not tend to own the data that emerges from our collaborations with
agencies. So, although we can commit to making our own work open, we
cannot commit on their behalf. That said, we can make it as easy as
possible for them to be maximally open and reap the benefits of
openness. If possible, and ethical, we will share data, including de-identified interviews and user experience research to enable others to go beyond our analyeses. Right now, sharing data with agencies is difficult --- such that our standard practice might involve sending code for them to run on their own machines, or sending a virtual machine image for them to use on their own machines (or even lending a laptop). With other agencies data sharing is easier and we might be able to share simulated versions of the original data (i.e. try to follow best practices in differential privacy as results accumulate)^[<https://en.wikipedia.org/wiki/Differential_privacy>,  <http://www.cs.cmu.edu/afs/cs/academic/class/15859m-s11/www/lectures/lect0420.pdf>] OR we might run our own virtual machine where we can allow people (upon request) to run R code (that we pre-screen).


# How to report results?


We might want to include some assessment of the heterogeneity of treatment effects. And/or we might want an assessment about hypotheses about rare and aberrant effects (i.e. if a small number of people might be harmed by the change).

# End Matter

This document builds on the [*commitment of the federal government to
openness*](https://www.whitehouse.gov/open) and especially on our
interpretation of the detailed [*US Open Government National Action Plan
3.0*](https://www.whitehouse.gov/sites/default/files/microsites/ostp/final_us_open_government_national_action_plan_3_0.pdf)
as it applies to our mission and work. It is also inspired by the ways and virtues of our colleagues in the GSA at [*18F*](https://18f.gsa.gov/2014/07/31/working-in-public-from-day-1/)

Principles of open government collaborative, participatory, transparent <http://www.opengovpartnership.org/about/open-government-declaration>i
i<http://sciencecommons.org/resources/readingroom/principles-for-open-science/>
Principles of open science <https://cos.io/> integrity, reproducibility, openness.  


"Trust is not a scientific value.  Transparency is a replacement for trust.  The irrelevance of trust is facilitated by having no central authority for truth, and by making evidence and its source available publicly.  In principle, anyone can evaluate the basis of claims, and reproduce the procedures in order to verify the claims." (page 5 of Center for Open Science: Strategic Plan)

<https://docs.google.com/document/d/17OTxjE5zl34VcXiAORayFOCDIkyRCiefh1ZBN1qEBUc/edit>

Open science schools of thought <http://book.openingscience.org/basics_background/open_science_one_term_five_schools_of_thought.html> 


## Principles of Open Government Data

<https://opengovdata.org/>





<http://www.forbes.com/sites/rosspomeroy/2013/11/29/the-three-values-of-science/#6393728510c4>

Feynman's three values of science: "...scientific knowledge enables us to do all kinds of things and to make all kinds of things." 
"ANOTHER VALUE of science is the fun called intellectual enjoyment which some people get from reading and learning and thinking about it, and which others get from working in it.”

“Now, we scientists… take it for granted that it is perfectly consistent to be unsure, that it is possible to live and not know. But I don’t know whether everyone realizes this is true. Our freedom to doubt was born out of a struggle against authority in the early days of science. It was a very deep and strong struggle: permitting us to question – to doubt – to not be sure. I think that it is important that we do not forget this struggle and thus perhaps lose what we have gained. Herein lies a responsibility to society.”

"“The scientist has a lot of experience with ignorance and doubt and uncertainty, and this experience is of very great importance, I think.”"


