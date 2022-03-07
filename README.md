# The Group Project
## Overview and Objectives
### General Overview
This group project will give you an opportunity to apply the skills you are
learning in [R for Data Science][Grolemund and Wickham 2017] and [Text Mining
With R][Silge and Robinson 2017] to the arenas of customer and text analytics,
such that you will end up turning numeric and text data into significant,
actionable, and interesting insights for [Meals on Wheels of
Charlottesville/Albemarle][cvillemeals] (C'ville Meals), a local nonprofit
organization that is partnering with us for the purposes of this group project.

The more you engage in [this process of data science][Hadley 2017], the better
you will be at [generating, disseminating, and responding][Jaworski and Kohli
1993] to market intelligence. Improving your ability to perform these three core
activities will in turn allow you to help companies&mdash;especially those you
want to work for&mdash;achieve a market orientation and optimize collective
value. After all, optimizing collective value (i.e., prosperity) is arguably why
society engages in commerce ([Donaldson and Walsh 2015][]) and, as a result,
customer and text analytics in the first place.

### Company Overview
As a brief summary, TJL is an organic juice and smoothie bar with three
locations in Charlottesville, VA. Founded by UVA alumni Mike and Sarah Keenan,
TJL's mission is "to inspire healthy, organic, powerful change." In-store
signage articulates Mike and Sarah's [value proposition][] to customers as
follows:

> The Juice Laundry was founded on the concept of keeping our bodies clean and
healthy, starting with what we put into them. Raw, organic fruits and veggies
are nature's medicine and the foundation of preventative health care. Whether
juiced, blended, or eaten whole, fresh produce is full of life-giving nutrients
and enzymes. We choose to use 100% organic ingredients, 100% of the time,
because the phrase 'organic whenever possible' is often highly misleading. If we
can't find something organic on a given day, it won't be on our menu. That's our
commitment to you, and to your health.

Elsewhere in TJL's locations, the brand's [slogan][] "Clean Your Machine" is
displayed prominently, as are the brand's [defining principles][]: "We are Raw.
We are Fresh. We are Clean. We are Organic. We are Curious. We are Passionate.
We are Transparent. We Leave a Gentle Footprint." Missing in stores, however,
are trash cans, as 100% of TJL's packaging is either [compostable][] or
reusable.

For this group project, TJL is offering us a "[lab of sorts][]," somewhere you
can talk with business owners, employees, and customers; analyze data; develop
ideas; and, eventually, see the impact of your hard work when you come back to 
Grounds [at the AFC][] and [on the Corner][].

### Project Scope
The specific ask from Mike and Sarah is for you to develop a month's worth of
Instagram content for a new account,
[@thejuicelaundryuva](https://www.instagram.com/thejuicelaundryuva/), that they
will use to communicate with and engage the UVA community, starting June 1,
2021. With [@thejuicelaundry](https://www.instagram.com/thejuicelaundry/), Mike
and Sarah are hesitant to convey as much UVA-specific content as they believe is
necessary, since it could turn off Charlottesville residents who are followers
but not affiliated with the University. Further, Mike and Sarah are excited to
hear your ideas for month-long campaigns that can be themed (i.e., focused on a
specific topic) and your ideas for posts or campaigns that stem from the
analysis of consumer and customer behavior (e.g., posts about the number of
bottles that have been returned to the Corner and AFC locations in a given
month).

Therefore, your objectives are twofold: (1) identify a month or 30-day period in
the June 2021 to May 2022 time frame and (2) develop a concrete, comprehensive,
and convincing Instagram campaign that logically stems from [data-informed
insights][Parker 2017/06/06].

### Data and Methods Advice
As you get started on this project, we encourage you to be divergent in your
thinking (see [Peng 2018][]). Begin today by conducting secondary research on
platforms such as [Business Source Complete], [Euromonitor], [Factiva],
[IBISWorld], [Statista], and other platforms (see the [Commerce LibGuide] for
options). Then, with a better understanding of the industry and landscape that
TJL operates in, conduct primary research via relevant online sites, such as
[Elevate], [Instagram], and [Yelp].

In class, we will analyze the following data sets:  

* The {juicelaundry} data package, which includes point-of-sale transaction
details for TJL's locations on the Corner and in the AFC, as well as information
about a select set of other juice and smoothie bars' Instagram accounts and the
engagement they have generated from their posts.
* Google Review data, which contains the text comments and star rating of all
reviews posted to Google Maps/Places for TJL and a select set of other juice and
smoothie bars.
* [Google Trends][] data, which can capture relative search interest and
emerging trends for topics that are relevant to TJL's business.

Get to know the variables in these data sets as soon as you can to increase the
likelihood that your Instagram campaign will rest on a strong foundation of
data-informed insights.

As always, it will be important for you to describe the [provenance][Polich and
Whitenack 2017] of your data parsimoniously and to define the variables you
analyze [clearly, completely, and credibly][Zhang and Shaw 2012].

   __Pro tip__: Be [radically open minded]&mdash;and [productively
   stupid][Schwartz 2008]&mdash;from the get go and strive to not let
   confirmation bias contaminate your findings as you make sense of the market
   that TJL operates in ([Gallo 2017][]).

   __Pro tip__: Organize your observations into tidy data sets, such as those
   discussed in [Chapter 12][Grolemund and Wickham 2017, 12] of R for Data
   Science so you can summarize them statistically and visually. This process
   will add rigor to your analysis and the insights you generate.

Finally, be sure to apply the methods you learn in Customer Analytics and Big
Data & Text Analytics effectively. You will get separate grades for each course,
so it is imperative that you demonstrate proper uses of methods being covered in
both courses. There are no firm requirements for the number of techniques you
need to perform as part of your analysis; however, we encourage you to generate
recommendations from the analysis of numeric data, text data, and some
combination of both. As such, we strongly encourage you to identify and act on
opportunities to incorporate the results of text analyses into models/procedures
that utilize numeric customer data.

## Deliverables
There are a total of four key deliverables for the group project, two of which
will serve as status checks and two that will be formally graded:

### Status Checks
1.  A 1-2 page memo outlining your team's high-level strategy for organizing
itself and preparing for data analysis. This memo will serve as a written
representation of your team's journey through the [business understanding][]
phase of TDSP. To prepare this memo, teams must first discuss each team member's
strengths and weaknesses to establish where each team member may productively
contribute to the final submissions. Teams must then review the data
models/dictionaries provided to them and chart a path for how to perform
exploratory data analysis. There is no formal grade for this deliverable, rather
it will be used as a mechanism for ensuring accountability within the team and
for general guidance from your professor to maximize the efficiency by which you
begin the data exploration process. This memo will be evaluated only by
Professor Maurer, as it aligns with processes specific to Big Data & Text
Analytics.  Memos should be submitted via email to Professor Maurer no later
than 5:00 pm on March 19.

2.  A 1-2 page memo outlining one or two potential ideas for your Instagram
campaign, and preliminary analyses (based on secondary and primary data) that
could serve as the foundation for your proposed path(s) forward. This memo
should offer a high-level description of how you plan to create a data-informed
Instagram campaign. Which variables and methods do you plan to leverage to
uncover insights, and how might these insights come to life in your Instagram
campaign? No grade will be assigned to this memo. However, it does offer a
valuable opportunity for you to get feedback from us on both the scope of your
proposed project as well as the analytical strategy you are proposing to
implement. This memo must be submitted via email to both Prof. Boichuk and Prof.
Maurer no later than 5:00 pm on April 2.

### Final Submissions
3. A report of no more than 25 pages, 12-point font, double-spaced (excluding
references, exhibits, and appendices). We will use the [report
guidelines](#report-guidelines) below to assess your report and give you
developmental feedback. Submit your report along with any scripts and data you
used to perform your analyses via email to both Prof. Boichuk and Prof. Maurer
no later than 12:30 pm on May 4.

4. A presentation of no more than 20 minutes, plus up to 10 minutes of Q&A. An
agenda will guide when groups present. Your peers and your professors will use
the [presentation guidelines](#presentation-guidelines) below to assess your
presentation and give you developmental feedback. Submit your slide deck via
email to both Prof. Boichuk and Prof. Maurer no later than 12:30 pm on May 4.

## Grading Breakdown

Your final grade for the project will be determined based on both the report and
your presentation. Certain elements of this grade will be consistent across both
courses (Style & Grammar and Presentation Skills) while others may diverge. Your
professors will independently review and evaluate your report and presentation,
giving special attention to the portions of your analysis that relate to the
content covered in their courses. They will share their evaluations with each
other and discuss discrepancies; hence, it is possible that groups may receive
different grades for each class. While the grading categories will be the same
for both courses, group performance in some categories may be stronger for
analyses aligning with one course as compared to the other.

The following table summarizes the breakdown of how final project grades will be
determined:

Grading Component          | Percentage of Total Grade|
---------------------------|:------------------------:|
Decision-making principles |	15%                     |
Data                       |	15%                     |
Methods                    |	25%                     |
Action plan	               |  20%                     |
Report style & grammar     |	10%                     |
Presentation skills        |	15%                     |

## Status Check #1 Guidelines
This memo will ultimately address three primary questions:
1. How will your team be organized and what roles will each team member assume
to ensure a high-quality final deliverable?
2. How will you approach the data exploration phase of the project?
3. Are there any additional data points that may assist you in delivering an
impactful recommendation to TJL?

In terms of point number one, you should have a reasonably strong working
relationship with your group based on your experiences in GCOM 7240. At the end
of the project, each team member will be asked to evaluate themselves and their
teammates on whether they have a legitimate claim to ownership of the final
submissions. Take this opportunity to plan how each team member will actively
engage and establish a claim to ownership of the finished product. Your group is
undoubtedly composed of analysts, thinkers, and writers at different stages of
their respective journeys. In fact, it's natural for group members to assume
different roles, make unique contributions, and even go above and beyond at
different points in time. While there are no pre-defined titles or roles you are
expected to adhere to, share with one another your passions for where you want
to contribute and document them in this memo. Teams are encouraged to rotate
responsibilities such that they have an opportunity to engage more deeply in an
area where another teammate took the lead on previous group work. This will
serve as a "Team Charter" to help hold all team members accountable for the work
they contribute to the final deliverable.

In terms of the second question, you will not have access to most of the data
outlined in the Data and Methods Advice section of this group project description 
when you compile this memo. However, you will be provided with data 
models/dictionaries that describe all of the data that will be available to you. 
Using these data models, formulate a plan for how you will begin exploring the 
data such that you can gain a deeper understanding of the business and the 
challenges Mike and Sarah have tasked you with addressing. This process will 
involve thinking about how to best combine disparate data, initial queries you 
might execute to extract data for exploratory analysis, and answers you hope to 
find such that you can begin refining the scope of your efforts for the 
remainder of the project.

For the third question, there is no requirement that you analyze additional data
beyond what is provided by your professors.  However, final submissions that 
exceed expectations will incorporate some form of additional, external data. At 
this stage, you should simply think about what data may assist you in developing 
a more robust recommendation for TJL. Your professors will most likely not have
this data readily available and it will be your responsibility to gather it. As
such, an informal cost-benefit analysis is necessary: Is the additional time
spent collecting, cleaning, and analyzing this data worth the additional
insights that may emerge from it? In many cases, the costs will exceed the
benefits, but you are still encouraged to think about the topics covered in Big
Data & Text Analytics and how a business like TJL could yield greater insights
from a variety of data sources.

This memo will only need to be addressed to Professor Maurer as it specifically
relates to concepts covered in Big Data & Text Analytics. No grade will be
awarded; however, this is a great opportunity to receive valuable feedback on
how you can efficiently begin analyzing data in preparation for your second
status check.


## Status Check #2 Guidelines
This memo should refine your original plan based on your initial exploration of
the data.  Specifically, it should describe:

1. One or two potential ideas for your Instagram campaign. 
2. The data (i.e., data sets, rows, and columns) that you plan to analyze.
3. Analytical procedures that you believe are appropriate for developing
insights and recommendations from the data you plan on analyzing.

There is no one "right" way to organize this proposal; however, you should make
sure to outline what you plan to do&mdash;over the four weeks between the date
this proposal is due and the week you present to Mike and Sarah&mdash;very
carefully. While your memo must be concise, it should illustrate that your group
has thought critically, and in a divergent manner, about TJL's business. Your
idea(s) should have the potential to become a concrete, comprehensive, and
convincing Instagram campaign that logically stems from data-informed insights.

Regarding the second requirement for this memo, we want to see that you have
more than a surface-level understanding of the {juicelaundry} point-of-sale
data, Google Review data, and [Google Trends][Google Trends] data, all of which
you are being trained to analyze. At a minimum, you should have already thought
about and experimented with some`filter()` and `mutate()` statements that will
get these data sets into the forms you need them in. This is why it is important
to not only describe your analysis but also describe the data you intend to use.
Although not required, it will be exemplary if you describe any new-to-the-world
tidy datasets that you compiled since composing your first status check memo.
For example, you could supplement the `sku` data set in the {juicelaundry}
package with comparable datas ets for a competitor, such as Corner Juice, if
doing so would aid your decision making.

For the third requirement, two questions we want to see you convey answers to
include: How do you plan on analyzing these data sets (i.e., with what
methods?), and what artifacts (e.g., graphics and model estimates) do you plan
on producing?

Again, there is no grade associated with this status check; however, this is an
opportunity to gain valuable feedback on the approach you have devised to
satisfy the project requirements. Your professors will review your memo in
detail and provide feedback meant to guide you toward a high-quality final
report and presentation. If appropriate, a meeting may be scheduled to discuss
your memo in more detail and ensure that your group is on a path toward success.

## Report Guidelines

Your report should advocate for an Instagram campaign that TJL could put into
place in the June 2021 to May 2022 time frame. Base your recommendation on (i) a
decision-making process with strong [principles][Dalio 2017]; (iii) data that
are described [clearly, completely, and credibly][Zhang and Shaw 2012]; (iv) a
breadth and depth of analyses that are applied [accurately, collaboratively, and
reproducibly][Parker 2017]; and (v) [stylish writing][Sword 2012].

Your report should contain the following sections: (1) title page, (2) executive
summary, (3) main body, (4) references, (5) exhibits, and, potentially, (6)
appendices. Before you submit your final document, make sure it is as error free
as possible, clearly communicated, and professionally designed&mdash;i.e.,
client-ready. Note: Producing client-ready business documents is time consuming.
Plan early and review your progress often to make sure that you are working
collaboratively to design, create, and deliver a client-ready document.

There is no one "right" way to organize the main body of the report; however,
you should think carefully about what your audience (in this case, Mike and
Sarah Keenan) already knows and prioritize discussing original analysis that you
have conducted over general statements about TJL's business, for example. 

After reading your report, we will use the following guidelines to assess your
work and provide you with developmental feedback. Internalizing these guidelines
will help you develop a report worthy of an exemplary grade.

### Decision-Making Principles (15%)
* Cogent reasoning explains why the Instagram campaign you are recommending is
likely to succeed.
* Long-term, detrimental implications of not implementing your Instagram
campaign for TJL are argued concretely.
* The proposed course of action is very well reasoned.
* Hoofbeats are interpreted as signs of horses not [zebras][Sotos 2006].  
* The recommended Instagram campgain stems from analytical results, which
provides legitimacy to it.

### Data (15%)
* The [provenance][Polich and Whitenack 2017] and definitions of the data and
variables being analyzed to make decisions are described [clearly, completely,
and credibly][Zhang and Shaw 2012].
* Convincing reasons explain why certain data are given priority (over others).
* An appropriate variety of data is included in the analysis to inform
decision-making from multiple angles using a mixture of numeric and text data.
* Statements about data limitations are made at appropriate times.

### Methods (25%)
* A breadth and depth of techniques covered in [R for Data Science][Grolemund
and Wickham 2017] and [Text Mining With R][Silge and Robinson 2017] are applied 
[accurately, collaboratively, and reproducibly][Parker 2017].
* The techniques being performed complement one another and create synergies
that offer deeper insights than the individual analyses would offer
independently.
* A knowledgeable individual could [reproduce][Peng 2011] the report's findings
with ease, because the group's submission provides access to not only the
report, but also self-contained, executable code and the data being analyzed.
* Visualizations are used in ways that force the reader to notice [unexpected
phenomena][Grolemund and Wickham 2017, 3.3].
* Statements about methodological limitations are made at appropriate times.

### Action Plan (20%)
* All relevant elements of your Instagram campaign are covered in detail.  
* What should be posted (i.e., picture, caption, location, tags) and when it
should be posted are outlined fully.
* The overall recommendation being proposed is creative (i.e., novel and
useful).
* Goals related to follower engagement and sales are set in [specific,
measurable, achievable, relevant, and time-bound][Miller 2018] ways in order to
establish expected results.

### Style \& Grammar (10%)
* The expectations set in Communication&mdash;which include, but are not limited
to, BLUF writing, SAS headings/tables/figures, and SEC plain English&mdash;are
met or exceeded at all times.
* Tables and figures are all formatted properly and [effectively][Grolemund and
Wickham 2017, 28.1].
* Appendices are used appropriately and as needed.
* Every sentence is grammatically correct, and all sentences flow together
naturally.
* The report is free of spelling errors.  
* All references, including endnotes and reference list entries, adhere to the
[HBS Citation Guidelines][].
* The [Tidyverse Style Guide][] is adhered to at all times with respect to the
report's [files][style files], [syntax][style syntax], and [pipes][style pipes].

## Presentation Guidelines
Your group should prepare your presentation as you would if you were presenting
to Mike and Sarah in "the real world," with the goal of persuading them to
actually implement the Instagram campaign you are advancing. Ask for the highest
realistic level of commitment you can at the end of your presentation, and try
your best to receive their approval during the Q&A period.

After listening to your presentation, invited guests, your peers, and your
professors will use the following guidelines to assess it and give you
developmental feedback. Internalizing these guidelines will help you deliver a
presentation, which constitutes one-third of the group project grade, that is
worthy of an exemplary grade.

* The group built a case for the Instagram campaign they proposed with a breadth
and depth of well-principled analyses that motivated me to accept their claims.
* The group discussed the data they analyzed in a [simple, easy-to-understand
way][Allen 2017].
* The group was captivating, edutaining, and eye-catching, a "[fusion of
scientific rigor with canny attention-grabbing][Allen 2017]."
* The group presented as a team (i.e., their contributions were comparable and
complementary).
* The group's slides were [self-explanatory][Grolemund and Wickham 2017,
28.1], well referenced, and free of errors.
* The group responded to questions and reservations [appropriately][Jolles
2013].

[agenda]: https://github.com/GCOM7140/group-project/blob/master/agenda.md#customer-analytics-group-project-presentations
[Allen 2017]: https://www.ft.com/content/df4af260-eece-11e6-930f-061b01e23655
[at the AFC]: https://www.thejuicelaundry.com/about/locations/the-afc
[Bradlow, Fader, Yyengar, and Bernman]: https://www.coursera.org/learn/wharton-customer-analytics
[Business Source Complete]: http://proxy.its.virginia.edu/login?url=http://search.ebscohost.com/login.aspx?authtype=ip,uid&profile=ehost&defaultdb=bth
[commerce libguide]: https://guides.lib.virginia.edu/commerce
[compostable]: https://www.instagram.com/p/B2TwAjcFoPx/
[Colquitt and George 2011]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-TopicChoice.pdf
[cvillemeals]: https://www.cvillemeals.org/
[Dalio 2017]: https://smile.amazon.com/Principles-Life-Work-Ray-Dalio/dp/1501124021/ref=sr_1_3?ie=UTF8&qid=1522529948&sr=8-3&keywords=principles+ray+dalio
[defining principles]: https://www.instagram.com/p/BizUfw1lLqu/?taken-by=thejuicelaundry
[Donaldson and Walsh 2015]: http://www.sciencedirect.com/science/article/pii/S0191308515000088
[elevate]: https://www.elevatemealplan.com/uva-meal-plan
[euromonitor]: http://proxy.its.virginia.edu/login?url=http://www.portal.euromonitor.com/portal/server.pt
[factiva]: http://proxy.its.virginia.edu/login?url=http://global.factiva.com/en/sess/login.asp?xsid=S003cbsYXmnNdmnMDItMDIoMDAp5DByMU38ODJ9RcyqUUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUEA
[Gallo 2017]:https://www.inc.com/carmine-gallo/a-self-made-billionaire-reveals-the-1-mental-hurdl.html
[Google Trends]: https://trends.google.com/trends/
[Grolemund and Wickham 2017]: http://r4ds.had.co.nz
[Grolemund and Wickham 2017, 3.3]: http://r4ds.had.co.nz/data-visualisation.html#aesthetic-mappings
[Grolemund and Wickham 2017, 12]: https://r4ds.had.co.nz/tidy-data.html
[Grolemund and Wickham 2017, 28.1]: http://r4ds.had.co.nz/graphics-for-communication.html
[Hadley 2017]: https://rstudio.com/resources/rstudioconf-2017/data-science-in-the-tidyverse-hadley-wickham/
[HBS Citation Guidelines]:https://www.library.hbs.edu/content/download/49322/file/HBS%20Citation%20Guide%20%202019-20.pdf
[ibisworld]: http://proxy.its.virginia.edu/login?url=http://www.ibisworld.com/
[instagram]: https://www.instagram.com/
[Jaworski and Kohli 1993]: https://pdfs.semanticscholar.org/82e7/864936822e1c97d5ebc9996fab705defcfdb.pdf
[Johnson 2018]: https://nyti.ms/2C558Py
[Jolles 2013]: http://www.amanet.org/training/articles/i-object-four-steps-to-handling-objections.aspx
[jmr 1]: https://auth.ama.org/publications/JournalOfMarketingResearch/Pages/JMRSubmissionGuidelines.aspx
[jmr 2]: https://auth.ama.org/publications/JournalOfMarketingResearch/Pages/JMR_Accepted_Ms.aspx
[juicelaundry]: https://github.com/GCOM7140/juicelaundry#juicelaundry
[lab of sorts]: https://news.virginia.edu/content/seeking-real-world-case-study-one-commerce-professor-turned-corner
[Miller 2018]: https://www.nytimes.com/guides/smarterliving/resolution-ideas
[on the corner]: https://www.thejuicelaundry.com/about/locations/the-corner
[Parker 2017]: https://peerj.com/preprints/3210/
[Parker 2017/06/06]: https://twitter.com/hspter/status/872135582100578304
[Peng 2011]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/
[Peng 2018]: https://simplystatistics.org/2018/09/14/divergent-and-convergent-phases-of-data-analysis/
[Polich and Whitenack 2017]: https://dataskeptic.com/blog/episodes/2017/data-provenance-and-reproducibility-with-pachyderm
[radically open minded]: https://www.inc.com/carmine-gallo/a-self-made-billionaire-reveals-the-1-mental-hurdl.html
[Schwartz 2008]: http://jcs.biologists.org/content/121/11/1771
[Silge and Robinson 2017]: https://www.tidytextmining.com/
[slogan]: https://www.instagram.com/p/Bf_D0ZRHzEL/?taken-by=thejuicelaundry
[Sotos 2006]: https://en.wikipedia.org/wiki/Zebra_(medicine)
[Sword 2012]: https://smile.amazon.com/Stylish-Academic-Writing-Helen-Sword/dp/0674064488/ref=sr_1_1?s=books&ie=UTF8&qid=1522530104&sr=1-1&keywords=stylish+academic+writing
[statista]: http://proxy01.its.virginia.edu/login?url=https://www.statista.com
[style files]: https://style.tidyverse.org/files.html 
[style pipes]: https://style.tidyverse.org/pipes.html
[style syntax]: https://style.tidyverse.org/syntax.html
[Tidyverse Style Guide]: https://style.tidyverse.org/
[tjl]: https://www.thejuicelaundry.com/
[topic choice decision matrix template]: https://github.com/GCOM7140/group-project/blob/master/docs/topic-choice-decision-matrix-template.docx
[value model template]: https://github.com/GCOM7140/class-sessions/raw/master/02_group-project-overview/readings/value-model-template.docx
[value proposition]: https://www.instagram.com/p/BYoOJaPjCGz/?taken-by=thejuicelaundry
[yelp]: https://www.yelp.com/
[Zeithaml 1988]: https://www.jstor.org/stable/pdf/1251446.pdf?casa_token=Xa8qdat3R3sAAAAA:UIVbmoYyPjGk0G5lRYUvGjIkQUa0O_-0X109e03kfzy9oeyMjMco37hLxQHMmv3_gQPNrNP63Zjxa3rSS7urFo9WmRBwfjJJENx112_8N9RZr-zdEy85
[Zhang and Shaw 2012]: https://journals.aom.org/doi/10.5465/amj.2012.4001
[business understanding]: https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/lifecycle-business-understanding
