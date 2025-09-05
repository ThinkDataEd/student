#Introduction to Data Science: Overview

##**Course Overview**

###**Goals**

Introduction to Data Science (IDS) is designed to introduce you - through hands-on activities - to the exciting opportunities available at the intersection of data analysis, computing, and mathematics. Data are
everywhere, and this curriculum will help prepare you to live in a world of data. The curriculum
focuses on practical applications of data analysis to give you concrete and applicable skills. Instead
of using small, tailored, curated data sets as in a traditional statistics curriculum, this curriculum engages
you in the wider world of data that fall into the "Big Data" that are relevant to your life. In contrast to the traditional formula-based approach, in IDS statistical inference is taught
algorithmically, using modern randomization and simulation techniques. You will learn to find and
communicate meaning in data, and to think critically about arguments based on data.

###**Standards**

The standards used for the IDS curriculum are based on the High School Probability and Statistics
Mathematics Common Core State Standards **(CCSS-M)** and the Standards for Mathematical
Practice **(SMP)**. Standards addressed are outlined in detail in the Scope and Sequence section. The Computer
Science Teacher’s Association **(CSTA)** K-12 Computer Science Standards were also consulted and
incorporated. Applied Computational Thinking Standards **(ACT)** outline the application of Data Science
concepts using technology.

###**Hardware**

An ideal laboratory environment has a 1:1 computer-to-student ratio. Your computer can be Apple,
PC, or Chromebook, depending upon availability. Internet access is required for the use of RStudio on an
external server.

###**Software**

Ideally, your computer should have a modern, updated web browser installed (such as Firefox
or Google Chrome). This will allow you to access RStudio from an external server, and to perform
searches and make use of a variety of websites and Internet tools. RStudio is available at
[https://tools.thinkdataed.org](https://tools.thinkdataed.org "https://tools.thinkdataed.org"). The IDS team will provide the remainder of the software used in the IDS curriculum, available at [https://tools.thinkdataed.org](https://tools.thinkdataed.org "https://tools.thinkdataed.org"). This software includes the [IDS app](download/app.md), which is deployed for [Android](https://play.google.com/store/apps/details?id=org.thinkdataed.app.survey) and [iOS](https://apps.apple.com/us/app/ids-thinkdata-ed/id6746621731) smartphones and
tablets, as well as through the web browser on a desktop or laptop computer. The app allows you to
collect the Participatory Sensing data that is a motivational foundation for the course. In addition to the
app, you will use the IDS software to access and manipulate their Participatory Sensing data and to
author your own campaigns.

###**Prerequisites**

It is recommended that you successfully complete a first-year Algebra course prior to taking IDS. This will provide you with the background you'll need to learn about data science and statistics through this challenging and innovative curriculum. No previous statistics or computer science courses are required to take this course.

###**Assignments & Homework**

IDS work will take place as much as possible during class time. Lessons are designed for a 50-60 minute
class period. Classes on block schedule will need to complete two lessons; however, the teacher will decide where to stop in each lesson. You will be given computer-based assignments to be completed during class time, as well as open-ended assignments to be completed on your own. If you miss lab time, you will need to find a time to complete the assignment outside of class. As discussed in the software section above, you can use an Internet-enabled computer to do make-up work.

You will be expected to have both a calculator and your Data Science (IDS) Journal - a notebook where you will record your notes, work on small assignments, and sketch plots - on hand daily. Teachers may choose to check IDS journals and other assignments in the curriculum for credit. You will also be assigned oral presentations, Practicums, and End of Unit Projects.

##**Overview of Instructional Topics**

The purpose of IDS is to introduce you to something called "dynamic data analysis". The four major components of this
curriculum are based on the following standards, the Common Core State Standards High School - Statistics and Probability, which are explained in greater detail below:

<ul style="list-style-type:none">
	<b><li>I. Interpreting Categorical and Quantitative Data</li></b>
    <b><li>II. Making Inferences and Justifying Conclusions</li></b>
    <b><li>III. Conditional Probability and the Rules of Probability</li></b>
    <b><li>IV. Using Probability to Make Decisions</li></b>
</ul>

IDS will emphasize the use of statistics and computation as tools for creative work, and as a means of
telling stories with data. Seen in this way, its content will also prepare you to "read" and think
critically about existing data stories. Ultimately, this course will be about how we discern good stories
from bad through a practice that involves compiling evidence from one or more sources, a process which often
requires hands-on examination of one or more data sets.

Through IDS you will learn about tools, techniques, and principles for reasoning about the world with data. It will
present a process that is iterative and authentically inquiry-based, comparing multiple "views" of one or
more data sets. These views are the result of some kind of computation, producing numerical
summaries or graphical displays, the interpretation of which relies on a special kind of computation known as
"simulation" to describe the uncertainty in each view. This kind of reasoning is exploratory and
investigatory, sometimes framed as hypothesis evaluation, and sometimes as hypothesis generation.

###**Interpreting Categorical and Quantitative Data**

A handful of data interpretations are standard. Some, including summaries of shape, center, and spread
of one or more variables in a data set - as well as graphical displays like histograms and scatterplots - are
standard in the sense that they provide interpretable information in a number of research contexts. They
are portable from one set of data to the next, and the rules for their use are simple; and yet our
interpretation of data is rarely “standard.” Data have no natural look - even a spreadsheet or a table of
numbers embeds within it a certain representational strategy. We construct multiple views of data in an
attempt to uncover stories about the world.

In addition to numerical data, this course will consider time, location, text, and image as data types, and
will examine views that uncover patterns or stories. Throughout the course, simulation will be used to
calibrate our interpretation of a view, or of a numerical or graphical summary, so that we understand what
“story-less” data (i.e., pure noise, no association) look like.

In addition to summaries and simple graphics, you will engage in a modeling practice aligned with
the CCSS mathematical practices in order to learn how statistical analyses can explain and describe real-world
phenomena. You will practice fitting and evaluating standard mathematical and statistical
models, such as the least-squares regression line, and you will learn the concept of modeling as you design and implement probabilistic simulations in order to test and compare hypothetical chance processes to real-world data.

###**Making Inferences and Justifying Conclusions**

Data are becoming increasingly plentiful, supported by a host of new "publication" techniques or services.
Post-Web 2.0, data are interoperable (they flow out of one service and into another), helping us easily build
a detailed data version of many phenomena in the world. Reasoning with data, then, starts with the
sources and the mechanics of this flow. Which sources do we trust? How do data from different
organizations compare? What stories have been told previously with these data, and by whom?

This course answers these questions, in part, by using the tools and techniques already mentioned. The
ability to read and critique published stories and visualizations are additions to these tools and
techniques. Finally, you will also learn to formulate questions, identify existing data sets, and evaluate how the new stories stack up against the old. To support this cycle of inquiry, you will examine the basic publication mechanisms for data and develop a set of questions to ask of any data source - computation meets critical thinking. In some cases, data will exhibit special structures that can be used to aid in inference. The simulation techniques for calibrating different views of
a data set take on new life when some form of random process was followed to generate the data. Polls,
for example, rely on random samples of the population, and clinical trials randomly assign patients to
treatment and control groups. A simulation strategy that repeats these random mechanisms can be used
to assess uncertainty in the data, assigning a margin of error to poll results, or identifying new drugs that
have a "significant" effect on some health outcome.

In many cases, data will not possess this kind of special origin story. A census, for example, is meant to
be a comprehensive list of a population, and we can reason in a very direct way from the data. In
other cases, no formal principle was applied, perhaps being a sample "of convenience." The techniques
for telling stories from these kinds of data will also rely on a mix of simulation and subsetting.
Finally, this course will introduce Participatory Sensing as a technique for collecting data. The idea of a
data collection campaign will be introduced as a means of formalizing a question to be addressed with
data. Campaigns will be informed by research and data analysis, and will build on, augment, or challenge
existing sources. The "culture" behind the existing sources and the summaries or views they promote will
be part of the classroom discussions.

It is worth noting that everything described so far depends on computation, using a piece of statistical
software on a computer. You will learn simple programming tools for accessing data, creating
views or fitting models, and then assessing their importance via simulation. Computation becomes a
medium through which you will learn about data. The more expressive the language, the more elaborate
the stories we can tell.

###**Probability**

Since simulation is our main tool for reasoning with data, interpreting the output of simulations requires
understanding some basic rules of probability. First and foremost, this course will discuss the ways in
which a computer can generate random phenomena. For example, how does a computer toss a coin? You'll first use simple
probability calculations to describe what you expect to see from random phenomena, then
you will compare your results to simulations. The point is to both rehearse these basic calculations
and to make a formal tie between simulation and theory in simple cases.

In that vein, this course will motivate the relationship between frequency and probability. You will
essentially be simulating independent trials and creating summaries of those simulations. In turn, you
should understand that the frequency with which an event occurs in a series of independent simulations
tends to the probability for that event as the number of simulations gets large (the Law of Large Numbers,
a topic that is often taught in introductory statistics courses).

From here you will simulate a variety of random processes to aid in formal statistical inference when
some random mechanism was applied as part of the data design. In short, probability becomes a sort of ruler for assessing the importance of any story we might tell. In this approach to probability, a combination of direct mathematical calculation and computer simulations will be used in order to give you a good sense of the underlying statistical concepts.

##**Topic Outline**

This outline describes only the scope of the course; the sequence is described in each unit.

###**I. Interpreting Data**

A. Types of data

B. Numerical and graphical summaries

1. Measures of center and spread, boxplots

2. Bar plots

3. Histograms

4. Scatterplots

5. Graphical summaries of multivariate data

C. Simulation and visual inference

1. Side-by-side bar plots and association

2. Scatterplots

D. Models

1. Linear models

2. k-means

3. Smoothing

4. Learning and tree-based models

###**II. Making Inferences and Justifying Conclusions**

A. Aggregating data

1. Identification of sources

2. Mechanics of Web 2.0

3. Comparison of sources

B. Data with special structures

1. Random sampling

2. Random assignment and A/B testing

3. Simulation-based inference

C. Participatory Sensing

1. Designing a campaign

2. Participation as a data collection strategy

###**III. Probability**

A. Computers and randomness

1. Web services

2. Pseudo-random numbers (optional)

B. Frequency and probability

C. Probability calculations

###**IV. Algebra in RStudio**

1. Vectors

2. Algorithms

3. Functions

4. Evaluating and fitting models to data

5. Graphical representations of multivariate data

6. Numerical summaries of distributions and interpreting in context

