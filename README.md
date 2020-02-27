# The Group Project
## Overview and Objectives
### Project Overview
The primary goal of this group project is to give you an opportunity to apply
the skills you are learning in [R for Data Science][Grolemund and Wickham 2017]
and [Text Mining With R][Silge and Robinson 2017] to the arenas of customer and
text analytics, such that you end up turning numeric and text data into
[significant, actionable, interesting, novel, and broad insights][Colquitt and
George 2011] for [The Juice Laundry][tjl] (TJL), a local Charlottesville
business that is partnering with us for the purposes of this group project.

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
locations, two in Charlottesville, VA, and one in Washington, DC. Founded by UVa
alumni Mike and Sarah Keenan, TJL's mission is "to inspire healthy, organic,
powerful change." In-store signage articulates Mike and Sarah's [value
proposition][] to customers as follows:

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

For this group project, TJL offers a "[lab of sorts][]," somewhere you can talk
with business owners, employees, and customers; analyze data; develop and test
ideas; and, eventually, see the impact of your hard work right in our backyard
[at the AFC][] and [on the Corner][].

### Objectives
Your objectives are twofold: (1) identify an area of TJL's business that is
worth looking into and (2) develop a comprehensive and convincing action plan
that logically flows from what you learn.

#### Topic Identification
While developing a list of potential topics to focus on, we encourage you to be
divergent in your thinking ([Peng 2018][]). Begin today by conducting secondary
research on platforms such as [Business Source Complete], [Euromonitor],
[Factiva], and [IBISWorld]. Then, with a better understanding of the landscape
The Juice Laundry operates in, conduct primary research using online sources,
such as [Elevate], [Instagram], and [Yelp], and personal interviews, which can
occur in TJL's and its competitors' storefronts with their permission so long as
you present yourself as a student doing research for a class project rather than
an employee of The Juice Laundry.

These two modes of research will guide you to challenges that TJL is facing
(e.g., some consumers perceive that TJL offers low [value][Zeithaml 1988]) as
well as promising alternatives that TJL could consider implementing to address
these challenges (e.g., launching an advertising campaign focused on educating
potential customers about the true cost of food).

The datasets we are giving you access to so you can further support your
decision making with [data-informed insights][Parker 2017/06/06] include:

* The [juicelaundry][] R data package, which has point-of-sale transaction
details for all of TJL's locations from October 11, 2016 to January 31, 2020, 
customer survey data, which contains both numeric and text data, and 
customer-supplied reviews posted to Google.
* [Google Trends][] data, which can capture relative search interest and
emerging trends for topics relevant to TJL's business.

While analyzing and communicating insights about these and other datasets, the
key is to describe the [provenance][Polich and Whitenack 2017] of your data
parsimoniously and to define the variables you are analyzing to make decisions
[clearly, completely, and credibly][Zhang and Shaw 2012].

   __Pro tip__: Be [radically open minded]&mdash;and [productively
   stupid][Schwartz 2008]&mdash;during this first step and strive not to let
   confirmation bias contaminate your findings as you make sense of the market
   ([Gallo 2017][]).

   __Pro tip__: Organize your observations into tidy datasets, such as those
   discussed in [Chapter 12][Grolemund and Wickham 2017, 12] of R for Data
   Science so you can summarize them statistically and visually. This process
   will add rigor to your analysis and the insights you generate.

#### Action Plan
Focused on the topic you identify, your next objective is to develop an action
plan covering all relevant elements of the marketing mix in detail (i.e.,
product, price, promotion, and place). Clients need to understand what has to be
done (i.e., by who, when, what, where, why, and how?) before they can accept
your claims and even begin to consider implementing your recommendations. In
order to set expectations, strive to establish goals related to consumers'
attitudes, emotions, and/or actions as well as to TJL's triple bottom line
(i.e., profits, people, and the planet) in [specific, measurable, achievable,
relevant, and time-bound][Miller 2018] ways.

### Scope Considerations
While determining the specific topic you wish to explore and developing a
strategic plan that TJL may wish to pursue, be sure to think about how the
analytical methods you are learning in Customer Analytics and Text Analytics can
be used effectively. You will be getting separate grades for each course so it
is imperative that you demonstrate proper uses of both customer analytics and
text analytics.

There are no firm requirements for the number of techniques/methods you should
be performing as part of your analysis; however; groups are encouraged to
evaluate how they may be able to generate recommendations from analyzing numeric
data, text data, and some combination of both. At a minimum, each group must
generate at least one meaningful recommendation directly from the analysis of
text data. Groups are strongly urged to identify an opportunity to incorporate
the results of a text analysis into a model/procedure that also utilizes other
numeric customer data being provided to you.

## Deliverables
There are three key deliverables for the group project, two of which will be
formally graded:

1. A 1-2 page memo outlining your proposed analytical plan. This memo should
identify the topic that your team will be tackling and offer a high-level
description of how you plan on addressing that topic (which variables and what
methods may be appropriate for uncovering insights that can lead to
recommendations in your final action plan). No grades will be assigned to this
proposal memo yet it does offer a valuable opportunity to get feedback from your
professors on both the scope of your proposed project as well as the analytical
strategy for addressing the challenge. This memo must be submitted via email to
both Prof. Boichuk and Prof. Mauer no later than March 27 at 3:00 pm.

2. A report of no more than 25 pages, 12-point font, double-spaced (excluding references, exhibits, and appendices). We will use the [report
guidelines](#report-guidelines) below to assess your report and give you
developmental feedback. Submit your report along with any scripts used to perform your analyses via email no later than April 22 at
3:00 pm.

3. A presentation of no more than 15 minutes, plus up to 10 minutes of Q&A. An
agenda will guide when groups present. Make sure your final presentation title
gets added to the agenda by submitting it no later than April 16 at 12:30 pm.
Invited guests, your peers, and your professors will use the [presentation
guidelines](#presentation-guidelines) below to assess your presentation and give
you developmental feedback. Submit your slide deck via email to both Prof.
Boichuk and Prof. Maue no later than April 22 at 3:00 pm.

## Grading Breakdown

Your final grade for the project will be determined from both the report and
your presentation. Certain elements of this grade will be consistent across both
courses (Style & Grammar and Presentation Skills) while others may diverge. Your
professors will independently review and evaluate your report and presentation,
giving special attention to the portions of your analysis that relate to the
content covered in each course. They will share their evaluations with each
other and discuss discrepancies, but it is possible that groups may receive
different grades for each class. While the grading categories will be the same
for both courses, there is a possibility that group performance in some
categories may be stronger for analyses aligning with one course as compared to
the other.

The following table summarizes the breakdown of how final project grades will be
determined:

Grading Component          | Percentage of Total Grade|
---------------------------|:------------------------:|
Decision-making principles |	15%                     |
Data                       |	15%                     |
Methods                    |	25%                     |
Action Plan	               |  20%                     |
Report Style & Grammar     |	10%                     |
Presentation skills        |	15%                     |


## Proposal Guidelines
Your proposal should outline your plan for this group project and describe:

1. The topic or primary research question that you plan to focus on 
2. The data (i.e., datasets, rows, and columns) that you plan to analyze.
3. The analytical procedures you believe will be appropriate for developing
insights and recommendations from the data you plan on analyzing.

There is no one "right" way to organize this proposal; however, you should make
sure to outline what you plan to do&mdash;over the four weeks between the date
this proposal is due and the date you present to Mike and Sarah&mdash;very
carefully. While the memo must be concise, it should illustrate that your group
has thought critically, and in a divergent manner, about TJL's business. Your
chosen topic/questions should be logical, significant, actionable, and
interesting.

Regarding the second requirement for the memo, we want to see that you have more
than a surface-level understanding of the [juicelaundry point-of-sale
data][juicelaundry] and [Google Trends data][Google Trends], both of which you
are being trained to analyze. At a minimum, you should have already thought
about some`filter()` and `mutate()` statements that will get these datasets into
the forms you need them in. This is why it is important to not only describe the
topic or questions guiding your analysis but also describe the data you intend
to use. Although not required, it will be exemplary if you propose to reach
data-informed decisions about your chosen topic by way of creating
new-to-the-world tidy datasets. You could supplement the `menu_item` and `sku`
datasets in the juicelaundry package with comparable datasets for a competitor,
such as Corner Juice, for example, if doing so would aid your decision making.

For the third requirement, some questions we want to see you convey answers to
include: how do you plan on analyzing these datasets (i.e., with what methods?),
and what artifacts (e.g., graphics and model estimates) do you plan on
producing?

There is no grade associated with your proposal memo; however, this is an
opportunity to gain valuable feedback on the approach you have devised to
satisfy the project requirements. Your professors will review your proposal memo
in detail and provide feedback meant to guide you toward a high-quality final
deliverable. If appropriate, a meeting may be scheduled to discuss the proposal
in more detail and set your group on a path toward success.

## Report Guidelines

Your report should advocate for a strategic change to TJL's marketing mix. Base
your action plan on the shoulders of (i) a topic with an impressive
[anatomy][Colquitt and George 2011]; (ii) a decision-making process with strong
[principles][Dalio 2017]; (iii) data that are described [clearly, completely,
and credibly][Zhang and Shaw 2012]; (iv) a breadth and depth of analyses that
are applied [accurately, collaboratively, and reproducibly][Parker 2017]; and
(v) [stylish writing][Sword 2012].

Your report should contain the following sections: (1) title page, (2) executive summary, (3) main body (see “Content” above), (4) references, (5) exhibits, and, potentially, (6) appendices. Before you submit your final document, you’ll want to make sure it is as error free as possible, clearly communicated, and professionally designed—i.e., client-ready. Note: Producing client-ready business documents is time consuming. Plan early and revisit often how you will work collaboratively to design, create and deliver your final client documents.

There is no one "right" way to organize the main body of the report; however, you should think
carefully about what your audience (in this case, Mike and Sarah Keenan) already
knows and prioritize discussing original analysis that you have conducted over
general statements about TJL's business, for example. After reading your report,
we will use the following guidelines to assess your work and provide you with
developmental feedback. Internalizing these guidelines will help you develop a
report worthy of an exemplary grade.

### Decision-Making Principles (15%)
* Cogent reasoning explains why the major topic being considered has an
impressive [anatomy][Colquitt and George 2011].
* The long-term, detrimental implications of inaction for The Juice Laundry are
argued concretely.
* The proposed course of action is very well reasoned.

### Data (15%)
* The [provenance][Polich and Whitenack 2017] and definitions of the data and
variables being analyzed to make decisions are described [clearly, completely,
and credibly][Zhang and Shaw 2012].
* Convincing reasons explain why certain data are given priority over others
(e.g., red herrings).
* An appropriate variety of data is included in the analysis to tackle the 
core topic from multiple angles using a mixture of numeric and text data. 
* Statements about data limitations are made at appropriate times.

### Methods (25%)
* A breadth and depth of techniques covered in [R for Data Science][Grolemund
and Wickham 2017] and [Text Mining With R][Silge and Robinson 2017] are applied 
[accurately, collaboratively, and reproducibly][Parker 2017].
* Techniques performed complement one another and create synergies that offer 
deeper insights than the individual analyses may offer independently.
* A knowledgeable individual could [reproduce][Peng 2011] the report's findings
with ease, because the group's submission provides access to not only the
report, but also self-contained, executable code and the data being analyzed.
* Visualizations are used in ways that force the reader to notice [unexpected
phenomena][Grolemund and Wickham 2017, 3.3].
* Hoofbeats are interpreted as signs of horses not [zebras][Sotos 2006].  
* Statements about methodological limitations are made at appropriate times.

### Action Plan (20%)
* All relevant elements of the marketing mix are covered in detail.  
* What needs to be done (i.e., who, when, what, where, why, and how) is
discussed expansively.
* The overall recommendation being proposed is creative (i.e., novel and
useful).
* Recommendations stem from analytical results, thus providing legitimacy to the
action plan.
* Goals related to consumers' attitudes, emotions, and/or actions as well as to
TJL's triple bottom line (i.e., profits, people, and the planet) are set in
[specific, measurable, achievable, relevant, and time-bound][Miller 2018] ways
in order to establish expected results.

### Style \& Grammar (10%)
* The expectations that Prof. Patterson set in Communication&mdash;which
include, but are not limited to, BLUF writing, SAS headings/tables/figures, and
SEC plain English&mdash;are met or exceeded at all times.
* Tables and figures are all formatted properly and [effectively][Grolemund and
Wickham 2017, 28.1].
* Appendices are used appropriately, as needed
* Every sentence is grammatically correct, and all sentences flow together
naturally.
* The report is free of spelling errors.  
* All references adhere to the [HBS Citation Guidelines][] (endnotes, reference list)
* The [Tidyverse Style Guide][] is adhered to at all times in the report's
[files][style files], [syntax][style syntax], and [pipes][style pipes].

## Presentation Guidelines
Your group should prepare your presentation as you would if you were presenting
to Mike and Sarah in "the real world," with the goal of persuading them to
pursue the action plan you are advancing. Ask for the highest realistic level of
commitment you can, and try your best to receive their approval.

After listening to your presentation, invited guests, your peers, and your
professors will use the following guidelines to assess it and give you
developmental feedback. Internalizing these guidelines will help you deliver a
presentation worthy of an exemplary grade (worth 15% of the project grade).

* The group built a case for the action plan they proposed with a breadth and
depth of well-principled analyses that motivated me to accept their claims.
* The group discussed the data they analyzed in a [simple, easy-to-understand
way][Allen 2017].
* The group was captivating, edutaining, and eye-catching, a "[fusion of
scientific rigor with canny attention-grabbing][Allen 2017]."
* The group presented as a team (i.e., their contributions were comparable and
complementary).
* The group's slides were [self-explanatory][Grolemund and Wickham 2017, 28.1],
well referenced, and free of errors.
* The group responded to questions and reservations [appropriately][Jolles
2013].

[agenda]: https://github.com/GCOM7140/group-project/blob/master/agenda.md#customer-analytics-group-project-presentations
[Allen 2017]: https://www.ft.com/content/df4af260-eece-11e6-930f-061b01e23655
[at the AFC]: https://www.thejuicelaundry.com/about/locations/the-afc
[Bradlow, Fader, Yyengar, and Bernman]: https://www.coursera.org/learn/wharton-customer-analytics
[Business Source Complete]: http://proxy.its.virginia.edu/login?url=http://search.ebscohost.com/login.aspx?authtype=ip,uid&profile=ehost&defaultdb=bth
[compostable]: https://www.instagram.com/p/B2TwAjcFoPx/
[Colquitt and George 2011]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-TopicChoice.pdf
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
[Hadley 2017]: https://www.rstudio.com/resources/videos/data-science-in-the-tidyverse/
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
[Zhang and Shaw 2012]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-Crafting.pdf
