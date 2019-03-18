# The Group Project

## Table of Contents
 * [Overview and Objectives](#overview-and-objectives)
 * [Deliverables](#deliverables)
 * [Proposal Guidelines](#proposal-guidelines)
 * [Report Guidelines](#report-guidelines)
 * [Presentation Guidelines](#presentation-guidelines)

### Overview and Objectives

The primary goal of this group project is to give you an opportunity to apply
the skills you are learning in [R for Data Science][Grolemund and Wickham 2017]
to the arena of [customer analytics][Bradlow, Fader, Yyengar, and Bernman], such
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

#### The Juice Laundry

TJL is an organic juice and smoothie bar with three locations, two in
Charlottesville, VA, and one in Washington, DC. Founded by UVa alumni Mike and
Sarah Keenan, TJL's mission is "to inspire healthy, organic, powerful change."
In-store signage articulates Mike and Sarah's value proposition to customers as
follows:

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
business owners, employees, and customers; develop and test ideas; analyze data;
and, eventually, see the impact of your hard work right in our backyard on the
Corner.

#### Objectives
Your objectives are threefold: (1) identify an area of TJL's business that is
worth looking into; (2) make a data-informed and well-principled decision on
what direction TJL should go in; and (3) develop a comprehensive and convincing
action plan that logically flows from what you learn.

##### Topic Identification
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

As is reflected in [Table 1][], Mike and Sarah are interested in topics that
focus on grand challenges, promise to offer actionable insights, and peak their
curiosity. With these priorities in mind, you should be set to engage in the
marketing process and help TJL further achieve a market orientation.

While developing a list of potential topics to focus on, I encourage you to be
divergent in your thinking ([Peng 2018][]). Begin by conducting extensive
research on Elevate, Euromonitor, Factiva, Google Trends, Instagram, Yelp, etc.
This research, which can also occur in TJL's and its competitors' storefronts,
will guide you to challenges that TJL is facing (e.g., some consumers perceive
that TJL offers low [value][Zeithaml 1988]) as well as promising alternatives
that TJL could consider implementing to address these challenges (e.g.,
launching an Instagram campaign focused on educating their followers about the
true cost of food).

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
Table 1. From here, you will arrive at the topic that you believe is most worth
doing further research and reporting on for your group project report and
presentation.

   __Pro tip__: Explain your topics in Table 1 clearly, so that Mike and Sarah
   will be able to fully appreciate: (a) the challenges your topics are focused
   on overcoming and (b) the alternatives your research has led you to consider.

#### Decision
Focused on the topic you identify, develop a [value model][Johnson 2018]

The data sets we'll cover in class for this purpose include the following:

* The [juicelaundry][] R data package that has transaction information for all
of TJL's locations from October 11, 2016 to December 31, 2018.
* [Google Trends][] - search interest data for topics relevant to The Juice
Laundry.

### Deliverables

There are three key deliverables for the group project:

1. A proposal of no more than 25 pages. I will use the [proposal
guidelines](#proposal-guidelines) below to assess your proposal and give you
developmental feedback. Submit your proposal via GitHub no later than March 28
at 11:59 pm.

2. A report of no more than 50 pages. I will use the [report
guidelines](#report-guidelines) below to assess your report and give you
developmental feedback. Submit your report via GitHub no later than April 25 at
12:30 pm.

3. A presentation of no more than 12 minutes, plus up to eight minutes of Q&A.
Invited guests, your peers, and I will use the [presentation
guidelines](#presentation-guidelines) below to assess your presentation and give
you developmental feedback. This [agenda][] will guide when groups present. Add
your *final* presentation title to the [agenda][] via this Google Sheet no later
than April 18 at 12:30 pm. Submit your slide deck via GitHub no later than April
25 at 12:30 pm.

### Proposal Guidelines

Your proposal should outline your plan for this group project and describe in
detail:

1. The topic you plan to focus on and the process you engaged in to find it.
2. The data (i.e., datasets, rows, and columns) you to plan to analyze.
3. The visualizations and models you plan to create and estimate in order to
turn the data you plan to analyze into market intelligence.
4. The processes and procedures you have developed as a group to ensure that
your work is [collaborative, accurate, and reproducible][Parker 2017].

There is no one "right" way to organize this proposal; however, you should make
sure to outline what you plan to do&mdash;over the four weeks between the date
this proposal is due and the date you present to Mike and Sarah&mdash;very
carefully. I want to see evidence of you thinking critically, and in a divergent
manner, about TJL's business. What should TJL's top research priority be, and
why? What makes this topic significant, actionable, and interesting? These are
but two of the questions your proposal should address to touch on the first
point above.

Regarding the second point, show me that you have more than a surface-level
understanding of the [juicelaundry point-of-sale data][juicelaundry] and the
[Google Trends data][Google Trends], both of which you are being trained to
analyze. At a minimum, you should highlight some `filter()` and `mutate()`
statements that will get these datasets into the forms you need them in. In a
best-case scenario, you will not only advance a detailed proposal about how you
plan to utilize these datasets fully, but also propose to supplement the scope
of your analyses with additional secondary datasets (think weather data, for
example). It will also be outstanding if you propose to reach data-informed
decisions about your chosen topic by way of creating new-to-the-world tidy
datasets. You could supplement the `menu_item` and `sku` datasets in the
juicelaundry package with comparable datasets for a competitor, such as Corner
Juice, for example, if doing so will aid your decision making.

For the third point, questions I want to see you address include: how do you
plan on analyzing these datasets (i.e., with what methods?), and what artifacts
(e.g., graphics and model estimates) do you plan on producing? For the fourth,
be specific about the systems your group has agreed to put in place to increase
the chances that you will develop analyses for this project in a [collaborative,
accurate, and reproducible][[Parker 2017]] manner.

On April 1, I will meet with each team for 30 minutes between the times of 11:00
am and 2:30 pm in RRH 203. The purpose of these meetings will be to discuss your
progress and help you create some momentum going into the final month.

### Report Guidelines

Your report should advocate for strategic change to The Juice Laundry's
marketing mix. Base your action plan on the shoulders of (i) a topic with an
impressive [anatomy][Colquitt and George 2011]; (ii) a decision-making process
with strong [principles][Dalio 2017]; (iii) data that are described [clearly,
completely, and credibly][Zhang and Shaw 2012]; (iv) a breadth and depth of
analyses that are applied [accurately, collaboratively, and reproducibly][Parker
2017]; and (v) [stylish writing][Sword 2012].

There is no one "right" way to organize this report; however, you should think
carefully about what your audience (in this case, Mike and Sarah Keenan) already
knows and prioritize discussing original analysis that you have conducted over
general statements about TJL's business, for example. After reading your report,
I will use the following guidelines to assess your work and provide you with
developmental feedback. Internalizing these guidelines will help you develop a
report worthy of an exemplary grade.

#### Decision-Making Principles (20%)
* Cogent reasoning explains why the major decision being considered has an
impressive [anatomy][Colquitt and George 2011].
* The long-term, detrimental implications of inaction for The Juice Laundry are
argued concretely.
* Alternative courses of action are identified in a balanced, convincing manner.
* Decision criteria relevant to the major decision at hand are defined and
ranked cogently.
* The proposed course of action is very well reasoned, because said decision
criteria are used to evaluate the alternatives rigorously.

#### Data (20%)
* The [provenance][Polich and Whitenack 2017] and definitions of the data and
variables being analyzed to make decisions are described [clearly, completely,
and credibly][Zhang and Shaw 2012].
* Convincing reasons explain why certain data are given priority over others
(e.g., red herrings).
* Statements about data limitations are made at appropriate times.

#### Method (20%)
* A breadth and depth of techniques covered in [R for Data Science][Grolemund
and Wickham 2017] are applied [accurately, collaboratively, and
reproducibly][Parker 2017].
* A knowledgeable individual could [reproduce][Peng 2011] the report's findings
with ease, because the group's GitHub repository provides access to not only the
report, but also self-contained, executable code and the data being analyzed.
* Visualizations are used in ways that force the reader to notice [unexpected
phenomena][Grolemund and Wickham 2017, 3.3].
* Hoofbeats are interpreted as signs of horses not [zebras][Sotos 2006].  
* Statements about methodological limitations are made at appropriate times.

#### Action Plan (20%)
* All relevant elements of the marketing mix are covered in detail.  
* What needs to be done (i.e., who, when, what, where, why, and how) is
discussed expansively.
* The overall recommendation being proposed is creative (i.e., novel and
useful).
* Goals related to consumers' attitudes, emotions, and actions as well as to
TJL's triple bottom line (i.e., profits, people, and the planet) are set in
[specific, measurable, achievable, relevant, and time-bound][Miller 2018] ways
in order to establish expected results.

#### Style \& Grammar (20%)
* The expectations that Prof. Patterson set in Communication&mdash;which
include, but are not limited to, BLUF writing, SAS headings/tables/figures, and
SEC plain English&mdash;are met or exceeded at all times.
* Tables and figures are all formatted properly and [effectively][Grolemund and
Wickham 2017, 28.1].
* Every sentence is grammatically correct, and all sentences flow together
naturally.
* The report is free of spelling errors.  
* The [*Journal of Marketing Research* Style Guide][JMR] is adhered to at
all times.
* The [Tidyverse Style Guide][] is adhered to at all times in the report's
[files][style files], [syntax][style syntax], and [pipes][style pipes].

### Presentation Guidelines

Your group should prepare your presentation as you would if you were presenting
to Mike and Sarah in "the real world," with the goal of persuading them to
pursue the action plan you are advancing. Ask for the highest realistic level of
commitment you can, and try your best to be granted their approval.

After listening to your presentation, invited guests, your peers, and I will use
the following guidelines to assess it and give you developmental feedback.
Internalizing these guidelines will help you deliver a presentation worthy of an
exemplary grade.

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
[comScore]: https://auth2.comscore.com/
[Dalio 2017]: https://smile.amazon.com/Principles-Life-Work-Ray-Dalio/dp/1501124021/ref=sr_1_3?ie=UTF8&qid=1522529948&sr=8-3&keywords=principles+ray+dalio
[Dhakad et al. 2018]: https://github.com/GCOM7140/group-project/blob/master/agenda.md#invited-guests
[Donaldson and Walsh 2015]: http://www.sciencedirect.com/science/article/pii/S0191308515000088
[Euromonitor Passport]: http://proxy.its.virginia.edu/login?url=http://www.portal.euromonitor.com/portal/server.pt
[Gallo 2017]:https://www.inc.com/carmine-gallo/a-self-made-billionaire-reveals-the-1-mental-hurdl.html
[Google Trends]: https://trends.google.com/trends/
[Grolemund and Wickham 2017]: http://r4ds.had.co.nz
[Grolemund and Wickham 2017, 3.3]: http://r4ds.had.co.nz/data-visualisation.html#aesthetic-mappings
[Grolemund and Wickham 2017, 12]: https://r4ds.had.co.nz/tidy-data.html
[Grolemund and Wickham 2017, 28.1]: http://r4ds.had.co.nz/graphics-for-communication.html
[Hadley 2017]: https://www.rstudio.com/resources/videos/data-science-in-the-tidyverse/
[Jaworski and Kohli 1993]: https://bear.warrington.ufl.edu/weitz/mar7786/articles/jaworski%20and%20kohli.pdf
[Johnson 2018]: https://nyti.ms/2C558Py
[Jolles 2013]: http://www.amanet.org/training/articles/i-object-four-steps-to-handling-objections.aspx
[JMR]: https://www.ama.org/publications/JournalOfMarketingResearch/Pages/JMRSubmissionGuidelines.aspx
[juicelaundry]: https://github.com/GCOM7140/juicelaundry#juicelaundry
[Miller 2018]: https://www.nytimes.com/guides/smarterliving/resolution-ideas
[Parker 2017]: https://peerj.com/preprints/3210/
[Parker 2017/06/06]: https://twitter.com/hspter/status/872135582100578304
[Peng 2011]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3383002/
[Peng 2018]: https://simplystatistics.org/2018/09/14/divergent-and-convergent-phases-of-data-analysis/
[Polich and Whitenack 2017]: https://dataskeptic.com/blog/episodes/2017/data-provenance-and-reproducibility-with-pachyderm
[Schwartz 2008]: http://jcs.biologists.org/content/121/11/1771
[Sotos 2006]: https://en.wikipedia.org/wiki/Zebra_(medicine)
[Sword 2012]: https://smile.amazon.com/Stylish-Academic-Writing-Helen-Sword/dp/0674064488/ref=sr_1_1?s=books&ie=UTF8&qid=1522530104&sr=1-1&keywords=stylish+academic+writing
[style files]: https://style.tidyverse.org/files.html 
[style pipes]: https://style.tidyverse.org/pipes.html
[style syntax]: https://style.tidyverse.org/syntax.html
[Table 1]: https://github.com/GCOM7140/class-sessions/raw/master/02_group-project-overview/01_readings/table-1-topic-choice-decision-matrix-template.docx
[Tidyverse Style Guide]: https://style.tidyverse.org/
[tjl]: https://www.thejuicelaundry.com/
[Zhang and Shaw 2012]: https://aom.org/uploadedFiles/Publications/AMJ/FTE-Crafting.pdf
