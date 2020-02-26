# The Group Project
## Overview and Objectives
### Project Overview
The primary goal of this group project is to give you an opportunity to apply
the skills you are learning in [R for Data Science][Grolemund and Wickham 2017]
and [Text Mining With R][Silge and Robinson 2017] to the arena of [customer analytics][Bradlow, Fader, Yyengar, and Bernman], such
that you end up turning consumer/customer data into [significant, actionable,
interesting, novel, and broad insights][Colquitt and George 2011] for [The Juice
Laundry][tjl] (TJL), a local Charlottesville business that is partnering with us
for the purposes of this group project.

The more you engage in [this process of data science][Hadley 2017], the better
you will be at [generating, disseminating, and responding][Jaworski and Kohli
1993] to market intelligence. Improving your ability to perform these three core
activities will in turn allow you to help companies&mdash;especially those you
want to work for&mdash;achieve a market orientation and optimize collective
value. After all, optimizing collective value (i.e., prosperity) is arguably why
society engages in commerce and, as a result, customer analytics in the first
place ([Donaldson and Walsh 2015][]).

### Company Overview
As a brief summary, TJL is an organic juice and smoothie bar with three
locations, two in Charlottesville, VA, and one in Washington, DC. Founded by UVa
alumni Mike and Sarah Keenan, TJL's mission is "to inspire healthy, organic,
powerful change." In-store signage articulates Mike and Sarah's value
proposition to customers as follows:

> The Juice Laundry was founded on the concept of keeping our bodies clean and
healthy, starting with what we put into them. Raw, organic fruits and veggies
are nature's medicine and the foundation of preventative health care. Whether
juiced, blended, or eaten whole, fresh produce is full of life-giving nutrients
and enzymes. We choose to use 100% organic ingredients, 100% of the time,
because the phrase 'organic whenever possible' is often highly misleading. If we
can't find something organic on a given day, it won't be on our menu. That's our
commitment to you, and to your health.

Elsewhere in TJL's locations, the brand's slogan "Clean Your Machine" is
displayed prominently, as are the brand's defining principles: "We are Raw. We
are Fresh. We are Clean. We are Organic. We are Curious. We are Passionate. We
are Transparent. We Leave a Gentle Footprint." Missing in stores, however, are
trash cans, as 100% of TJL's packaging is either compostable or reusable.

For this group project, TJL offers a lab of sorts, somewhere you can talk with
business owners, employees, and customers; analyze data; develop and test ideas;
and, eventually, see the impact of your hard work right in our backyard on the
Corner.

### Objectives
Your objectives are threefold: (1) identify an area of TJL's business that is
worth looking into; (2) evaluate three directions that TJL could go in in this
respect; and (3) develop a comprehensive and convincing action plan that
logically flows from what you learn.

#### Topic Identification
In line with [Colquitt and George (2011)][Colquitt and George 2011], you should
strive to identify and address a topic that:

* __Takes on a grand challenge__ (i.e., has a compelling raison d'être)
   + By aiming to solve a piece of a larger societal puzzle and, thus, having a
   compelling purpose (e.g., encouraging healthier eating habits, making
   commerce more sustainable).
* __Changes the conversation__
   + By exploring the potential of a bold idea that could lead TJL in an
   unfamiliar, nascent, and radically different direction.
* __Catches and holds Mike and Sarah's attention__
   + By challenging their taken-for-granted assumptions and solving a mystery
   you uncover that has multiple plausible endings and cannot be guessed.
* __Casts a wide net__
   + By covering the landscape of your topic adequately and, thus, considering a
   multitude of outcome variables (including potential unintended consequences),
   boundary conditions, and explanations.
* __Offers insights for practice__
   + By estimating the potential effect of a new and important practice and
   conveying findings that Mike and Sarah will be able to act on in the near
   term.

As is reflected in [this document][topic choice decision matrix template], Mike
and Sarah are interested in topics that focus on grand challenges, promise to
offer actionable insights, and peak their curiosity. With these priorities in
mind, you should be positoned to engage in the marketing process and help TJL
further achieve a market orientation.

While developing a list of potential topics to focus on, I encourage you to be
divergent in your thinking ([Peng 2018][]). Begin by conducting extensive
research on [Elevate], [Euromonitor], [Factiva], [Google Trends], [Instagram],
[Yelp], etc. This research, which can also occur in TJL's and its competitors'
storefronts, will guide you to challenges that TJL is facing (e.g., some
consumers perceive that TJL offers low [value][Zeithaml 1988]) as well as
promising alternatives that TJL could consider implementing to address these
challenges (e.g., launching an Instagram campaign focused on educating their
followers about the true cost of food).

   __Pro tip__: Be radically open minded&mdash;and [productively
   stupid][Schwartz 2008]&mdash;during this first step and strive not to let
   confirmation bias contaminate your findings as you make sense of the market
   ([Gallo 2017][]).

   __Pro tip__: Organize your observations into tidy datasets, such as those
   discussed in [Chapter 12][Grolemund and Wickham 2017, 12] of R for Data
   Science so you can summarize them statistically and visually. This process
   will add rigor to your analysis and the insights you generate.

Sort the challenges stemming from your research into buckets full of
alternatives. Then, use the prioritization framework that [Colquitt and George
(2011)][Colquitt and George 2011] offer to select the three challenges (i.e.,
"topics") you believe are most worth looking into and highlight these topics in
a [topic choice decision matrix][topic choice decision matrix template]. From
here, you will arrive at the topic that you believe is most worth doing further
research and reporting on for your group project report and presentation.

   __Pro tip__: Explain your topics clearly, so that Mike and Sarah will be able
   to fully appreciate: (a) the challenges your topics are focused on overcoming
   and (b) the alternatives your research has led you to consider.

#### Alternative Evaluation
Focused on the topic you identify, your next objective is to, in a concise and
well-balanced manner, explain three fundamentally different strategic directions
that TJL could go in. Further, you should arrive at and implement a set of
criteria that you believe Mike and Sarah should use to make decisions of this
sort.

Taken together, these two components (alternatives and criteria) will allow you
to employ a [value model][Johnson 2018] for decision-making purposes. You might
find it helpful to structure your value model using [this template][value model
template]. Overall, the goal is to evaluate a set of well-balanced alternatives
with a ranked set of relevant decision criteria in order to propose a course of
action in a convincing manner.

On this point, you should strive to explain your alternatives clearly and define
your criteria well, so that the scores you assign to the alternatives in your
value model will seem logical. In other words, try to increase the chances that
separate people (namely, your group, peers, me, Mike, and Sarah) will more or
less agree on the scores you assign to given alternative-criterion pairs and,
thus, the logic underlying your strategic recommendation by explaining your
alternatives clearly and defining your criteria cogently.

The datasets we will cover in class to help you support your decision making
with [data-informed insights][Parker 2017/06/06] include:

* The [juicelaundry][] R data package, which has point-of-sale transaction
details for all of TJL's locations from October 11, 2016 to December 31, 2018.
* [Google Trends][] data, which can capture relative search interest and
emerging trends for topics relevant to TJL's business.

While analyzing and communicating insights about these and other datasets, the
key is to describe the [provenance][Polich and Whitenack 2017] of your data
parsimoniously and to define the variables you are analyzing to make decisions
[clearly, completely, and credibly][Zhang and Shaw 2012].

#### Action Plan
Having made your decision, your final objective is to develop an action plan
covering all relevant elements of the marketing mix in detail (i.e., product,
price, promotion, and place). Clients need to understand what has to be done
(i.e., by who, when, what, where, why, and how?) before they can accept your
claims and even begin to consider implementing your recommendations. In order to
set expectations, strive to establish goals related to consumers' attitudes,
emotions, and/or actions as well as to TJL's triple bottom line (i.e., profits,
people, and the planet) in [specific, measurable, achievable, relevant, and
time-bound][Miller 2018] ways.

## Deliverables
There are three key deliverables for the group project, two of which will be formally graded:

1. A 1-2 page memo outlining your proposed analytical plan.  This memo should identify
the grand challenge that your team will be tackling and offer a high level description
of how you plan on addressing that grand challenge (which variables and what methods
may be appropriate for uncovering insights that can lead to recommendations in your
final action plan).  No grades will be assigned to this proposal memo yet it will 
offer a valuable opportunity to get feedback from your professors on both the 
scope of your proposed project as well as the analytical strategy for addressing
the challenge.  This memo must be submitted via GitHub no later than March 27 at 3:00 pm.

2. A report of no more than 25 pages, using the stylistic requirements outlined
in the _Journal of Marketing Research_ Style Guide for formatting purposes (see
[here][jmr 1] and [here][jmr 2] for details). I will use the [report
guidelines](#report-guidelines) below to assess your report and give you
developmental feedback. Submit your report via GitHub no later than April 23 at
12:30 pm.

3. A presentation of no more than 15 minutes, plus up to 10 minutes of Q&A.
An agenda will guide when groups present. Make sure your final presentation
title gets added to this agenda by submitting it no later than April 18 at 12:30
pm. Invited guests, your peers, and I will use the [presentation
guidelines](#presentation-guidelines) below to assess your presentation and give
you developmental feedback. Submit your slide deck via GitHub no later than
April 23 at 12:30 pm.

## Grading Breakdown

Your final grade for the project will be determined from both the report and 
your presentation.  Certain elements of this grade will be consistent across both 
courses (Style & Grammar and Presentation Skills) while others may diverge. Your 
professors will independently review and evaluate your report and presentation, 
with special attention to the portions of the analysis that relate to the content 
covered in each course.  They will share their evaluations with each other and 
discuss discrepancies, but it is possible that groups may receive different grades
for each class.  While the grading categories will be the same for both courses, 
there is a possibility that group performance in some categories may be stronger 
for analyses aligning with one course as compared to the other.

The following table summarizes the breakdown of final project grades

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
3. The analytical procedures you believe will be appropriate in developing
insights and recommendations from the data you plan on analyzing.


There is no one "right" way to organize this proposal; however, you should make
sure to outline what you plan to do&mdash;over the four weeks between the date
this proposal is due and the date you present to Mike and Sarah&mdash;very
carefully. While the memo must be concise, it should illustrate that your group
has thought critically, and in a divergent manner,  about the TJL's business. 
Your chosen topic/questions should be logical, significant, actionable, and 
interesting.

Regarding the second requirement for the memo, I want to see that you have more than a
surface-level understanding of the [juicelaundry point-of-sale
data][juicelaundry] and [Google Trends data][Google Trends], both of which
you are being trained to analyze. At a minimum, you should have already thought 
about some`filter()` and `mutate()` statements that will get these datasets into 
the forms you need them in. This is why it is important to not only describe the 
topic or questions guiding your analysis but also describe the data you intend to
use. Although not required, it will be exemplary if you propose to reach
data-informed decisions about your chosen topic by way of creating
new-to-the-world tidy datasets. You could supplement the `menu_item` and `sku`
datasets in the juicelaundry package with comparable datasets for a competitor,
such as Corner Juice, for example, if doing so would aid your decision making.

For the third point, some questions I want to see you convey answers to include:
how do you plan on analyzing these datasets (i.e., with what methods?), and what
artifacts (e.g., graphics and model estimates) do you plan on producing? 

There is no grade associated with your proposal memo, however this is an opportunity
to gain valuable feedback on your approach to satisfying the project requirements.
Your professors will review each proposal memo in detail and will provide feedback
meant to guide you toward a high-quality final deliverable.  If appropriate, a
meeting may be scheduled to discuss the proposal in more detail and set your group
on a path toward success.

## Report Guidelines

Your report should advocate for strategic change to TJL's marketing mix. Base
your action plan on the shoulders of (i) a topic with an impressive
[anatomy][Colquitt and George 2011]; (ii) a decision-making process with strong
[principles][Dalio 2017]; (iii) data that are described [clearly, completely,
and credibly][Zhang and Shaw 2012]; (iv) a breadth and depth of analyses that
are applied [accurately, collaboratively, and reproducibly][Parker 2017]; and
(v) [stylish writing][Sword 2012].

There is no one "right" way to organize this report; however, you should think
carefully about what your audience (in this case, Mike and Sarah Keenan) already
knows and prioritize discussing original analysis that you have conducted over
general statements about TJL's business, for example. After reading your report,
I will use the following guidelines to assess your work and provide you with
developmental feedback. Internalizing these guidelines will help you develop a
report worthy of an exemplary grade.

### Decision-Making Principles (15%)
* Cogent reasoning explains why the major decision being considered has an
impressive [anatomy][Colquitt and George 2011].
* The long-term, detrimental implications of inaction for The Juice Laundry are
argued concretely.
* Decision criteria relevant to the major decision at hand are defined and
ranked cogently.
* The proposed course of action is very well reasoned

### Data (15%)
* The [provenance][Polich and Whitenack 2017] and definitions of the data and
variables being analyzed to make decisions are described [clearly, completely,
and credibly][Zhang and Shaw 2012].
* Convincing reasons explain why certain data are given priority over others
(e.g., red herrings).
* Statements about data limitations are made at appropriate times.

### Methods (25%)
* A breadth and depth of techniques covered in [R for Data Science][Grolemund
and Wickham 2017] and [Text Mining With R][Silge and Robinson 2017] are applied 
[accurately, collaboratively, and reproducibly][Parker 2017].
* Techniques performed complement one another and create synergies that offer 
deeper insights than the individual analyses may offer independently.
* A knowledgeable individual could [reproduce][Peng 2011] the report's findings
with ease, because the group's GitHub repository provides access to not only the
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
action plan
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
* Every sentence is grammatically correct, and all sentences flow together
naturally.
* The report is free of spelling errors.  
* The *Journal of Marketing Research* Style Guide is adhered to at
all times (see [here][jmr 1] and [here][jmr 2] for details).
* The [Tidyverse Style Guide][] is adhered to at all times in the report's
[files][style files], [syntax][style syntax], and [pipes][style pipes].

## Presentation Guidelines
Your group should prepare your presentation as you would if you were presenting
to Mike and Sarah in "the real world," with the goal of persuading them to
pursue the action plan you are advancing. Ask for the highest realistic level of
commitment you can, and try your best to receive their approval.

After listening to your presentation, invited guests, your peers, and I will use
the following guidelines to assess it and give you developmental feedback.
Internalizing these guidelines will help you deliver a presentation worthy of an
exemplary grade (15% of the project grade).

* The group discussed the data they analyzed in a [simple, easy-to-understand
way][Allen 2017].
* The group built a case for the action plan they proposed with a breadth and
depth of well-principled analyses that motivated me to accept their claims.
* The group was captivating, edutaining, and eye-catching, a "[fusion of
scientific rigor with canny attention-grabbing][Allen 2017]."
* The group responded to questions and reservations [appropriately][Jolles
2013].
* The group presented as a team (i.e., their contributions were comparable and
complementary).
* The group's slides were [self-explanatory][Grolemund and Wickham 2017, 28.1],
well referenced, and free of errors.

[agenda]: https://github.com/GCOM7140/group-project/blob/master/agenda.md#customer-analytics-group-project-presentations
[Allen 2017]: https://www.ft.com/content/df4af260-eece-11e6-930f-061b01e23655
[Bradlow, Fader, Yyengar, and Bernman]: https://www.coursera.org/learn/wharton-customer-analytics
[Colquitt and George 2011]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-TopicChoice.pdf
[Dalio 2017]: https://smile.amazon.com/Principles-Life-Work-Ray-Dalio/dp/1501124021/ref=sr_1_3?ie=UTF8&qid=1522529948&sr=8-3&keywords=principles+ray+dalio
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
[instagram]: https://www.instagram.com/
[Jaworski and Kohli 1993]: https://pdfs.semanticscholar.org/82e7/864936822e1c97d5ebc9996fab705defcfdb.pdf
[Johnson 2018]: https://nyti.ms/2C558Py
[Jolles 2013]: http://www.amanet.org/training/articles/i-object-four-steps-to-handling-objections.aspx
[jmr 1]: https://auth.ama.org/publications/JournalOfMarketingResearch/Pages/JMRSubmissionGuidelines.aspx
[jmr 2]: https://auth.ama.org/publications/JournalOfMarketingResearch/Pages/JMR_Accepted_Ms.aspx
[juicelaundry]: https://github.com/GCOM7140/juicelaundry#juicelaundry
[Miller 2018]: https://www.nytimes.com/guides/smarterliving/resolution-ideas
[Parker 2017]: https://peerj.com/preprints/3210/
[Parker 2017/06/06]: https://twitter.com/hspter/status/872135582100578304
[Peng 2011]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/
[Peng 2018]: https://simplystatistics.org/2018/09/14/divergent-and-convergent-phases-of-data-analysis/
[Polich and Whitenack 2017]: https://dataskeptic.com/blog/episodes/2017/data-provenance-and-reproducibility-with-pachyderm
[Schwartz 2008]: http://jcs.biologists.org/content/121/11/1771
[Silge and Robinson 2017]: https://www.tidytextmining.com/
[Sotos 2006]: https://en.wikipedia.org/wiki/Zebra_(medicine)
[Sword 2012]: https://smile.amazon.com/Stylish-Academic-Writing-Helen-Sword/dp/0674064488/ref=sr_1_1?s=books&ie=UTF8&qid=1522530104&sr=1-1&keywords=stylish+academic+writing
[style files]: https://style.tidyverse.org/files.html 
[style pipes]: https://style.tidyverse.org/pipes.html
[style syntax]: https://style.tidyverse.org/syntax.html
[Tidyverse Style Guide]: https://style.tidyverse.org/
[tjl]: https://www.thejuicelaundry.com/
[topic choice decision matrix template]: https://github.com/GCOM7140/group-project/blob/master/docs/topic-choice-decision-matrix-template.docx
[value model template]: https://github.com/GCOM7140/class-sessions/raw/master/02_group-project-overview/readings/value-model-template.docx
[yelp]: https://www.yelp.com/
[Zeithaml 1988]: https://www.jstor.org/stable/pdf/1251446.pdf?casa_token=Xa8qdat3R3sAAAAA:UIVbmoYyPjGk0G5lRYUvGjIkQUa0O_-0X109e03kfzy9oeyMjMco37hLxQHMmv3_gQPNrNP63Zjxa3rSS7urFo9WmRBwfjJJENx112_8N9RZr-zdEy85
[Zhang and Shaw 2012]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-Crafting.pdf
