---
layout: post
title: My experience and project at Computing4Change
categories: Conference
---


I worked on this during Computing4Change, which is a week-long conference/workshop/group project that uses data science to analyze a pertinent social issue. It was an incredible experience because 20 or so college students and mentors came together to help each other learn these tools and think critically about the issues we were looking at. I looked at how the mother's health insurance (public, private, uninsured) influences her and her infant's chances of survival within the first year of birth, using data from the CDC birth and death records. I subsetted the data mostly with R, and made visualizations with MatPlotLib. 

From the data and analysis that I conducted, I found that the mortality rates and rates of admission to the NICU didn't vary by much, between births that were paid for by the three insurance types. This is interesting to me since it seems like public opinion (and I'm sure there is research to back this up but I don't have it right here) could indicate that being on Medicaid means you are more likely to lack some of the positive social determinants of health or have a co-morbidity that could increase the chance of mortality. I acknowledge that this is a very basic analysis, but it was a really enjoyable learning experience.

There are a few things I would do differently next time I work on a project like this, first and foremost being that I would keep all the data and code I used. Unfortunately, I didn't do this for this project. Because of this, I've included notes under each of the slides with the information that I can remember. 

I am curious if these results are different in states that expanded Medicaid, versus those that haven't, and states that have the 60-day pregnancy/postpartum Medicaid expansion policy.

I have no formal medical or epidemiology training so any connections or correlations I have made are just my own, based on the data sets that I used. I used the 2016 CDC Live Birth/Infant Death Linked File, which links together all birth and infant death records in the US for the year 2016.

![Definitions that I used for this project.](/images/c4c1.png)
Definitions that I used for this project. 

![The different payment sources for all births, and all births that resulted in the death of the infant within its first year.](/images/c4c2.png)
The different payment sources for all births, and all births that resulted in the death of the infant within its first year.

![Pearson Correlation Matrix for the three most common payment types.](/images/c4c3.png)
The Pearson Correlation Matrix for the three most common payment types. The parameters are things like number of days infant lived, number of cigarettes mother smoked, mother's education attainment, etc. These results seem to show that for each of the insurance types, the correlation of factors surrounding infant and maternal mortality stay relatively equal. This analysis doesn't show any highly positive or negative correlations between different factors that could affect mortality rates.

One thing I would change about this is that I would include the labels for the factors, which just wasn't possible with the charts on one slide - there wasn't enough space.

![Two charts show the odds of an infant dying within the first month of life versus the first year, for each of the insurance types. ](/images/c4c4.png)
The first chart shows the odds of an infant dying within the first month of life versus the first year, for each of the insurance types. 

The second chart shows the percentage of births that resulted in the infant needing to spend time in the NICU (admission to the NICU might be an indication of an increased chance of infant or maternal mortality). 

If I were to re-do this, I would put each of these charts on a different slide.


This program really taught me how far I can go in a short period of time... how much I can teach
myself, how forgiving I can be with myself when I struggle to understand a new concept, and how
generous I can be with my time by helping my peers.

The most unique part of this program was that each student was there of their own volition. We weren’t
getting paid to be there, we weren’t getting class credit... heck, I did extra work to
make up the week of school that I missed. It was 100% internally motivated.

Even prior to arriving, there were last-minute webinars and tutorials that I had to complete, which
meant I had to add more to my schedule and make sure I was balancing them. Upon arriving, I realized
that I wasn’t entirely sure how much of the end product was in my control. It turned out that it was
100% in my control. There were suggestions (some very strong) of what type of data to look at, which
tools to use, etc, and I did check in with the mentors to get their feedback, but ultimately it was up to
me. 

Something very interesting happened mid-way through the week. I had became frustrated because I
was asked to try some techniques that to me were advanced, something that I hadn’t expected to learn or do that week. It
would be more work, and harder work, than than I expected, but a mentor had suggested
I try it.

At first, I struggled with this because part of me wanted to take the easy way out. I let myself feel
annoyed for a few minutes, and then came to my senses. I didn’t take an entire week off of school just to
do a minimal amount of work, and not push myself as far as I can. 

That evening was spent doing lots of trial and error and searching online to understand how to do this
statistical method. I stayed in my hotel room by myself because I didn’t want to be tempted to let
anyone do it for me. I wanted to struggle for a few hours so that I would at least have some questions to
ask in the morning. In the process, I encountered some things that I would never have run into if I
hadn’t struggled with this - mainly around how to clean the data.

The next morning, I was very nervous because I felt like perhaps I had wasted an entire evening, and
maybe I should have asked someone for help? What if the result I had was statistically invalid? I
showed my work to a mentor and as I explained it, I realized my work was valid, if I just change one
thing!

I usually can’t stay up past a certain hour, but while working on this problem, I consistently stayed up
after that, no caffeine necessary, because I was so engaged and invested in the research. That sort of
intrinsic motivation and ability to choose what direction I take my work (within the constraints of
working on a team) is what I strive for.


