# The Group Project
## Overview and Objectives
### General Overview
This group project will allow you to apply the skills you are learning in [R for
Data Science][Grolemund and Wickham 2017] to customer analytics, such that you
will turn numeric and text data into significant, actionable, and interesting
insights.

The more you engage in [data science][Hadley 2017], the better you will be at
[generating, disseminating, and responding][Jaworski and Kohli 1993] to market
intelligence. Improving your ability to perform these three core activities
will, in turn, allow you to help companies&mdash;especially those you want to
work for&mdash;achieve a market orientation and optimize collective value. After
all, optimizing collective value (i.e., prosperity) is arguably why society
engages in commerce ([Donaldson and Walsh 2015][]) and, as a result, customer
analytics in the first place.

### Project Scope
For this group project, Twitter offers us a training ground wherein you can
analyze its users' data, develop ideas, and turn them into compelling
recommendations. The specific ask is for you to create a month's worth of
Twitter content for an automaker. Also, your objectives are twofold: (1)
identify a month or 30-day period in the May 2023 to April 2024 time frame and
(2) develop a concrete, comprehensive, and convincing set of tweets that
logically stem from [data-informed insights][Parker 2017/06/06].

### Data and Methods Advice
As you start this project, I encourage you to think *divergently* (see [Peng 2018][]). You can begin today by conducting secondary research on
platforms such as [Business Source Complete], [Euromonitor], [Factiva],
[IBISWorld], [Statista], and other platforms (see the [Commerce LibGuide] for
options). With a thorough understanding of the landscape automakers are
operating in, you will be in a better position to conduct primary research.

In class, we will conduct primary research by analyzing data in the {tslatwtr} R
package, which houses information about a related set of Twitter accounts and
their tweets. Knowing this data inside and out will increase the likelihood that
your project rests on a solid foundation of data-informed insights.

For example, you should strive to describe the [provenance][Polich and Whitenack
2017] of the data in the {tslatwtr} package parsimoniously and to define the
variables you analyze [clearly, completely, and credibly][Zhang and Shaw 2012].
Be [radically open minded]&mdash;and [productively stupid][Schwartz
2008]&mdash;from the get go and strive not to let confirmation bias contaminate
your findings as you make sense of the automotive landscape ([Gallo 2017][]). As
you collect data, do so tidily (see [Chapter 12][Grolemund and Wickham 2017, 12]
of R for Data Science) so you can summarize it statistically and visually with
ease using the {tidyverse} package. This process will add rigor to your analysis
and the insights you generate.

## Deliverables
There are three key deliverables for the group project: a status check, a
report, and a presentation:

### Status Check
A two-page memo outlining promising ideas for your month of Twitter content and
preliminary analyses (based on secondary and, perhaps, primary research) that
could be the foundation for your proposed path forward. This memo should offer a
high-level description of how you plan to create a data-informed recommendation.
What month or 30-day period in the May 2023 to April 2024 time frame will you
focus on? Which variables and methods do you plan to leverage to uncover
insights, and how might these insights come to life in your tweets? No grade
will be assigned to this memo. However, it does offer a valuable opportunity for
you to get feedback on the scope of your proposed project and the analytical
strategy you are proposing to implement. Submit this memo by email to the TA,
Michael Xia (zx4cn@virginia.edu), no later than 5:00 pm on March 31.

### Final Submissions
3. A report of no more than 20 pages, 12-point font, double-spaced (excluding
references, exhibits, and appendices). I will use the [report
guidelines](#report-guidelines) below to assess your report and give you
developmental feedback. Submit your report along with the scripts and data you
used to perform your analyses via Blackboard no later than 11:59 pm on April 19.

4. A presentation of no more than 20 minutes, plus up to 10 minutes of Q&A. An
agenda will guide when groups present. Your peers and I will use the
[presentation guidelines](#presentation-guidelines) below to assess your
presentation and give you developmental feedback. Submit your slide deck via
Blackboard no later than 11:59 pm on April 19.

## Grading Breakdown

Your final grade for the group project will be determined based on both your
report and presentation, according to the following breakdown:

Grading Component          | Percentage of Total Grade|
---------------------------|:------------------------:|
Decision-making principles |	15%                     |
Data                       |	15%                     |
Methods                    |	25%                     |
Action plan	               |  20%                     |
Report style & grammar     |	10%                     |
Presentation               |	15%                     |

## Status Check Guidelines

This memo should outline a promising path forward based on your initial
exploration of secondary and primary data.  Specifically, it should describe:

1. Your idea for a month-long set of Twitter content. 
2. The data (i.e., data sets, rows, and columns) that you plan to incorporate in
your analyses.
3. Analytical procedures that you believe are appropriate for developing
insights and recommendations from the data you plan on analyzing.

There is no one "right" way to organize this proposal; however, you should make
sure to outline what you plan to do&mdash;between the date this proposal is due
and the week you present&mdash;very carefully. While your memo must be concise,
it should illustrate that your group has thought critically, and in a divergent
manner, about the automakers and their competitive positions. Your idea(s)
should have the potential to become a concrete, comprehensive, and convincing
recommendation that logically stems from data-informed insights.

Regarding the second requirement for this memo, I want to see that you have
more than a surface-level understanding of the {tslatwtr} data package, which
you will be trained to analyze. At a minimum, you should have already thought
about and experimented with {dplyr} statements to get its data sets into the
forms you need them in. That is why it is important to describe not only your
analysis but also the data you intend to use. Although not required, it will be
exemplary if you describe any new-to-the-world tidy data sets that you have
compiled or plan to compile. For example, you could supplement the `tweet` table
in the {tslatwtr} package with comparable data for another account that has
successfully implemented a month-long Twitter campaign using the Twitter API.

For the third requirement, two questions I want to see you convey answers to
include: How do you plan on analyzing these data sets (i.e., with what
methods?), and what artifacts (e.g., graphics and model estimates) do you plan
on producing?

Again, there is no grade associated with this status check; however, this is an
opportunity to gain valuable feedback on the approach you have devised to
satisfy the project requirements. I will review your memo in detail and provide
feedback meant to guide you toward a high-quality final report and presentation.
If appropriate, I may schedule a meeting to discuss your memo in more detail and
ensure that your group is on a path toward success.

## Report Guidelines

Your report should advocate for a set of tweets that a major automaker could
put into place in the May 2023 to April 2024 time frame. Base your
recommendation on (i) a decision-making process with strong [principles][Dalio
2017]; (iii) data that are described [clearly, completely, and credibly][Zhang
and Shaw 2012]; (iv) a breadth and depth of analyses that are applied
[accurately, collaboratively, and reproducibly][Parker 2017]; and (v) [stylish
writing][Sword 2012].

Your report should contain the following sections: (1) title page, (2) executive
summary, (3) main body, (4) references, (5) exhibits, and, potentially, (6)
appendices. Before you submit your final document, make sure it is as error free
as possible, clearly communicated, and professionally designed&mdash;i.e.,
client-ready. Note: Producing client-ready business documents is time consuming.
Plan early and review your progress often to make sure that you are working
collaboratively to design, create, and deliver a client-ready document.

There is no one "right" way to organize the main body of the report; however,
you should think carefully about what your audience (in this case, the social
media team of a major automaker) already knows and prioritize discussing
original analysis that you conducted over general statements about the
automotive industry, for example.

After reading your report, I will use the following guidelines to assess your
work and provide you with developmental feedback. Internalizing these guidelines
will help you develop a report worthy of an exemplary grade.

### Decision-Making Principles (15%)
* Cogent reasoning explains why the set of tweets you are recommending is
likely to succeed.
* Long-term, detrimental implications of not implementing your recommendation 
are argued concretely.
* Hoofbeats are interpreted as signs of horses not [zebras][Sotos 2006].  
* Analytical results provide legitimacy to the recommendation.

### Data (15%)
* The [provenance][Polich and Whitenack 2017] and definitions of the data and
variables being analyzed to make decisions are described [clearly, completely,
and credibly][Zhang and Shaw 2012].
* Convincing reasons explain why certain data are given priority (over others).
* An appropriate variety of data is included in the analysis to inform
decision-making from multiple angles.
* Statements about data limitations are made at appropriate times.

### Methods (25%)
* A breadth and depth of techniques covered in [R for Data Science][Grolemund
and Wickham 2017] are applied [accurately, collaboratively, and
reproducibly][Parker 2017].
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
* All relevant elements of your recommendation are covered in detail.  
* What should be tweeted (i.e., pictures, captions, tags) and when it
should be posted are outlined fully.
* The overall recommendation being proposed is creative (i.e., novel and
useful).
* Goals related to follower engagement and donations are set in [specific,
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
to the company you choose in "the real world," with the goal of persuading its
team to actually implement the recommendation you are advancing. Ask for the
highest realistic level of commitment you can at the end of your presentation,
and try your best to receive her approval during the Q&A period.

After listening to your presentation, your peers and I will use the following
guidelines to assess it and give you developmental feedback. Internalizing these
guidelines will help you deliver a presentation that is worthy of an exemplary
grade.

* The group built a case for its recommendation they proposed with a breadth and
depth of well-principled analyses that motivated me to accept their claims.
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
[Colquitt and George 2011]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-TopicChoice.pdf
[cvillemeals]: https://www.cvillemeals.org/
[Dalio 2017]: https://smile.amazon.com/Principles-Life-Work-Ray-Dalio/dp/1501124021/ref=sr_1_3?ie=UTF8&qid=1522529948&sr=8-3&keywords=principles+ray+dalio
[Donaldson and Walsh 2015]: http://www.sciencedirect.com/science/article/pii/S0191308515000088
[euromonitor]: http://proxy.its.virginia.edu/login?url=http://www.portal.euromonitor.com/portal/server.pt
[facebook]: https://www.facebook.com/
[factiva]: http://proxy1.library.virginia.edu/login?url=https://global.factiva.com/en/sess/login.asp?xsid=S003cbsYXmnNdmnNTamN9apN96s5DByWa3w3DB94cj0WErBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUFBQUEA
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
[Miller 2018]: https://www.nytimes.com/guides/smarterliving/resolution-ideas
[Parker 2017]: https://peerj.com/preprints/3210/
[Parker 2017/06/06]: https://twitter.com/hspter/status/872135582100578304
[Peng 2011]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/
[Peng 2018]: https://simplystatistics.org/posts/2018-09-14-divergent-and-convergent-phases-of-data-analysis/
[Polich and Whitenack 2017]: https://dataskeptic.com/blog/episodes/2017/data-provenance-and-reproducibility-with-pachyderm
[radically open minded]: https://www.inc.com/carmine-gallo/a-self-made-billionaire-reveals-the-1-mental-hurdl.html
[Schwartz 2008]: http://jcs.biologists.org/content/121/11/1771
[Silge and Robinson 2017]: https://www.tidytextmining.com/
[Sotos 2006]: https://en.wikipedia.org/wiki/Zebra_(medicine)
[Sword 2012]: https://smile.amazon.com/Stylish-Academic-Writing-Helen-Sword/dp/0674064488/ref=sr_1_1?s=books&ie=UTF8&qid=1522530104&sr=1-1&keywords=stylish+academic+writing
[statista]: http://proxy01.its.virginia.edu/login?url=https://www.statista.com
[style files]: https://style.tidyverse.org/files.html 
[style pipes]: https://style.tidyverse.org/pipes.html
[style syntax]: https://style.tidyverse.org/syntax.html
[Tidyverse Style Guide]: https://style.tidyverse.org/
[topic choice decision matrix template]: https://github.com/GCOM7140/group-project/blob/master/docs/topic-choice-decision-matrix-template.docx
[twitter]: https://www.twitter.com/
[value model template]: https://github.com/GCOM7140/class-sessions/raw/master/02_group-project-overview/readings/value-model-template.docx
[Zeithaml 1988]: https://www.jstor.org/stable/pdf/1251446.pdf?casa_token=Xa8qdat3R3sAAAAA:UIVbmoYyPjGk0G5lRYUvGjIkQUa0O_-0X109e03kfzy9oeyMjMco37hLxQHMmv3_gQPNrNP63Zjxa3rSS7urFo9WmRBwfjJJENx112_8N9RZr-zdEy85
[Zhang and Shaw 2012]: https://journals.aom.org/doi/10.5465/amj.2012.4001
[business understanding]: https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/lifecycle-business-understanding
