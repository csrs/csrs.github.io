---
layout: page
title: Projects
permalink: /projects/
---

## Data Analysis projects
I've been learning statistics and data analysis using Python. Here are some projects I've worked on.

#### Computing4Change: Analyzing maternal and infant mortality 

I worked on this during Computing4Change, which is a week-long conference/workshop/group project that uses data science to analyze a pertinent social issue. It was an incredible experience because 20 or so college students and mentors came together to help each other learn these tools and think critically about the issues we were looking at. I looked at how the mother's health insurance (public, private, uninsured) influences her and her infant's chances of survival within the first year of birth, using data from the CDC birth and death records. I subsetted the data mostly with R, and made visualizations with MatPlotLib. 

From the data and analysis that I conducted, I found that the mortality rates and rates of admission to the NICU didn't vary by much, between births that were paid for by the three insurance types. This is interesting to me since it seems like public opinion (and I'm sure there is research to back this up but I don't have it right here) could indicate that being on Medicaid means you are more likely to lack some of the positive social determinants of health or have a co-morbidity that could increase the chance of mortality. I acknowledge that this is a very basic analysis, but it was a really enjoyable learning experience.

There are a few things I would do differently next time I work on a project like this, first and foremost being that I would keep all the data and code I used. Unfortunately, I didn't do this for this project. Because of this, I've included notes under each of the slides with the information that I can remember. 

I am curious if these results are different in states that expanded Medicaid, versus those that haven't, and states that have the 60-day pregnancy/postpartum Medicaid expansion policy.

I have no formal medical or epidemiology training so any connections or correlations I have made are just my own, based on the data sets that I used. I used the 2016 CDC Live Birth/Infant Death Linked File, which links together all birth and infant death records in the US for the year 2016.

![C4C image](/images/c4c1.png)
Definitions that I used for this project. 

![C4C image](/images/c4c2.png)
The different payment sources for all births, and all births that resulted in the death of the infant within its first year.

![C4C image](/images/c4c3.png)
The Pearson Correlation Matrix for the three most common payment types. The parameters are things like number of days infant lived, number of cigarettes mother smoked, mother's education attainment, etc. These results seem to show that for each of the insurance types, the correlation of factors surrounding infant and maternal mortality stay relatively equal. This analysis doesn't show any highly positive or negative correlations between different factors that could affect mortality rates.

One thing I would change about this is that I would include the labels for the factors, which just wasn't possible with the charts on one slide - there wasn't enough space.

![C4C image](/images/c4c4.png)
The first chart shows the odds of an infant dying within the first month of life versus the first year, for each of the insurance types. 

The second chart shows the percentage of births that resulted in the infant needing to spend time in the NICU (admission to the NICU might be an indication of an increased chance of infant or maternal mortality). 

If I were to re-do this, I would put each of these charts on a different slide.

## Programming projects
These are class projects, and each link goes to a GitHub repo for each class. My favorite project was the web development projects year calendar and class sceduler, as well as the Python hangman game. 

* Javascript, NodeJS, CSS, HTML: [class scheduler, year calendar, weather and more](https://github.com/csrs/CS290-web-dev)
* See live code [here](https://website-cs290.herokuapp.com) 
* Python: [hangman](https://github.com/csrs/CS160-python) & [more advanced](https://github.com/csrs/CS162-python)
* C: [tic tac toe game and more ](https://github.com/csrs/CS133C)
* C++: [data structures](https://github.com/csrs/CS260-data-structures)

## Websites
I worked on these at a web agency that specializes in using the Umbraco CMS. 

#### Design implementation
I alternated my time between bug fixes, feature additions, and implementing new designs. My work involved portions of a page rather than the entire site. I used CSS, C# (Razor), and Javascript. I also did some browser testing, UX design/research, and even converted some of the older sites to be responsive. Here are some of my favorites:
* Leyard [[link]](https://www.leyard.com/) 
* Homepage slider, product pages
* Grant European Travel [[link]](https://www.getours.com)
* Header, tour pages, trip boxes
* S.R.Smith [[link]](https://srsmith.com/)
* Header, product pages
* Celestron [[link]](https://www.celestron.com/)
* User stories

#### Accessibility-specific work
My proudest work is the accessibility improvements, testing, audits, documentation, and teaching I did. 
* Rivermark Credit Union [[link]](https://www.rivermarkcu.org)
* Homepage, contact us page, buttons, links, images, etc
* University of Nevada, Reno Office of IT [[link]](https://oit.unr.edu/) 
* Homepage

## Other

#### Web design workshops
As part of ChickTech, I led two workshops on HTML and CSS for high schoolers with no prior experience. This experience improved my public speaking, listening, and empathy skills.

#### Short documentary about changes in online education [[link]](https://www.youtube.com/watch?v=kp7DKzTxFSw)
This video investigates what the future of prestigious higher education might look like if it was online and available to anyone in the world. 
